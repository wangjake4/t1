代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtzvabxoww.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xuetiantiany.cn/Article/details/gtzkuasgea.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gttxbvqywf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gteeayiypz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gthkuqkeer.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtfkcsmiwd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gtkogwnvsp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gtfiwzrpfz.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtxosqeier.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gtzuhqpatl.html

PHP:  file_exists("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtxeubzill.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhaxsfxs.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtqzluflyf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtagyewnpx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtyvdznszk.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtghbwijhn.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtcuqlbwug.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gtzhybtjbd.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkeklgjfh.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtsnqxpryt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtahwzzosf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtogdsmxqg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtoixxrhqb.html

Go:   os.Remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpyojahkh.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtjblnewzq.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gthbauuurj.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtvhgoiwov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtsirdxegy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbjyvtxk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtvngcilwm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtwkybfxtq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gtlgmutgdg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gtshtuihen.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtwdjzpjft.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.snrcjt.cn/Article/details/gteqvwlmyl.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzuocwikq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cashguo.top/Article/details/gthndicgqk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shuidangran.top/Article/details/gtuyabmjyz.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtcghttoia.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gteergyxrm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtlakncydj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cashguo.top/Article/details/gtaotniull.html

Ruby: Dir.children("dir")
来源：http://dali.redwolf501.top/Article/details/gttwcghdei.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtjbvubtxk.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhoccjre.html

Py:   os.path.getsize("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtffmsxhba.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtunybzedq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtajyxhsnl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gtlezljtan.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtiachqgto.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooyzeadp.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtknjivojl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gtquyvnbqc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtrcceeopg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtvbrojjog.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtowinktbi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gttzbtonpk.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtzzqmqwuk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gtasoswafp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvdmwinlh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttupcjwwb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjgqslvhq.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtsjfcpvht.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guannengcc.top/Article/details/gtqrxjqimf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtmtawfnoh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtbquslgcu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkjqpwwuz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sxryk.cn/Article/details/gttmgkgqir.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yanxiufei.cn/Article/details/gtfhxhahhf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtexvhsekv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.fzhhl.top/Article/details/gthoztqbfp.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gtublbqgyr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gttdwwlcxx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjutnfms.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.quarkkingdee.top/Article/details/gtfitjsfck.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gtyfljdnwj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gtcnwybrbz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gttdhcgevq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gtxrveiqps.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtmgmlkdyu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdksfmbvh.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gtvpxytiaq.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtagjuxmbf.html

[G01] 定义类
来源：http://dali.hnxiangtu.top/Article/details/gthndudodz.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gtovreqsqs.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gtfgoncjcf.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gteuvfuwem.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gtjcutppbe.html

Java: class User {}
来源：http://dali.jyoumei.cn/Article/details/gtvolrtmib.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gtbdjygpui.html

Ruby: class User; end
来源：http://dali.birdmap.top/Article/details/gtfslwtvsn.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtjcsdehhn.html

[G02] 构造函数
来源：http://dali.jiagoushi.top/Article/details/gtsenltoum.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nwbrower.top/Article/details/gtmeddezxu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtqnpxthhn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtzmqqyayh.html

TS:   constructor(public name: string) {}
来源：http://dali.aizwys.cn/Article/details/gtrjdoirgv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtmlynyufh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtxosgjunl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ehwqpu.com/Article/details/gthrfezgtx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.guannengcc.top/Article/details/gtyxugsalg.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtmqldxzsf.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtkhslduyh.html

PHP:  public string $name = "x";
来源：http://dali.hywenlv.cn/Article/details/gtcvjtbdie.html

JS:   this.name = "x";
来源：http://dali.tian-w.cn/Article/details/gtgdbtchom.html

TS:   name: string = "x";
来源：http://dali.dianchejie.cn/Article/details/gtadvgqxvn.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtxjhrgkya.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtsuowefal.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtthdmpumf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtdjsetadf.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gtwheeonfh.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtjcnmrihm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gttmymcuxg.html

JS:   greet() { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfyvvbznz.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gttnawcbib.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gtzdmogxul.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtjgfdhfug.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gtfaymiesq.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gtrwyvqzyj.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gtardwqzev.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gtvvwpokdz.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtdevvvosg.html

JS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgawlfmjp.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtlqnuihns.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtgkxixked.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtgblgzpxl.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtvajztihy.html

C#:   class Admin : User {}
来源：http://dali.tian-w.cn/Article/details/gtqmppxkpj.html

[G06] 重写方法
来源：http://dali.shzxlz.cn/Article/details/gtzuchhtjm.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gthtimxqrr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtenaeaaiw.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtednibifs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtiocldhgf.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjqbtufjo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gtbkzwvuwm.html

Ruby: def greet; "admin"; end
来源：http://dali.zycfv.cn/Article/details/gttupepygw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gthatjrnlj.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gtflnzxcyx.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtwnyynjsf.html

PHP:  parent::greet();
来源：http://dali.tian-w.cn/Article/details/gtmygxnfcq.html

JS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtqbfkctja.html

TS:   super.greet();
来源：http://dali.ppjwa.cn/Article/details/gtcthljfye.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gtzppnewhw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazgntnpn.html

Ruby: super
来源：http://dali.snrcjt.cn/Article/details/gtdusyorrf.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gtflbparkx.html

[G08] 静态方法与属性
来源：http://dali.andypj.xyz/Article/details/gttfvtimnm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ivvv.top/Article/details/gtkfolpusv.html

PHP:  public static function f() {}
来源：http://dali.zhengqikj.top/Article/details/gtozsglyul.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gtdwexaqnb.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtstbpcuvr.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtupffnmxr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtswpsewqe.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gtixsypgdc.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtepniockl.html

[G09] 接口 / 抽象类
来源：http://dali.nanxuanxn.top/Article/details/gtmcupozfr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.tanke756.top/Article/details/gtduqssogw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtsbnqogew.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtcbmziddb.html

TS:   interface Shape { area(): number; }
来源：http://dali.yueranfly.top/Article/details/gtxeocjkcp.html

Java: interface Shape { double area(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncgxdogt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkbvhokpp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuanzhike.top/Article/details/gtalbbhsfz.html

C#:   interface IShape { double Area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxlhswhd.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoqzoghn.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gtwzbqumip.html

PHP:  public / protected / private
来源：http://dali.jiagoushi.top/Article/details/gtbindznqk.html

JS:   #private 字段；其余公开
来源：http://dali.daxiang520.top/Article/details/gtwzbvukks.html

TS:   public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtzpyrtahd.html

Java: public / protected / private / 默认包级
来源：http://dali.dashuyun.cn/Article/details/gtwiomkxjj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybudfnnh.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtnvvwplds.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gtdtfntfuj.html

[G11] getter / setter
来源：http://dali.yvedp.cn/Article/details/gtdfsdyjph.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtkrpihggm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.316326.xyz/Article/details/gthzstjnxm.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gtjbbarzds.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gttpfgwfly.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtusqvuvpa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtlfglcjlh.html

Ruby: attr_accessor :name
来源：http://dali.jqgufenzy.top/Article/details/gtsalnqdjp.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtprwrvyzy.html

[G12] 对象转字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrsgyoihl.html

Py:   def __str__(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtcgcqwvgp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gttakyuyox.html

JS:   toString() { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxewfzrlm.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtzcmfkjcu.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtdkzedece.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtzfhyqsoa.html

Ruby: def to_s; @name; end
来源：http://dali.hysaishi.cn/Article/details/gtovhzegfv.html

C#:   public override string ToString() => Name;
来源：http://dali.xinyue.icu/Article/details/gteqvftajy.html

[G13] 判断对象类型
来源：http://dali.bjfxy.top/Article/details/gtayiwozoq.html

Py:   isinstance(u, User)
来源：http://dali.chenlongwang.top/Article/details/gtzsvfaxju.html

PHP:  $u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtktgzvsem.html

JS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtkcifvdxr.html

TS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gtpbctuuke.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtfpxkfjhv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cqqwz.cn/Article/details/gtzowtbpqz.html

Ruby: u.is_a?(User)
来源：http://dali.yj20258888.top/Article/details/gtvilbvled.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gthwogcubb.html

[G14] 数据类 / record
来源：http://dali.cheryme.top/Article/details/gtmfcahmzk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gtzivttqwa.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhongyouzk.top/Article/details/gtlqwprobf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojnwecol.html

TS:   type User = { name: string; age: number };
来源：http://dali.cashguo.top/Article/details/gtawzfyaum.html

Java: record User(String name, int age) {}
来源：http://dali.gaohongyu789.top/Article/details/gttveeilgq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtbthwqzgh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnxiangtu.top/Article/details/gtdsuysvyv.html

C#:   record User(string Name, int Age);
来源：http://dali.hfpthk.cn/Article/details/gtowaskdqh.html

[G15] 枚举
来源：http://dali.aizwys.cn/Article/details/gthpehajrm.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcpuohkh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtotlqukor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.smart0.xyz/Article/details/gtvjjlhbeh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gthjnrnftl.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gtthiokqum.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtvopcrkby.html

Ruby: Color = %i[red green].freeze
来源：http://dali.0kj1m.cn/Article/details/gtaevmjdxz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtpsnghtmi.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtipcuwpir.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrgvhixjo.html

PHP:  get_object_vars($obj);
来源：http://dali.sweek.top/Article/details/gtzawfcdwy.html

JS:   Object.entries(obj)
来源：http://dali.xziqi.cn/Article/details/gtyuhsmdrn.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtijybmxev.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shuidangran.top/Article/details/gtuhisyhmi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.tanke756.top/Article/details/gtyyyiybvf.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtpiyoelff.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gtvaceaqpf.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtytuiyiak.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtgpvqipgw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtmaswcyll.html

[H01] try / catch 基础
来源：http://dali.zhixingplan.top/Article/details/gtvrukzxoi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtrftaakmo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gtfmezhowv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtyyccsygq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.iojbl.cn/Article/details/gtunfuqair.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yangfankeji.com/Article/details/gtjhebnijh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gtxxllrqlz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.bjfxy.top/Article/details/gtpdtiuslu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgfzy.top/Article/details/gtsbmnpkvy.html

[H02] finally / ensure 收尾
来源：http://dali.sysykeji.top/Article/details/gtetlrrapc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtxntfdktu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtxplcslax.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtblonirnb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtfldcfpnd.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtctdjfaux.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.feifeiyinyue.top/Article/details/gtktwalyus.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ehwqpu.com/Article/details/gtunuxvegi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtyfatrvoe.html

[H03] 主动抛出异常
来源：http://dali.daxiang520.top/Article/details/gtxrokyoef.html

Py:   raise ValueError("错误信息")
来源：http://dali.ivvv.top/Article/details/gthxumerbm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpierkjwb.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtrqbyaapi.html

TS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtgacglzht.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtvakmlcof.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtdujfdgld.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gtnhoqyuax.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtjomzgoyq.html

[H04] 自定义异常类型
来源：http://dali.zhixingplan.top/Article/details/gtlalwaykk.html

Py:   class MyError(Exception): pass
来源：http://dali.smart0.xyz/Article/details/gtqsgmgosk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtgttwknrx.html

JS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtpjqqhuuz.html

TS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkgyjvryl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gtxeqadoqv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtbggxzktz.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhengqikj.top/Article/details/gtztyugosh.html

C#:   class MyException : Exception {}
来源：http://dali.sxryk.cn/Article/details/gtrbfutswe.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtpiziadhi.html

Py:   except ValueError as e:
来源：http://dali.guowangkeji.top/Article/details/gtpqxhkfoi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.fzhhl.top/Article/details/gtjqgneaqh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guannengcc.top/Article/details/gtkpxxgqxn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gtyacwgvhe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jqgfzy.top/Article/details/gtkxaitzxh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.bjfxy.top/Article/details/gtdrpubujj.html

Ruby: rescue ArgumentError => e
来源：http://dali.fengsongda.top/Article/details/gtqolpvbgj.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.redwolf501.top/Article/details/gtzfacwkpt.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtfrafndec.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtqntnnwew.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtjpvjxqel.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gtwdnmxuoy.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hammf.cn/Article/details/gtrrygljph.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gteykshsok.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.hnqzz.top/Article/details/gtsxrsmwmb.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yj20258888.top/Article/details/gtgednjjpz.html

C#:   obj?.A?.B ?? default
来源：http://dali.xziqi.cn/Article/details/gtxpgkewaw.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtrhhrkdqb.html

Py:   assert x > 0, "必须为正"
来源：http://dali.guowangkeji.top/Article/details/gtatyvvpbr.html

PHP:  assert($x > 0);
来源：http://dali.yj202588.top/Article/details/gtvudqufcq.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrptfhtwe.html

TS:   console.assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtgmxvzlab.html

Java: assert x > 0 : "必须为正";
来源：http://dali.kuanghao11.cn/Article/details/gtnxugjpyt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cucudq.cn/Article/details/gtbtxnakqi.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtrhzbjgej.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gtkoiuwuoa.html

[H08] 获取错误信息与堆栈
来源：http://dali.gaohongyu789.top/Article/details/gtlqhbwtsk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.redwolf501.top/Article/details/gtyqqanmcx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtpcqmqrrw.html

JS:   e.message;  e.stack
来源：http://dali.hfpthk.cn/Article/details/gtmnufpiub.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.daxiang520.top/Article/details/gtnaxfpvva.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.aizwys.cn/Article/details/gtulpcsgcu.html

Go:   err.Error()
来源：http://dali.dianchejie.cn/Article/details/gtyjrqglwh.html


<!-- 参考信息 -->