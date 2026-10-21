代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gtexlmfyhs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtrjozpbgo.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtfxxsnbfu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgnjgnkyy.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoftulhid.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtpucdwyie.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtbhysypat.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.aizwys.cn/Article/details/gtsmtqhseu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtgwldngdk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtvqarzkkp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gtvvfrsbss.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtkmmcmdbh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cashguo.top/Article/details/gtpdvsccse.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtwzdtsmev.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cqqwz.cn/Article/details/gtzvsntdpq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxuanxn.top/Article/details/gtiabptaeu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gtjobupbyq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.bjfxy.top/Article/details/gtmvbaimpa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtopuxeolz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhengqikj.top/Article/details/gtdoquihnv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yueranfly.top/Article/details/gtuxbtdpaj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtvqmkftvv.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtscsrxxva.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yanxiufei.cn/Article/details/gttldqllwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gteacoeblo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtkjagvmmq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtdpxethyu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gthhusbnmi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gtuesztmsd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258888.top/Article/details/gtzbrdmlvb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gtxhoezagz.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gtiudvuztd.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtqrloitaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtanxtlilm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtqjoxqnqq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtircpmrpp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jqgfzy.top/Article/details/gtoizgbxoi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jqgufenzy.top/Article/details/gtupemzzal.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gthbevkgef.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtrozojgxl.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtbxskfgvm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangshuangyany.cn/Article/details/gtqbykuwjr.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtrezapohu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gttvsvbtfk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpxnexegl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gttbfyxhwb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxinkj.top/Article/details/gtozmlghnd.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdfojynww.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtkolenita.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gtcrktximi.html

Py:   os.remove("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtujfgwwwm.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtigbpsnuf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyrmfsewj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtglxhgjxp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtdawnpiwp.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtjvyuvywu.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtnomwsjnv.html

C#:   File.Delete("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnlprhhb.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtlsqsmhrq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gthwqkcnua.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gtnceoaufd.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gtpveotbkw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtuncbvrgd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.kuanghao11.cn/Article/details/gtzdwtlaif.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gttrxqaouz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gtagmsrelo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cashguo.top/Article/details/gtzwjjdbzm.html

[F08] 遍历目录
来源：http://dali.zhongyouzk.top/Article/details/gtzcnklmka.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hysaishi.cn/Article/details/gtyiefcedj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gttxgwpevl.html

JS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gtbhdujdmv.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtrwvxsovb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gthfagundr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtdureczqz.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gteglvgqpo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hysaishi.cn/Article/details/gtclngfayf.html

[F09] 获取文件大小
来源：http://dali.ybcxt.top/Article/details/gtmigrxcbd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtoygktbry.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtgcjnoxih.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yanxiufei.cn/Article/details/gtjotrwutw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtegvbewbj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtlroxcmbx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ivvv.top/Article/details/gtpndqugfz.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtvgikzqwr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258888.top/Article/details/gtcpishhqn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gthffrcsyv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtausmbqzf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gzhubu.top/Article/details/gtvkxpcgyl.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gtngdyzwll.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnctxpxjl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aizwys.cn/Article/details/gtqwtarjkl.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaxavutmp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpdiebyni.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtwlogehzt.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gtoparyqft.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gttgpcqkll.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gotoacloud.top/Article/details/gtprdhaatp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtrbxwnfmv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtbddycoto.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gtbtrpaukk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fzhhl.top/Article/details/gthubpxnbn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtwblyonez.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gtlcgghwlt.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtgldfllhm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnqzz.top/Article/details/gtpengnnoh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnlpfuos.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sxryk.cn/Article/details/gtewxdpvrf.html

TS:   // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtnhymxmcj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtgdxswziu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtnzsnazxx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xziqi.cn/Article/details/gtzruyoaid.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ybcxt.top/Article/details/gtotvhwswa.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtqiddqbfp.html

G. 面向对象
来源：http://dali.jlsjyb.cn/Article/details/gtozaycquw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsgyqrtjb.html

[G01] 定义类
来源：http://dali.cheryme.top/Article/details/gthmnznvev.html

Py:   class User: pass
来源：http://dali.zhongyouzk.top/Article/details/gtgvcgrkur.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gtoietptxa.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gtonrnohxa.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtfcblqxdp.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpxfbdfzk.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gtqvxjhezl.html

Ruby: class User; end
来源：http://dali.iojbl.cn/Article/details/gtmegxjnue.html

C#:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtebzchkjn.html

[G02] 构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkacdlta.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gtefimbfoz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gaohongyu789.top/Article/details/gtpsbhsbiq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtfxwwyxny.html

TS:   constructor(public name: string) {}
来源：http://dali.dianchejie.cn/Article/details/gtmiaaiapl.html

Java: User(String name) { this.name = name; }
来源：http://dali.hfpthk.cn/Article/details/gttlgocyvu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gtlmlqraqz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtdaudfcsg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ybcxt.top/Article/details/gteltuqrvp.html

[G03] 实例属性
来源：http://dali.vqdsnc.cn/Article/details/gtvzesrwgi.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gtpifaamzg.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtkduvrasn.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtmlluuejs.html

TS:   name: string = "x";
来源：http://dali.hywenlv.cn/Article/details/gtsxkrpvap.html

Java: private String name;
来源：http://dali.dianchejie.cn/Article/details/gtgqoywrzg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yvedp.cn/Article/details/gtnynxhkvc.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gtirxqfsze.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xylfe.cn/Article/details/gtihczpdsj.html

[G04] 定义方法
来源：http://dali.daxiang520.top/Article/details/gtoeoaqblf.html

Py:   def greet(self): return self.name
来源：http://dali.jinqigufen.top/Article/details/gtwszjnqsp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fzhhl.top/Article/details/gtqkprpohw.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkogsakq.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtzoxihqjz.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtjrbbgtnt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtgthlnbtj.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtkpocyshx.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtveztqcys.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvlfjqvq.html

Py:   class Admin(User): pass
来源：http://dali.chenlongwang.top/Article/details/gtrpjrzguy.html

PHP:  class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqdnynqkm.html

JS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtggjcxfeo.html

TS:   class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtpwqqrwpy.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtbdezobfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gtevvcuqjn.html

Ruby: class Admin < User; end
来源：http://dali.iojbl.cn/Article/details/gtferevfyd.html

C#:   class Admin : User {}
来源：http://dali.xziqi.cn/Article/details/gtbyomsoti.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtydyqynxv.html

Py:   def greet(self): return "admin"
来源：http://dali.wangdashe.top/Article/details/gtzqajtvhg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtzmiiicxp.html

JS:   greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtfnvcfmnb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtsaxafvfc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gtwfxdtcxk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuetiantiany.cn/Article/details/gtqiwwuufc.html

Ruby: def greet; "admin"; end
来源：http://dali.xuanzx.com/Article/details/gtaiqtovgx.html

C#:   public override string Greet() => "admin";
来源：http://dali.snrcjt.cn/Article/details/gtmdiceeoh.html

[G07] 调用父类方法
来源：http://dali.wangshuangyany.cn/Article/details/gtpgdvtxes.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gtqmxqihjl.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtoqifvbsl.html

JS:   super.greet();
来源：http://dali.gaohongyu789.top/Article/details/gtamyyadxn.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gtmoruvifl.html

Java: super.greet();
来源：http://dali.cucudq.cn/Article/details/gtnwqlvtex.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gtkpfjlidb.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gtzvtfwilw.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtkttcvxwx.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gticlxqrsh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtndpmukfv.html

PHP:  public static function f() {}
来源：http://dali.jiagoushi.top/Article/details/gtspqelcfa.html

JS:   static f() {}
来源：http://dali.hywenlv.cn/Article/details/gtbripjple.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtelcgzdhe.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gtruojlsby.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj20258888.top/Article/details/gtpilagshg.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtzppdjslz.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtqmmgawnn.html

[G09] 接口 / 抽象类
来源：http://dali.jinqigufen.top/Article/details/gtdhwtihdz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.haohaochexian.top/Article/details/gtutfcspbn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.aizwys.cn/Article/details/gtcmnpdkdf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.bjfxy.top/Article/details/gtadarlghw.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhengqikj.top/Article/details/gtkbhwcewp.html

Java: interface Shape { double area(); }
来源：http://dali.birdmap.top/Article/details/gturgbahvi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.snrcjt.cn/Article/details/gtduodvkgb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.fzhhl.top/Article/details/gtheofykfj.html

C#:   interface IShape { double Area(); }
来源：http://dali.jyoumei.cn/Article/details/gtcipfjhvw.html

[G10] 访问控制
来源：http://dali.yueranfly.top/Article/details/gtjvhjclvp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gtwsgrlejd.html

PHP:  public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtqnbvsuvq.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtjxeymeyg.html

TS:   public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gtqynqdqxx.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gtmodcslmu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtdlcptpxs.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gthgwzfevq.html

C#:   public / protected / private / internal
来源：http://dali.jiagoushi.top/Article/details/gtpznbqtly.html

[G11] getter / setter
来源：http://dali.smart0.xyz/Article/details/gttvtbidey.html

Py:   @property 与 @x.setter
来源：http://dali.hywenlv.cn/Article/details/gtzuwyttpk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtbdtgrdsx.html

JS:   get name() { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtegoqlaqh.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gtmytwtptn.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gtchktgulv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtflvarmad.html

Ruby: attr_accessor :name
来源：http://dali.hfpthk.cn/Article/details/gtelrfrjjm.html

C#:   public string Name { get; set; }
来源：http://dali.zhiwuduotai.top/Article/details/gtthunzaee.html

[G12] 对象转字符串
来源：http://dali.9152youxi.cn/Article/details/gtblmmuxvu.html

Py:   def __str__(self): return self.name
来源：http://dali.pengpengdd.cyou/Article/details/gtcooqfirl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtrsaludpi.html

JS:   toString() { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskljgqnp.html

TS:   toString(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtaoztosns.html

Java: @Override public String toString() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtmwfilrba.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gthmoleijt.html

Ruby: def to_s; @name; end
来源：http://dali.aibaodan.cn/Article/details/gtlruymghb.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gtaktlhrsn.html

[G13] 判断对象类型
来源：http://dali.vqdsnc.cn/Article/details/gthoyylfzx.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gthmpuwuxv.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gteaxleqlt.html

JS:   u instanceof User
来源：http://dali.meibo888.top/Article/details/gthtuvrslt.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gthraiduzr.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gtcgfkdyxk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yuxming.cn/Article/details/gthebdkfgv.html

Ruby: u.is_a?(User)
来源：http://dali.birdmap.top/Article/details/gtdbwyzjdb.html

C#:   u is User
来源：http://dali.zycfv.cn/Article/details/gtgegwixbp.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gtpmguxswz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.c1oappe.top/Article/details/gtecjarfcy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gtaqgbzatl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyltslltp.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtetrefgtx.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gtsfehjldz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gttihttifm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fzhhl.top/Article/details/gtlgtdiueq.html

C#:   record User(string Name, int Age);
来源：http://dali.zhengqikj.top/Article/details/gtunizzkix.html

[G15] 枚举
来源：http://dali.jianghu66.top/Article/details/gtbcnlsbeo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xinyue.icu/Article/details/gtrleimwvg.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmraqbhat.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj202588.top/Article/details/gtyzwppepb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yj202588.top/Article/details/gtqznskeip.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtikeqraoo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwzkrbzf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tianlin.xyz/Article/details/gtadpsamkj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppttyywe.html

[G16] 对象转数组 / 字典
来源：http://dali.hongshengwenyu.top/Article/details/gtnueyloat.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gtmvkrenlt.html

PHP:  get_object_vars($obj);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjrhnerx.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gtxkckqyad.html

TS:   Object.entries(obj)
来源：http://dali.316326.xyz/Article/details/gtkqtlazks.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tanke756.top/Article/details/gtoktxornx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gtmwttwnly.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gtywvzwocq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tianlin.xyz/Article/details/gtdvzhziso.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtbanhzbal.html

H. 异常与错误处理
来源：http://dali.sysykeji.top/Article/details/gtfodixbsn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiggrlxyi.html

[H01] try / catch 基础
来源：http://dali.aizwys.cn/Article/details/gtqynsimyg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sufxvd.cn/Article/details/gtoeapotig.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hywenlv.cn/Article/details/gtrhoyuapm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtnwavlpxu.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtwyrbhkti.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbhktxnm.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.sweek.top/Article/details/gtjvlnbvqw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daxiang520.top/Article/details/gtyzwbghqq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.hnxiangtu.top/Article/details/gtonccodtw.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtvkzahuul.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvgkzmfv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtvhqknuqx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtuydtbykm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtrhckueji.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkntpstsv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangshuangyany.cn/Article/details/gtgsnkhfym.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtbwwydgvw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtyrdktuoe.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtyzwowvld.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjbthkou.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gtxddmrjps.html

JS:   throw new Error("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtioxrrqko.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gtmjuyuaez.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtjwyllviu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.daria6918.cn/Article/details/gthatexmeu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gtsmoyblwv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gtnbhudebo.html

[H04] 自定义异常类型
来源：http://dali.fengsongda.top/Article/details/gtcuppsooz.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtzzdjxhpo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gtjfievcec.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtwniajdwt.html

TS:   class MyError extends Error {}
来源：http://dali.chenlongwang.top/Article/details/gtukusjbmu.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtgjccyfat.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqyitulrm.html

Ruby: class MyError < StandardError; end
来源：http://dali.pengpengdd.cyou/Article/details/gtcxgewcrh.html

C#:   class MyException : Exception {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuehordmr.html

[H05] 捕获特定类型
来源：http://dali.9152youxi.cn/Article/details/gtabdhmfyv.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gtpdweqhdy.html


<!-- 参考信息 -->