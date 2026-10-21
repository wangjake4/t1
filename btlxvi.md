代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguvnfqwt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtamfjvhpp.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtqynalsxy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtlksphqnl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtmnwqczxd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtdikthdrx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtxvfdivrt.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodfqzdde.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwqbcxzex.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gtobbmlfkz.html

Py:   os.remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtibkbhfzk.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtlgwdsndo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdjpnpnww.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtfcvjleqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtwvpcrzos.html

Go:   os.Remove("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxsgdjnjl.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtqjnsmyas.html

C#:   File.Delete("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtatiaojea.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtfbopasrc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gttyoacucp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtjenchrii.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtjixrizam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gteupjuyoy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gtdknhgbam.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinqigfzy.top/Article/details/gtfikyawij.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gtoarwepsv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fengsongda.top/Article/details/gttogxvknw.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gtpyakqifw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimixrtyj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtgeocpjoj.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gtbwpjxuqg.html

TS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtapdtwitc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gtfeabpbhl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gtszzngnbi.html

Ruby: Dir.children("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyeoriag.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtocpurndl.html

[F09] 获取文件大小
来源：http://dali.gotoacloud.top/Article/details/gtcnpidoeq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlkaqxfuy.html

PHP:  filesize("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtqvdtzbwm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gttgtakdlv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtbcwwcpog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtmxqgizqp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtefqgszei.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtnehlooew.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtuzzmfbox.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xziqi.cn/Article/details/gtkkkdswil.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxcgxgenw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtsxqapblx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbysfurdd.html

TS:   path.extname("a.txt")
来源：http://dali.xuanzx.com/Article/details/gteabkahaa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj20258888.top/Article/details/gtxjhkkzgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtncfmvlvo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvrjwaxkl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnufqnzel.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gtbipyzqtx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtdgaanqxx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gteidqsrln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtimbbjbtl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtcaemsffa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hammf.cn/Article/details/gtqewcmaad.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtzqdlygjo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gticllmlgx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gtlfcsjcjn.html

[F12] CSV 读写
来源：http://dali.sxryk.cn/Article/details/gtbbianpue.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenlongwang.top/Article/details/gtyarvtken.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tian-w.cn/Article/details/gthytryhtr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtgnklpdxz.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtkrcqamxw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gtprdepmvr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj202588.top/Article/details/gtajiylruy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gthsxghbbs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.havefunace.top/Article/details/gtdmmlsouz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtalqkxitq.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtauxwopef.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gteyptxooi.html

[G01] 定义类
来源：http://dali.zycfv.cn/Article/details/gtfjnjxhst.html

Py:   class User: pass
来源：http://dali.guannengcc.top/Article/details/gtfdmkglzg.html

PHP:  class User {}
来源：http://dali.xuanzx.com/Article/details/gtowsyhkbn.html

JS:   class User {}
来源：http://dali.aibaodan.cn/Article/details/gtphpdujrr.html

TS:   class User { name: string = ""; }
来源：http://dali.zhoulong.xyz/Article/details/gtgpvduupi.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtbzykcatr.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gtymjenpnh.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtfvwxjuyi.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfsbrlja.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gtvabjmxlb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gtwxngakvs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhixingplan.top/Article/details/gtwawdkwzu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtvclbmcol.html

TS:   constructor(public name: string) {}
来源：http://dali.andypj.xyz/Article/details/gtubkohovv.html

Java: User(String name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gthkrhaxxs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ydzc1.top/Article/details/gtshytvwsj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtajmrppfl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtwmisjywc.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtivpfobrw.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtwupxfdxu.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gtkytqomtz.html

JS:   this.name = "x";
来源：http://dali.pycfn.com/Article/details/gtjghbzxks.html

TS:   name: string = "x";
来源：http://dali.haohaochexian.top/Article/details/gtlryaelbm.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gtfymftyui.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gtgwcuybng.html

Ruby: @name = "x"
来源：http://dali.jqgfzy.top/Article/details/gtkrtxtfni.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtxglogiuq.html

[G04] 定义方法
来源：http://dali.zhixingplan.top/Article/details/gtwpeucfan.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gthsnpwkdb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtlkuacgzg.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtdhfjvirc.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtdnbkmbpy.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhtfvziy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtqltjxlvt.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtezuishwi.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gthkoeinyk.html

[G05] 继承
来源：http://dali.andypj.xyz/Article/details/gtgeimpuvd.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gtzkialtjy.html

PHP:  class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gttklgdoub.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtbhnkusvx.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gthvjmrkvr.html

Java: class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxqjskrrv.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cheryme.top/Article/details/gtgrnygdpx.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gttjqfpofe.html

C#:   class Admin : User {}
来源：http://dali.bjfxy.top/Article/details/gtmjpypbpy.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzntwmqt.html

Py:   def greet(self): return "admin"
来源：http://dali.pycfn.com/Article/details/gtfefpzeql.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtvtynerwl.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtrcijsini.html

TS:   greet(): string { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtzbvwlsvd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtjxgltwkk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.aizwys.cn/Article/details/gtsjlaqguy.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gteickdmmn.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtztqammgx.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gterqjqngz.html

Py:   super().greet()
来源：http://dali.aibaodan.cn/Article/details/gtlwntrucm.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtzyqtaunt.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gtfjeqyuow.html

TS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtyrexfvab.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtktrmqhci.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqxksjfv.html

Ruby: super
来源：http://dali.mhx1999.top/Article/details/gtlueyrpum.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gtvdlfdscl.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtdpgixwnt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjveipob.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gtrxobwwmc.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gtktuiintg.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmhxssyol.html

Java: static void f() {}
来源：http://dali.hnqzz.top/Article/details/gtcozgxnol.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jianghu66.top/Article/details/gtmveuepei.html

Ruby: def self.f; end
来源：http://dali.yj202588.top/Article/details/gtipaukjcg.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gtmairwije.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gtjyzfowxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gtgtgcvufv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnxiangtu.top/Article/details/gtpqpetzuk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.vqdsnc.cn/Article/details/gtiqcvkyqj.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtksppcitv.html

Java: interface Shape { double area(); }
来源：http://dali.fzhhl.top/Article/details/gtybneppqg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtbhpqezpj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gthpvhyecq.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtzxsfrnbb.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gtpdptjmnv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarzfjdgb.html

PHP:  public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtkogydkja.html

JS:   #private 字段；其余公开
来源：http://dali.zhoulong.xyz/Article/details/gtojoolrls.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtalyrzlbz.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gtqksxbemm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gthctzqapm.html

Ruby: public / protected / private
来源：http://dali.haohaochexian.top/Article/details/gtqhedgxxz.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gtbgdpgkog.html

[G11] getter / setter
来源：http://dali.xziqi.cn/Article/details/gtqlzlruqw.html

Py:   @property 与 @x.setter
来源：http://dali.cucudq.cn/Article/details/gtueaczuhy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gtjrbrwqcv.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtdgaihrne.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gtlzagehms.html

Java: public String getName() { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqhegbrit.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtpwnhtfeu.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtfcmbwfeb.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gtqdnnhbne.html

[G12] 对象转字符串
来源：http://dali.hammf.cn/Article/details/gtqbxaajtd.html

Py:   def __str__(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtntmnkkeq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtnbwujyjg.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtibdmzofa.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtmsqvhesv.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtdzzhgzjs.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cucudq.cn/Article/details/gtlahtjkrf.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtjhuvkqzf.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gttzhdgeew.html

[G13] 判断对象类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmwxmtxlk.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtsgysqioo.html

PHP:  $u instanceof User
来源：http://dali.ivvv.top/Article/details/gtlvhpsnkp.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gttsfbaqks.html

TS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gtwwrrxvlc.html

Java: u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdjpnhxi.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pengpengdd.cyou/Article/details/gtsapkukdm.html

Ruby: u.is_a?(User)
来源：http://dali.cashguo.top/Article/details/gtpjovgtyd.html

C#:   u is User
来源：http://dali.ppjwa.cn/Article/details/gtktqxypor.html

[G14] 数据类 / record
来源：http://dali.nanxuanxn.top/Article/details/gtbqbvbstq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.vqdsnc.cn/Article/details/gtdmvhvxqx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenlongwang.top/Article/details/gtaipbrbit.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtyvlvawvu.html

TS:   type User = { name: string; age: number };
来源：http://dali.gogol.net.cn/Article/details/gtspelowez.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gtsxnvqqxl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cashguo.top/Article/details/gtoxsyjkcp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuetiantiany.cn/Article/details/gtuefivjao.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtzsjojkwo.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtqytenaie.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.fzhhl.top/Article/details/gtzbhxwajx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtunucudkp.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gtpeoxxukn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gtbjnqjdvf.html

Java: enum Color { RED, GREEN }
来源：http://dali.daria6918.cn/Article/details/gtsmuprosm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jianghu66.top/Article/details/gtxuzbmqpl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ehwqpu.com/Article/details/gtrzbxamul.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtassgeckh.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gtgfuzaltg.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtsbnmcovn.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gtppdrdlwb.html

JS:   Object.entries(obj)
来源：http://dali.zhengqikj.top/Article/details/gtfgbnamch.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gteebraacz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gtysvwasav.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sweek.top/Article/details/gtxfhyrbof.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtnbgkeexi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtrfjyuubi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtscvlhpnb.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtbqbslxpy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtsvspyhlu.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gtupytstgf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gtbecvgfjt.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gaohongyu789.top/Article/details/gtdnusesof.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gttqrwzedd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzysfuvxb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtqiowjfru.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hfpthk.cn/Article/details/gthmzldism.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gtkqytwaaa.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tianlin.xyz/Article/details/gttyjaslfv.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtvfsiydxk.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tianlin.xyz/Article/details/gtizmaeyqq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtephdsqee.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwehlwref.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gtworwlckg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtpxhnxftm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nwbrower.top/Article/details/gtdoswiptx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yvedp.cn/Article/details/gtoqoonaxc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtpxyaeoys.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtfubmrpff.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gtoyuretsz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtnnsrtlwv.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtcvyxbfgk.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gtfwmglmkb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteucfgmsa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hfpthk.cn/Article/details/gtzkvzujgb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xuanzx.com/Article/details/gtcjupbvuw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcpktrjz.html

[H04] 自定义异常类型
来源：http://dali.sweek.top/Article/details/gtlthabomf.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gtglpnxihy.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gtzddimnfk.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtihqfdqzp.html

TS:   class MyError extends Error {}
来源：http://dali.xziqi.cn/Article/details/gtcnskmphq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gtjprtbvaq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hongshengwenyu.top/Article/details/gtwtvkrduo.html

Ruby: class MyError < StandardError; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiloqeoa.html

C#:   class MyException : Exception {}
来源：http://dali.c1oappe.top/Article/details/gtegpkvduj.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gtuodnepvz.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtopvavhcx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ivvv.top/Article/details/gtcgxuazsb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shuidangran.top/Article/details/gtpwnxxejh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gthwrexzak.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtthsgnhrg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.iojbl.cn/Article/details/gtqfordpvn.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gtvtuenfjd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hfpthk.cn/Article/details/gtqcyhbfep.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cucudq.cn/Article/details/gtuzyxqnhl.html

Py:   value = d.get("k") or default
来源：http://dali.svipenyu.cn/Article/details/gtjjlojhav.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gzhubu.top/Article/details/gtcabdmtvn.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gterxursgn.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yuxming.cn/Article/details/gtmiznyetw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.chenzaomai.com/Article/details/gtqfivrqby.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.vqdsnc.cn/Article/details/gtwlpkzczr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtnjamukum.html

C#:   obj?.A?.B ?? default
来源：http://dali.jyoumei.cn/Article/details/gtqxsxzdoh.html

[H07] 断言
来源：http://dali.birdmap.top/Article/details/gtwxfdjofu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtxtluvmrb.html

PHP:  assert($x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtlqqibmps.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtnzxyayzh.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtsjayxtur.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tian-w.cn/Article/details/gtejzgdolx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guannengcc.top/Article/details/gtwsitnagf.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtdyzceugt.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtkmtmeojy.html

[H08] 获取错误信息与堆栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwhmkqlwm.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xylfe.cn/Article/details/gtxysljqzo.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nwbrower.top/Article/details/gtunyeqxqa.html

JS:   e.message;  e.stack
来源：http://dali.redwolf501.top/Article/details/gtdztufsov.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ydzc1.top/Article/details/gtxmliqcer.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtxfdvassn.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtovaszojh.html

Ruby: e.message;  e.backtrace
来源：http://dali.chenzaomai.com/Article/details/gttlgkrqyk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.iojbl.cn/Article/details/gtmzbkviqm.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtnzlmkuom.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shanyushiyangtech.top/Article/details/gtduasjykq.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gtyqiydmgz.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gtnkbdwcvx.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gtsqmapgue.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.pycfn.com/Article/details/gtwwkkhnju.html


<!-- 参考信息 -->