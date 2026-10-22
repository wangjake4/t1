代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2dtsxhfhd.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gt2qbukjotz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigfzy.top/Article/details/gt2eomzisof.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vaqcyyvz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2jrvvdkxd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ansrtmcp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2olsxfsxw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2guidrfsb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.gzhubu.top/Article/details/gt2spzhpgup.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2ivfkessx.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2iibmkzka.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2urikvncj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fzhhl.top/Article/details/gt2hvsiahol.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2cmmqwojo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2heycyzdv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwbehfxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2oabnpmod.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangdashe.top/Article/details/gt2nybzxzyg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daria6918.cn/Article/details/gt2xeuemdek.html

[F04] 追加写入文件
来源：http://dali.yj202588.top/Article/details/gt2gbrgbftl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2zijjvola.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.aibaodan.cn/Article/details/gt2fgjrswjz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2pykieniy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2mztnomuw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tian-w.cn/Article/details/gt2wbabmvov.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rysltsoq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gt2esnrqbck.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2tvsdwfpf.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2qdghkpga.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2xcimpbvt.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ambtpkkr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2gtcwrmag.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ngrgtbam.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gt2efzmully.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gt2hizhuooc.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2vaqlffai.html

C#:   File.Exists("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2yeuwyfmg.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftwcxuuj.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2mhhtnupd.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2tkpukosc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2fcdqicgs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2vtwckhbu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2nwyjszua.html

Go:   os.Remove("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2lickmafh.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2neutwqng.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2ramhsjwv.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2ivpvvmmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gt2ruwxfldq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gt2boigshgq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2zvtujhjp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2qdiyzttk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxuanxn.top/Article/details/gt2gadcvuxi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gt2qdtoycne.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wndgupay.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gt2wejuroks.html

[F08] 遍历目录
来源：http://dali.xuetiantiany.cn/Article/details/gt2nrlizsvx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gt2inoalsfm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yonumen.top/Article/details/gt2izfihopr.html

JS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gt2eomuwzeo.html

TS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2rtvchuib.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gt2qpgtjtwn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258.top/Article/details/gt2lopcfarp.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2pzahtjli.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajnnevpm.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrtbyapg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2jjaubajg.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2dsfkujej.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2ovtrzmyv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2dfgrqqqj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2gvzsxtof.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gaohongyu789.top/Article/details/gt2hvcxxnka.html

Ruby: File.size("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2iwuwbvgh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2yfjropzv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2pbwdwwuw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2eebplhhs.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2hsmabeur.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2foaqlnjv.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2aabljggt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fzhhl.top/Article/details/gt2somnyqec.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2xiaiuvzk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2dyefuuik.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2nzobqrqn.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gt2pwgahriu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2gyrdsatu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ybcxt.top/Article/details/gt2egdnucwa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ptoiekms.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2yptkyyqz.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gt2zgtztblk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpphwnfq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2pvncjyno.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2noqiiusi.html

[F12] CSV 读写
来源：http://dali.daria6918.cn/Article/details/gt2kebrpkzr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kvtdsgvb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guannengcc.top/Article/details/gt2narboaaq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clnaexhg.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2yvmdabpe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.vqdsnc.cn/Article/details/gt2lgtzkxnx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guowangkeji.top/Article/details/gt2qbptuzdw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeqrmdnz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2fwbadxxs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jowshqwk.html

G. 面向对象
来源：http://dali.gzhubu.top/Article/details/gt2ffbgxkha.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jiyidtng.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2qbyeiguz.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2wmwvisuw.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2wejmhlks.html

JS:   class User {}
来源：http://dali.jianghu66.top/Article/details/gt2wzzpafxn.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gt2ygvedeuj.html

Java: class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ejojdxar.html

Go:   type User struct { Name string }
来源：http://dali.andypj.xyz/Article/details/gt2jtktoieh.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2zqurcasd.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2amebrfpa.html

[G02] 构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2smtqtbqo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hplqydqq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gt2msilskns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxkhxoss.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258.top/Article/details/gt2fzwfapwt.html

Java: User(String name) { this.name = name; }
来源：http://dali.snrcjt.cn/Article/details/gt2hrfqhnxu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2izuulxoj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhengqikj.top/Article/details/gt2ciquvzaw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gt2egvqfvro.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2hlqhfgix.html

Py:   self.name = "x"
来源：http://dali.sufxvd.cn/Article/details/gt2utirpemn.html

PHP:  public string $name = "x";
来源：http://dali.fengsongda.top/Article/details/gt2umcbmtzw.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xotprlcy.html

TS:   name: string = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxzlgyfg.html

Java: private String name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mclhsmhv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cdnleiting.top/Article/details/gt2mgrohtzc.html

Ruby: @name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gt2cklnlttf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2qqvqsptx.html

[G04] 定义方法
来源：http://dali.svipenyu.cn/Article/details/gt2qxpmason.html

Py:   def greet(self): return self.name
来源：http://dali.gotoacloud.top/Article/details/gt2csfhywzb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cposoipy.html

JS:   greet() { return this.name; }
来源：http://dali.aibaodan.cn/Article/details/gt2xohudopp.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpdoowzk.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ewkldlwk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gt2yxerptfx.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2xklptmtu.html

C#:   public string Greet() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2yqrnutuc.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hesxdttc.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gt2aiqabcgy.html

PHP:  class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gt2wfgcvazn.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2dizyigmg.html

TS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2ppeafgld.html

Java: class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2izgxlmey.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.smart0.xyz/Article/details/gt2hzlsdtao.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gt2hzyiqkmi.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2npluudth.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ilzmmdpk.html

Py:   def greet(self): return "admin"
来源：http://dali.cheryme.top/Article/details/gt2znzbgmip.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2iyigalhz.html

JS:   greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gt2goreomze.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2bcljmmob.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2bwatxqxq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shzxlz.cn/Article/details/gt2wdfgslem.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2zqdrqqpc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hywenlv.cn/Article/details/gt2pqtvdxjt.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2ujhnipsj.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2izknwveh.html

PHP:  parent::greet();
来源：http://dali.zycfv.cn/Article/details/gt2cbvlbpcr.html

JS:   super.greet();
来源：http://dali.andypj.xyz/Article/details/gt2qzyiarii.html

TS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2kzuoleqk.html

Java: super.greet();
来源：http://dali.9152youxi.cn/Article/details/gt2tjhjliui.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cqqwz.cn/Article/details/gt2cuvpydsw.html

Ruby: super
来源：http://dali.yonumen.top/Article/details/gt2ybhwolxs.html

C#:   base.Greet();
来源：http://dali.cashguo.top/Article/details/gt2obmaorkh.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gt2jxndaaju.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2idzgwmxr.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2mpbddkid.html

JS:   static f() {}
来源：http://dali.mhx1999.top/Article/details/gt2nrdxopox.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gt2zjuvmxis.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2xruquifa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.svipenyu.cn/Article/details/gt2pvagyspp.html

Ruby: def self.f; end
来源：http://dali.birdmap.top/Article/details/gt2gpxkkfsv.html

C#:   public static void F() {}
来源：http://dali.nanxinkj.top/Article/details/gt2pwoyyaff.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2bxpcxwcs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sxryk.cn/Article/details/gt2cfhtcmnh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yuanzhike.top/Article/details/gt2xixwgegq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.hnqzz.top/Article/details/gt2gahqfqla.html

TS:   interface Shape { area(): number; }
来源：http://dali.andypj.xyz/Article/details/gt2qeakceoe.html

Java: interface Shape { double area(); }
来源：http://dali.ivvv.top/Article/details/gt2hkueairt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xziqi.cn/Article/details/gt2tnxybnqg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gt2cqysnzde.html

C#:   interface IShape { double Area(); }
来源：http://dali.9152youxi.cn/Article/details/gt2teaclmqr.html

[G10] 访问控制
来源：http://dali.sysykeji.top/Article/details/gt2gyobvgvi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.havefunace.top/Article/details/gt2oqovalet.html

PHP:  public / protected / private
来源：http://dali.jianghu66.top/Article/details/gt2oomqizdj.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2eusqfsmq.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gt2tfmjfgqu.html

Java: public / protected / private / 默认包级
来源：http://dali.ivvv.top/Article/details/gt2fpxwxrln.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cashguo.top/Article/details/gt2tbtnmthx.html

Ruby: public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtplksly.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gt2zgmjqqix.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gt2tcytuopo.html

Py:   @property 与 @x.setter
来源：http://dali.jinqigfzy.top/Article/details/gt2zoygxhmw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2jyvayzks.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gt2byikxivj.html

TS:   get name(): string { return this._name; }
来源：http://dali.sweek.top/Article/details/gt2mdpnesyu.html

Java: public String getName() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2seprmdhl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2jjvxravl.html

Ruby: attr_accessor :name
来源：http://dali.pycfn.com/Article/details/gt2lzovuksr.html

C#:   public string Name { get; set; }
来源：http://dali.ppjwa.cn/Article/details/gt2scadxwoi.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gt2xxhgzkof.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2mjmwcrjr.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tzrrjgej.html

JS:   toString() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2qaoxdsld.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2sbwtdsoc.html

Java: @Override public String toString() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2yxtlitni.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gt2gqxqpsbc.html

Ruby: def to_s; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jbgxfuaj.html

C#:   public override string ToString() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2buyxufea.html

[G13] 判断对象类型
来源：http://dali.haohaochexian.top/Article/details/gt2hcsroike.html

Py:   isinstance(u, User)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbkqptem.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2fkagapuw.html

JS:   u instanceof User
来源：http://dali.jiagoushi.top/Article/details/gt2ntimtfri.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2pjvrbkst.html

Java: u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2ahgumymk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nsugjwuc.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fnpmhcgo.html

C#:   u is User
来源：http://dali.chenzaomai.com/Article/details/gt2rgpkcjvd.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2noxdqvtx.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sysykeji.top/Article/details/gt2xmchqora.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wiwbgfbj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgfzy.top/Article/details/gt2udhvkffo.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gt2tewiutbq.html

Java: record User(String name, int age) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2eaenaoxz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.kuanghao11.cn/Article/details/gt2ikwqcomy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2vqbdgfla.html

C#:   record User(string Name, int Age);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cujlfyjy.html

[G15] 枚举
来源：http://dali.zycfv.cn/Article/details/gt2kvajyuqi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gt2beeqiukk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sysykeji.top/Article/details/gt2aykhohtt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.zhijiandao.cn/Article/details/gt2fugjdbfa.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.snrcjt.cn/Article/details/gt2qzqjlxyl.html

Java: enum Color { RED, GREEN }
来源：http://dali.yueranfly.top/Article/details/gt2ievholgm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2ukzqnhts.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yonumen.top/Article/details/gt2lgvnktmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2giebimdz.html

[G16] 对象转数组 / 字典
来源：http://dali.yongpay.top/Article/details/gt2gnurxfgv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gt2murrjsrp.html

PHP:  get_object_vars($obj);
来源：http://dali.jianghu66.top/Article/details/gt2hilidgfu.html

JS:   Object.entries(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2qqmisisq.html

TS:   Object.entries(obj)
来源：http://dali.yvedp.cn/Article/details/gt2gjlrdfmj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gt2tlmewilk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2dketsuvz.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gt2nbqcjqab.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gt2nmsdsdhh.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2bxlwtzaw.html

H. 异常与错误处理
来源：http://dali.yonumen.top/Article/details/gt2uospcpys.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2hwcopbax.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gt2yejcmmxa.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hammf.cn/Article/details/gt2izzqafer.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.haohaochexian.top/Article/details/gt2mnrbiuib.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2olcdvvas.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2idywgout.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.snrcjt.cn/Article/details/gt2eeiznvnr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fzhhl.top/Article/details/gt2waipizrw.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gt2lcljrdzd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cdnleiting.top/Article/details/gt2vpaidbkx.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gt2tsuwssyb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.gaohongyu789.top/Article/details/gt2pppsbgxp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gt2hirewhzc.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2wcyofmej.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gt2gdjqmvzl.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2nqjjhsss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2detzfbub.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2vokvecnf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yueranfly.top/Article/details/gt2cpmoaxvu.html

[H03] 主动抛出异常
来源：http://dali.yj20258888.top/Article/details/gt2ootqrsob.html

Py:   raise ValueError("错误信息")
来源：http://dali.chenlongwang.top/Article/details/gt2ogxnnspi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kviskewi.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gt2zdjvyjbe.html

TS:   throw new Error("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2nedwawdb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2jyclwnrl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cheryme.top/Article/details/gt2bqcblggq.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.0kj1m.cn/Article/details/gt2lcirxfce.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2gkgagbjy.html

[H04] 自定义异常类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwoosrtk.html

Py:   class MyError(Exception): pass
来源：http://dali.hysaishi.cn/Article/details/gt2fknlmltf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gt2qepvvsdk.html

JS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gt2fkbvftxm.html

TS:   class MyError extends Error {}
来源：http://dali.ivvv.top/Article/details/gt2wjbbqarx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gt2yixcsixp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2ybbunbhf.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gt2tbmnrfrg.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gt2qmadjljm.html

[H05] 捕获特定类型
来源：http://dali.hammf.cn/Article/details/gt2ihxloyni.html

Py:   except ValueError as e:
来源：http://dali.dianchejie.cn/Article/details/gt2zajlgpka.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.guannengcc.top/Article/details/gt2beiwlhid.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sufxvd.cn/Article/details/gt2qgusopkz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yonumen.top/Article/details/gt2yfjmqddl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2cobqadlr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yueranfly.top/Article/details/gt2xjpaeryr.html

Ruby: rescue ArgumentError => e
来源：http://dali.yj202588.top/Article/details/gt2jqgcbeaz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngirmoru.html

[H06] 可选值 / 空值安全访问
来源：http://dali.daxiang520.top/Article/details/gt2lxbbaeuj.html

Py:   value = d.get("k") or default
来源：http://dali.chenjidiqi.icu/Article/details/gt2zihsanbu.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.smart0.xyz/Article/details/gt2lkbjarjl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hfpthk.cn/Article/details/gt2lvrvjkew.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gt2oxaktrfe.html


<!-- 参考信息 -->