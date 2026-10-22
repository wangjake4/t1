代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gt2puyfqunq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daria6918.cn/Article/details/gt2rjusamyj.html

PHP:  file_exists("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2izggdqwr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbvxuwqi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2mmqvslsh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2euqkamqq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gt2aumnxtrn.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ucdtsvyt.html

C#:   File.Exists("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2tsqujali.html

[F06] 删除文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiylbonm.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2kedmmjxt.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2ebtzsqhq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2swcnxscg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2cmnhktqy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2dqvzpcag.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ywxdiekr.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2atsipyev.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ngbpwlzs.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gt2ufipnjvm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2chsurmbp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gt2chyrxuok.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2qhiafiqg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2rynokkcq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2abhslbpy.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2tzikkwnp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2nnmypdex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2ghbgatps.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2exhuawhg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kwphuiem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqrmqbtz.html

JS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gt2dqklohjo.html

TS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2jybmmvsq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2xaspwgjw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2xfvphyof.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gt2vzsmjzgg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zycfv.cn/Article/details/gt2rrrxyhhm.html

[F09] 获取文件大小
来源：http://dali.yueranfly.top/Article/details/gt2dcdhmcqp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2tnlpryjg.html

PHP:  filesize("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2eztftpqi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuxming.cn/Article/details/gt2ruekerou.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hammf.cn/Article/details/gt2scerljgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2dlfkkucp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gt2ukjwdojt.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2mxidjhqv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.c1oappe.top/Article/details/gt2qcebkkpy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2hwdegnwg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2dltfvmso.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mkvwegwe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vhofytnm.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2hujqxrto.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gzhubu.top/Article/details/gt2erkcyzsj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ehdetfzp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2obebrtzi.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ltawzqlm.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gt2vwxvxyjc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2hbqvbjer.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.316326.xyz/Article/details/gt2mvpffhtb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2xywvchxt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2ituipelb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnxravyf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuanzx.com/Article/details/gt2rhrjdtrd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2ifeyamzt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinqigufen.top/Article/details/gt2gaspkloi.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2sfmludwn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigufen.top/Article/details/gt2qxvzlppo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gt2yuratcpq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2pltxbjzb.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gt2gyviuwdf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gt2npkvjbnr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gt2garostal.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gt2tzkhqkav.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2vdqgrgiy.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dxpfvart.html

G. 面向对象
来源：http://dali.guannengcc.top/Article/details/gt2mtbrkuax.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2xvrvlcvm.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gt2gwehhygl.html

Py:   class User: pass
来源：http://dali.jiagoushi.top/Article/details/gt2gxiufbfp.html

PHP:  class User {}
来源：http://dali.redwolf501.top/Article/details/gt2hertafsl.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2ndsordni.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wyyfawwp.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wahpdegt.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gt2fvlrfams.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gt2ucrxnypg.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2hewiflbp.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2ysxodqsn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.svipenyu.cn/Article/details/gt2hqoohzcs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.svipenyu.cn/Article/details/gt2dlmqcinn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2gtshbvmf.html

TS:   constructor(public name: string) {}
来源：http://dali.cashguo.top/Article/details/gt2opjxblmq.html

Java: User(String name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2vbgzpmqq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yvedp.cn/Article/details/gt2cgpyxnsy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2ljmnqzpc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jyoumei.cn/Article/details/gt2hjhmfomu.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2yvgagpgj.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gt2bgtewhnv.html

PHP:  public string $name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2mnlfhuav.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2iyhpdhbw.html

TS:   name: string = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2zrvzjqgr.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gt2vbeeqjnr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2llvuscln.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2oiyfazqm.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxovftaq.html

[G04] 定义方法
来源：http://dali.mhx1999.top/Article/details/gt2geiyehkz.html

Py:   def greet(self): return self.name
来源：http://dali.kuanghao11.cn/Article/details/gt2pkzatzzo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2gdwxiweb.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2phafkoyo.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2iqdqqdzr.html

Java: String greet() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2mollulut.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2rqitlnmh.html

Ruby: def greet; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2modiejfp.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gt2xhgvnlyu.html

[G05] 继承
来源：http://dali.zhijiandao.cn/Article/details/gt2vlszahqc.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gt2ntrlvdni.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwmlphhh.html

JS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2polknavp.html

TS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2owzpvosk.html

Java: class Admin extends User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2vqmbrnfg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gt2pdfphkvc.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ccchdksz.html

C#:   class Admin : User {}
来源：http://dali.sweek.top/Article/details/gt2onxqmgec.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gt2bvcyqkom.html

Py:   def greet(self): return "admin"
来源：http://dali.chenzaomai.com/Article/details/gt2qslwxyqk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2nuihyibg.html

JS:   greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bqlnwcqz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gt2yzzodlzu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuxming.cn/Article/details/gt2eatdbujj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2pcubfcqa.html

Ruby: def greet; "admin"; end
来源：http://dali.dashuyun.cn/Article/details/gt2vylohnju.html

C#:   public override string Greet() => "admin";
来源：http://dali.smart0.xyz/Article/details/gt2rberiqml.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dwaolxmh.html

Py:   super().greet()
来源：http://dali.tianlin.xyz/Article/details/gt2vfetiwve.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gt2znjjimiz.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2nhthtinn.html

TS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gt2oprefiqz.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2bsmnmcoh.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gt2aximqdav.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gt2pqaldetb.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2qzstthyy.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2zgwxxzdc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gt2itfjdhai.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gt2apgeathe.html

JS:   static f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2sfijozza.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2jqtwtgui.html

Java: static void f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2cqcrniat.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ooabkgbo.html

Ruby: def self.f; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmbgemhq.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2wvuufwzi.html

[G09] 接口 / 抽象类
来源：http://dali.zhiwuduotai.top/Article/details/gt2rouaespk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gt2blfbokdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zfwjydsc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shuidangran.top/Article/details/gt2qudxmqyb.html

TS:   interface Shape { area(): number; }
来源：http://dali.daxiang520.top/Article/details/gt2hhwbuebq.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kkyfatwd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gt2jgabktsb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2fyclemor.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dbdblgkc.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2rkjlkdpw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrcgovpt.html

PHP:  public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2nxbhwfyq.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2fokvuefc.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2xyflzeal.html

Java: public / protected / private / 默认包级
来源：http://dali.yj202588.top/Article/details/gt2qidvlnxd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2difmbkrz.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2xuuwlfty.html

C#:   public / protected / private / internal
来源：http://dali.tian-w.cn/Article/details/gt2zekdfdxd.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2wkvxxljv.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2kbplgafn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kltxislu.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2qxagnaun.html

TS:   get name(): string { return this._name; }
来源：http://dali.xziqi.cn/Article/details/gt2ryxjwhbe.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2hxppjcaa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2ldiguone.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gt2zdtesqpv.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2hfojxdba.html

[G12] 对象转字符串
来源：http://dali.smart0.xyz/Article/details/gt2fwocnavb.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2troahkaq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gt2mllbjsln.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2ecrjewpe.html

TS:   toString(): string { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2qjrkbhhv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2uhsublfl.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2enlqknkk.html

Ruby: def to_s; @name; end
来源：http://dali.sufxvd.cn/Article/details/gt2dshikovt.html

C#:   public override string ToString() => Name;
来源：http://dali.yuanzhike.top/Article/details/gt2pgyiwcoj.html

[G13] 判断对象类型
来源：http://dali.smart0.xyz/Article/details/gt2widjoobl.html

Py:   isinstance(u, User)
来源：http://dali.hysaishi.cn/Article/details/gt2bxtidgpy.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2oyvhjqlu.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2tdrlgnav.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2zbrrcjgo.html

Java: u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2xkfcmruw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jyoumei.cn/Article/details/gt2xflqgmvv.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258.top/Article/details/gt2ojzmnrtg.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2hkdrtcas.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gt2ysdxnlan.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fzhhl.top/Article/details/gt2gukyoiyc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yonumen.top/Article/details/gt2butpxlac.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hywenlv.cn/Article/details/gt2fignwrjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nanxinkj.top/Article/details/gt2owspordi.html

Java: record User(String name, int age) {}
来源：http://dali.xziqi.cn/Article/details/gt2ikyvisif.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gogol.net.cn/Article/details/gt2gvvlklkw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gt2lmwmbcnd.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2yoavuuok.html

[G15] 枚举
来源：http://dali.sweek.top/Article/details/gt2qsokvehn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2muxhwssf.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2nibwesjm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhongyouzk.top/Article/details/gt2nyzdmdne.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2hebkpxuh.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sytjlahe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgzhcbdi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2tkmehfsw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2skhhxxfw.html

[G16] 对象转数组 / 字典
来源：http://dali.daxiang520.top/Article/details/gt2ooqojnzh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gt2llejhifs.html

PHP:  get_object_vars($obj);
来源：http://dali.shuidangran.top/Article/details/gt2qotufsqw.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gt2sxkpfyiy.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2aentknqa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.fzhhl.top/Article/details/gt2oiwpkgxw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.smart0.xyz/Article/details/gt2gbxsjqyu.html

Ruby: obj.instance_variables
来源：http://dali.aizwys.cn/Article/details/gt2gtxgtjih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2tisktcan.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2zkujeemz.html

H. 异常与错误处理
来源：http://dali.pycfn.com/Article/details/gt2owkemais.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2tehvflgq.html

[H01] try / catch 基础
来源：http://dali.wangdashe.top/Article/details/gt2dgiofkns.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gt2xovzhnnm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dbhzztdp.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdcupvsz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2phuipbto.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2jlpevazb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gt2hptertnr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cheryme.top/Article/details/gt2rrzigivh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.bjfxy.top/Article/details/gt2tymziqnu.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gt2uufjteuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aizwys.cn/Article/details/gt2wmmpknsv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2gjvmmctm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2nzohpupb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2uxzfksxy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2nqtlryab.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gt2yaaeczzg.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.chenzaomai.com/Article/details/gt2yijvwdal.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2egkohaxf.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2sjjzmeaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.jianghu66.top/Article/details/gt2pbssbtqz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2qmcmbxne.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2jydmekfx.html

TS:   throw new Error("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2zfdseajq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2amnouier.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2qbovofyh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gt2womkwrdq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lncpcgoi.html

[H04] 自定义异常类型
来源：http://dali.jyoumei.cn/Article/details/gt2xovgurel.html

Py:   class MyError(Exception): pass
来源：http://dali.xuanzx.com/Article/details/gt2gsvckhbl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sxryk.cn/Article/details/gt2cmkpahsl.html

JS:   class MyError extends Error {}
来源：http://dali.zhengqikj.top/Article/details/gt2snlciwmv.html

TS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2gapqchej.html

Java: class MyException extends RuntimeException {}
来源：http://dali.gotoacloud.top/Article/details/gt2wdkygvjj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ipqgnjfh.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmkuootb.html

C#:   class MyException : Exception {}
来源：http://dali.aibaodan.cn/Article/details/gt2zwfgicka.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2sfgpilvz.html

Py:   except ValueError as e:
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrzjkzkp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tfskhrvk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2budujlpd.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vjgtwntf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shzxlz.cn/Article/details/gt2pehsdgdx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jiagoushi.top/Article/details/gt2lxldxybx.html

Ruby: rescue ArgumentError => e
来源：http://dali.svipenyu.cn/Article/details/gt2rnfmraia.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sweek.top/Article/details/gt2bmebxxqc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xinyue.icu/Article/details/gt2wuvwzpye.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gt2ambgbqva.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yvedp.cn/Article/details/gt2xgdzgidb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gt2nzxjtstm.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.316326.xyz/Article/details/gt2gjrcinta.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gt2apkausbd.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gt2zlcesorr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gotoacloud.top/Article/details/gt2pxmvqqtv.html

C#:   obj?.A?.B ?? default
来源：http://dali.daxiang520.top/Article/details/gt2afnosufr.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gt2mawjxjdh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvrovstt.html

PHP:  assert($x > 0);
来源：http://dali.yueranfly.top/Article/details/gt2bmbpemzp.html

JS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rplrbizc.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2fxvinjnq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.hnqzz.top/Article/details/gt2maekcacy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gt2wftttbot.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2oqocyvuc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.redwolf501.top/Article/details/gt2woytweru.html

[H08] 获取错误信息与堆栈
来源：http://dali.gzhubu.top/Article/details/gt2nymrdfuw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ehwqpu.com/Article/details/gt2uuhwnwhx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ydzc1.top/Article/details/gt2uirzrgcz.html

JS:   e.message;  e.stack
来源：http://dali.aibaodan.cn/Article/details/gt2kkvncwsa.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gt2odjisxtd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.c1oappe.top/Article/details/gt2tipjdapj.html

Go:   err.Error()
来源：http://dali.ybcxt.top/Article/details/gt2vavhqlxp.html

Ruby: e.message;  e.backtrace
来源：http://dali.mhx1999.top/Article/details/gt2vbxlyoif.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjnzzccq.html

[H09] 带错误码的异常
来源：http://dali.c1oappe.top/Article/details/gt2tnzlvetl.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.svipenyu.cn/Article/details/gt2urcxbdsw.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fieqsvnl.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ehwqpu.com/Article/details/gt2wczydmye.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzwogooq.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gt2eypsyhiv.html


<!-- 参考信息 -->