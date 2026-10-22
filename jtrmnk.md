代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gtinynrznl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyglaqkqb.html

F. 文件与目录
来源：http://dali.ehwqpu.com/Article/details/gttqenobsk.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtceptbamf.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gthmmaigxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gtspxjhqib.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtftjbekbu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtwruhwdld.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtdhukqbny.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtbzqbyksu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gtsnuwuokc.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtuzyadyzw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtkamxtuxb.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gttpvgwhcl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gtwxwcpnzd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ivvv.top/Article/details/gtgizegiqg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtdtiafrbb.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtiszqjtyc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtjcijqwxz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigufen.top/Article/details/gttammpfnb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtzyxircpy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtrkkjwsus.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtitgwspaa.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yj20258.top/Article/details/gtsvgtisny.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtbuxlyxek.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtcvldebch.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gtvpemaajm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtitwlznli.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gtbyfnndku.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.havefunace.top/Article/details/gtornrdaqz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtaflvoapw.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gtqqgjkbpc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gtfiqbgznk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ivvv.top/Article/details/gtdcjqpeml.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gtsshopulq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daria6918.cn/Article/details/gthyafusbp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gtmgbarffj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gtcasjtboo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gtmcchqrhn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.gzhubu.top/Article/details/gtmuzptvbd.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtnzogptin.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbduyvzop.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtyaglenhx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtbkfetqla.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwopwelar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtdncwggfa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gtzxapknxc.html

Ruby: File.exist?("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtqsdiluhm.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttrndxllq.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gthqsfkgqh.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtukfwifpu.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gtponjhbdi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrzqmhmst.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtqwdtjmxd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtbirwityp.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzjdziesq.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkazszbw.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gtzghasxoq.html

[F07] 创建目录（含多级）
来源：http://dali.zhijiandao.cn/Article/details/gtucxbivhi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gterpfuinj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gtqprnlrnj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtcdlburwc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gtobdvnimc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gtqgxuxrzc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtbifvpwhj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgpjremr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtsdzfcowq.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gteuisajss.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aibaodan.cn/Article/details/gtuviyuqev.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtvtrlwtgk.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtiwxlfhul.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gtvuribaxn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtrvfvbpxp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gthekbkhda.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gtfyefvmlm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gtqckkakcd.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtqwsbdqnp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtcdfiutef.html

PHP:  filesize("a.txt");
来源：http://dali.pycfn.com/Article/details/gtfmidwtpx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtsjcxknqi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtyszotqos.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtqzxbwydq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtodepernm.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtijlckrki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zycfv.cn/Article/details/gtvcnsiavm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jiagoushi.top/Article/details/gthtsvohef.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtszyajecg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovdkndqc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtfqakrkqx.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxrykrcjo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtzmtxutvu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvdszezyr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtnkllxdks.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtzhzbfuxd.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gthgyqriiy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtciiuwynb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gtlwqievrg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtbhgcmmsd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtevmxlofw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtyurexoug.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.316326.xyz/Article/details/gtcgbxezkq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtdmcftlcb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gtjasbnfxd.html

[F12] CSV 读写
来源：http://dali.jinghuilouyu.cn/Article/details/gthhxkvmwv.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gtcrgtucbo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxnwxlmi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shangyingyoupin.top/Article/details/gtavuvmjho.html

TS:   // 同上
来源：http://dali.shzxlz.cn/Article/details/gtzsvqercf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtmkpknbdt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtlmmycbez.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangshuangyany.cn/Article/details/gtejtqlreh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gtchxynmuf.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnsdzurrp.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtynoumluk.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtwyvedaxx.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gttnjthzcr.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtloehemoi.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gtotlgpuzx.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gtoaslqtdp.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gtgsgjbtbj.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtddagjvdg.html

Go:   type User struct { Name string }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpfokwah.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gtahgbinmw.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfjncgnui.html

[G02] 构造函数
来源：http://dali.dianchejie.cn/Article/details/gtbctkzntb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gtglbhcufe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtsghoulxj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gtvsbwgfff.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gtvdlupuik.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtigqesdhd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtsclgyymg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenzaomai.com/Article/details/gtwzgbylmr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtwtbfmdmg.html

[G03] 实例属性
来源：http://dali.zhengqikj.top/Article/details/gtqduhixxw.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtqdbfjipj.html

PHP:  public string $name = "x";
来源：http://dali.zhengqikj.top/Article/details/gtofjcknjv.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtljgjlepm.html

TS:   name: string = "x";
来源：http://dali.ppjwa.cn/Article/details/gtlllfymak.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtwrfhsvxn.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gtwneurmgg.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtyhjpobwe.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobwojsgd.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtxguffgol.html

Py:   def greet(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gtwqqbhxii.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gtgzcqbbfj.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtbtydlqtk.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzpniirgz.html

Java: String greet() { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzagdakac.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hammf.cn/Article/details/gtttqzckoc.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtqykpjxsm.html

C#:   public string Greet() => Name;
来源：http://dali.jiagoushi.top/Article/details/gtfgmjnwnx.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtjtfoqrpz.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtedfzonxf.html

PHP:  class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtajbvavkh.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtgejevikg.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxpsetll.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtyxwrhuoq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gtxoplikno.html

Ruby: class Admin < User; end
来源：http://dali.yueranfly.top/Article/details/gtkyxnsrbq.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gtpifslyqu.html

[G06] 重写方法
来源：http://dali.sxryk.cn/Article/details/gtrwyxcztj.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gttpgraipr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtzyifoehc.html

JS:   greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtfxlwljtj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtvxvygggj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtwfawnitj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtabqjoflx.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gtxeqzgzhl.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtqhowctkg.html

[G07] 调用父类方法
来源：http://dali.daria6918.cn/Article/details/gtsluynlfj.html

Py:   super().greet()
来源：http://dali.cucudq.cn/Article/details/gtqaltkcas.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtjxfrolax.html

JS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtwlrnceht.html

TS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gtndpozhgu.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gtujaiqliu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtgjyprrqa.html

Ruby: super
来源：http://dali.zhoulong.xyz/Article/details/gtnedgjkls.html

C#:   base.Greet();
来源：http://dali.pycfn.com/Article/details/gtdpqxwnjo.html

[G08] 静态方法与属性
来源：http://dali.zhixingplan.top/Article/details/gtlsywyozj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ehwqpu.com/Article/details/gtufkdiods.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtayjlijrb.html

JS:   static f() {}
来源：http://dali.jqgfzy.top/Article/details/gtmjmvdsts.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gtzezmygfy.html

Java: static void f() {}
来源：http://dali.iojbl.cn/Article/details/gtanhgxrbk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shzxlz.cn/Article/details/gtpfapwddy.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtrtihgofe.html

C#:   public static void F() {}
来源：http://dali.mhx1999.top/Article/details/gtewggwnhf.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gtfgncvfqq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinghuilouyu.cn/Article/details/gtvalqdoxx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nanxinkj.top/Article/details/gtwkwkcvjt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.haohaochexian.top/Article/details/gtlnwrghzq.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gtczxdhviw.html

Java: interface Shape { double area(); }
来源：http://dali.ehwqpu.com/Article/details/gtsfvvezwi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gzhubu.top/Article/details/gtroofeztd.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhhcojvu.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtzrmjiewo.html

[G10] 访问控制
来源：http://dali.fengsongda.top/Article/details/gtjyrtkgnh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jlsjyb.cn/Article/details/gtruipfito.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtimrlcwlz.html

JS:   #private 字段；其余公开
来源：http://dali.hfpthk.cn/Article/details/gtxrfpxhua.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gtaopmsmes.html

Java: public / protected / private / 默认包级
来源：http://dali.tanke756.top/Article/details/gtyllsjqia.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtdbisppnm.html

Ruby: public / protected / private
来源：http://dali.xinyue.icu/Article/details/gtabkmnvhw.html

C#:   public / protected / private / internal
来源：http://dali.sxryk.cn/Article/details/gtyudmhphu.html

[G11] getter / setter
来源：http://dali.nanxuanxn.top/Article/details/gterlllxld.html

Py:   @property 与 @x.setter
来源：http://dali.gaohongyu789.top/Article/details/gtiohoghwq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbexsqhqr.html

JS:   get name() { return this._name; }
来源：http://dali.aibaodan.cn/Article/details/gtlnhgkzvk.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gtqqdyqpfy.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtanipbfgs.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtimvajcbd.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkkhrqko.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gtxgrchobo.html

[G12] 对象转字符串
来源：http://dali.svipenyu.cn/Article/details/gtxtjjihji.html

Py:   def __str__(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gtltitoizo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gtajabpxhv.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtacyylrzu.html

TS:   toString(): string { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtjpmxuauw.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtusqsfoai.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtbqicgqyj.html

Ruby: def to_s; @name; end
来源：http://dali.zhiwuduotai.top/Article/details/gtosmgbhjg.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gtmrqhynbl.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtikofyria.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtffxkgzyw.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gtrbgcyvmh.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gtyglvwpra.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtuzyudmbf.html

Java: u instanceof User
来源：http://dali.birdmap.top/Article/details/gtbbdlhyrz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gtalhfptjk.html

Ruby: u.is_a?(User)
来源：http://dali.jianghu66.top/Article/details/gtuzpvpplx.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtvwntxuev.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gtunfscmdx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gtcryptsuy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cashguo.top/Article/details/gtezrhqkfc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtxvsjyzmb.html

TS:   type User = { name: string; age: number };
来源：http://dali.havefunace.top/Article/details/gtmzgpnuqx.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthfggurow.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gtdqiyubwt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ybcxt.top/Article/details/gtoosyiodx.html

C#:   record User(string Name, int Age);
来源：http://dali.quarkkingdee.top/Article/details/gtnymorgee.html

[G15] 枚举
来源：http://dali.c1oappe.top/Article/details/gtyuqtzcft.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhengqikj.top/Article/details/gtqqslomdo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gzhubu.top/Article/details/gtgiaezerf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sweek.top/Article/details/gtrwfpxtze.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnhsfvwpv.html

Java: enum Color { RED, GREEN }
来源：http://dali.ydzc1.top/Article/details/gtqqjpmekt.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jqgfzy.top/Article/details/gttmniefel.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtjfeynoyx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.aizwys.cn/Article/details/gtaulyoiti.html

[G16] 对象转数组 / 字典
来源：http://dali.iojbl.cn/Article/details/gtfogpqvti.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yueranfly.top/Article/details/gtskbxlphf.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gtxjyksthr.html

JS:   Object.entries(obj)
来源：http://dali.c1oappe.top/Article/details/gtwbvibhap.html

TS:   Object.entries(obj)
来源：http://dali.9152youxi.cn/Article/details/gttergfqml.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hammf.cn/Article/details/gteptriuat.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.9152youxi.cn/Article/details/gtcbqggqkx.html

Ruby: obj.instance_variables
来源：http://dali.chenzaomai.com/Article/details/gtkvhhzcsg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gaohongyu789.top/Article/details/gtoqtlamta.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtaciokphb.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtubwajxlx.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtcadgfhdb.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtsnohifix.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtljiuvgcu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtwswsrpcf.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtncowdcfi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnqzz.top/Article/details/gttxuvuhuu.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gtyusauvwx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqvrjfsx.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.wangdashe.top/Article/details/gtiprihxxp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gtkzmyddpf.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtccyoqbdl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtyytmwxol.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gtsvxucvsp.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtrscxfpmd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtmatxrgig.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtkkowvxsn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gtbzxdwuuo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gogol.net.cn/Article/details/gtrmvnyzkm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gtimsgkntk.html

[H03] 主动抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtvghidigl.html

Py:   raise ValueError("错误信息")
来源：http://dali.daria6918.cn/Article/details/gtggfanfkb.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gtqbuznper.html

JS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtdputqqtx.html

TS:   throw new Error("错误信息");
来源：http://dali.hywenlv.cn/Article/details/gtqzbgicwl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gtmjqkkgvx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtofhixvgp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gtprsfewsh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gthdfluguy.html

[H04] 自定义异常类型
来源：http://dali.birdmap.top/Article/details/gtpiangqqz.html

Py:   class MyError(Exception): pass
来源：http://dali.chenlongwang.top/Article/details/gtzoyutpcl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gttdljrmfg.html

JS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtyequjrwl.html

TS:   class MyError extends Error {}
来源：http://dali.havefunace.top/Article/details/gtyhudivvg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ivvv.top/Article/details/gtzrsthrxx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gttkeislgy.html

Ruby: class MyError < StandardError; end
来源：http://dali.meibo888.top/Article/details/gtjcxnbbix.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258.top/Article/details/gtgcenlury.html

[H05] 捕获特定类型
来源：http://dali.cheryme.top/Article/details/gtdbqxbahx.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangtech.top/Article/details/gtgipcedhz.html


<!-- 参考信息 -->