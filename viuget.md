代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gtsqmqcyli.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtxktnndlk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtrshxwczz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtvgqiburo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtvytrkfgr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtqjihfrju.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtrsvmecfj.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtmxmjrndv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gttgeozfxu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtvmwvqgen.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtgxtuqedn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gtnakhamza.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtzjuqiifn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hammf.cn/Article/details/gtbzaxtcyo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gtmegcigmt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtrflkqiyj.html

[F05] 判断文件或目录是否存在
来源：http://dali.ppjwa.cn/Article/details/gtunvtmjtu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.kuanghao11.cn/Article/details/gtcvxjssmn.html

PHP:  file_exists("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtsfojmsci.html

JS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtygzocpbl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbstqovht.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtcfkvjgex.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtylsggipj.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gttztfbscw.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnvrigsxw.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwdlyjry.html

Py:   os.remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtseoazazu.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtauhbwipm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gttvsnvqpa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnmhkkxeb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtvutdtlwv.html

Go:   os.Remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbjgvbumw.html

Ruby: File.delete("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtsmaburhy.html

C#:   File.Delete("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gtuxskjlju.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gthbhuzpey.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtbotxcdvc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhoulong.xyz/Article/details/gtkjbfhojt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtatgxmsuh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gtymytaeet.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gtpbeaiikv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtxlhavrox.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gogol.net.cn/Article/details/gtezewnqnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daria6918.cn/Article/details/gttdrdxcbh.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtshaxteup.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sysykeji.top/Article/details/gtsleyskhh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtcmkfrzax.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtcvilhwpp.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtyofosdvx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtnmuuhguj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtfexnuohi.html

Ruby: Dir.children("dir")
来源：http://dali.xziqi.cn/Article/details/gthmdzwbqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gtdulqxqlh.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gtainybgif.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuntpfxdz.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtqndgnewe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtleilmyjn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gttsewtycn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtdemubauv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.9152youxi.cn/Article/details/gthhbnhooz.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtagarrsom.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpizvleb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gtaemrdwri.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gttiehwtmz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtahevghcw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtshhrlrqz.html

TS:   path.extname("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtsiqiusrg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gtoahvqrwl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuohszgxn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtgdnkdvby.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtseeecagm.html

[F11] 复制与移动文件
来源：http://dali.tanke756.top/Article/details/gtooiubrue.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaspipjq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvccsvvqk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuanzhike.top/Article/details/gtetdjtfgn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtsrlvsxxy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.andypj.xyz/Article/details/gtduntbqys.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtfiemvrfz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtjhpzccnk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtohvhibej.html

[F12] CSV 读写
来源：http://dali.tian-w.cn/Article/details/gtalwvvtns.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gtidlguzga.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtuxkaiyep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gtuzbwwsrt.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtyqddggcq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtlkdogalv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuanzhike.top/Article/details/gtrvaeavnd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtlqggzthz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gtzdwpyxqh.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxludwsnu.html

G. 面向对象
来源：http://dali.sysykeji.top/Article/details/gtyqusyhwj.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtsnkggvnv.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtuyttvbqz.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtewuvdjym.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtzimzofvz.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gtkejsyvfa.html

TS:   class User { name: string = ""; }
来源：http://dali.cqqwz.cn/Article/details/gtrqabhfax.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtcfczufrd.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gtzywchvbj.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gtogaewenh.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtgrfixkvx.html

[G02] 构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtijghyxlm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yonumen.top/Article/details/gthnkshmbk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtsogaqwkk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtgddnuumy.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtxlufsaow.html

Java: User(String name) { this.name = name; }
来源：http://dali.guannengcc.top/Article/details/gtzlgswxpi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtnzrpjpyq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtnqlrwauw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gtdijpuxbv.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtyosqzoyq.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gtkguxkolk.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtvejnrpcz.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtxywmeker.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtwzhrjvpg.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtwuqjuwtm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gtvjoxuvzw.html

Ruby: @name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gtdhahnrla.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtvhfsqcnv.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtqtgjonup.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gthlglfrnj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gthnhuixka.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtscjpgdyc.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtqkdpdyzk.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtydxiitsb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gtsziemocl.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gttikvvsxl.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtbatqcelx.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gttdcteguk.html

Py:   class Admin(User): pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxkfrgbl.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtimiqviau.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtqwonbtws.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtdptrjdxs.html

Java: class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gtdzdzegpx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gtywnabmiu.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gtdotzzmzd.html

C#:   class Admin : User {}
来源：http://dali.hfpthk.cn/Article/details/gteylrxbjj.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gtxuytvrra.html

Py:   def greet(self): return "admin"
来源：http://dali.iojbl.cn/Article/details/gtosyqcrlh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtofjcakyw.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gtbrgsvxlq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtlqjrasnp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtehqbrche.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtadgoiwcd.html

Ruby: def greet; "admin"; end
来源：http://dali.tianlin.xyz/Article/details/gtvoyzuunn.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtiodxfadt.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gtajzypirc.html

Py:   super().greet()
来源：http://dali.jqgufenzy.top/Article/details/gtmtxcfqvx.html

PHP:  parent::greet();
来源：http://dali.dashuyun.cn/Article/details/gtyjqenpiv.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gtvdzbheuo.html

TS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtcvdtnogf.html

Java: super.greet();
来源：http://dali.cdnleiting.top/Article/details/gtrnjlubyz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gtlnjyjxev.html

Ruby: super
来源：http://dali.zhengqikj.top/Article/details/gtnqbyrzwe.html

C#:   base.Greet();
来源：http://dali.yuanzhike.top/Article/details/gtfaajiwpp.html

[G08] 静态方法与属性
来源：http://dali.sufxvd.cn/Article/details/gtpbojlvze.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xziqi.cn/Article/details/gtqoyawwdw.html

PHP:  public static function f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gtpebnfvmu.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtmxdahhlu.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gtghnuhwpz.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gtftessery.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gogol.net.cn/Article/details/gtccssqqwf.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gtivihcbln.html

C#:   public static void F() {}
来源：http://dali.aibaodan.cn/Article/details/gtlhqrzryt.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtkgzzrtmr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gtwmwwbjwz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsqqkvij.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzricxoj.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtessyyzko.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtlzqdgdld.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhixingplan.top/Article/details/gtododyven.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jyoumei.cn/Article/details/gtyndwhgdy.html

C#:   interface IShape { double Area(); }
来源：http://dali.cqqwz.cn/Article/details/gtsmnmzghw.html

[G10] 访问控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfxsxqqa.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gtqryknvcb.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtbcemxrek.html

JS:   #private 字段；其余公开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwixuihaa.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtnfyefjlp.html

Java: public / protected / private / 默认包级
来源：http://dali.yuxming.cn/Article/details/gtkitcsdyj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gttanoogne.html

Ruby: public / protected / private
来源：http://dali.jianghu66.top/Article/details/gtautnhapm.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gtxmgchumx.html

[G11] getter / setter
来源：http://dali.zhoulong.xyz/Article/details/gtufaprdlg.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gttmwrybmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gtdinvkxnv.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtfkqmvqtk.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgmfonxrb.html

Java: public String getName() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkdqejhon.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ybcxt.top/Article/details/gtaiucpabw.html

Ruby: attr_accessor :name
来源：http://dali.gaohongyu789.top/Article/details/gtzqxjhlqn.html

C#:   public string Name { get; set; }
来源：http://dali.fengsongda.top/Article/details/gtzvobhwma.html

[G12] 对象转字符串
来源：http://dali.pycfn.com/Article/details/gtixyabxwx.html

Py:   def __str__(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gtmtezhkhn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfjhoqprs.html

JS:   toString() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gtuswxiagl.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gtchciabwd.html

Java: @Override public String toString() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtplxmakks.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gterxgvgdn.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtbdnrqfth.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gtgpwrwhcw.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gtwwkpdoty.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtdponoiwc.html

PHP:  $u instanceof User
来源：http://dali.dianchejie.cn/Article/details/gtmphhquda.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtivpmdjtv.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtycmtbbvz.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtzhsyxfgo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gtswvyebcr.html

Ruby: u.is_a?(User)
来源：http://dali.yueranfly.top/Article/details/gtcdbilozd.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gtcrmrrkdh.html

[G14] 数据类 / record
来源：http://dali.yangfankeji.com/Article/details/gtvurfjwwa.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtqsihlagd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gtlthuyvfk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtfwzijhgo.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhixingplan.top/Article/details/gtmychrpcm.html

Java: record User(String name, int age) {}
来源：http://dali.sysykeji.top/Article/details/gtpazjwavg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.aibaodan.cn/Article/details/gtjhotnecy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sweek.top/Article/details/gtbxwgmjdh.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gtvvvfijez.html

[G15] 枚举
来源：http://dali.ppjwa.cn/Article/details/gttpyucohd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.9152youxi.cn/Article/details/gtulcfbuai.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmlwuylkx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.haohaochexian.top/Article/details/gtxnxodpmv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtzaigmeif.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gttndachnn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yonumen.top/Article/details/gtwjbjfjxf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gttngqloau.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtbykgaioy.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtkalsdldw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.9152youxi.cn/Article/details/gtnktjsxpl.html

PHP:  get_object_vars($obj);
来源：http://dali.quarkkingdee.top/Article/details/gtrguvkulk.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gtivwkzvxl.html

TS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gttiwugyal.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xylfe.cn/Article/details/gtszgiibqu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gtkjmlyvnq.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gtlvnafprp.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtoqisofgn.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtvxvgjivj.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gtlokxwlvc.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpkrssafp.html

[H01] try / catch 基础
来源：http://dali.zycfv.cn/Article/details/gtqmxugwsx.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinqigufen.top/Article/details/gtgcitegls.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.quarkkingdee.top/Article/details/gtzvhziltz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gtkdybyqiu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gtngbvpeoj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zycfv.cn/Article/details/gtqtlgcjlh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gttqdusiub.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gtbrhtcxlv.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gthoiitrpv.html

[H02] finally / ensure 收尾
来源：http://dali.quarkkingdee.top/Article/details/gtmtvdkblg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shangyingyoupin.top/Article/details/gtddhkfvtc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzxyfccyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gtkmortias.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxlfbdepv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gthvmohebd.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtplhsgfaw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yj202588.top/Article/details/gtelirxabc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfloycspt.html

[H03] 主动抛出异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsshujew.html

Py:   raise ValueError("错误信息")
来源：http://dali.aizwys.cn/Article/details/gthiwijdva.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgwfdjym.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmdljzve.html

TS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gthxsylcnr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tian-w.cn/Article/details/gtohigawbk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gtqvilsypu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.316326.xyz/Article/details/gtoqgomvbo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtklkeutay.html

[H04] 自定义异常类型
来源：http://dali.dianchejie.cn/Article/details/gtizfgutpz.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtihfwohfh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.c1oappe.top/Article/details/gtgiusuxhq.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtzshrfwdt.html

TS:   class MyError extends Error {}
来源：http://dali.nwbrower.top/Article/details/gtnktbccmo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yj20258888.top/Article/details/gtfovzptft.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.tianlin.xyz/Article/details/gtkvdhzbgk.html

Ruby: class MyError < StandardError; end
来源：http://dali.bjfxy.top/Article/details/gtdqrptkjd.html

C#:   class MyException : Exception {}
来源：http://dali.hywenlv.cn/Article/details/gtddjxqxjt.html

[H05] 捕获特定类型
来源：http://dali.pycfn.com/Article/details/gtixdqvdzt.html

Py:   except ValueError as e:
来源：http://dali.nwbrower.top/Article/details/gtwshkfgru.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cucudq.cn/Article/details/gtthkexryb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtizileabt.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtuikfnyet.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gtoozyilns.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.wangdashe.top/Article/details/gteaukprmk.html

Ruby: rescue ArgumentError => e
来源：http://dali.sufxvd.cn/Article/details/gtrscykqmr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.andypj.xyz/Article/details/gtexepjhxx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ybcxt.top/Article/details/gtonwopvoo.html

Py:   value = d.get("k") or default
来源：http://dali.hnxiangtu.top/Article/details/gtqurtzxhd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtatqfrosb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtiqvnbire.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gtmoxzlqxw.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.ydzc1.top/Article/details/gtgjhoeess.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhixingplan.top/Article/details/gtqzhrvwed.html

Ruby: d&.dig(:a, :b)
来源：http://dali.guannengcc.top/Article/details/gtecovlded.html

C#:   obj?.A?.B ?? default
来源：http://dali.hammf.cn/Article/details/gtlulyagca.html

[H07] 断言
来源：http://dali.cashguo.top/Article/details/gtpbgldfnr.html

Py:   assert x > 0, "必须为正"
来源：http://dali.gogol.net.cn/Article/details/gtxkbkorio.html

PHP:  assert($x > 0);
来源：http://dali.yj20258.top/Article/details/gtnnwnphym.html

JS:   console.assert(x > 0);
来源：http://dali.chenlongwang.top/Article/details/gteognainv.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtwhbcttcw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yj20258.top/Article/details/gtcqgmqwkl.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jyoumei.cn/Article/details/gtytckgsla.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gtstytqoze.html


<!-- 参考信息 -->