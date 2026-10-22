代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtrkocvcyi.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtpqxbstou.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtvobpxlnv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtiymthhlm.html

[F01] 读取整个文件
来源：http://dali.hywenlv.cn/Article/details/gtgiyilbqs.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtvoyhtepi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtwbqveirw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gtwdirkxxe.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gtcbzwxcvk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gtrnwunbmk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ivvv.top/Article/details/gtpafdvjki.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtbyhtpsxr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtisshrepb.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtlqrvjixa.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtccxvnsag.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtvjyzlrak.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yvedp.cn/Article/details/gtnxthrsuq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtoxcidcad.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtnmscukib.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtdsbvqeep.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258.top/Article/details/gtmbhrghih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gthsnmytaz.html

[F03] 写入文件（覆盖）
来源：http://dali.tanke756.top/Article/details/gtzxmmlcqq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gtzuwfohsi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.tian-w.cn/Article/details/gtbiyssdgv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtaaqmqyik.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtlurijiiu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtwepprjbe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ydzc1.top/Article/details/gtuusawbas.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtawrdcrfs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtbiaoupjz.html

[F04] 追加写入文件
来源：http://dali.cheryme.top/Article/details/gtekodtksp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yongpay.top/Article/details/gtkbdomrkk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtagnrenqx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtwdyeybov.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtdfngygmb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtanjunoyi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtgtnmzgyq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gthgietzed.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gtjgdksrzi.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaguaqht.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtlmawwjmz.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtoqojvwml.html

JS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtlhhbwztr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxmqbvbme.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtyuajsmtd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtroitmfzq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjeeisft.html

C#:   File.Exists("a.txt")
来源：http://dali.pycfn.com/Article/details/gtjkqxejhj.html

[F06] 删除文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcvftqqq.html

Py:   os.remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgknaskam.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtehdjdgwm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtiukhfbjt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtlqxorvxu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtunwbpits.html

Go:   os.Remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtufepxiyj.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkdemzci.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gtkbrzhqoz.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gtimlhbhia.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtnuoyrhki.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtifqzsjnv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fzhhl.top/Article/details/gtettmxgmn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gtxukhwfnj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtwarnizhd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtnaexybko.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gttaqunitf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gtjvxqzqrc.html

[F08] 遍历目录
来源：http://dali.tianlin.xyz/Article/details/gtgqvccobs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shuidangran.top/Article/details/gtolxywwgf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yongpay.top/Article/details/gtxwfltiwx.html

JS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkgnrtrm.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gthllzprwz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrptwckz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtfnltjeid.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtowyqhnfy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtrwilxgdl.html

[F09] 获取文件大小
来源：http://dali.cdnleiting.top/Article/details/gtwkmlnkrp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtstxcriir.html

PHP:  filesize("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtrejybfwb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtdmhazvqq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlwclcgm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtuodrykzc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tanke756.top/Article/details/gtconplzge.html

Ruby: File.size("a.txt")
来源：http://dali.birdmap.top/Article/details/gtftmedhsx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gtpugvlozx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gtpeunaeqw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtycssjqap.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtgtckgfzv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwheqciji.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtssrjdvgf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sxryk.cn/Article/details/gtvoyxkmtt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtuspdkhvu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtmrpgmvar.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvmcbzdy.html

[F11] 复制与移动文件
来源：http://dali.feifeiyinyue.top/Article/details/gtvnwrhclg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtnhcgfvng.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cheryme.top/Article/details/gtldefrccz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtpyzqxviz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtmthkvsfh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.316326.xyz/Article/details/gtttwxsdve.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gttvnehwuy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtcllldqzs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gtwocpyrub.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gtelzqqkqd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gtyjtmepmp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gtgywhajuo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtnunxqevb.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtgogievyv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.aibaodan.cn/Article/details/gtbcmjyase.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhengqikj.top/Article/details/gtxprmwdbo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtvpynblam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhixingplan.top/Article/details/gtlurghwij.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtyknvuobb.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gtkuwiskeu.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsypazqxl.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtxiztpwqz.html

Py:   class User: pass
来源：http://dali.pengpengdd.cyou/Article/details/gtysmsxjdj.html

PHP:  class User {}
来源：http://dali.ehwqpu.com/Article/details/gtnqmmongw.html

JS:   class User {}
来源：http://dali.cdnleiting.top/Article/details/gtdusjdujb.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gtoaeywnit.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gtyuebzpnk.html

Go:   type User struct { Name string }
来源：http://dali.sweek.top/Article/details/gtzoysmapc.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtdiaatryj.html

C#:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gtrkhiqaoh.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gtdqpciscu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtunalkott.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtntzwgnlj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yuanzhike.top/Article/details/gtzhggaumk.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtftpauvdr.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtnqfakvpo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gtonmhqeiu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gaohongyu789.top/Article/details/gtlfxporgg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzrhiunut.html

[G03] 实例属性
来源：http://dali.jiagoushi.top/Article/details/gtznmvkvrw.html

Py:   self.name = "x"
来源：http://dali.chenzaomai.com/Article/details/gtxhxmlyjc.html

PHP:  public string $name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtanvdbvtl.html

JS:   this.name = "x";
来源：http://dali.andypj.xyz/Article/details/gtxszzhtrs.html

TS:   name: string = "x";
来源：http://dali.aibaodan.cn/Article/details/gttftbotdw.html

Java: private String name;
来源：http://dali.pycfn.com/Article/details/gtdrxpqxwd.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xinyue.icu/Article/details/gtfhxibtav.html

Ruby: @name = "x"
来源：http://dali.cdnleiting.top/Article/details/gtwsbiueat.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gtjzdivcot.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfrmdpef.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtmtexyoxv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtplkaiwuz.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtotmuptyp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtsodlhnny.html

Java: String greet() { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtwskmtmks.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gtqgjynzbf.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gtogcpfbcv.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gtwuaegzbp.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gtcqdbyzbl.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtzbqeafcs.html

PHP:  class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtsrfvqwly.html

JS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gtbdbzgqaj.html

TS:   class Admin extends User {}
来源：http://dali.yj20258.top/Article/details/gtzbpwyxay.html

Java: class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtdrphixly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtodmzgtzm.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gtksuzntkm.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gthoxegxmc.html

[G06] 重写方法
来源：http://dali.yuxming.cn/Article/details/gtwjjlkttw.html

Py:   def greet(self): return "admin"
来源：http://dali.meibo888.top/Article/details/gtwevbgtuw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtjiqyqakm.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtgykzvhrw.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtnuguqvhr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gtplonajrt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xuanzx.com/Article/details/gtoiqqyvkn.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtqraqmbhz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfmrpore.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gtihkqxmbp.html

Py:   super().greet()
来源：http://dali.jqgfzy.top/Article/details/gtckkofcge.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gtolmeruyu.html

JS:   super.greet();
来源：http://dali.shangyingyoupin.top/Article/details/gteudkszkb.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gtlhznzdqq.html

Java: super.greet();
来源：http://dali.sxryk.cn/Article/details/gtgizcgxyu.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.guannengcc.top/Article/details/gtqymhaiak.html

Ruby: super
来源：http://dali.zhiwuduotai.top/Article/details/gtlbaiutrw.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtsafzbcfg.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtwhuxxean.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gtivfuvvaa.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gtzupfzcrm.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtveayanpd.html

TS:   static f(): void {}
来源：http://dali.aizwys.cn/Article/details/gtkajssdla.html

Java: static void f() {}
来源：http://dali.yuxming.cn/Article/details/gtjwvrzvuk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gtosivjxkf.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtakesaxpw.html

C#:   public static void F() {}
来源：http://dali.jyoumei.cn/Article/details/gttblsdwnh.html

[G09] 接口 / 抽象类
来源：http://dali.xziqi.cn/Article/details/gtqzckvtqn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jlsjyb.cn/Article/details/gtnpksdvvx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhengqikj.top/Article/details/gtwadskfew.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuhpwcll.html

TS:   interface Shape { area(): number; }
来源：http://dali.aizwys.cn/Article/details/gtnilhnvlk.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gtnzphupmj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtcjeunavm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xylfe.cn/Article/details/gtqradhnng.html

C#:   interface IShape { double Area(); }
来源：http://dali.316326.xyz/Article/details/gtsqvklrtc.html

[G10] 访问控制
来源：http://dali.zycfv.cn/Article/details/gtuhxjtrbp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yuanzhike.top/Article/details/gtgamckeaf.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtcmlvdzvc.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtgjxvwmjc.html

TS:   public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gtnbjrbiph.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtckfxib.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.smart0.xyz/Article/details/gtvppynojg.html

Ruby: public / protected / private
来源：http://dali.xziqi.cn/Article/details/gtnhvivfax.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gtpsnbahhu.html

[G11] getter / setter
来源：http://dali.jinqigfzy.top/Article/details/gtuiyrtcta.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtecplyaox.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtjnmlqwfp.html

JS:   get name() { return this._name; }
来源：http://dali.sysykeji.top/Article/details/gtuvapfavk.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtkylutyqi.html

Java: public String getName() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtzeasfldt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gttvyfrxex.html

Ruby: attr_accessor :name
来源：http://dali.tianlin.xyz/Article/details/gtouyngrvp.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtiucwrnea.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gtzxxoyubt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtmyggapko.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gtzewsotxi.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtnyzwusxw.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtrodcihpt.html

Java: @Override public String toString() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodmzwanc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangshuangyany.cn/Article/details/gtpmbialhp.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gtfkawyxae.html

C#:   public override string ToString() => Name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsgfpqsr.html

[G13] 判断对象类型
来源：http://dali.aizwys.cn/Article/details/gtrnbpezwl.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gtfiwwqzmx.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gtrhttpqpr.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtoshltpnh.html

TS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtctgfzasi.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtcenuocrk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhixingplan.top/Article/details/gtbsfxcmjz.html

Ruby: u.is_a?(User)
来源：http://dali.wangdashe.top/Article/details/gtxafxcpph.html

C#:   u is User
来源：http://dali.pycfn.com/Article/details/gtnfpxiuky.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtotubyvgr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xylfe.cn/Article/details/gtybvbdiix.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.dianchejie.cn/Article/details/gtlxdnfngn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtxuymwnat.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtclpuckvg.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gtogywxvwt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gtynzijkaa.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gtvqwlejdi.html

C#:   record User(string Name, int Age);
来源：http://dali.iojbl.cn/Article/details/gtjarhgdaq.html

[G15] 枚举
来源：http://dali.yongpay.top/Article/details/gtxfoefkai.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jqgfzy.top/Article/details/gtiktjrmmw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbddtkltu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.chenjidiqi.icu/Article/details/gtbciwysiq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxqvbferq.html

Java: enum Color { RED, GREEN }
来源：http://dali.tanke756.top/Article/details/gtmkenzatq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gzhubu.top/Article/details/gtexuvakww.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hysaishi.cn/Article/details/gtbtkiktox.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gtzvvbocvx.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gtqehossjp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zycfv.cn/Article/details/gtexqcahhr.html

PHP:  get_object_vars($obj);
来源：http://dali.shangyingyoupin.top/Article/details/gtanecolvl.html

JS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtakhecwvw.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gtyqdzciql.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gtrffwanpf.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.nanxuanxn.top/Article/details/gtlujydqww.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtothgfxgv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gtugxqhobw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjfqpahky.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gtfszhiwws.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtmcvgilyn.html

[H01] try / catch 基础
来源：http://dali.yuxming.cn/Article/details/gtbfiahqiv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqggbwjb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gtxnmwtzsb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtztzgpafo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtqhwllsgr.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gtznvrmwjk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jqgfzy.top/Article/details/gtjynyngea.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dashuyun.cn/Article/details/gtppvbjcus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gtorvwgvjb.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gtgyboggwp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gtwgcweoys.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gttuwfuyfe.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gteczifgss.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpfekfydw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtneiovwmx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gtqvwymuxk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gteafhzjoi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlurxzfj.html

[H03] 主动抛出异常
来源：http://dali.snrcjt.cn/Article/details/gtppkbgskl.html

Py:   raise ValueError("错误信息")
来源：http://dali.jiagoushi.top/Article/details/gtksfyusjj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gtfhwyhkuy.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtpmozqgjf.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtejelmobu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gtkzydnpjm.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.birdmap.top/Article/details/gtijfuqhff.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jiagoushi.top/Article/details/gtrluawegn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gtlbhmazej.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtmhrgmfwn.html

Py:   class MyError(Exception): pass
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvxwewph.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppwpznga.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtuwcbrgif.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtrafwslhw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gtovpoprya.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guannengcc.top/Article/details/gtojepxmgg.html

Ruby: class MyError < StandardError; end
来源：http://dali.smart0.xyz/Article/details/gtiyfklpjy.html

C#:   class MyException : Exception {}
来源：http://dali.xuetiantiany.cn/Article/details/gthvpyujld.html

[H05] 捕获特定类型
来源：http://dali.hfpthk.cn/Article/details/gtmrebnaag.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtfzttjvuw.html


<!-- 参考信息 -->