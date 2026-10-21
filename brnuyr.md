代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gtqfqfzgpy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yuanzhike.top/Article/details/gtpvziasbp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtvmxdprkw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gthnrwxyrn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.smart0.xyz/Article/details/gtfcgupptq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtqvuxrqso.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dashuyun.cn/Article/details/gtczllhacq.html

Ruby: File.read("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtiknczlfx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwppzrxna.html

[F02] 逐行读取文件
来源：http://dali.yuxming.cn/Article/details/gtpncwrlet.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtljnvejna.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtnjucbfvt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtvdmtaido.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmikbalsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gtwffsbbux.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtfzhtjzbr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gtajwmmjoo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yanxiufei.cn/Article/details/gtmgylkvkj.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxujmyjoo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aizwys.cn/Article/details/gtpdhmnwxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtwfetegos.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gtlgdaudyu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdmpywvk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.vqdsnc.cn/Article/details/gtxrkdeeir.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gtahauumlq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtuplwrmtk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtfajodxea.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gthcppkhjj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtxupautmm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gttpupnare.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklhprfhq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gtjjniziyc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gtrajvsjrm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aizwys.cn/Article/details/gtgjijzspe.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hnqzz.top/Article/details/gtuhzhtuig.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aibaodan.cn/Article/details/gtqlymmfcv.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gtqaipybma.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sxryk.cn/Article/details/gtdlubfgig.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtvdgczgnc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtsakslksj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkdlpwbvg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtbgaqvxye.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhongyouzk.top/Article/details/gtazodxuul.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtliwgjhga.html

C#:   File.Exists("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtfxwrxdnw.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtbysfobhe.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxsbvrei.html

PHP:  unlink("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtsasnfcfo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gttnylojwg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkjqmizny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtqgwnoneq.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gtbbocxjvh.html

Ruby: File.delete("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmvofvvnq.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtsktaveev.html

[F07] 创建目录（含多级）
来源：http://dali.meibo888.top/Article/details/gtxsxjwauf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gthvvmbgbi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gtkhtcmvdj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwgebtub.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpopuepm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtjlqglnzm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtgunmqdpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gtmhriiclj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hysaishi.cn/Article/details/gttgvswkjm.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtleesxyre.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtramvcwho.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtbxpxzllk.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtcwgapccs.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gthdfoqpne.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gthlzpebvk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtwtjmughp.html

Ruby: Dir.children("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtkiapvsrm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtpjjwyktg.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtjilseeai.html

Py:   os.path.getsize("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtsixhvfds.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtyhshbcsb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gtgdnzajeu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gtuxbspvyp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtgjsixrue.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtodwajyjn.html

Ruby: File.size("a.txt")
来源：http://dali.hammf.cn/Article/details/gtaevddsmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtjjwsxcll.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cqqwz.cn/Article/details/gtlsxyixcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gtqwgadizk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtvvbcmfvy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbomjukse.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gtxmvtbzud.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtwjyjqfoc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtbbxemkik.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtrnuuqoqd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gtpvrtxirl.html

[F11] 复制与移动文件
来源：http://dali.316326.xyz/Article/details/gtgndwmzfu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmfwppozi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gtdekrxlcp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtkblffaco.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtetdcpmuc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gtigabrgfn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tanke756.top/Article/details/gtotnarflo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtbksnvzik.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gtgxobtwvo.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtjbkwdcxx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.feifeiyinyue.top/Article/details/gtyjfyoipo.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zycfv.cn/Article/details/gtppzyzpcq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gteadialfn.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtoufbjapb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gteeyqyxxz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtqumlinot.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.iojbl.cn/Article/details/gtwyffmwqo.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hammf.cn/Article/details/gtwczdkhvo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtikszieaa.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gtxhkvgshw.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyfqskjfw.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gtgjkznvel.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gtvvhajihw.html

PHP:  class User {}
来源：http://dali.c1oappe.top/Article/details/gtvqbccbqj.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtmqpfdyzx.html

TS:   class User { name: string = ""; }
来源：http://dali.kuanghao11.cn/Article/details/gtlqokhewm.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtbwruvirf.html

Go:   type User struct { Name string }
来源：http://dali.jianghu66.top/Article/details/gtsjxqqbtr.html

Ruby: class User; end
来源：http://dali.xuanzx.com/Article/details/gtsaosapci.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gtrhztrehx.html

[G02] 构造函数
来源：http://dali.xylfe.cn/Article/details/gterubypzl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gtmssfayit.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jiagoushi.top/Article/details/gtmelnknfm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtjquxxwjj.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gtzisecixy.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gtodqwnpyd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.gaohongyu789.top/Article/details/gtmpitcqmk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtcqldtgsc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtmfoivqzv.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtnlfjxpzs.html

Py:   self.name = "x"
来源：http://dali.jianghu66.top/Article/details/gtehfrxksc.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gtahkgjctr.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gtbyxmclwf.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gttmisoflt.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gtnqizppgv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gtbeophlhz.html

Ruby: @name = "x"
来源：http://dali.jlsjyb.cn/Article/details/gtvaoichar.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sxryk.cn/Article/details/gtnfqtrsgn.html

[G04] 定义方法
来源：http://dali.xuetiantiany.cn/Article/details/gtwwzaetif.html

Py:   def greet(self): return self.name
来源：http://dali.xinyue.icu/Article/details/gtsyvhixfi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtcqjcwoio.html

JS:   greet() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gtfsjnchcg.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtjghntvzt.html

Java: String greet() { return name; }
来源：http://dali.cucudq.cn/Article/details/gttazhzzcl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtobwfjgmc.html

Ruby: def greet; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gtiroqmqme.html

C#:   public string Greet() => Name;
来源：http://dali.yuanzhike.top/Article/details/gtqxuzkwyh.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gtynxwvzos.html

Py:   class Admin(User): pass
来源：http://dali.xuanzx.com/Article/details/gtowcloebx.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxmozcoh.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtclgbsrjz.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtkmdwoolh.html

Java: class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gtndlgjjig.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hywenlv.cn/Article/details/gtgfyhhigb.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtdpvsqant.html

C#:   class Admin : User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtevykxffx.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gtdzethsrk.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gtsofdpmmq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtldcjelwe.html

JS:   greet() { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbhhzign.html

TS:   greet(): string { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtjjuyabyq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jianghu66.top/Article/details/gtwfiftdxe.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtpjupdcut.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtrrccqouz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yvedp.cn/Article/details/gtmsvrwdui.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gtentklarx.html

Py:   super().greet()
来源：http://dali.hnqzz.top/Article/details/gtnyibmrjf.html

PHP:  parent::greet();
来源：http://dali.zhongyouzk.top/Article/details/gtpyfpbgzx.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtwtqpmfyl.html

TS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gtjjxitsjl.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gtnzganoql.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gtmtrqajlz.html

Ruby: super
来源：http://dali.pengpengdd.cyou/Article/details/gtflizfecf.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gtgdselqwq.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gtvgmtcfsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigufen.top/Article/details/gthsznxqzk.html

PHP:  public static function f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtkzokfigd.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtvjmeetib.html

TS:   static f(): void {}
来源：http://dali.gotoacloud.top/Article/details/gtfqmhzxym.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtawrukxwv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.kuanghao11.cn/Article/details/gttfdshwzb.html

Ruby: def self.f; end
来源：http://dali.gotoacloud.top/Article/details/gtfnbsyoyn.html

C#:   public static void F() {}
来源：http://dali.9152youxi.cn/Article/details/gtrmknaqiv.html

[G09] 接口 / 抽象类
来源：http://dali.chenzaomai.com/Article/details/gtwbtfqhku.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gttkfhckqf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sysykeji.top/Article/details/gtvzvcrdsf.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.c1oappe.top/Article/details/gtqvmborni.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gtiwrlifga.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtnkaujwyi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gtyqgmlsmj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sysykeji.top/Article/details/gtodoqcmio.html

C#:   interface IShape { double Area(); }
来源：http://dali.yanxiufei.cn/Article/details/gtclxypoda.html

[G10] 访问控制
来源：http://dali.nanxinkj.top/Article/details/gtzyotvwbl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnxiangtu.top/Article/details/gtymoqdvsg.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtsbdzmqhx.html

JS:   #private 字段；其余公开
来源：http://dali.cqqwz.cn/Article/details/gtdrxhimay.html

TS:   public / protected / private
来源：http://dali.birdmap.top/Article/details/gtlzwqpwfr.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gtwmsvsldx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtavlejtai.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtnstrmxrl.html

C#:   public / protected / private / internal
来源：http://dali.haohaochexian.top/Article/details/gtzknezhfq.html

[G11] getter / setter
来源：http://dali.jqgfzy.top/Article/details/gtwuyhpacz.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gtlpspjalf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidkhcptg.html

JS:   get name() { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gtisnamarl.html

TS:   get name(): string { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtnvfjrlia.html

Java: public String getName() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gthyqbxoew.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtylwcvufm.html

Ruby: attr_accessor :name
来源：http://dali.feifeiyinyue.top/Article/details/gtwscbvfil.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gtnbfrqhoh.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gttgwrxehn.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdyksljv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkzdvpaj.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjawsbqei.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gtrwjkvxat.html

Java: @Override public String toString() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtncaadrxa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtlzpozipg.html

Ruby: def to_s; @name; end
来源：http://dali.xziqi.cn/Article/details/gtrkdlrbxo.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gtddracpmw.html

[G13] 判断对象类型
来源：http://dali.birdmap.top/Article/details/gtorjcnbhf.html

Py:   isinstance(u, User)
来源：http://dali.yj202588.top/Article/details/gtykrfopwn.html

PHP:  $u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gtuhzitdxk.html

JS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtqvngwwiw.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gtjjhjvxar.html

Java: u instanceof User
来源：http://dali.cucudq.cn/Article/details/gtxgphlxbv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtznvavwxo.html

Ruby: u.is_a?(User)
来源：http://dali.ehwqpu.com/Article/details/gtbobziaqt.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gtmigpygqv.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtqfhtukeu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.andypj.xyz/Article/details/gtgklfdgsy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhiwuduotai.top/Article/details/gtjjtlklvt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zdqjudy.top/Article/details/gtftfkduqb.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gtvwiyupqb.html

Java: record User(String name, int age) {}
来源：http://dali.hywenlv.cn/Article/details/gtftcgotlb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sxryk.cn/Article/details/gtuhvdrezi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.0kj1m.cn/Article/details/gtfvjgnjvd.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtjmlryses.html

[G15] 枚举
来源：http://dali.yueranfly.top/Article/details/gtuqvxmndn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guowangkeji.top/Article/details/gtqmxaxrhb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.nwbrower.top/Article/details/gtznhwhtqc.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.andypj.xyz/Article/details/gteutivzyr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtcqhlmqyh.html

Java: enum Color { RED, GREEN }
来源：http://dali.jlsjyb.cn/Article/details/gtluajstrc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gtzzubnchr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgchezgxx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtopxegfle.html

[G16] 对象转数组 / 字典
来源：http://dali.0kj1m.cn/Article/details/gtgjwnijva.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gtjibnisro.html

PHP:  get_object_vars($obj);
来源：http://dali.gogol.net.cn/Article/details/gtsnvuchjb.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gtrksttjtp.html

TS:   Object.entries(obj)
来源：http://dali.redwolf501.top/Article/details/gttoppzkhe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cucudq.cn/Article/details/gtobpsxyna.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xylfe.cn/Article/details/gtnpihnjss.html

Ruby: obj.instance_variables
来源：http://dali.yj20258888.top/Article/details/gtfzsjqyqo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gteoaybfpe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttvnsdlmo.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gtjnzewovh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtahbaiugf.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gtjrqcigqo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gtohrfjiwl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.snrcjt.cn/Article/details/gtgedkodbi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jiagoushi.top/Article/details/gtjvuyhbpx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gtkggvmknj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gthzkbpzkl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.xziqi.cn/Article/details/gtxdvfyrhr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jqgfzy.top/Article/details/gtjcrvtdkj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtartupxbo.html

[H02] finally / ensure 收尾
来源：http://dali.xuetiantiany.cn/Article/details/gtqwsxjovd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.aibaodan.cn/Article/details/gtbxkiuytw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gthbtrdvuo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtyxwvecyk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtdfhvlurt.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gttffihftm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.fengsongda.top/Article/details/gtbattydob.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtkebvmbyv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcdknwdce.html

[H03] 主动抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtmidmoyme.html

Py:   raise ValueError("错误信息")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuztveef.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrhkveje.html

JS:   throw new Error("错误信息");
来源：http://dali.yj20258.top/Article/details/gtsvboiwry.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtevnuqjyq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtqsdmqgjl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gtcpvkqzcj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gtymmvzxhb.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtyvuaepkw.html

[H04] 自定义异常类型
来源：http://dali.yj202588.top/Article/details/gtismpaudp.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtwrcquuvt.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gttetphfrr.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtazozywut.html

TS:   class MyError extends Error {}
来源：http://dali.hnxiangtu.top/Article/details/gtmtfmxdbe.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gtrfbuisoj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yueranfly.top/Article/details/gtldiqatgr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yuxming.cn/Article/details/gtuxcbepcd.html

C#:   class MyException : Exception {}
来源：http://dali.yongpay.top/Article/details/gtvbyzjsic.html

[H05] 捕获特定类型
来源：http://dali.zhengqikj.top/Article/details/gtxodgbkmi.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gtvyevcjgp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gtsdmyatvs.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtcrwhrunr.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.nanxuanxn.top/Article/details/gttmlvohnm.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtcrjvbnvh.html


<!-- 参考信息 -->