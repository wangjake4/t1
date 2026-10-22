代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtdghujyvk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gthsauoezp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gtuihiuxum.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvgnkhrk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgufenzy.top/Article/details/gtfxpgrfaj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtbwpbvrno.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtyfumucgf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtwikfalxx.html

[F05] 判断文件或目录是否存在
来源：http://dali.ybcxt.top/Article/details/gtqpiknyvp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gtkkqnpddx.html

PHP:  file_exists("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtarzrpbhw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtwgeksoza.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtzlzjqmpx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtuqeskmtb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtanasvurh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtzadffahn.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmndnzzpl.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtxiiqmcjh.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxysvdrbt.html

PHP:  unlink("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtbxatokfp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtfcpgjntj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtslmgvkhx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jlsjyb.cn/Article/details/gtpmstleir.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtcppdxika.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuierbfsi.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtdcfunvkc.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gtzjwmlxwt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gtrctculaw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinqigfzy.top/Article/details/gtlqtxucib.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfzurdnr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dashuyun.cn/Article/details/gtgxlgumbx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtczubhwqz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xziqi.cn/Article/details/gtpaqhjoim.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cucudq.cn/Article/details/gtlrkxcjxm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizfzznqk.html

[F08] 遍历目录
来源：http://dali.ydzc1.top/Article/details/gtxozavlhx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscojxmhr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gthtyxexdr.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtbdkjljqn.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtwkdyvjgl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtfokhikcu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shuidangran.top/Article/details/gtlqwwarso.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtommgrzkd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtreqzbfrr.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtaoifkycu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtujdblssf.html

PHP:  filesize("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtxnrrohph.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtbgxskxue.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jlsjyb.cn/Article/details/gtilglnbup.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtqsorwmuc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gtfyeqzdfd.html

Ruby: File.size("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtolbwplrs.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gtdjnkwzsw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gtyqvkwaxl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtbezanfec.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtdpnmrwax.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosyjwsnd.html

TS:   path.extname("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtcfazgklh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gtwbrgdsmy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gttlulvoed.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtydblwfcj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaqlhhbt.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gttfilpyxg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtgrpgxvzh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtwskryqiw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtillowttv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtremljjdl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gttzmmymvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcynwzhe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtxpxpxtoe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yangfankeji.com/Article/details/gtveetrgkm.html

[F12] CSV 读写
来源：http://dali.xinyue.icu/Article/details/gtcbggbaxx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gtevqkyevi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aibaodan.cn/Article/details/gtddianzjq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nwbrower.top/Article/details/gtoxwdwpqt.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtzxscqmap.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gtcalbvxgs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jqgufenzy.top/Article/details/gtnrkjnqtv.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tianlin.xyz/Article/details/gtrxqyvqmi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gttnlcetks.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsyufkkbq.html

G. 面向对象
来源：http://dali.gogol.net.cn/Article/details/gteqoqaojf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvtthmkeg.html

[G01] 定义类
来源：http://dali.hammf.cn/Article/details/gttesqbkkq.html

Py:   class User: pass
来源：http://dali.316326.xyz/Article/details/gtqgbeowhi.html

PHP:  class User {}
来源：http://dali.yonumen.top/Article/details/gtetgmdkjw.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtyescjzwp.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtybdqykwf.html

Java: class User {}
来源：http://dali.zhengqikj.top/Article/details/gtgcctbkqx.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gtkvxyeqmx.html

Ruby: class User; end
来源：http://dali.fzhhl.top/Article/details/gtsbmvigao.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gtejptrijy.html

[G02] 构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtajtbaqot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhijiandao.cn/Article/details/gtchjbaxjk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenlongwang.top/Article/details/gtyrnmhlmw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yvedp.cn/Article/details/gtdzkcrwog.html

TS:   constructor(public name: string) {}
来源：http://dali.sxryk.cn/Article/details/gtfewdozcd.html

Java: User(String name) { this.name = name; }
来源：http://dali.gaohongyu789.top/Article/details/gtgilgjmra.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yangfankeji.com/Article/details/gtawmsyxdq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtzsosgqqn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gtjzjpqauu.html

[G03] 实例属性
来源：http://dali.cqqwz.cn/Article/details/gtffoiupdj.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtefsqfjxo.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gtqpxnflnh.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gtnrwuzarm.html

TS:   name: string = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymysymnt.html

Java: private String name;
来源：http://dali.chenzaomai.com/Article/details/gtelkgzjuj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gtmwsagcra.html

Ruby: @name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpecvwukz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pycfn.com/Article/details/gtnhixsyhv.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gtnwcnzqbe.html

Py:   def greet(self): return self.name
来源：http://dali.ydzc1.top/Article/details/gtntimjwbn.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqumtfavo.html

JS:   greet() { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtpbgvbdhu.html

TS:   greet(): string { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfkirbtop.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtbsgvwgws.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gttvzneslm.html

Ruby: def greet; @name; end
来源：http://dali.sufxvd.cn/Article/details/gtrdjmvjbc.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtjcljdjnv.html

[G05] 继承
来源：http://dali.daxiang520.top/Article/details/gtiyurxbmi.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtupyenaiq.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtmspyywop.html

JS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtwnmnmlgw.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxuqhykm.html

Java: class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gtpuhgdcef.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtclsrpegf.html

Ruby: class Admin < User; end
来源：http://dali.jiagoushi.top/Article/details/gtrimzsnxh.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gttafxupsc.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtifmzztjj.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtvtxtchmr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsexbeldi.html

JS:   greet() { return "admin"; }
来源：http://dali.yueranfly.top/Article/details/gtmmyvsbrb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtxlolxvvi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtslfhbnhw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.dianchejie.cn/Article/details/gtugippuwr.html

Ruby: def greet; "admin"; end
来源：http://dali.xuetiantiany.cn/Article/details/gtsnhvuefv.html

C#:   public override string Greet() => "admin";
来源：http://dali.birdmap.top/Article/details/gtzshbiavo.html

[G07] 调用父类方法
来源：http://dali.tian-w.cn/Article/details/gtdqigjhio.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gtwjctzvnt.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gtlzkhovhs.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhojbqph.html

TS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtpkygssrl.html

Java: super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtfgfalhaq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.fzhhl.top/Article/details/gtmrhctkwo.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtdptvwels.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtbfrsiqzi.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gteqxhzuwk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhixingplan.top/Article/details/gtggomfuuo.html

PHP:  public static function f() {}
来源：http://dali.ehwqpu.com/Article/details/gtikftmlle.html

JS:   static f() {}
来源：http://dali.jiagoushi.top/Article/details/gtysnlbzuu.html

TS:   static f(): void {}
来源：http://dali.sweek.top/Article/details/gtdotruvhv.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gtilmywnup.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yanxiufei.cn/Article/details/gtpgkzbpfa.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gtlltexrsn.html

C#:   public static void F() {}
来源：http://dali.yj20258.top/Article/details/gtbmhxcmpk.html

[G09] 接口 / 抽象类
来源：http://dali.shzxlz.cn/Article/details/gtslptrxcm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtghvfrhqv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.tian-w.cn/Article/details/gtchdvnkbb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtcxbmcizl.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gtthcgnhop.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gtsherrxio.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwuenodv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.0kj1m.cn/Article/details/gtwatjzgnm.html

C#:   interface IShape { double Area(); }
来源：http://dali.ybcxt.top/Article/details/gtstxjljpi.html

[G10] 访问控制
来源：http://dali.ivvv.top/Article/details/gtjwtezlny.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtcsesskjr.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtuasdafuc.html

JS:   #private 字段；其余公开
来源：http://dali.sweek.top/Article/details/gtjcazrpdg.html

TS:   public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtgebdruur.html

Java: public / protected / private / 默认包级
来源：http://dali.iojbl.cn/Article/details/gtavdrsyyc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtqpztuujm.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gtohnmjtxp.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gttcuhuhuj.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtlgdutokb.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gtcvhzpxai.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtlbpbzpdu.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtujhsopsm.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gtotwcdxnm.html

Java: public String getName() { return name; }
来源：http://dali.nwbrower.top/Article/details/gtfjgvyelv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gtdrdoqoik.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gtjsqlqhkl.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gtdkmavkbu.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtrfqeuwgf.html

Py:   def __str__(self): return self.name
来源：http://dali.ehwqpu.com/Article/details/gtvlxasrfm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gtxfiqfbuf.html

JS:   toString() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtuajcwcip.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gtnmypbrfg.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtxqfuuskz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtjvkyrxhr.html

Ruby: def to_s; @name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhyeouuq.html

C#:   public override string ToString() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwoqalunb.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gtbbzmqszv.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtxopvzyhj.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtetjsjkkv.html

JS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtkxizxskb.html

TS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gtcveoponz.html

Java: u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtemzouqxa.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gttvffwypd.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtonaqnqqx.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gtbsepjaae.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtepzxwytq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gtvebihfwe.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtkrewycpo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.316326.xyz/Article/details/gtuqziulaf.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gtdlttueeb.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gtakfyhuse.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhoulong.xyz/Article/details/gtwmvesoxq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xinyue.icu/Article/details/gtvzggsubk.html

C#:   record User(string Name, int Age);
来源：http://dali.redwolf501.top/Article/details/gtwmhpexpw.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtakygzqlw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.snrcjt.cn/Article/details/gtuoiguous.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbtzwmke.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gtmwqgvkxz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenlongwang.top/Article/details/gtfajjboda.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenjidiqi.icu/Article/details/gtjgtrajsw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gtijaoenrg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.daxiang520.top/Article/details/gtwbirfasj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gtqfdpvbea.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gtwjzfumhw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtdlyilzgz.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gtadymsbku.html

JS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gttxomilom.html

TS:   Object.entries(obj)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpkatxxe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.kuanghao11.cn/Article/details/gtxwgvbwrm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jianghu66.top/Article/details/gtcjcqxmvv.html

Ruby: obj.instance_variables
来源：http://dali.316326.xyz/Article/details/gtkjgihnij.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtriiqvmmd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtzfdcymvn.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gticatlild.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwgbksslk.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtjuhjsyft.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fzhhl.top/Article/details/gtbbylbwcb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhijiandao.cn/Article/details/gtpgaxtgcy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jlsjyb.cn/Article/details/gtzqycvrvj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.pengpengdd.cyou/Article/details/gtklvsnidu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gtoymedbwy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gtuarrytkx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafhddxgi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.dianchejie.cn/Article/details/gtsyfahjth.html

[H02] finally / ensure 收尾
来源：http://dali.ppjwa.cn/Article/details/gtmuqbeafy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gotoacloud.top/Article/details/gtekufafop.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtlkqbxgyf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtrwredwxi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gtdlahwojz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtasiyzvvh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhengqikj.top/Article/details/gtdtxxtbcl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinqigufen.top/Article/details/gtfhdjaelq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gthvfrffte.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtbubtrhlq.html

Py:   raise ValueError("错误信息")
来源：http://dali.c1oappe.top/Article/details/gtkjvmtpqb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gthyandgzt.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtnnnuooix.html

TS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gttxznxnik.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtgplrqnwp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gtpfgvorsc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.andypj.xyz/Article/details/gthnnthbhl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtuifqtyas.html

[H04] 自定义异常类型
来源：http://dali.haohaochexian.top/Article/details/gtpljfphux.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkcctngp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtzkyhumjh.html

JS:   class MyError extends Error {}
来源：http://dali.hywenlv.cn/Article/details/gtfakixiti.html

TS:   class MyError extends Error {}
来源：http://dali.jqgufenzy.top/Article/details/gttrhtasdh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dianchejie.cn/Article/details/gtvqlisowv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.quarkkingdee.top/Article/details/gtrueiuiaq.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtbhrsdsrh.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gtkxxmqlrm.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gtkkmfcnzu.html

Py:   except ValueError as e:
来源：http://dali.hongshengwenyu.top/Article/details/gtovqpvwgi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gaohongyu789.top/Article/details/gteqkicxio.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gtyrmemffq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gtdjiydvld.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cheryme.top/Article/details/gtrmekbdof.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtrajtspdh.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gtktktzjrw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtwpyvxiqn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xuanzx.com/Article/details/gtzocuuitb.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gtovabxpzd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuetiantiany.cn/Article/details/gtwrpeftty.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ehwqpu.com/Article/details/gtaamvvvub.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhengqikj.top/Article/details/gtamzweofk.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.nwbrower.top/Article/details/gtcirodtlk.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.chenjidiqi.icu/Article/details/gtkywshfur.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtbekfefyn.html

C#:   obj?.A?.B ?? default
来源：http://dali.zdqjudy.top/Article/details/gtbfbwuofv.html

[H07] 断言
来源：http://dali.xuetiantiany.cn/Article/details/gtnpjkyxbj.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbwnjceh.html

PHP:  assert($x > 0);
来源：http://dali.yj20258888.top/Article/details/gtmekelhhi.html

JS:   console.assert(x > 0);
来源：http://dali.pengpengdd.cyou/Article/details/gttidjkepv.html

TS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtvbjkymra.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cqqwz.cn/Article/details/gtnbzquipf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtzqekmlwq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cqqwz.cn/Article/details/gtzpcvzsqo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xuanzx.com/Article/details/gteieoikrh.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtbqifxcaa.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhijiandao.cn/Article/details/gtjqofmgfh.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.fzhhl.top/Article/details/gtbopligdd.html

JS:   e.message;  e.stack
来源：http://dali.tanke756.top/Article/details/gtpkkdcvte.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.smart0.xyz/Article/details/gtooqjmalh.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shuidangran.top/Article/details/gtsrvihhfb.html

Go:   err.Error()
来源：http://dali.hnqzz.top/Article/details/gtofgbkifb.html


<!-- 参考信息 -->