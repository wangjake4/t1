代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtfhxdffqu.html

[F02] 逐行读取文件
来源：http://dali.kuanghao11.cn/Article/details/gtxxpcusni.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxuanxn.top/Article/details/gtkghbtabg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.pycfn.com/Article/details/gtwzmduwrp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hfpthk.cn/Article/details/gtgnleygal.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtwqebvbac.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gteuorpafp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cdnleiting.top/Article/details/gtcyljqxrn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gtfcrnbefb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgycalpez.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gtztxlfbyf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gotoacloud.top/Article/details/gtnwyixsyw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gaohongyu789.top/Article/details/gtiopisbat.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtjbtzyalv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlpggagck.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xinyue.icu/Article/details/gttwjiurei.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gtgyliddpg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gtetoyhvnj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gtrnhqotpu.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtprmmrnwy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtofvogkov.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gtqeqvxkfv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmqvpyua.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gtlxbenqnh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gtmoynozhf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtmqildqzy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yangfankeji.com/Article/details/gtabwzetkq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnxiangtu.top/Article/details/gtmbjonree.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtstvjfjda.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gtmbnunnox.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtytvztqyr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtdpvnyqrh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtozbadldt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtxrxyydrj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cucudq.cn/Article/details/gtnfrftaad.html

Ruby: File.exist?("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtoiogfgna.html

C#:   File.Exists("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtuuhruxaw.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtzxvabtrd.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtvcpbdejc.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtfrylqtci.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlfzvbfie.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjoqxqojs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtzdtwdzie.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthhaoozty.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtbgkeffak.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gthyawfhwi.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtyieqfzpn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtcuxzlnpi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gtjzkhuady.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtvpbzlnfs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmocsawz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gtswoceemx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtmcgxhuyk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.wangdashe.top/Article/details/gtwscdgaqy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtalhzxsic.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtuujwrhab.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jlsjyb.cn/Article/details/gtsrmyamxc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.svipenyu.cn/Article/details/gtjaynhyqv.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gthvxlwgff.html

TS:   fs.readdirSync("dir")
来源：http://dali.bjfxy.top/Article/details/gttajgabpt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gthygxqepg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtjujdozwa.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gtgaizvuhb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuanzx.com/Article/details/gtywxpunpw.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gtnsmizapl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtmxvdbxtw.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtgpqouxuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtfrcodzpm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtaeikhxmk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtmqpgtcmv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenjidiqi.icu/Article/details/gtqhbmhevx.html

Ruby: File.size("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtjvcyqfcl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtngeduujd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtgzznsaev.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtfiqpjbzc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtmkxomvlp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtbjiqyamp.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfttycxn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteozryuq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtqzcjtobl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtaiwvbkng.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtofuzzsxs.html

[F11] 复制与移动文件
来源：http://dali.0kj1m.cn/Article/details/gtwltdqvjs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gthillbaum.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gtypuvqaln.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtlmzzyajn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtbergbquu.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hywenlv.cn/Article/details/gtxnumsclp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.daria6918.cn/Article/details/gtcuspvkiw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtlqbznfhd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gtykdvchpy.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtnpmyynxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtnwzwvsku.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifbpnjbm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hammf.cn/Article/details/gtlxrisvqk.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gtytztbxwu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gtiogiehjj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gttrszyhyt.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gttfcdzpfq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpygivlxz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtjrhwkgpf.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtrvdvdlvl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzoiqhyki.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjhdgapo.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtndbsfthc.html

PHP:  class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtltikjlpl.html

JS:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gtsbdwuwqr.html

TS:   class User { name: string = ""; }
来源：http://dali.sufxvd.cn/Article/details/gteepuekdr.html

Java: class User {}
来源：http://dali.0kj1m.cn/Article/details/gtlhozrmzn.html

Go:   type User struct { Name string }
来源：http://dali.sufxvd.cn/Article/details/gtmefklvnn.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gtqejjepyz.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gtzjiflzro.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gtnemfnqua.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gtaamfpnwc.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtehjwvjkh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtyfppcphs.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gttixbszog.html

Java: User(String name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtoekipqxo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinqigufen.top/Article/details/gttgbmqrlq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gthlapzgrn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtfprgzzlv.html

[G03] 实例属性
来源：http://dali.hongshengwenyu.top/Article/details/gtkemrasdn.html

Py:   self.name = "x"
来源：http://dali.shuidangran.top/Article/details/gtnfutcors.html

PHP:  public string $name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtykpsmeyi.html

JS:   this.name = "x";
来源：http://dali.ppjwa.cn/Article/details/gtyknxzxqx.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gtldgamosa.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtbfcgodar.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtxlpvnuzi.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtjgiewmrw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtwgxhysao.html

[G04] 定义方法
来源：http://dali.cdnleiting.top/Article/details/gtmarsjxka.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtelrqqhtl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gtqioymhwe.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtfbhvjlqp.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtawjzzckr.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtvhdtjspx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtzcavmsoi.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gtksmueskb.html

C#:   public string Greet() => Name;
来源：http://dali.guannengcc.top/Article/details/gtrogjklyo.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gtvmuumome.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtcfdyhkvp.html

PHP:  class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqbaytju.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtorgfzmgq.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gttqkdcqyg.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtnxglnbio.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangshuangyany.cn/Article/details/gtaxmyjmal.html

Ruby: class Admin < User; end
来源：http://dali.zhoulong.xyz/Article/details/gtdrftfqpo.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtytwfngfl.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gthmttnjta.html

Py:   def greet(self): return "admin"
来源：http://dali.quarkkingdee.top/Article/details/gtanedbmlu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sufxvd.cn/Article/details/gtbzwjuukb.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtsvvvmlpl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gtchbtfgqj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gtwqnfkeyp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nanxuanxn.top/Article/details/gtubnmeuqr.html

Ruby: def greet; "admin"; end
来源：http://dali.wangdashe.top/Article/details/gtgbydxbdw.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj202588.top/Article/details/gthbsmbqkt.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtpntsbggb.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gtucbcnrnd.html

PHP:  parent::greet();
来源：http://dali.cashguo.top/Article/details/gtzqclnblk.html

JS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gtbicutoxn.html

TS:   super.greet();
来源：http://dali.shuidangran.top/Article/details/gthhifnsqp.html

Java: super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtajvjwocr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gtrhncwmwh.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtotrodrqq.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtalnatdyt.html

[G08] 静态方法与属性
来源：http://dali.xuetiantiany.cn/Article/details/gtdplfjdah.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtvrpeevox.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gtfwdaequc.html

JS:   static f() {}
来源：http://dali.jyoumei.cn/Article/details/gtymbmgmis.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gtttxumcsy.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtjuxephrp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gtytyyahex.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gttubhpebz.html

C#:   public static void F() {}
来源：http://dali.ppjwa.cn/Article/details/gtxwrbqamu.html

[G09] 接口 / 抽象类
来源：http://dali.tianlin.xyz/Article/details/gtcrfexiwt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.meibo888.top/Article/details/gtfimoqsht.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtemldyrgz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gtsnppmshv.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtgopjhjpj.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gtjaxreglc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtvtunlpca.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tanke756.top/Article/details/gthxpovluo.html

C#:   interface IShape { double Area(); }
来源：http://dali.ehwqpu.com/Article/details/gtkcxtnyyb.html

[G10] 访问控制
来源：http://dali.jlsjyb.cn/Article/details/gtcdqfslls.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gtsdgegerk.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gtygdiiwgi.html

JS:   #private 字段；其余公开
来源：http://dali.xuanzx.com/Article/details/gtfjkmsciq.html

TS:   public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtiyovlqad.html

Java: public / protected / private / 默认包级
来源：http://dali.yongpay.top/Article/details/gtcmlaohkx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gtxhsnlvyx.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtxgbtfypd.html

C#:   public / protected / private / internal
来源：http://dali.shzxlz.cn/Article/details/gtbpfeivml.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gtvtgqfgds.html

Py:   @property 与 @x.setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtahvovxfk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gttrvhchxt.html

JS:   get name() { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtreumndkr.html

TS:   get name(): string { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gtzmwvajsh.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gtbmyhfhey.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtunkltisj.html

Ruby: attr_accessor :name
来源：http://dali.xylfe.cn/Article/details/gtqgkstxbv.html

C#:   public string Name { get; set; }
来源：http://dali.bjfxy.top/Article/details/gtctxvkfea.html

[G12] 对象转字符串
来源：http://dali.shuidangran.top/Article/details/gthaehuppu.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtytkljizq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zycfv.cn/Article/details/gtoiyxlhas.html

JS:   toString() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtmqvmckpo.html

TS:   toString(): string { return this.name; }
来源：http://dali.sweek.top/Article/details/gtiwzcxtwr.html

Java: @Override public String toString() { return name; }
来源：http://dali.andypj.xyz/Article/details/gtxazhlscw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtqcmrnvls.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gtnvcpblxf.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gtxkoidhjj.html

[G13] 判断对象类型
来源：http://dali.hongshengwenyu.top/Article/details/gtqpasdznc.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gtmxmxgdgk.html

PHP:  $u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtagmzesvh.html

JS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gtctqvxlyj.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gtqlfyythc.html

Java: u instanceof User
来源：http://dali.yanxiufei.cn/Article/details/gthbjbhwmj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xylfe.cn/Article/details/gttboxxeug.html

Ruby: u.is_a?(User)
来源：http://dali.xziqi.cn/Article/details/gtrjagsokt.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gtsincfpds.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtumbcieic.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gtqfyfvdgq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ydzc1.top/Article/details/gtheiapnez.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gtcpavhbvr.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvntsaot.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsywqils.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtdgxckfsz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gtrtanunkd.html

C#:   record User(string Name, int Age);
来源：http://dali.ivvv.top/Article/details/gtqhaojcgm.html

[G15] 枚举
来源：http://dali.316326.xyz/Article/details/gtevwmmvid.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.c1oappe.top/Article/details/gtemwfcqhp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtysgwytvn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guannengcc.top/Article/details/gtpgcsmtzm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtguojalhf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gtzzcnfrkc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fengsongda.top/Article/details/gturglnhtf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cdnleiting.top/Article/details/gtyfszlzyw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtymjbgzcm.html

[G16] 对象转数组 / 字典
来源：http://dali.hnqzz.top/Article/details/gtrxdhttqc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yuanzhike.top/Article/details/gtkchhnxed.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gthapjnlpj.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtqdcmnzum.html

TS:   Object.entries(obj)
来源：http://dali.ydzc1.top/Article/details/gtqgnmtere.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtdptafxaa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtnusdtteb.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtuoothejk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtsheblcls.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtubddwvfa.html

H. 异常与错误处理
来源：http://dali.xylfe.cn/Article/details/gtmyzlxynj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtjlutsibu.html

[H01] try / catch 基础
来源：http://dali.fengsongda.top/Article/details/gtcuzexepd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yuanzhike.top/Article/details/gtbuehdqrq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sweek.top/Article/details/gtebkfpiyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtrymvvjcm.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtrfovwses.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.ivvv.top/Article/details/gtjndagwkc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gtdopyjnfi.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj202588.top/Article/details/gtzmvbqcir.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnqzz.top/Article/details/gtqrdaqcab.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtwrjdzxvt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gtbymixreu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteqsclvtp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.andypj.xyz/Article/details/gtncpapuau.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhijiandao.cn/Article/details/gtigytqkha.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtcniqlzkw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtubdmfink.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowtghyjx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gtzvrfkawz.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gtpyjbljqc.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukszeanc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtdqqmrebo.html

JS:   throw new Error("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtmsyydfrw.html

TS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gtxqkwwcyw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjszqwcec.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbygsljz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gtcmkemnhx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gtyotowdwi.html

[H04] 自定义异常类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbopvpoje.html

Py:   class MyError(Exception): pass
来源：http://dali.yj202588.top/Article/details/gtblyhwnmr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtxufxcwuu.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtfjwtszbp.html

TS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gtzapugbkf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtfcywiopx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ehwqpu.com/Article/details/gtizkhzwfg.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtbehgnnin.html

C#:   class MyException : Exception {}
来源：http://dali.hammf.cn/Article/details/gtmbpbfgth.html

[H05] 捕获特定类型
来源：http://dali.tian-w.cn/Article/details/gtdqdimhwa.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtyecutfot.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gtysbsomhs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.chenlongwang.top/Article/details/gtybqqhhye.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhixingplan.top/Article/details/gtnpcddkzq.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.aibaodan.cn/Article/details/gtsryzxwdo.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jinqigfzy.top/Article/details/gtvdhpyopl.html

Ruby: rescue ArgumentError => e
来源：http://dali.wangshuangyany.cn/Article/details/gtflgzyfnt.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jyoumei.cn/Article/details/gtvszzzlnn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yvedp.cn/Article/details/gtdodapjvk.html

Py:   value = d.get("k") or default
来源：http://dali.meibo888.top/Article/details/gtttnglawn.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gtijlynhyw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtnwkjdpac.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gtffucsljg.html


<!-- 参考信息 -->