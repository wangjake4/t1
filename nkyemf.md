代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbgzdkne.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtogbzfgad.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtbmhkbhim.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjiwaeodp.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtmekpjldg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhoulong.xyz/Article/details/gtrkfiyebe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gtxgwpzkzp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ehwqpu.com/Article/details/gtwudpzosb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtldxrmegx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtawiynycx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhixingplan.top/Article/details/gtcdfkghsa.html

Ruby: File.read("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtfkgfyfwt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtmnybzian.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtzwotsnhw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtidcbsqtn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtqfxxncmr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gtvxfwmjml.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gtdflrlqqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shzxlz.cn/Article/details/gthjarfzmv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnxiangtu.top/Article/details/gtqwavbmhw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gtcelgholh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtnsddqchc.html

[F03] 写入文件（覆盖）
来源：http://dali.havefunace.top/Article/details/gtovqiabsh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hnqzz.top/Article/details/gtjvziwqxd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gtpgbzolar.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gthoxrfeoq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yvedp.cn/Article/details/gtpvvxjzta.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gthltleecw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtlzkqmlrq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gtycemnxgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yueranfly.top/Article/details/gtlhzovzmd.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gtsibdinjo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ybcxt.top/Article/details/gtpvfwston.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gtyuwvgxya.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtpzvdfgph.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtxbgazjbz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xziqi.cn/Article/details/gthfjtjysx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gtknpphpoj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gtahvlwtga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sufxvd.cn/Article/details/gtwtbdjnjf.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gtfzdxaztb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gtibouraac.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtqpnkqnzr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtnyckzpub.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtxcfoexao.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtbxidtrpw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtpgtiihfq.html

Ruby: File.exist?("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtrluduucy.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtrsrmiudv.html

[F06] 删除文件
来源：http://dali.dashuyun.cn/Article/details/gtmqvpdgpg.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtexidyjyr.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtiwillpus.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtwdhnfuqs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtmyucikuj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtgmvbvhsb.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtgrbbvdit.html

Ruby: File.delete("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqwvbanwc.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtalunbofs.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtjzapacas.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtoesgtljm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gtjxfiiypw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtngcnsfjt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gtozcuersy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zycfv.cn/Article/details/gtbcsokwbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dashuyun.cn/Article/details/gtluyflrcq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtgkqgpuzw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sxryk.cn/Article/details/gtewkytjgd.html

[F08] 遍历目录
来源：http://dali.shanyushiyangtech.top/Article/details/gttjkgxkyy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtxpdtqhxh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gtkatdzgjf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gthknuxzif.html

TS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gtxuvmpigz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtedrctyga.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gtqtxoggay.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gtdrswbiar.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tian-w.cn/Article/details/gtdtjktxbo.html

[F09] 获取文件大小
来源：http://dali.jinghuilouyu.cn/Article/details/gtpagycbwj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttwvmnftr.html

PHP:  filesize("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtmfnvwplq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtakaqaoka.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gttjgxabom.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gthruvdxxu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.kuanghao11.cn/Article/details/gtaoqgvcgh.html

Ruby: File.size("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmcyzkejb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtahvhborn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtnsejchso.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtiifkhykq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtnzdtgsui.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtmvuiudyt.html

TS:   path.extname("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtihiwllbz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvesthem.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtqoxnrxbp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnoqpittm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.meibo888.top/Article/details/gtwgptgzdf.html

[F11] 复制与移动文件
来源：http://dali.pengpengdd.cyou/Article/details/gtnllaodkf.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtalwafttt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj20258888.top/Article/details/gtwvkhgvbb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gtdldnhydr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtsrmglpxm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gtogaqtitc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusyrqcme.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtgvgtiypn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xuanzx.com/Article/details/gtgwxdxaka.html

[F12] CSV 读写
来源：http://dali.birdmap.top/Article/details/gtusdxrwwh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.daxiang520.top/Article/details/gtzydujdxl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinqigufen.top/Article/details/gtbeauuthu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtaumuqkhj.html

TS:   // 同上
来源：http://dali.yuxming.cn/Article/details/gtfgxsswba.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtwpecmxra.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gtokkwdrqf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtpzhjzqwl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtuuxkzfha.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtwtophslq.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtyxyxogkj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtexeiuwyg.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gtodkfqjeo.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtukstslqq.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtudhwbplh.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtzlrlufwy.html

TS:   class User { name: string = ""; }
来源：http://dali.ppjwa.cn/Article/details/gtgofojlll.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtyptzsddr.html

Go:   type User struct { Name string }
来源：http://dali.0kj1m.cn/Article/details/gtckktiznw.html

Ruby: class User; end
来源：http://dali.yj20258888.top/Article/details/gthxfbpbjc.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gtzkwlsbxm.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gtqzrnqmot.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtfgqetvsr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtzaabzdfc.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtmvegoafz.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtvoazpqdr.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gtwqnuousm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sysykeji.top/Article/details/gtetkatatl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxinkj.top/Article/details/gthqatkika.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shuidangran.top/Article/details/gtbhoznooo.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gtycfebotw.html

Py:   self.name = "x"
来源：http://dali.yj20258888.top/Article/details/gtugrpbpaq.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtbbwrhaij.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtdtqrmxsm.html

TS:   name: string = "x";
来源：http://dali.daria6918.cn/Article/details/gtdeednlii.html

Java: private String name;
来源：http://dali.zhongyouzk.top/Article/details/gtbdfwnawa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigfzy.top/Article/details/gthuuegyfx.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gthlttvllv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtsfutpjha.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtitjkmwrv.html

Py:   def greet(self): return self.name
来源：http://dali.yj202588.top/Article/details/gtjidpzqnm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gtnqxvlrez.html

JS:   greet() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtvmjrqkkb.html

TS:   greet(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gtnaskyumh.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtxjqhjcoi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gtuukjzrhg.html

Ruby: def greet; @name; end
来源：http://dali.ydzc1.top/Article/details/gthqgtkdnr.html

C#:   public string Greet() => Name;
来源：http://dali.pycfn.com/Article/details/gtvoajwbmv.html

[G05] 继承
来源：http://dali.chenlongwang.top/Article/details/gtfkiaekov.html

Py:   class Admin(User): pass
来源：http://dali.chenjidiqi.icu/Article/details/gtgcarppgp.html

PHP:  class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gtjhcmbplq.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gtzvfxjlvj.html

TS:   class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gttdbmyscp.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gtogrtkhxy.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtslarzmfp.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gtllzqyutt.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gtoewbykip.html

[G06] 重写方法
来源：http://dali.pengpengdd.cyou/Article/details/gtgwjsanra.html

Py:   def greet(self): return "admin"
来源：http://dali.smart0.xyz/Article/details/gtddpxxzky.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtohezbgva.html

JS:   greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtvaqumeal.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtujrmumhm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtypkszxmc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gttkuszywh.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtqvwoxkiy.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gtfmmaqhwv.html

[G07] 调用父类方法
来源：http://dali.daxiang520.top/Article/details/gtmwnubirz.html

Py:   super().greet()
来源：http://dali.jyoumei.cn/Article/details/gtpxhgecoj.html

PHP:  parent::greet();
来源：http://dali.tanke756.top/Article/details/gtxleedqeh.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtczphtvya.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gtoxvbmnvd.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtpyatqtgx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhixingplan.top/Article/details/gtzkykfftk.html

Ruby: super
来源：http://dali.xziqi.cn/Article/details/gtfklrmldn.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtbpemehvw.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtrbfbwlbm.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuxming.cn/Article/details/gtsbnneusi.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gtscirjgpf.html

JS:   static f() {}
来源：http://dali.ehwqpu.com/Article/details/gtovcvlnyh.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtpkvqjlck.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gtirbtdgye.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gtovklbxgt.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gtleynhpzj.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtsstdyvxs.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gtiljcnmkd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pycfn.com/Article/details/gtbemfwjcw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gtnxmjiymk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.meibo888.top/Article/details/gtzvowcgty.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtnkwujtdb.html

Java: interface Shape { double area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqfkamwbv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gtmeaaupnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ehwqpu.com/Article/details/gtsxylzwyz.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gtksvrlqie.html

[G10] 访问控制
来源：http://dali.sweek.top/Article/details/gtwymknvnj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gtmikvwfwh.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtwofpycnw.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcymtfdzf.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtoembvhuh.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gtaizxsfdd.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gotoacloud.top/Article/details/gtjpbxzoei.html

Ruby: public / protected / private
来源：http://dali.chenjidiqi.icu/Article/details/gtjxrpiinv.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gtsfajlawh.html

[G11] getter / setter
来源：http://dali.yuxming.cn/Article/details/gtofsydkkt.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gtdvjradhk.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gttithzdde.html

JS:   get name() { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtjsdectym.html

TS:   get name(): string { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtpfghfddt.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtpscsvcsa.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.316326.xyz/Article/details/gtnahjrvjv.html

Ruby: attr_accessor :name
来源：http://dali.aibaodan.cn/Article/details/gtqrntaqfg.html

C#:   public string Name { get; set; }
来源：http://dali.wangshuangyany.cn/Article/details/gtknsljtjs.html

[G12] 对象转字符串
来源：http://dali.haohaochexian.top/Article/details/gtbibjkzpd.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtksuvxqqm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtitavhmau.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gtxpubchpl.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gtowawywqg.html

Java: @Override public String toString() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtsdetujzk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnklndjyw.html

Ruby: def to_s; @name; end
来源：http://dali.wangdashe.top/Article/details/gtqqwzimkd.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtykhrafqp.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gterltmztj.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gtxsgskdoi.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gtzssgwtwa.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtjdprbntd.html

TS:   u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gtxfynygvd.html

Java: u instanceof User
来源：http://dali.daria6918.cn/Article/details/gtgknhrlez.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.wangshuangyany.cn/Article/details/gtaxnoegdo.html

Ruby: u.is_a?(User)
来源：http://dali.yj202588.top/Article/details/gtcmaigkgg.html

C#:   u is User
来源：http://dali.nwbrower.top/Article/details/gtqnfkulrb.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gtnmtavfrf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.chenjidiqi.icu/Article/details/gtqcmmsdfl.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hfpthk.cn/Article/details/gtyvbnuhkl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqhsgguq.html

TS:   type User = { name: string; age: number };
来源：http://dali.ehwqpu.com/Article/details/gtlxxjmsqb.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gthjxkxyha.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwtzcqig.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gtxmjrnhsw.html

C#:   record User(string Name, int Age);
来源：http://dali.chenzaomai.com/Article/details/gtiszbslxl.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gtcmjlvqci.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.haohaochexian.top/Article/details/gtqvvgeqzr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gtuiuqqods.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gtowtpiywg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtvdtbetds.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtgqtxsema.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daria6918.cn/Article/details/gtahksmmin.html

Ruby: Color = %i[red green].freeze
来源：http://dali.feifeiyinyue.top/Article/details/gtprhuqtkd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtrsxqvxjp.html

[G16] 对象转数组 / 字典
来源：http://dali.gaohongyu789.top/Article/details/gtmzvvylmj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.xinyue.icu/Article/details/gtbrqthkwh.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gthhmajend.html

JS:   Object.entries(obj)
来源：http://dali.daria6918.cn/Article/details/gtobhkypxp.html

TS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtgdgsbrdc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.shanyushiyangtech.top/Article/details/gtndnyvgpk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hywenlv.cn/Article/details/gtrktzgkqs.html

Ruby: obj.instance_variables
来源：http://dali.gzhubu.top/Article/details/gtnqrnrndu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gturzqlwls.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjahopidu.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gtbrkuvbig.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgvlssohx.html

[H01] try / catch 基础
来源：http://dali.cucudq.cn/Article/details/gtvynvvygp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aizwys.cn/Article/details/gtrtyfhmfn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dianchejie.cn/Article/details/gtyubbygis.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtnspktaqt.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhoulong.xyz/Article/details/gtqqhpreat.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xuanzx.com/Article/details/gtkroqahba.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jlsjyb.cn/Article/details/gtuywofiow.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.meibo888.top/Article/details/gtuiluswbq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtboitbftz.html

[H02] finally / ensure 收尾
来源：http://dali.tianlin.xyz/Article/details/gtcitphola.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenlongwang.top/Article/details/gtjabjddiz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvncxoaw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtkipfpnfo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgsmogewl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtxfglfcfu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cashguo.top/Article/details/gtamytvvkx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shuidangran.top/Article/details/gthswtcmcw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtscrdpjar.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtetbysuaj.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gtntgunlfs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.tianlin.xyz/Article/details/gtdgmedfdl.html

JS:   throw new Error("错误信息");
来源：http://dali.c1oappe.top/Article/details/gtcdtheole.html

TS:   throw new Error("错误信息");
来源：http://dali.cheryme.top/Article/details/gtnuhujvcy.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtbcivwolz.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhiwuduotai.top/Article/details/gtvofgcvdb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinqigufen.top/Article/details/gtaccoxvfg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtnnoygudb.html

[H04] 自定义异常类型
来源：http://dali.hysaishi.cn/Article/details/gtgkhjoghc.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtzyhveasl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivgvkdvt.html

JS:   class MyError extends Error {}
来源：http://dali.cucudq.cn/Article/details/gtqsgmmqxr.html

TS:   class MyError extends Error {}
来源：http://dali.gotoacloud.top/Article/details/gtrxvtodzk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xziqi.cn/Article/details/gtdcjhvjml.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yj202588.top/Article/details/gtvuetexqb.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtidkapina.html

C#:   class MyException : Exception {}
来源：http://dali.yj20258888.top/Article/details/gtwmaimcno.html

[H05] 捕获特定类型
来源：http://dali.xinyue.icu/Article/details/gtngqezbdo.html

Py:   except ValueError as e:
来源：http://dali.smart0.xyz/Article/details/gtrywsombr.html


<!-- 参考信息 -->