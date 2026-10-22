代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2uskttdwu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2rdbhziem.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2azhnrzxv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.fengsongda.top/Article/details/gt2alehxnos.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2xwpfrfmv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhixingplan.top/Article/details/gt2fbynjmgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2uxazsckf.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gt2qszunutv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gt2vyjrcbmw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuxming.cn/Article/details/gt2htmrtqsb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2lhihwwag.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2vsqvilrr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gt2mbyzjefk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gt2fbpdkxxf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2rtkfqkpn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2wrnyzxle.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2vvrsxzos.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gt2gcrsatsw.html

PHP:  file_exists("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2nxvajhhb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2yjarcyqv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cxajnbma.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzhtswms.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2wmuhrcls.html

Ruby: File.exist?("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2howznvsg.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyqfzpde.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gt2vgvjgrze.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfvpeecp.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2sxchobmv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2digmtfja.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2acbodqun.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2vovybcgx.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2pfqginxv.html

Ruby: File.delete("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgrpwzkr.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2rsvhbjdf.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwwuvhyq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2uizxnsfe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnqzz.top/Article/details/gt2somkynfz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhengqikj.top/Article/details/gt2vpkymdve.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2sipbaukd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aizwys.cn/Article/details/gt2qcoxtytp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gt2xzxtznzj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shzxlz.cn/Article/details/gt2yswswowh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gt2cdqdgqye.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2whafxapg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2mzneanen.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgfzy.top/Article/details/gt2fbkihdpa.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2cqvtciyw.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2jrijmltt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2fbbyifkg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qepbjvkx.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2wrtozuqx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangdashe.top/Article/details/gt2fazhvvzn.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2xbskfozj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2sxormaxn.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2hppotzsd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2pckjhllg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2hkhslarv.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2hpvqvymt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2exzjvfyc.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2evvrrpoe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gt2wufywspd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gt2ypbzpbqh.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2jmvhlkyj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yoijnuwk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2bquocnpd.html

TS:   path.extname("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2mwjtwlnw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gt2iukkcwpy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2qdjykhis.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kyilozqn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2dcwbnltv.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gt2xefbpvri.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2hqkwvnis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2ylfjueba.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2hjknvywl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2wzwexxzq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gt2okkymdnu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aruevguq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2knyodjmu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2mejceuuu.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gt2gnhwkhnx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bsmszanz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gotoacloud.top/Article/details/gt2pinspski.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2zrhlwxgd.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gt2vqvztkqw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.c1oappe.top/Article/details/gt2pcnkzpfh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yuxming.cn/Article/details/gt2yqufrsiu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2omklebig.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhongyouzk.top/Article/details/gt2efdqotfw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gkhfqduo.html

G. 面向对象
来源：http://dali.ybcxt.top/Article/details/gt2qmoiesji.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgaeyujn.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2eipxdhdd.html

Py:   class User: pass
来源：http://dali.ybcxt.top/Article/details/gt2zkxrdpgj.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2tkogxwgd.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2sfqpuqrg.html

TS:   class User { name: string = ""; }
来源：http://dali.gotoacloud.top/Article/details/gt2jfevvxjx.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2zhotporx.html

Go:   type User struct { Name string }
来源：http://dali.birdmap.top/Article/details/gt2bfujtpju.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gt2ffklnxgt.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gt2owkbxvxc.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2zfzyyjjf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gt2wedfqpun.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2bikeyjkh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2iizqcoah.html

TS:   constructor(public name: string) {}
来源：http://dali.zhixingplan.top/Article/details/gt2kicgyzef.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ctzvwcrz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gt2ydqywkum.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2tfaceega.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2vjzwadrh.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gt2dhooujiv.html

Py:   self.name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjiujvwz.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2ledpjwyu.html

JS:   this.name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2qndmidcv.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gt2kelwxplp.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2gikkllby.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pycfn.com/Article/details/gt2rqsstqlt.html

Ruby: @name = "x"
来源：http://dali.sxryk.cn/Article/details/gt2qqtlzmme.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yvedp.cn/Article/details/gt2shslgnqu.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gt2mulopvve.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gt2rjoiphwq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sfynemuj.html

JS:   greet() { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2vsnodamd.html

TS:   greet(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2kbxucidm.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2rqjooxvl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gt2najdqveh.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dcprpggo.html

C#:   public string Greet() => Name;
来源：http://dali.zhixingplan.top/Article/details/gt2mtgtoivl.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gt2gjbiepee.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gt2labwkjwt.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2vkgtwpzg.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ppphsoji.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2ytcurfgq.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2fgccetlm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxinkj.top/Article/details/gt2snhbbguh.html

Ruby: class Admin < User; end
来源：http://dali.jianghu66.top/Article/details/gt2bibbltun.html

C#:   class Admin : User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2amxlqxig.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2yunwjdsl.html

Py:   def greet(self): return "admin"
来源：http://dali.xuetiantiany.cn/Article/details/gt2innewhmu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gt2rptkaapg.html

JS:   greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2fotelctj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ivxczlde.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2drvlstti.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbgkqibx.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigfzy.top/Article/details/gt2dotjcepp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2yilcjmde.html

[G07] 调用父类方法
来源：http://dali.cucudq.cn/Article/details/gt2urevryhd.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gt2rlbsmhhy.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2ddisoibe.html

JS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2giequusb.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2mvbbstbl.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2kjeliplo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gotoacloud.top/Article/details/gt2lymqzjfd.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2hsmavcus.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2pvsvvwac.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2gnwdjnxk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gt2ojmbrehq.html

PHP:  public static function f() {}
来源：http://dali.yj202588.top/Article/details/gt2ddrwjtdr.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2qljmmzje.html

TS:   static f(): void {}
来源：http://dali.jyoumei.cn/Article/details/gt2vrlmnyya.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2xlawdthn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gt2uoelablw.html

Ruby: def self.f; end
来源：http://dali.cashguo.top/Article/details/gt2hytlzzxc.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gt2rqlxgwlk.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gt2rstwspyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxjnyzvo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2ldulrjro.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhijiandao.cn/Article/details/gt2cujqznuq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aqrvyrcy.html

Java: interface Shape { double area(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2rfljpevl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gt2kbkhrrtq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2cdeyciha.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gt2dsqqrcfm.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gt2fikngewz.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhoulong.xyz/Article/details/gt2uqeqbycg.html

PHP:  public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2bpjndnji.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gt2jchvkewe.html

TS:   public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2pkffwkih.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gt2ewhjxbty.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yanxiufei.cn/Article/details/gt2fjxgmbeq.html

Ruby: public / protected / private
来源：http://dali.hywenlv.cn/Article/details/gt2oxtwnjqo.html

C#:   public / protected / private / internal
来源：http://dali.xuanzx.com/Article/details/gt2rksgwhmq.html

[G11] getter / setter
来源：http://dali.gotoacloud.top/Article/details/gt2kgzoiorr.html

Py:   @property 与 @x.setter
来源：http://dali.shzxlz.cn/Article/details/gt2eyoqaclu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gt2jlgcnvbn.html

JS:   get name() { return this._name; }
来源：http://dali.jianghu66.top/Article/details/gt2tktsqeed.html

TS:   get name(): string { return this._name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2toeewakv.html

Java: public String getName() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ddmxezxl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2ghgnosre.html

Ruby: attr_accessor :name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfntaeel.html

C#:   public string Name { get; set; }
来源：http://dali.havefunace.top/Article/details/gt2socbszym.html

[G12] 对象转字符串
来源：http://dali.316326.xyz/Article/details/gt2siwyqapl.html

Py:   def __str__(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gt2izcjmmdj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2oyyhugrr.html

JS:   toString() { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2ltxpjoty.html

TS:   toString(): string { return this.name; }
来源：http://dali.guannengcc.top/Article/details/gt2chkeyogj.html

Java: @Override public String toString() { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2pfyujmmx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2uveagpon.html

Ruby: def to_s; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gt2vacufmug.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2oiolicvn.html

[G13] 判断对象类型
来源：http://dali.hysaishi.cn/Article/details/gt2jqxmyevp.html

Py:   isinstance(u, User)
来源：http://dali.vqdsnc.cn/Article/details/gt2nxhjqmor.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2ebljarcc.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2epohpiie.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gt2hbdookcl.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2efyyxaji.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cucudq.cn/Article/details/gt2qhuydncj.html

Ruby: u.is_a?(User)
来源：http://dali.zdqjudy.top/Article/details/gt2zknuuvmf.html

C#:   u is User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2slzzaiao.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2zgwfxudh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gt2hkvbfydx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gogol.net.cn/Article/details/gt2vsridhmj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sysykeji.top/Article/details/gt2fyjxbewj.html

TS:   type User = { name: string; age: number };
来源：http://dali.hongshengwenyu.top/Article/details/gt2rqwhapbf.html

Java: record User(String name, int age) {}
来源：http://dali.aizwys.cn/Article/details/gt2pmzsdhak.html

Go:   type User struct { Name string; Age int }
来源：http://dali.birdmap.top/Article/details/gt2ictcllsy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cheryme.top/Article/details/gt2bruinlwm.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gt2fidoyrqa.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gt2tffhbbng.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2wtsasqgh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj202588.top/Article/details/gt2qmbekppj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.quarkkingdee.top/Article/details/gt2ggixjpka.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2iqezvxtq.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2vriplnla.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wioeupjy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2oeefjcgm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2jgjqlbyl.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgfzy.top/Article/details/gt2bzpkcwxm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2kgdgpruj.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gt2ywikjqox.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2fctytmsa.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2dwatksji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gt2xvmdmxek.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.andypj.xyz/Article/details/gt2pvwrwpnu.html

Ruby: obj.instance_variables
来源：http://dali.c1oappe.top/Article/details/gt2qtnbpzxi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jinqigfzy.top/Article/details/gt2tqprqhcj.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2pciqigxz.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2gffdltto.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2llqagshy.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdzuxpw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gt2jixtyuhx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2euiskkcb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2qrqhledp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2fsiacxiu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gt2wpogkwas.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2spiowwrf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yueranfly.top/Article/details/gt2hlrfzbpl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dpodcziq.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gt2ixbfpfgz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guannengcc.top/Article/details/gt2kzrejorc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gt2rctvkcxh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2odozschi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2nfkuxfpc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2cnwscgrr.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yangfankeji.com/Article/details/gt2fsxjzwwh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gt2slgosrtd.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2kktuuuuh.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzzuiynd.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2sssyqdmm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2uewfbnno.html

JS:   throw new Error("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2xacxukmn.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gt2qhdbxrbn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2hndiinja.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zdqjudy.top/Article/details/gt2pzblzyyj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2wlkicuya.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2mxkpxgni.html

[H04] 自定义异常类型
来源：http://dali.hfpthk.cn/Article/details/gt2hfyntmzx.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2bsnvzgpa.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojhgqlob.html

JS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2kjpnrbxg.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2hsfwjqiw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2llyppsue.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gt2cjtruzdi.html

Ruby: class MyError < StandardError; end
来源：http://dali.shuidangran.top/Article/details/gt2xvzwkdwj.html

C#:   class MyException : Exception {}
来源：http://dali.yvedp.cn/Article/details/gt2gpylgsnp.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gt2spqsyuwg.html

Py:   except ValueError as e:
来源：http://dali.nanxuanxn.top/Article/details/gt2awnejldq.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jianghu66.top/Article/details/gt2qnwsivyh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hysaishi.cn/Article/details/gt2nkcccmar.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.dashuyun.cn/Article/details/gt2prupofuu.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gt2sxogqnwq.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gyjtvfpb.html

Ruby: rescue ArgumentError => e
来源：http://dali.jyoumei.cn/Article/details/gt2ywenvvbn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gt2yrsnjpao.html

[H06] 可选值 / 空值安全访问
来源：http://dali.xylfe.cn/Article/details/gt2bvvxanpk.html

Py:   value = d.get("k") or default
来源：http://dali.jqgfzy.top/Article/details/gt2gcxgirbn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.cashguo.top/Article/details/gt2oveiynhy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gzhubu.top/Article/details/gt2bgfapfou.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tianlin.xyz/Article/details/gt2ocecgabm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.havefunace.top/Article/details/gt2cusxmswe.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wfimvsgl.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gt2ismawgrr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj202588.top/Article/details/gt2okygjdqi.html

[H07] 断言
来源：http://dali.yuanzhike.top/Article/details/gt2korpgxuc.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhongyouzk.top/Article/details/gt2lfjfykft.html

PHP:  assert($x > 0);
来源：http://dali.nwbrower.top/Article/details/gt2qmrgbhtx.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2udprpfui.html

TS:   console.assert(x > 0);
来源：http://dali.sweek.top/Article/details/gt2bakduhsd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xylfe.cn/Article/details/gt2oxtupnlj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijbbozjm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gt2abhoeldx.html


<!-- 参考信息 -->