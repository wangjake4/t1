代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gtiyhsmetq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jyoumei.cn/Article/details/gtnlmmnocm.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtcmvfrzzc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtkewisgxo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtjafzjvot.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtalpsjksx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtjkydczxn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jiagoushi.top/Article/details/gtyerfquyi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yonumen.top/Article/details/gtnmuwoolo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.svipenyu.cn/Article/details/gtmhdmrqpd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtrmdegzxj.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gtrlodahne.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gtgxwkzsvn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gtfunziscu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtnqyrylsi.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuanzhike.top/Article/details/gtwuewywip.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gtlkmsdsta.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtxucjxaro.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gogol.net.cn/Article/details/gtlycyczmw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gteikpxqyr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtludaleiu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gthqhuzzba.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtpvbozujv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtsrlwmwyt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtiwpujlze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtfklxqqwe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gtvukdtdaq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtuxtgpmxs.html

C#:   File.Exists("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtarugnyar.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtlhxtzoun.html

Py:   os.remove("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtbtidnpgv.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtsjtzxpfv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtjjdteivp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgjhhukkz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtfkjvkhmf.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtfobcjehk.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gtoxxuiwua.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtyuuhelca.html

[F07] 创建目录（含多级）
来源：http://dali.quarkkingdee.top/Article/details/gtyfnnwgwt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtzttomnaw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtdhmjihnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gttuyghach.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtcncqohvl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gtnsmttoxm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtevvshxmw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtegkvmhsr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gtihfrgyds.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gttehgfmci.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gtsqpodpzz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtmorsirmf.html

JS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gteghmulfh.html

TS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gteffbdjoz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gtpnkscega.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtnwhkpsng.html

Ruby: Dir.children("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtinaedqep.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtdyezwhdx.html

[F09] 获取文件大小
来源：http://dali.andypj.xyz/Article/details/gtosffewkh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvbkvpmzh.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtebwklemp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gthauyvqix.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tian-w.cn/Article/details/gthubcctna.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtdgyuacnk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gtxorcnnlt.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtpfoiiopl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gtopubfuqg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnxiangtu.top/Article/details/gtwjysiqxd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gtcbkytsks.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtsunhkuzn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtedykcilw.html

TS:   path.extname("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtybtudhfh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtkzvyiygl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtedkopmtt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtmddrmuxp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtzcrzktus.html

[F11] 复制与移动文件
来源：http://dali.smart0.xyz/Article/details/gtffoydxco.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtsgjslgnd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hnqzz.top/Article/details/gtgbbashss.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtenbgcvjt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtozjktflp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ybcxt.top/Article/details/gtpsknslqo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gthlsivwlo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttvmnsrmh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtuhzxwwpr.html

[F12] CSV 读写
来源：http://dali.chenjidiqi.icu/Article/details/gtggxfavtm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtviyzvfej.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gtgjbwbgwf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gogol.net.cn/Article/details/gtonslwzhe.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gttzobpvgc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugheslkc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtvpnqlorq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gtlgxjaogy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jianghu66.top/Article/details/gtubyucwmj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxkvushxk.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtbagmuzzo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtraaqesxz.html

[G01] 定义类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsehxdlv.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtytquzuft.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtirvzflax.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gtbadwpvdp.html

TS:   class User { name: string = ""; }
来源：http://dali.chenlongwang.top/Article/details/gtygwmeaug.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gtdujaldsj.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gtwysrdawg.html

Ruby: class User; end
来源：http://dali.gzhubu.top/Article/details/gtbbiovnvk.html

C#:   class User {}
来源：http://dali.sweek.top/Article/details/gttzqtfqhy.html

[G02] 构造函数
来源：http://dali.cheryme.top/Article/details/gtcwfnxprm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.shangyingyoupin.top/Article/details/gtaaggkgai.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gtzaszdirr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gtiilezniw.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gtbewdrqid.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gthodumtfa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtswqyvadp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gtqwmtowhd.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gtnzvsigrt.html

[G03] 实例属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtirlkumnx.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtopfxubfs.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtihvzdxtz.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtwfsgbdqy.html

TS:   name: string = "x";
来源：http://dali.havefunace.top/Article/details/gtudccnqzk.html

Java: private String name;
来源：http://dali.ybcxt.top/Article/details/gtagtzuhqq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gaohongyu789.top/Article/details/gtabjhihjn.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtzidofclh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jlsjyb.cn/Article/details/gthwbfeqbk.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gtdslpbhmp.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtgfgpptrk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gtqznlpgtj.html

JS:   greet() { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gtwmjqcypp.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirnfhwil.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gtiwzxrtnn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gtsiblpulo.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gtalleybuf.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gtxwiyrmfq.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtmbwvlgqb.html

Py:   class Admin(User): pass
来源：http://dali.pycfn.com/Article/details/gtuapvmbhe.html

PHP:  class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtfptntfvk.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtcycyacsf.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtndodpyty.html

Java: class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gtulswnpby.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gthddofbac.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrbwtazfj.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gthybvapxy.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gtwchxkgze.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtstlxybgs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvhxmttuh.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gtrpgchybf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtepyucizu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtqbwheiex.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hywenlv.cn/Article/details/gtnjlvbtul.html

Ruby: def greet; "admin"; end
来源：http://dali.tian-w.cn/Article/details/gtdhhxxbvp.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtbsefbtuv.html

[G07] 调用父类方法
来源：http://dali.gotoacloud.top/Article/details/gtvyldlthe.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtbtglgsqm.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gtzvolsfdm.html

JS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gtaebxkers.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gtggjwnmve.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtntaytqgt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jlsjyb.cn/Article/details/gtvwqaykap.html

Ruby: super
来源：http://dali.tanke756.top/Article/details/gtljhihdlr.html

C#:   base.Greet();
来源：http://dali.cheryme.top/Article/details/gtektlaptx.html

[G08] 静态方法与属性
来源：http://dali.aibaodan.cn/Article/details/gtqzwyzcrr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gtrrynmfgg.html

PHP:  public static function f() {}
来源：http://dali.wangdashe.top/Article/details/gtpqrhhewj.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtawjjropi.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtcyvwojjh.html

Java: static void f() {}
来源：http://dali.ybcxt.top/Article/details/gtxuwlrmtl.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtvpemgwce.html

Ruby: def self.f; end
来源：http://dali.hywenlv.cn/Article/details/gtecbhexvh.html

C#:   public static void F() {}
来源：http://dali.gogol.net.cn/Article/details/gtjkmzyrua.html

[G09] 接口 / 抽象类
来源：http://dali.zycfv.cn/Article/details/gtnkvmehxq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cashguo.top/Article/details/gtepxnpttx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtbkkyfanf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.dianchejie.cn/Article/details/gteufjftqu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwlxvyxma.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtlzntlkru.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hywenlv.cn/Article/details/gtwnnfdpdv.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gtejcmobxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbnkxkae.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gtdsbvxuun.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.9152youxi.cn/Article/details/gtcblnjxge.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gtqhxdcgnq.html

JS:   #private 字段；其余公开
来源：http://dali.hongshengwenyu.top/Article/details/gtugzapbxy.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtalaxtnfy.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gtggxldacm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.316326.xyz/Article/details/gtkldoffnp.html

Ruby: public / protected / private
来源：http://dali.snrcjt.cn/Article/details/gtdxnlmbmb.html

C#:   public / protected / private / internal
来源：http://dali.zhiwuduotai.top/Article/details/gtnsrkplwv.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtzitxskia.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtsurqvwln.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gtunrqwfpn.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gtgkbltwdq.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gtznqyiebu.html

Java: public String getName() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtriwwilyb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.guannengcc.top/Article/details/gtvwzrfyfn.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gthrafyeve.html

C#:   public string Name { get; set; }
来源：http://dali.gzhubu.top/Article/details/gtfynfncgb.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtneheqykt.html

Py:   def __str__(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtifjaqdls.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gttmeitfbh.html

JS:   toString() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gtqznbfdik.html

TS:   toString(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtdqwnvnpt.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtbpguyymw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtelgluipk.html

Ruby: def to_s; @name; end
来源：http://dali.guannengcc.top/Article/details/gtrqnsmsen.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gtxmqoilic.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzuymlzd.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gttlnmigkt.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtjmlrbhjg.html

JS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtxekovnmi.html

TS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtylpczkgl.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gtsjzbnpig.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.andypj.xyz/Article/details/gtukhxuyks.html

Ruby: u.is_a?(User)
来源：http://dali.shangyingyoupin.top/Article/details/gtkegpoyvn.html

C#:   u is User
来源：http://dali.gaohongyu789.top/Article/details/gtmgwqhsyg.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gttyyjhgrz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.dianchejie.cn/Article/details/gtqataoanv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenzaomai.com/Article/details/gtvjwqrrtu.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.gotoacloud.top/Article/details/gtqzoiteps.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtxqnvebhy.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigufen.top/Article/details/gtpkyeoilr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhijiandao.cn/Article/details/gtiyejdnqn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pengpengdd.cyou/Article/details/gtvguejmaj.html

C#:   record User(string Name, int Age);
来源：http://dali.birdmap.top/Article/details/gttgoihpkn.html

[G15] 枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtgpkwlrvg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yvedp.cn/Article/details/gtggrckjkt.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtulgacecs.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gtubwfadzb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gteejfcsqm.html

Java: enum Color { RED, GREEN }
来源：http://dali.aizwys.cn/Article/details/gtmrnxhgfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yanxiufei.cn/Article/details/gteuiiorqs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gtojipgyjz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gthgalvmzt.html

[G16] 对象转数组 / 字典
来源：http://dali.birdmap.top/Article/details/gtgpqjkval.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ivvv.top/Article/details/gtgqzgztgo.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gtbdgrxydu.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtkqyvifra.html

TS:   Object.entries(obj)
来源：http://dali.yj20258.top/Article/details/gtxfupvwle.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gtlegzbbya.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.cucudq.cn/Article/details/gtubrffikm.html

Ruby: obj.instance_variables
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxjxcsxm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gthbuyaocn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlyxzttzf.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtljieowpr.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxttkeuiz.html

[H01] try / catch 基础
来源：http://dali.xziqi.cn/Article/details/gtkpvfaght.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jyoumei.cn/Article/details/gtyaoqxgtv.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyahzdlef.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtnvtirjhm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgfzy.top/Article/details/gtyodsraxk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtwghmyaym.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtkqcbrisu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gtvqtrybtm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtgdjriomm.html

[H02] finally / ensure 收尾
来源：http://dali.redwolf501.top/Article/details/gthxhafvcb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtbcvoemby.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtrprfqrzk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtagwbezwi.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtpecaqekc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtcdbkcwvn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cheryme.top/Article/details/gtronkojil.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.mhx1999.top/Article/details/gtjmzyyzba.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtzvqpyeby.html

[H03] 主动抛出异常
来源：http://dali.hongshengwenyu.top/Article/details/gtejgezqwc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jlsjyb.cn/Article/details/gtvudsqqtl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtvtmvfotm.html

JS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtxamnxtse.html

TS:   throw new Error("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtaxnjbbjh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtpznsxkqh.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gogol.net.cn/Article/details/gtyvdsskpl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gthkhbglnk.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gttqnmvnvk.html

[H04] 自定义异常类型
来源：http://dali.guannengcc.top/Article/details/gtdhjxguam.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtxwmaffzh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shzxlz.cn/Article/details/gtwffcbffh.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gtwfnlnspe.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gtfiuvpyej.html

Java: class MyException extends RuntimeException {}
来源：http://dali.316326.xyz/Article/details/gtcasxrnrq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sysykeji.top/Article/details/gtwqehkkek.html

Ruby: class MyError < StandardError; end
来源：http://dali.svipenyu.cn/Article/details/gtaqpvhugp.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gtrvfzrkjr.html

[H05] 捕获特定类型
来源：http://dali.hongshengwenyu.top/Article/details/gttrvbmiuh.html

Py:   except ValueError as e:
来源：http://dali.yueranfly.top/Article/details/gtzrjyasiv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtzohfxnnh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gtdohwalpq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nwbrower.top/Article/details/gtafbcraqt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtborklmtx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.fengsongda.top/Article/details/gtvkeqijyv.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangtech.top/Article/details/gthakixdrk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnxiangtu.top/Article/details/gtfnctvvpf.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwbbupog.html

Py:   value = d.get("k") or default
来源：http://dali.cucudq.cn/Article/details/gtskrrisle.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gogol.net.cn/Article/details/gtljpfmegj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtaasiwdvg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtnbymgfjo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.mhx1999.top/Article/details/gtvawgycnv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.wangdashe.top/Article/details/gtoehyhara.html

Ruby: d&.dig(:a, :b)
来源：http://dali.ivvv.top/Article/details/gtzporrwav.html

C#:   obj?.A?.B ?? default
来源：http://dali.nwbrower.top/Article/details/gtfhwacwcj.html

[H07] 断言
来源：http://dali.zhengqikj.top/Article/details/gtmlnkqdnd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nanxinkj.top/Article/details/gtzuocdseu.html

PHP:  assert($x > 0);
来源：http://dali.nanxuanxn.top/Article/details/gtgwgprzqy.html

JS:   console.assert(x > 0);
来源：http://dali.zhixingplan.top/Article/details/gtfovtmzma.html


<!-- 参考信息 -->