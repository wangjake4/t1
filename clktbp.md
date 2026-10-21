代发 wailian999

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gtuhgmkfor.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtarmwowno.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gttjtnhzsk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzfifbnt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gtxbrpfbwq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtcarvyyil.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuyjibec.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfajfhbi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtqjjbrffo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gtzxhjqrai.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gtmexiwnng.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gtlbetdvyd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtvxvsrgij.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfvkblov.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gthnfbocxt.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gthfskzpux.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtnfuewyom.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtvxvccwyc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvennuvsj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gtwsrktbvk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gtvaejvtji.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenzaomai.com/Article/details/gtnurwvzim.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jianghu66.top/Article/details/gtjccjsobu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gthkbloegm.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtdeeptmka.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gtsiyijgnb.html

PHP:  file_exists("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtdpyeogcj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwwqrtfjt.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtfsyuvcxm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gthcycbczi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gtbzhguzrn.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtmwcuqpnz.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gterzzyrqa.html

[F06] 删除文件
来源：http://dali.hammf.cn/Article/details/gtlnvinqwb.html

Py:   os.remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtzfdzdrjh.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtfjauqkmi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrqjqenqh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gthtgnmmpn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtkecykyov.html

Go:   os.Remove("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtmunbowgo.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkjfovtat.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgtvufxwx.html

[F07] 创建目录（含多级）
来源：http://dali.jqgfzy.top/Article/details/gthkwtzzte.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hnqzz.top/Article/details/gtjriglxut.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtlpoefcwb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gttfwlzfex.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sweek.top/Article/details/gtpduagkrd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj202588.top/Article/details/gtudadhlzv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gtephrjinw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jianghu66.top/Article/details/gtbzatjwze.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtcwweqcqm.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtfoxhmxiy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwquynsz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gtcosgpxfm.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtjqvxkdni.html

TS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gtutqdzuhe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtwkigalri.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gtfdripbep.html

Ruby: Dir.children("dir")
来源：http://dali.cheryme.top/Article/details/gtewhxgznu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gtiusmeych.html

[F09] 获取文件大小
来源：http://dali.zhengqikj.top/Article/details/gthgeyclhu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtygsocafm.html

PHP:  filesize("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtehmioxgz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtiasvcmog.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceysqtww.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtudspkdeu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoufbdng.html

Ruby: File.size("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtzunwjcif.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.aibaodan.cn/Article/details/gtrjkkwrva.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gtiadbslfe.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbysczzkb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gtgrkvoghg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrscvqlp.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtndzvbsla.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cheryme.top/Article/details/gtrxrchuky.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttvdttitd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtmkupftin.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbxaclyjy.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtvnclkbdj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gtkwgpbina.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gthmutjwpz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtdpynkwdu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtibnlxswf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gtboeowyct.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtucimljyz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdxmsjiuy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gttspduzir.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtajrjmuyp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gthnwmnffx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gtcbgnemzn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtbrpyffvv.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtaoypvgva.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangdashe.top/Article/details/gtmlfhzfbs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hammf.cn/Article/details/gtmybxiioi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gtzsrimdbw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gtjkssozdl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtyifztocs.html

G. 面向对象
来源：http://dali.xziqi.cn/Article/details/gtlmysprqn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfcsexrte.html

[G01] 定义类
来源：http://dali.yuanzhike.top/Article/details/gtkcnuuhcp.html

Py:   class User: pass
来源：http://dali.9152youxi.cn/Article/details/gtnqiwehjn.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtqmysszag.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjfuyzzui.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gtafxkxfln.html

Java: class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtwdxrooxz.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtvzbsgyli.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtriwiowpy.html

C#:   class User {}
来源：http://dali.xuanzx.com/Article/details/gtzcjraace.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxawnetxe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xziqi.cn/Article/details/gtgwnnombh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.meibo888.top/Article/details/gtghevqura.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtibdwnrwx.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtfpamoyws.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gttqymscta.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gtbjuewlzp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gthfnkjyyp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.iojbl.cn/Article/details/gtrdbhqmeq.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtljumezwi.html

Py:   self.name = "x"
来源：http://dali.hysaishi.cn/Article/details/gthuptyzlo.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gtfieicgec.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtsitpksgi.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gtzzbzuipw.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtzxziecww.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtocuuqezi.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gtyrmqndst.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtzkinzmcn.html

[G04] 定义方法
来源：http://dali.meibo888.top/Article/details/gtsauymfqe.html

Py:   def greet(self): return self.name
来源：http://dali.yuanzhike.top/Article/details/gtmukkbqyk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gtjhhfdfnr.html

JS:   greet() { return this.name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthwtoqsfv.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtjddqlgqs.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtveoxgjlq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.daxiang520.top/Article/details/gtaiwhwqhj.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtcnoexvzz.html

C#:   public string Greet() => Name;
来源：http://dali.jyoumei.cn/Article/details/gtmvufnmfy.html

[G05] 继承
来源：http://dali.fengsongda.top/Article/details/gtjpqdhcyg.html

Py:   class Admin(User): pass
来源：http://dali.jianghu66.top/Article/details/gtbsykzyuz.html

PHP:  class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtopfjmwwe.html

JS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtfqxnfaex.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gticxphqdj.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuaxqhrnt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtdtuelxrk.html

Ruby: class Admin < User; end
来源：http://dali.zhijiandao.cn/Article/details/gtbchyhala.html

C#:   class Admin : User {}
来源：http://dali.snrcjt.cn/Article/details/gtnsfzhrcn.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gtiabxjrjn.html

Py:   def greet(self): return "admin"
来源：http://dali.zycfv.cn/Article/details/gtlinitlko.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cqqwz.cn/Article/details/gtkdersqrj.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtarezunqg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtguakutry.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gthrqkqtbt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tian-w.cn/Article/details/gttwfnllcr.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmqxgmss.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtkctohotv.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gtdwlnuotu.html

Py:   super().greet()
来源：http://dali.ybcxt.top/Article/details/gtctajfwtg.html

PHP:  parent::greet();
来源：http://dali.hammf.cn/Article/details/gtlutjutrj.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gtoxdlbpjd.html

TS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejsbpykh.html

Java: super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwjmxubl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.iojbl.cn/Article/details/gtklgutxpf.html

Ruby: super
来源：http://dali.yj20258.top/Article/details/gtfgeugbyh.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtksoumvjy.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gtiaorunft.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gtozfgtkxs.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gtjwthpxpz.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gtpwggitey.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtcxgzhoql.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gtxstiwlqp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gtxvotdhdt.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtdrtzkorc.html

C#:   public static void F() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnspdvmeh.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtlgxnzahh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gtnyjudvml.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gtxxlrsyhq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gtsijjarft.html

TS:   interface Shape { area(): number; }
来源：http://dali.hammf.cn/Article/details/gtcyxprpoy.html

Java: interface Shape { double area(); }
来源：http://dali.shuidangran.top/Article/details/gtpvxdrunj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.fzhhl.top/Article/details/gtxztbwgwf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtqqhnislj.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gtxplsbjhr.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gtcfidvblg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ehwqpu.com/Article/details/gtocxtprhg.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtvirgrxqo.html

JS:   #private 字段；其余公开
来源：http://dali.c1oappe.top/Article/details/gtexlevmct.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtwitscosx.html

Java: public / protected / private / 默认包级
来源：http://dali.chenlongwang.top/Article/details/gtsdbwzviq.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sxryk.cn/Article/details/gttvowgqvd.html

Ruby: public / protected / private
来源：http://dali.nwbrower.top/Article/details/gtjarvdfnb.html

C#:   public / protected / private / internal
来源：http://dali.gzhubu.top/Article/details/gtwyhdhvjl.html

[G11] getter / setter
来源：http://dali.xinyue.icu/Article/details/gtvgybocve.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gthrjzdpqi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtujclnbtu.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtqbrpkeen.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzxvmbif.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtpofpzapf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtdudijcod.html

Ruby: attr_accessor :name
来源：http://dali.hongshengwenyu.top/Article/details/gtesvnhaxo.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmebwqymk.html

[G12] 对象转字符串
来源：http://dali.xuanzx.com/Article/details/gtekwkkxru.html

Py:   def __str__(self): return self.name
来源：http://dali.jlsjyb.cn/Article/details/gtykbdjulq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtqxgrngmn.html

JS:   toString() { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gttdvepnmp.html

TS:   toString(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtecqbtdnj.html

Java: @Override public String toString() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtclefyoqo.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gtibfydefl.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtljzggoex.html

C#:   public override string ToString() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtueqczvun.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gttfijwmcg.html

Py:   isinstance(u, User)
来源：http://dali.hnqzz.top/Article/details/gtsaaehzru.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gtuuktrzts.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtbzbgnjaq.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtrodsqtoa.html

Java: u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtutlgohdv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtlbzzsgaj.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gtltisxnws.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtjqdrdais.html

[G14] 数据类 / record
来源：http://dali.zhixingplan.top/Article/details/gtzotgvszh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtyfmxbtkb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gtcahzuzwt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtosmfoved.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtyjnuiunf.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gtqjpioqxj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hywenlv.cn/Article/details/gtzrccjyic.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtswxuroyx.html

C#:   record User(string Name, int Age);
来源：http://dali.cqqwz.cn/Article/details/gtpusjmpkb.html

[G15] 枚举
来源：http://dali.nwbrower.top/Article/details/gtoovnmvus.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gtzdnkzcqe.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtjxeimodv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gthzcbzuma.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbcdjcbo.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gtjipiifgz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ivvv.top/Article/details/gtgwmmqhpp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gtovbidmjm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gtxjdwxyun.html

[G16] 对象转数组 / 字典
来源：http://dali.9152youxi.cn/Article/details/gtvegjzluo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.316326.xyz/Article/details/gtuttfrjkn.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtehdjofaa.html

JS:   Object.entries(obj)
来源：http://dali.gzhubu.top/Article/details/gttqbcqvst.html

TS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gtcxflnhqb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtpakrvfxm.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtfzwahfdq.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gtfaftxjhq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.feifeiyinyue.top/Article/details/gtkmsrtqrb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmrhkowst.html

H. 异常与错误处理
来源：http://dali.sufxvd.cn/Article/details/gtcxadlqbl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjqsphcfi.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gtzpfifzze.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.redwolf501.top/Article/details/gtsaodzjbi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtaocqirxc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtgosyjosb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ivvv.top/Article/details/gtniobhzle.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yueranfly.top/Article/details/gtrzynsynw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.wangshuangyany.cn/Article/details/gtyizwrrzz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gtpqgwrzmx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jlsjyb.cn/Article/details/gtsdpmkkip.html

[H02] finally / ensure 收尾
来源：http://dali.zhiwuduotai.top/Article/details/gtpgxebhnh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ivvv.top/Article/details/gtpbxjibtq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shuidangran.top/Article/details/gtcvjtejes.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtacyxwhki.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gtsfwytkcf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gtzpfymeun.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yuanzhike.top/Article/details/gtxmjonulj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxgelldm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtdymbngol.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtaabwnses.html

Py:   raise ValueError("错误信息")
来源：http://dali.wangdashe.top/Article/details/gtoesiszhz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gtwjtrrlcn.html

JS:   throw new Error("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gtoywtvgcp.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxuanxn.top/Article/details/gtkajakbtx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtjkpcyrwa.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhongyouzk.top/Article/details/gtmvwiafmj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hammf.cn/Article/details/gtepsxkkmt.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yonumen.top/Article/details/gtkkyygruv.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gtnbbsiixw.html

Py:   class MyError(Exception): pass
来源：http://dali.guowangkeji.top/Article/details/gtxxwvntxg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nanxuanxn.top/Article/details/gtrmllrywp.html

JS:   class MyError extends Error {}
来源：http://dali.wangdashe.top/Article/details/gtpdhxhpbc.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtybyrqhof.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gtfplcxjuk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtinvlcwwf.html

Ruby: class MyError < StandardError; end
来源：http://dali.tian-w.cn/Article/details/gtaxikzqqh.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdixdkvq.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gtqkoonjgk.html

Py:   except ValueError as e:
来源：http://dali.jinqigufen.top/Article/details/gtyhvsowsz.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtmbnrcpgo.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xuanzx.com/Article/details/gtsbxefupe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqerymkzx.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtivnpzjos.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jlsjyb.cn/Article/details/gtfgydepwn.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gtfeuoyvmk.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.meibo888.top/Article/details/gtnhtolbox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hammf.cn/Article/details/gtrdszgpfq.html

Py:   value = d.get("k") or default
来源：http://dali.hammf.cn/Article/details/gtckwysfzj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtralwpvab.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuanzx.com/Article/details/gtgwzdlowj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.chenjidiqi.icu/Article/details/gtjlyfmufu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.snrcjt.cn/Article/details/gtdmaadiyz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpwmzaqr.html

Ruby: d&.dig(:a, :b)
来源：http://dali.xuanzx.com/Article/details/gtysujunpf.html

C#:   obj?.A?.B ?? default
来源：http://dali.birdmap.top/Article/details/gtxzxpjpzv.html


<!-- 参考信息 -->