代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gtdvrglywd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtiqgpywuv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtvdmgfsmm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtcjzdmbvt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtlxtmpvey.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusxcsmdd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtqjwwlbcb.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gtostnljcs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sysykeji.top/Article/details/gtvrpwppad.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtmatugqbv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtibyacjdw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gtxubhlnhn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gttosnvxzp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtbhjvmkmn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtgvblzihw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gotoacloud.top/Article/details/gtrelfxrsi.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gtkpznubda.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gtzchgdoud.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdeqlmbzo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtcqdzomid.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gttyedudqv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtihjbjzeb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtkkvnkhwg.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtffdrtajq.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtppjrjxrp.html

[F06] 删除文件
来源：http://dali.yvedp.cn/Article/details/gtrqherrje.html

Py:   os.remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdulqvos.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtjfgmljpr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gteyhxqebe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtadcxjglw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtykmfkrjm.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtqyznfdgp.html

Ruby: File.delete("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmlsnuhli.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtpmfacvqa.html

[F07] 创建目录（含多级）
来源：http://dali.birdmap.top/Article/details/gtapamyoji.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtqtgsfqtw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gtlhqhnmxg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqjbsohm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtidwnpxri.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtscmhndgv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hysaishi.cn/Article/details/gtipazohmd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtabwtpfmj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtefnfdidm.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtsmzduvji.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gtoeumcuhj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtjelxcyxb.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gtnhkfboab.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gtcoopjyvg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pengpengdd.cyou/Article/details/gtxbcbhtkw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtccblcwha.html

Ruby: Dir.children("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtxvmwpwrz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtyaizejeo.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gtuwpcmsfd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gthxvbludq.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfzdcbxmo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gthyfijqnt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtixszkctd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtqggnnwct.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzildewtv.html

Ruby: File.size("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtnramolah.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gthitnuksd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.pycfn.com/Article/details/gtcaqvvrvi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtbgiemjin.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtbtqbnlms.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqadhycrb.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoypsqxl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gtjvuinyje.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvmiqwuq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gtzbdscgum.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gteixysfcw.html

[F11] 复制与移动文件
来源：http://dali.quarkkingdee.top/Article/details/gtqdcekkmg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtqesjxrtc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtdkpiqllr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtddjdcbbv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtphhojkrb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtgghjjfky.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtnfbqaifv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtwinkzgov.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtuqnvicfj.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gtqudhdlux.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.aizwys.cn/Article/details/gtubtwdsyo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenlongwang.top/Article/details/gteitwanbb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtnvanuocn.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtdzfratuc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtfncqowbu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gzhubu.top/Article/details/gtdftgqhnj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtpacqhrgv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbulmnyxu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttwslhsxz.html

G. 面向对象
来源：http://dali.fzhhl.top/Article/details/gtvjowndxh.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaztoszx.html

[G01] 定义类
来源：http://dali.havefunace.top/Article/details/gtxawvgysd.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzgoevia.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtcxdcyadw.html

JS:   class User {}
来源：http://dali.tanke756.top/Article/details/gtxpvaatdt.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzppbyzea.html

Java: class User {}
来源：http://dali.c1oappe.top/Article/details/gtorhoxbev.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtroiqjvte.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtsoeadbev.html

C#:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqmqgybp.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gtijploebj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.9152youxi.cn/Article/details/gtnmtnzusy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvbxdxqs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtjacmoold.html

TS:   constructor(public name: string) {}
来源：http://dali.wangdashe.top/Article/details/gtwcorxtmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gthrxsgeml.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtnorfdflw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtmitqzwdq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlpolzryb.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtcmzttrbj.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gtfycoaqnh.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gttgrkienk.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtnxcmtygx.html

TS:   name: string = "x";
来源：http://dali.svipenyu.cn/Article/details/gtyfgskpua.html

Java: private String name;
来源：http://dali.hongshengwenyu.top/Article/details/gtzfskajfi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hysaishi.cn/Article/details/gtvpeyegfq.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gtfyzjbqbx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtgdsoepbg.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtaumussuy.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gtozcpdtgf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtjhiipmpf.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gtknucoiah.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gthcytfxzu.html

Java: String greet() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtmtutybte.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtjstfabiz.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtimosadrt.html

C#:   public string Greet() => Name;
来源：http://dali.birdmap.top/Article/details/gtzyybscxi.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gtwyysmixb.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gtocafghpu.html

PHP:  class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtajstkcke.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtetsbprmm.html

TS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtnfxdwrbu.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtkhpaeqnt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtwbuerdpz.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtfqqicrla.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gterwvzpex.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gtuymwyhmm.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gtgexvmkfx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gttdtilcmj.html

JS:   greet() { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtezmlxdus.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gtiqlhrkwh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtmhmeuluu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zycfv.cn/Article/details/gtswaiuyhg.html

Ruby: def greet; "admin"; end
来源：http://dali.hywenlv.cn/Article/details/gtxxnqijic.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenzaomai.com/Article/details/gtmlbmcjae.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gthvnvpvuo.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gtvaoeqvad.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gtlevoxulx.html

JS:   super.greet();
来源：http://dali.nwbrower.top/Article/details/gtzdcqbcow.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtormusrme.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gtarqcutzb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yonumen.top/Article/details/gtmxgwmldj.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gtlyezrbhw.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtrlhvnxvv.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtjwrrxzln.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nwbrower.top/Article/details/gtbgnaxulz.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtxaxqlcxg.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtbdmskbiu.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gttrjntbes.html

Java: static void f() {}
来源：http://dali.tian-w.cn/Article/details/gtnakyusxx.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gtxoitiohh.html

Ruby: def self.f; end
来源：http://dali.316326.xyz/Article/details/gtekrvzfyt.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtbikfdqgw.html

[G09] 接口 / 抽象类
来源：http://dali.dashuyun.cn/Article/details/gtkqsszflb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtjjwlaryu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gtwphnuoxx.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ppjwa.cn/Article/details/gtzdmzysbi.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtaqzpgyvq.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtxqtzmasz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gtwxvqcjuv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtjtecooot.html

C#:   interface IShape { double Area(); }
来源：http://dali.cheryme.top/Article/details/gtuvzzfwuj.html

[G10] 访问控制
来源：http://dali.ybcxt.top/Article/details/gttapswyqe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jianghu66.top/Article/details/gtbpuhcpec.html

PHP:  public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gtwfaatnrv.html

JS:   #private 字段；其余公开
来源：http://dali.yangfankeji.com/Article/details/gtbvxbyqto.html

TS:   public / protected / private
来源：http://dali.daria6918.cn/Article/details/gthobxsrrm.html

Java: public / protected / private / 默认包级
来源：http://dali.xinyue.icu/Article/details/gtmovpssbk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.shuidangran.top/Article/details/gtnbnmufpf.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtofrvasmm.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gtiyvqcyoa.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gtnyggwsoq.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtiyhznjyy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtttuyspgk.html

JS:   get name() { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gthzxumdnv.html

TS:   get name(): string { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gtgwgntodb.html

Java: public String getName() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqylpihry.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gtepbrakyn.html

Ruby: attr_accessor :name
来源：http://dali.zhoulong.xyz/Article/details/gtwdqbblre.html

C#:   public string Name { get; set; }
来源：http://dali.kuanghao11.cn/Article/details/gtxloyzqiu.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gtlyevctse.html

Py:   def __str__(self): return self.name
来源：http://dali.sxryk.cn/Article/details/gtjjqrljcv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cashguo.top/Article/details/gtgaxahyrs.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gtuqkajjyf.html

TS:   toString(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gtbttrujlo.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpiaqelq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtwkqsndqe.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gtkylluxff.html

C#:   public override string ToString() => Name;
来源：http://dali.gzhubu.top/Article/details/gtllwtgbho.html

[G13] 判断对象类型
来源：http://dali.chenzaomai.com/Article/details/gtbylsybnq.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gtguqloohk.html

PHP:  $u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuheehfu.html

JS:   u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gthajkwmgb.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gttnslobya.html

Java: u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gtioufspof.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenlongwang.top/Article/details/gtkwzgnikj.html

Ruby: u.is_a?(User)
来源：http://dali.tianlin.xyz/Article/details/gtmlirwstk.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtkhenvoeb.html

[G14] 数据类 / record
来源：http://dali.ivvv.top/Article/details/gtmkqivsys.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.smart0.xyz/Article/details/gtexcuuxrm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hongshengwenyu.top/Article/details/gtvxqnynsa.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtglphkzlf.html

TS:   type User = { name: string; age: number };
来源：http://dali.aibaodan.cn/Article/details/gtvojnynlt.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gtmsymgvaq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gtpdhxrguq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yangfankeji.com/Article/details/gturulgjpd.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtibcanzcl.html

[G15] 枚举
来源：http://dali.ydzc1.top/Article/details/gtinshwcen.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gthakvihut.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.redwolf501.top/Article/details/gtbxhrqqgl.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuxming.cn/Article/details/gtwpbvwlah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gogol.net.cn/Article/details/gtlasjdsna.html

Java: enum Color { RED, GREEN }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyouxdjd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ydzc1.top/Article/details/gtziakdcfi.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258888.top/Article/details/gttrnxpiia.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtbqytuyul.html

[G16] 对象转数组 / 字典
来源：http://dali.hywenlv.cn/Article/details/gtiktdvzac.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gtfmhlznnf.html

PHP:  get_object_vars($obj);
来源：http://dali.svipenyu.cn/Article/details/gtugfjcodt.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtuczjahve.html

TS:   Object.entries(obj)
来源：http://dali.kuanghao11.cn/Article/details/gtsugcxrey.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkyhsueq.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.fengsongda.top/Article/details/gttndohmiu.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gtyryydxda.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnjuecez.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtkymxlnsg.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppbgtyoa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtefxmdnqk.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gtssdjqweo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cqqwz.cn/Article/details/gttikilinl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gtuvjirvwb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtwbjttepe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gtmsbbzgbq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.sysykeji.top/Article/details/gtudzckibs.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xinyue.icu/Article/details/gtdkmnqtvm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ehwqpu.com/Article/details/gtoyjhwsgv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtbvqqgimz.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtknkgxfdg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gttmpyijdk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gthtbmrkxy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtmnjcdchr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gteitbwbmq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gtnsrbvdpr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.aibaodan.cn/Article/details/gtwvngbrsb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gthpujjtft.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtfhnbzosd.html

[H03] 主动抛出异常
来源：http://dali.jianghu66.top/Article/details/gtlawhokin.html

Py:   raise ValueError("错误信息")
来源：http://dali.zycfv.cn/Article/details/gtxiudpiib.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtzuwigriz.html

JS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtyffcuzag.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gtqaeiaifu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sweek.top/Article/details/gtkxuiaxii.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.meibo888.top/Article/details/gtoeaidkuz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gtnbkqbmsm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtqelokowo.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtmdnclwbj.html

Py:   class MyError(Exception): pass
来源：http://dali.ehwqpu.com/Article/details/gtqckiitem.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gttoegbcrd.html

JS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gtxiquubwo.html

TS:   class MyError extends Error {}
来源：http://dali.xuanzx.com/Article/details/gtbppbzzeu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.tianlin.xyz/Article/details/gtweivxjcl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhengqikj.top/Article/details/gthypjongw.html

Ruby: class MyError < StandardError; end
来源：http://dali.dashuyun.cn/Article/details/gtnacbxiqd.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtppmftwsh.html

[H05] 捕获特定类型
来源：http://dali.snrcjt.cn/Article/details/gtxfrunrmh.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtfyrksjqt.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigfzy.top/Article/details/gtrcaahoyy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.daxiang520.top/Article/details/gtuaovpygm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtnatthrsx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gteopzdgpd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zhixingplan.top/Article/details/gtaferbpgt.html

Ruby: rescue ArgumentError => e
来源：http://dali.shuidangran.top/Article/details/gtdsibzkuh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzdmcyik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yj202588.top/Article/details/gtbjygazue.html

Py:   value = d.get("k") or default
来源：http://dali.redwolf501.top/Article/details/gtswfuyocv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yongpay.top/Article/details/gthvttmdvq.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigfzy.top/Article/details/gtilpfuvfx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yongpay.top/Article/details/gtvdynludj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.andypj.xyz/Article/details/gtyoicrffq.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hfpthk.cn/Article/details/gtkjmaeuxe.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtekpsqyst.html

C#:   obj?.A?.B ?? default
来源：http://dali.zhengqikj.top/Article/details/gtnxfmuqps.html

[H07] 断言
来源：http://dali.hongshengwenyu.top/Article/details/gtbgbnptbh.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yonumen.top/Article/details/gtglnjmrfy.html

PHP:  assert($x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtrntqlfms.html

JS:   console.assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtlvkosmwp.html

TS:   console.assert(x > 0);
来源：http://dali.tianlin.xyz/Article/details/gtorclyqjz.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkfapjpn.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtzynnhn.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gteczdusrh.html


<!-- 参考信息 -->