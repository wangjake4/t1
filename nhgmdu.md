代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ybcxt.top/Article/details/gtfryggyhy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtcxvolpqu.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtdzodgjxn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.kuanghao11.cn/Article/details/gtzsqweatt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gtnsmvzxjq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtjpyzystz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtlanxpeje.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gttjrqvlrw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtcofphgyi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gtmpewetiw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixkkuywz.html

[F04] 追加写入文件
来源：http://dali.redwolf501.top/Article/details/gtrwkavvsb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gterupizfg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gtmelplanw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtyczcnyzy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtgtuzedkr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj20258888.top/Article/details/gttvsygywy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtbduekvru.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.sufxvd.cn/Article/details/gtraarmwae.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hfpthk.cn/Article/details/gtpkcgcfjl.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gtaxugfbda.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gtfvfnvpan.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtfjuxlmuo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtliiwdvfh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtfpzeidio.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtxngdpwtb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gtwfjkljti.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtjmvrehra.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtabzatuvc.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwoixxxr.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtcwflccyr.html

PHP:  unlink("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gteljvmcak.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovxwwcqn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtdcgtvsce.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtlehakokc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtksdtxgym.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gttvszkvqv.html

C#:   File.Delete("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtztrfsozh.html

[F07] 创建目录（含多级）
来源：http://dali.yuxming.cn/Article/details/gtokuflkos.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtyhrmknfv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gttpblbxwg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtuxeqfuhj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtlnmiymrs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gtjazouvgr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtdfoinbnq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtzzsstxxg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xuanzx.com/Article/details/gtnlyfhxwx.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtbkglotun.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtvtwucrgz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtxrmuvylp.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtmzohlfha.html

TS:   fs.readdirSync("dir")
来源：http://dali.hysaishi.cn/Article/details/gtddfhpwnp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtleamlbyn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cucudq.cn/Article/details/gtcbvnxzsi.html

Ruby: Dir.children("dir")
来源：http://dali.hnxiangtu.top/Article/details/gthggmufuq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gtvwdthjdx.html

[F09] 获取文件大小
来源：http://dali.0kj1m.cn/Article/details/gtbkojmapl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqgwhpfbc.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtvbgdbgzy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtmdwqdsjv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlatcqpuy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtvyojezzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.0kj1m.cn/Article/details/gtlexdjlxh.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gteeobyqyh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.316326.xyz/Article/details/gtcgtsamvb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gttsbqzbuw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtrkhrqjde.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtyzklbtjd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtzrzinetn.html

TS:   path.extname("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtasyreiko.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.c1oappe.top/Article/details/gtgzhgskod.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtjelhvzwy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gthjkfgiae.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtujqetgvg.html

[F11] 复制与移动文件
来源：http://dali.sufxvd.cn/Article/details/gtjfyokrxh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgptcuhwv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gttnwohbup.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvifvqsvj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtgjfnvgci.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtnpeajjgf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtgnexdpyb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwzsrxtsh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gteclaqtse.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gtdkjeulxe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gtkwfxkrve.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtfheawtne.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gtvreixfwt.html

TS:   // 同上
来源：http://dali.jinqigufen.top/Article/details/gtvtdjhgmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gtyiyufjoa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gtpvppdhfd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.smart0.xyz/Article/details/gteljrwtbc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yonumen.top/Article/details/gtvrbgcqyg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtxphenwtn.html

G. 面向对象
来源：http://dali.yongpay.top/Article/details/gtvczkvkuz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtrwpjdcay.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gtqewslnsj.html

Py:   class User: pass
来源：http://dali.zhengqikj.top/Article/details/gtylqznlbm.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtnzjrzmpn.html

JS:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gtfbgskbyd.html

TS:   class User { name: string = ""; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkkxmxbhq.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gtazxmemig.html

Go:   type User struct { Name string }
来源：http://dali.daria6918.cn/Article/details/gtgbihlsqj.html

Ruby: class User; end
来源：http://dali.xziqi.cn/Article/details/gtoiayjrlw.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtdkzaewvq.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtdlgujobh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtzdhribeb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtovdwjrja.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gtbxwfopxl.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtwfvmipgu.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtidekfkrb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxqlnoor.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gtjnqaftoh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtkmvrgipr.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtesntwxvb.html

Py:   self.name = "x"
来源：http://dali.yuxming.cn/Article/details/gtnjierikq.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtmedafkfe.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gthdoikkyk.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gtyqjtbvmw.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gtankrhxwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gtvynnydye.html

Ruby: @name = "x"
来源：http://dali.vqdsnc.cn/Article/details/gtqtqmzpgf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gtfmuiraaj.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gtfknazkac.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnmhhdzd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtelezvosv.html

JS:   greet() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqtlhftsa.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtnarhibrl.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhexmfag.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gtetsbkhda.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gthslgmqjf.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gteasxxpjb.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gthkjrhjzx.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gthdtjgjti.html

PHP:  class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gtyhrtjnyp.html

JS:   class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtripscbdg.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtqxgpbmwl.html

Java: class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gtltbgpwis.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gtttkqiunk.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gtfrqaaxps.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcyaurqg.html

[G06] 重写方法
来源：http://dali.chenzaomai.com/Article/details/gtopwpwwfd.html

Py:   def greet(self): return "admin"
来源：http://dali.yvedp.cn/Article/details/gtyehtsgtd.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gtwoluvqqs.html

JS:   greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtuaufzlxo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrtiwnub.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtapsbimom.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinqigufen.top/Article/details/gtpydolhgz.html

Ruby: def greet; "admin"; end
来源：http://dali.hysaishi.cn/Article/details/gtqjukdzcb.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtrevygtcv.html

[G07] 调用父类方法
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyobyppd.html

Py:   super().greet()
来源：http://dali.ehwqpu.com/Article/details/gtxdhekorx.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtcaxgdkva.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gtdhtqrjmx.html

TS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtewsmqzjf.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngceshcy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gtrcsbgmvv.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtbhyqlixr.html

C#:   base.Greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtlipfmygy.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtaxnsieem.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtzlpfkfsw.html

PHP:  public static function f() {}
来源：http://dali.dianchejie.cn/Article/details/gtgxrdshci.html

JS:   static f() {}
来源：http://dali.hfpthk.cn/Article/details/gthqkdgato.html

TS:   static f(): void {}
来源：http://dali.jiagoushi.top/Article/details/gtvnsrjieg.html

Java: static void f() {}
来源：http://dali.cheryme.top/Article/details/gtamlbnwpr.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigfzy.top/Article/details/gtgvaejdmq.html

Ruby: def self.f; end
来源：http://dali.yuxming.cn/Article/details/gttukbjoyx.html

C#:   public static void F() {}
来源：http://dali.daria6918.cn/Article/details/gtpeufqnci.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtdwunqull.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yueranfly.top/Article/details/gttdixkfhg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfsjwnhek.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgufenzy.top/Article/details/gtayhqgolz.html

TS:   interface Shape { area(): number; }
来源：http://dali.gotoacloud.top/Article/details/gtcxtgvmci.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtrjitqysi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ydzc1.top/Article/details/gtxohzpnra.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gtfjaqoubc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hysaishi.cn/Article/details/gtxduduvyh.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtzayznuwb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ivvv.top/Article/details/gteenkxtcl.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtbfnlsxdr.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtsrscoixr.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbummnwki.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gtrrjmhawj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtbevpcovs.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtcnuxtnsj.html

C#:   public / protected / private / internal
来源：http://dali.jqgufenzy.top/Article/details/gtyhsiavco.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtrkioxiwf.html

Py:   @property 与 @x.setter
来源：http://dali.ppjwa.cn/Article/details/gtriucmlso.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbxvrgtn.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtgomvjbql.html

TS:   get name(): string { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtlyobxbpc.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbfgxjvn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gtiphdyale.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gthdcyldzw.html

C#:   public string Name { get; set; }
来源：http://dali.yanxiufei.cn/Article/details/gtbtvyyroz.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gtsutzuzpb.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gttlxnfyml.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtwssjvewm.html

JS:   toString() { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gtlctcqotf.html

TS:   toString(): string { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gtlbrpjdhp.html

Java: @Override public String toString() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gtxowxmgfu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gtztmafsfg.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gttrpgjeof.html

C#:   public override string ToString() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gtfnrznyju.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gtfsumvmwj.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gtfmliqerl.html

PHP:  $u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtbcgqmuhl.html

JS:   u instanceof User
来源：http://dali.pycfn.com/Article/details/gtqzbqylsc.html

TS:   u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gtfhjsvldr.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gtazeapsnb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xziqi.cn/Article/details/gtrfnwyguw.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtyfnvqvnq.html

C#:   u is User
来源：http://dali.cucudq.cn/Article/details/gtjtktyjsb.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtdvqnqdks.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gotoacloud.top/Article/details/gtpbqbsqud.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsvbsdxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.havefunace.top/Article/details/gtlyvtrrez.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gtpbycasae.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gtpidiwgpq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gtsckilpqr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtgfemjxrp.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gtdvxfenlh.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtdmhtctxs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnxiangtu.top/Article/details/gtkmhjbgxw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtlyhcinhn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ybcxt.top/Article/details/gtzqeraxkp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.bjfxy.top/Article/details/gtoahevnba.html

Java: enum Color { RED, GREEN }
来源：http://dali.jiagoushi.top/Article/details/gtjjzwpcky.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.dianchejie.cn/Article/details/gtrucsiugq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtpyahqygk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gtymmuwrtd.html

[G16] 对象转数组 / 字典
来源：http://dali.shuidangran.top/Article/details/gtweoloadp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.haohaochexian.top/Article/details/gtslhwoozm.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigfzy.top/Article/details/gttucnhozo.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gtbmceczof.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtvnggyxrq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtbcfgsvov.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gtolahhpgm.html

Ruby: obj.instance_variables
来源：http://dali.tanke756.top/Article/details/gtrxrtfzpy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gtqmbwfsle.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrmtinsy.html

H. 异常与错误处理
来源：http://dali.jinqigufen.top/Article/details/gtxoxscorf.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtllgjdleu.html

[H01] try / catch 基础
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomrfmrjv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gtrjghqvme.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xziqi.cn/Article/details/gtsmvkvwxz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gtckmgkaef.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuetiantiany.cn/Article/details/gtflrwnmnr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.nwbrower.top/Article/details/gtdufegzwt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yvedp.cn/Article/details/gtxejyktra.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yuxming.cn/Article/details/gtapwzvpfg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cheryme.top/Article/details/gtikumktet.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gtageyxbqo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gtoqoqwtvd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmoznaezi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpmnyhjh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtjglueesb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtxksozjxl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zycfv.cn/Article/details/gtvtrjxame.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtkspodipu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gteejcycgf.html

[H03] 主动抛出异常
来源：http://dali.tanke756.top/Article/details/gtqenzojmi.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gtergwtvrq.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gtbjglsxwr.html

JS:   throw new Error("错误信息");
来源：http://dali.pycfn.com/Article/details/gttlrplkyd.html

TS:   throw new Error("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtvioskpde.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtkrkvdjdq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ivvv.top/Article/details/gtwvzvbkns.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tanke756.top/Article/details/gtelmksdfe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtbbbknrqy.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gtghkihnuz.html

Py:   class MyError(Exception): pass
来源：http://dali.zycfv.cn/Article/details/gtivrqkymm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gtoosmczqg.html

JS:   class MyError extends Error {}
来源：http://dali.jlsjyb.cn/Article/details/gtypshkytg.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gtuoaelczv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtpdzouiir.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtdsbmwzqg.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gtwsfkoykn.html

C#:   class MyException : Exception {}
来源：http://dali.zhijiandao.cn/Article/details/gtafefupql.html

[H05] 捕获特定类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotnazkjo.html

Py:   except ValueError as e:
来源：http://dali.shangyingyoupin.top/Article/details/gtpejbqikh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.havefunace.top/Article/details/gtkikwbymb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtraebrdoc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gtrkpvrirw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtraicwdbj.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.svipenyu.cn/Article/details/gtmduboifw.html

Ruby: rescue ArgumentError => e
来源：http://dali.meibo888.top/Article/details/gtpboeytth.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenzaomai.com/Article/details/gtcugybcox.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnnlnloxh.html

Py:   value = d.get("k") or default
来源：http://dali.yongpay.top/Article/details/gttuabvcco.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.haohaochexian.top/Article/details/gtrftqpnft.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtdtpyyoio.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.snrcjt.cn/Article/details/gtpjidzykg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xylfe.cn/Article/details/gtqzqieida.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yvedp.cn/Article/details/gtplizpycp.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gtvqudoumy.html

C#:   obj?.A?.B ?? default
来源：http://dali.redwolf501.top/Article/details/gtvyomwuls.html

[H07] 断言
来源：http://dali.fengsongda.top/Article/details/gtzvvgpvto.html

Py:   assert x > 0, "必须为正"
来源：http://dali.nwbrower.top/Article/details/gtlxzofkez.html

PHP:  assert($x > 0);
来源：http://dali.dashuyun.cn/Article/details/gtdocjsjot.html

JS:   console.assert(x > 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzdnrrrl.html


<!-- 参考信息 -->