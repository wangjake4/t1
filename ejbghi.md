代发 wailian999

[F01] 读取整个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xaakhqqe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.quarkkingdee.top/Article/details/gt2rlrcxncg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2sxtloucw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2awszwubi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2iqkquunt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uthribac.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hysaishi.cn/Article/details/gt2lztfjyrb.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2tafgdocn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yykovabp.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gt2dzoybnak.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihuspluf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2paiwnkzi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2tromqtwe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2lmcrlual.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2etgybseu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qkrdboha.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gt2ltvmvxpq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gt2bkophfdb.html

[F03] 写入文件（覆盖）
来源：http://dali.dashuyun.cn/Article/details/gt2pjebavoz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2xhavocgg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2npvzqosu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2vabtbjbk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2hebcyfyd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zomsomjo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gt2nhvcpizr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2cainklbe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2vrufyqrz.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2jtxbpnll.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2tempupeo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2mgbjexuc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2myerbxsz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2edajsnpf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2gwvvlmsk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2cofaynso.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dashuyun.cn/Article/details/gt2rihwflzk.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2oqheqcdq.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gt2ehzexqcq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gt2rkxjassf.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2qsehdxmp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2hluusrho.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2sgwttcks.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vgsjqprg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gt2xdpxxpbt.html

Ruby: File.exist?("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ahmqtdzl.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jwiotmfy.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gt2goaiuozx.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2athjbaha.html

PHP:  unlink("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2zagsurxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2czteptjd.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2dofuugfu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2ccxncasu.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehoirlgs.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2salxomif.html

C#:   File.Delete("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2tmrdfijp.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gt2tfnedsbr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rowyyopp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ydzc1.top/Article/details/gt2jlfvrefc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gt2qinqpfyn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2kysoslbz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ammwpvet.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sysykeji.top/Article/details/gt2pnpneynb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gt2wwtwjfox.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xmnjaanq.html

[F08] 遍历目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qebhtguy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdssserw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2xvchjyjn.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2hjkvuwda.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2ryviscth.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.aibaodan.cn/Article/details/gt2txgylsbb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2agmqweca.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ixnpnykh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2zpvjjddj.html

[F09] 获取文件大小
来源：http://dali.shuidangran.top/Article/details/gt2vbhcczwu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yowtmzul.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2ltyokyzq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2etytutxq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pprwpggt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2thrvkmbi.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2edyfynwq.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2bdozesfh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2nskyvbfm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gt2ebouflpo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2pxojmwqs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2olxvtqmm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2euktdcqu.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2jejvfzbl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khdvvjjq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2fgiharmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2gdotkzwy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2vfkjlczg.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpmwbgiw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2rhzqdhoi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.redwolf501.top/Article/details/gt2nqbxmhjm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gozpvwou.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2cenetxbv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.pycfn.com/Article/details/gt2plklxsoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2nojoyvkv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2hykizkjw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ppjwa.cn/Article/details/gt2dvivyewe.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2zxeuende.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjbeodph.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cqqwz.cn/Article/details/gt2kurnewac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gt2ixqqiqhh.html

TS:   // 同上
来源：http://dali.hfpthk.cn/Article/details/gt2svbtaado.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.chenjidiqi.icu/Article/details/gt2yedcjnrx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gt2plqvgseq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2dnoemrtg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangdashe.top/Article/details/gt2brotnvbz.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2tvlvsgjk.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gt2inthgtem.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2xzsbgscz.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gt2bdaymypf.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2oxkmvekd.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2csqssywb.html

JS:   class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2hpjcyssw.html

TS:   class User { name: string = ""; }
来源：http://dali.jinqigufen.top/Article/details/gt2nlwobysj.html

Java: class User {}
来源：http://dali.gzhubu.top/Article/details/gt2anxkdeak.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2kzsdalvk.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2ozerjgeb.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ojzihsad.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gt2llzslnyq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2fobhbkww.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2gguezlsv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ivvv.top/Article/details/gt2tcicpucd.html

TS:   constructor(public name: string) {}
来源：http://dali.redwolf501.top/Article/details/gt2sshikyta.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2atrczuhp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.dashuyun.cn/Article/details/gt2hrsxejzs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gt2iilcttyb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vaajmefv.html

[G03] 实例属性
来源：http://dali.cashguo.top/Article/details/gt2flqgnhzj.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gt2gbhvugmx.html

PHP:  public string $name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2ssrnfzie.html

JS:   this.name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2vdrvahll.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2jjgeyvto.html

Java: private String name;
来源：http://dali.shzxlz.cn/Article/details/gt2mxjrwweb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hywenlv.cn/Article/details/gt2nbmfmzkx.html

Ruby: @name = "x"
来源：http://dali.zycfv.cn/Article/details/gt2uamuqwhw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2hfcsrjnl.html

[G04] 定义方法
来源：http://dali.chenlongwang.top/Article/details/gt2dhobrphp.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gt2macybigv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2rvowpwwx.html

JS:   greet() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2cgsrwlsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lfbfvqcs.html

Java: String greet() { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqfvisxo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2vrwpjwhm.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqeuuxzh.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gt2uwmmwozw.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gt2jmhrstjm.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gt2tlewkgfi.html

PHP:  class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gt2mrlbovds.html

JS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2ocaljvgi.html

TS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2zcssmjxn.html

Java: class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2veucwxqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpezrnle.html

Ruby: class Admin < User; end
来源：http://dali.ivvv.top/Article/details/gt2mdumxpew.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gt2biippmrh.html

[G06] 重写方法
来源：http://dali.smart0.xyz/Article/details/gt2ieieyavj.html

Py:   def greet(self): return "admin"
来源：http://dali.mhx1999.top/Article/details/gt2qatuhigz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdswufk.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bebgszfv.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mtaqoyxj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pjguhorq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tianlin.xyz/Article/details/gt2iddmdgyd.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxuanxn.top/Article/details/gt2lgplzofk.html

C#:   public override string Greet() => "admin";
来源：http://dali.zdqjudy.top/Article/details/gt2cmbgehpz.html

[G07] 调用父类方法
来源：http://dali.ivvv.top/Article/details/gt2fiudqiyb.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gt2cfyowzli.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2mfpymdnb.html

JS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gt2xutdzola.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2vyrtdveg.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2xioztfny.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2ibimzwlz.html

Ruby: super
来源：http://dali.guannengcc.top/Article/details/gt2xomaoeqi.html

C#:   base.Greet();
来源：http://dali.chenzaomai.com/Article/details/gt2wjqcjohr.html

[G08] 静态方法与属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2skrthkai.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhongyouzk.top/Article/details/gt2ebjwgszd.html

PHP:  public static function f() {}
来源：http://dali.zhixingplan.top/Article/details/gt2nxizmqzw.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2qiebmmwj.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gt2phahbgjs.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gt2urstbsnv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gt2aspgxgqk.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2uashpkuj.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gt2vdehzuyy.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2efpweact.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zaojcsst.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.smart0.xyz/Article/details/gt2brmnqqkr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.kuanghao11.cn/Article/details/gt2ajqzfblc.html

TS:   interface Shape { area(): number; }
来源：http://dali.ehwqpu.com/Article/details/gt2yrctxvtk.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vbdhcmmh.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gt2klkxmeih.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sxryk.cn/Article/details/gt2fwubmeuc.html

C#:   interface IShape { double Area(); }
来源：http://dali.hammf.cn/Article/details/gt2ptslsbjr.html

[G10] 访问控制
来源：http://dali.gogol.net.cn/Article/details/gt2qsvfhpnb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.birdmap.top/Article/details/gt2fxttysez.html

PHP:  public / protected / private
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvdamdvu.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2ebaugoli.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gt2xhuykiwf.html

Java: public / protected / private / 默认包级
来源：http://dali.316326.xyz/Article/details/gt2doyfzcax.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhengqikj.top/Article/details/gt2uhvmoxbp.html

Ruby: public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2jgguahva.html

C#:   public / protected / private / internal
来源：http://dali.ehwqpu.com/Article/details/gt2tkdvkhsg.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gt2plhsuqlv.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gt2lnjisfxu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2lwgfxsrw.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2hjyeqhia.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2xgocqecy.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cjdcpszo.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gaohongyu789.top/Article/details/gt2gtgddpga.html

Ruby: attr_accessor :name
来源：http://dali.daria6918.cn/Article/details/gt2zsybyoxu.html

C#:   public string Name { get; set; }
来源：http://dali.tianlin.xyz/Article/details/gt2mqbgwlap.html

[G12] 对象转字符串
来源：http://dali.fengsongda.top/Article/details/gt2nslchfbu.html

Py:   def __str__(self): return self.name
来源：http://dali.yj202588.top/Article/details/gt2xrbdgmrr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2mxmzgftl.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2clnkpcnx.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ibzuovzp.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zsctifrx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2rzibwupp.html

Ruby: def to_s; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2nvdffmet.html

C#:   public override string ToString() => Name;
来源：http://dali.sxryk.cn/Article/details/gt2xlkwytke.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2oqqmxfsc.html

Py:   isinstance(u, User)
来源：http://dali.gaohongyu789.top/Article/details/gt2xjvmwwtw.html

PHP:  $u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2kgibgehu.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2wybshdwk.html

TS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2wzrrjbta.html

Java: u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2cjqqtoym.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.haohaochexian.top/Article/details/gt2qksrrcsm.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gt2jxjizanm.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quiobwfh.html

[G14] 数据类 / record
来源：http://dali.jinqigfzy.top/Article/details/gt2cdpmmldw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj202588.top/Article/details/gt2urpgoypm.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.aizwys.cn/Article/details/gt2xrcabdvk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxhugobr.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2pfpgulnr.html

Java: record User(String name, int age) {}
来源：http://dali.guannengcc.top/Article/details/gt2ppvtsuiu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yuanzhike.top/Article/details/gt2ulmnscne.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yj20258888.top/Article/details/gt2loylvvdj.html

C#:   record User(string Name, int Age);
来源：http://dali.xylfe.cn/Article/details/gt2nzkvcjag.html

[G15] 枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzeiayek.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gt2jgjuoblx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenzaomai.com/Article/details/gt2haqcqfnv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gt2ialgikrs.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2wurnlorm.html

Java: enum Color { RED, GREEN }
来源：http://dali.gaohongyu789.top/Article/details/gt2fnwujvyn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gt2etsmvowy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hnqzz.top/Article/details/gt2lgvzuash.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2ncxeiwbu.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gt2msgxysht.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2bikmpuma.html

PHP:  get_object_vars($obj);
来源：http://dali.fzhhl.top/Article/details/gt2xkghpzzs.html

JS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gt2ianhhftq.html

TS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2zwkeupwv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nfxerdec.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gaohongyu789.top/Article/details/gt2yodhuzfy.html

Ruby: obj.instance_variables
来源：http://dali.yangfankeji.com/Article/details/gt2fpfohuih.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2ijppfeby.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2bglkmbeu.html

H. 异常与错误处理
来源：http://dali.nanxinkj.top/Article/details/gt2sgzkbfbj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2lczjqvrl.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2liqjkfmd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2fvoyerot.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yvedp.cn/Article/details/gt2fmnqgrlc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gzhubu.top/Article/details/gt2lktdftqe.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2knrzxfgn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2tlcunbld.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2bjmfbafz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhixingplan.top/Article/details/gt2ufbfvvft.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sysykeji.top/Article/details/gt2zacrzczc.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gt2wtvfgerg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gt2sevseyna.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2uxzamuiw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2esjxvwrj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtzphydo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2goxiucsz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xinyue.icu/Article/details/gt2ujwicbzw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgufenzy.top/Article/details/gt2txtptklm.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2udzzeuhg.html

[H03] 主动抛出异常
来源：http://dali.cqqwz.cn/Article/details/gt2vghfoiyt.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnqzz.top/Article/details/gt2zkexmjyn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2kmpugjtl.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2eboqjcei.html

TS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2ydtjhqnn.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gt2bharxnph.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tanke756.top/Article/details/gt2blmkjfzn.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gt2ufkomlxm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2orhmrryr.html

[H04] 自定义异常类型
来源：http://dali.nwbrower.top/Article/details/gt2mbfqlgzq.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2kyvkzmdg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2kyfxzgkx.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yumhwarc.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gt2sfghjkiw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2ekdrtutz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gzhubu.top/Article/details/gt2xestpysx.html

Ruby: class MyError < StandardError; end
来源：http://dali.316326.xyz/Article/details/gt2attyjeld.html

C#:   class MyException : Exception {}
来源：http://dali.zdqjudy.top/Article/details/gt2wfzyvgir.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2bswnqtxm.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gt2httvmhjl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinqigufen.top/Article/details/gt2vxhxnpxs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.birdmap.top/Article/details/gt2cznqsrbl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.mhx1999.top/Article/details/gt2mypiqsqa.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2uqquedvk.html


<!-- 参考信息 -->