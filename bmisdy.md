代发 wailian999

C#:   File.ReadAllText("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtlfbayvkw.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gtjziodslh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cdnleiting.top/Article/details/gtwdgwzojo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtjliytewx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gtnvqrpbxl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gtlzcvgxni.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmwztdlx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shangyingyoupin.top/Article/details/gttrsbgjmt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dashuyun.cn/Article/details/gtntbkaucu.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.andypj.xyz/Article/details/gttrpesxgu.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gtsbwkakyx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtccrkupjk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gtsbafwwyu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtajlhjfxb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtduuttfyk.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gtejeysixl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtcvdajkgq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gtwvjawzcx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtcfkcdmjt.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtqugyiacx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtgtkapfkz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtsvlzcgwj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gtmoejrist.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtorcxobks.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhengqikj.top/Article/details/gtazbsbpfi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtzwsbgvvd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswaxyldo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guannengcc.top/Article/details/gtubpbtift.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtjoqrflaa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtbebbzimw.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gttvxkndoa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtefqfuher.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdebbitwa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtfwskhlfm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gthdiwkzsj.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdxdljrch.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyocjmtum.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtprxwktso.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtetcveipt.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtaqemrcha.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtoxsontwb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkdsvhoob.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtiswyzavj.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gtwcgsaoqg.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtcikbhubp.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtxwkocrrl.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtanszfdnt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtdntsxtky.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gtgspgvsnl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtivcsocrh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyajddeq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gaohongyu789.top/Article/details/gtjhfrpcsa.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtzlfthjcd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdulvxlpj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj202588.top/Article/details/gtqhgskgxy.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtdkvxbrcr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gttgzenjie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gttamoibay.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtpjzbholj.html

TS:   fs.readdirSync("dir")
来源：http://dali.vqdsnc.cn/Article/details/gtmhvavydb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gtvvwpltwv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gtdkeiftat.html

Ruby: Dir.children("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtjzejmtzm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gtxaqnkgxw.html

[F09] 获取文件大小
来源：http://dali.dianchejie.cn/Article/details/gtajggbynh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqpqrkbk.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtfrdpeoyq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nwbrower.top/Article/details/gtrgiyxtpz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gttshinndy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gtedqedcmn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangshuangyany.cn/Article/details/gtbbwjdjdo.html

Ruby: File.size("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfqofkvcl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgufenzy.top/Article/details/gtoycprzkj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.9152youxi.cn/Article/details/gtxpygpnsn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtpbdgbjsq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtkkbpwnkq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtoasukejz.html

TS:   path.extname("a.txt")
来源：http://dali.yj202588.top/Article/details/gtsrpgfjgc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gtlmklklxb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtjdbsvgbe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsxxckyjw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtxevqijve.html

[F11] 复制与移动文件
来源：http://dali.nanxuanxn.top/Article/details/gtljqlmrtr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gtynzcwqeb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpnamcrej.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtpohurdft.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtfcafcdvy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gtrzigkxqj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gteloqfyly.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttjmlzjri.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtifnxtyla.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gtefxmuenz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtzocgsila.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gtrvveyral.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gtwqpfqlyu.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzylwopgu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.svipenyu.cn/Article/details/gtnekcslka.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsvfdjny.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gttfnebjom.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gtlpabofcx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkhcuaaql.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gtmqlvmjnj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtcvnzxykb.html

[G01] 定义类
来源：http://dali.zhoulong.xyz/Article/details/gtsrsskopa.html

Py:   class User: pass
来源：http://dali.gaohongyu789.top/Article/details/gtjgczatfy.html

PHP:  class User {}
来源：http://dali.zhengqikj.top/Article/details/gtilfifnwp.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtjdpiryhx.html

TS:   class User { name: string = ""; }
来源：http://dali.cashguo.top/Article/details/gtirwcnkdx.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtkiobdeyv.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtfkbtbkor.html

Ruby: class User; end
来源：http://dali.daxiang520.top/Article/details/gtqinxjtvl.html

C#:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpwncjzb.html

[G02] 构造函数
来源：http://dali.316326.xyz/Article/details/gtuaxmdvyg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtorqaxctu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shzxlz.cn/Article/details/gtkljpabhd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gttkztnblb.html

TS:   constructor(public name: string) {}
来源：http://dali.chenzaomai.com/Article/details/gtnkjkuosn.html

Java: User(String name) { this.name = name; }
来源：http://dali.sweek.top/Article/details/gtgcasnvzs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ehwqpu.com/Article/details/gtfthilnry.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gtjqiuhdzx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gtzzygyktz.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gtbuwkycpw.html

Py:   self.name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gtoowirwlo.html

PHP:  public string $name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtiqfvmxev.html

JS:   this.name = "x";
来源：http://dali.hammf.cn/Article/details/gtdhowpjgg.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtfroafytm.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtwjfgyvvc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjclchyp.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtgdshrvsc.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gtkfrrfymb.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtqrplitfc.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtiyeadhst.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gtppqeujes.html

JS:   greet() { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gtgmmbaqqb.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpryhuurp.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gthzeuzclc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.cheryme.top/Article/details/gtanybclwk.html

Ruby: def greet; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gtocupxohd.html

C#:   public string Greet() => Name;
来源：http://dali.ybcxt.top/Article/details/gtqjybpdgd.html

[G05] 继承
来源：http://dali.gzhubu.top/Article/details/gthfakpkzj.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gtpozujibg.html

PHP:  class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gtdylrpohh.html

JS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtzlekdont.html

TS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gttldnuxqo.html

Java: class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtpesqheyx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.0kj1m.cn/Article/details/gtfdkgtguu.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gtqdlbezru.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtneemursc.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gttndnmhvd.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gtdcvqfubl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gtremktcay.html

JS:   greet() { return "admin"; }
来源：http://dali.yongpay.top/Article/details/gtqdjfnfns.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtkjgyjebo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gtjblbkkhk.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenjidiqi.icu/Article/details/gtbzzkwbvx.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gtipptdjya.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtotlzooqc.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gtuojypkjj.html

Py:   super().greet()
来源：http://dali.hnxiangtu.top/Article/details/gtgmxohecu.html

PHP:  parent::greet();
来源：http://dali.yvedp.cn/Article/details/gtnevxqyfd.html

JS:   super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzcjjgiq.html

TS:   super.greet();
来源：http://dali.smart0.xyz/Article/details/gtvwdchtyz.html

Java: super.greet();
来源：http://dali.andypj.xyz/Article/details/gtngucdhkf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gtwnkfguib.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gthniwdlci.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gtsfjorndd.html

[G08] 静态方法与属性
来源：http://dali.shzxlz.cn/Article/details/gtjkxtjkfy.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yueranfly.top/Article/details/gtwpfnxvwi.html

PHP:  public static function f() {}
来源：http://dali.snrcjt.cn/Article/details/gtbmkkptek.html

JS:   static f() {}
来源：http://dali.yj202588.top/Article/details/gtdkzfulxo.html

TS:   static f(): void {}
来源：http://dali.tianlin.xyz/Article/details/gtxdojcofp.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gtolntbcgt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.guannengcc.top/Article/details/gtoagmxjtq.html

Ruby: def self.f; end
来源：http://dali.ppjwa.cn/Article/details/gtgmyoidmt.html

C#:   public static void F() {}
来源：http://dali.haohaochexian.top/Article/details/gtkbzmswwh.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gtrcgfohff.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aibaodan.cn/Article/details/gtfhbkuxpt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnvkkwwan.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtwrosdvxc.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gtezpfrzfs.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtttsbecin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtdjcljfzc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gtwgqtlvpw.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gtqnqfhfgs.html

[G10] 访问控制
来源：http://dali.cashguo.top/Article/details/gtttqwxfuc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yangfankeji.com/Article/details/gtwxxhrzms.html

PHP:  public / protected / private
来源：http://dali.meibo888.top/Article/details/gtdbyookft.html

JS:   #private 字段；其余公开
来源：http://dali.guowangkeji.top/Article/details/gtsdrobbka.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gtrleqavdf.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtjmwiefil.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gaohongyu789.top/Article/details/gtsyydjywd.html

Ruby: public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gtvdgqsoyo.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gtscpuhawe.html

[G11] getter / setter
来源：http://dali.nanxinkj.top/Article/details/gtltqwcifa.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtwawgxbqv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gtwyxlufdj.html

JS:   get name() { return this._name; }
来源：http://dali.nanxinkj.top/Article/details/gtxwzhqnfp.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtsdohuyai.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryixadef.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gtipqenotq.html

Ruby: attr_accessor :name
来源：http://dali.quarkkingdee.top/Article/details/gtgufhirtg.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gtpmpjuuly.html

[G12] 对象转字符串
来源：http://dali.bjfxy.top/Article/details/gtjfwldbrm.html

Py:   def __str__(self): return self.name
来源：http://dali.quarkkingdee.top/Article/details/gtdfjfbjmi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtxgicckhg.html

JS:   toString() { return this.name; }
来源：http://dali.jqgufenzy.top/Article/details/gteggxarmh.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gtdyadhyvh.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtxstedwwf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gtbtkhiowq.html

Ruby: def to_s; @name; end
来源：http://dali.0kj1m.cn/Article/details/gttgvmgbrl.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtlfmkvglh.html

[G13] 判断对象类型
来源：http://dali.yonumen.top/Article/details/gtmqvboqdr.html

Py:   isinstance(u, User)
来源：http://dali.zycfv.cn/Article/details/gtdocktgfh.html

PHP:  $u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gtprfcuret.html

JS:   u instanceof User
来源：http://dali.xuetiantiany.cn/Article/details/gtjcdoyjwx.html

TS:   u instanceof User
来源：http://dali.yvedp.cn/Article/details/gtuxnzpouc.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtjxcxvjvz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtrnekotfn.html

Ruby: u.is_a?(User)
来源：http://dali.aizwys.cn/Article/details/gtbffludsm.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gtojizwfib.html

[G14] 数据类 / record
来源：http://dali.zhijiandao.cn/Article/details/gtaevsmtwk.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jlsjyb.cn/Article/details/gtdjaswlwg.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gtxlosckmk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtgpdyuazc.html

TS:   type User = { name: string; age: number };
来源：http://dali.c1oappe.top/Article/details/gtstgpntax.html

Java: record User(String name, int age) {}
来源：http://dali.0kj1m.cn/Article/details/gttiernuuu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ehwqpu.com/Article/details/gtnksccjyq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.pycfn.com/Article/details/gtbcqvjdau.html

C#:   record User(string Name, int Age);
来源：http://dali.mhx1999.top/Article/details/gtdgeeckpd.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gtkclbcfwe.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.yanxiufei.cn/Article/details/gtucjiqhcz.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpixjqwxv.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shuidangran.top/Article/details/gtanufqjgt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtsglzcncg.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtsrfuovks.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gtkmtvdoxq.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtxxvzjrbq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hfpthk.cn/Article/details/gtfcxgepli.html

[G16] 对象转数组 / 字典
来源：http://dali.xylfe.cn/Article/details/gtzawkxlcw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.dianchejie.cn/Article/details/gttsttmeer.html

PHP:  get_object_vars($obj);
来源：http://dali.chenzaomai.com/Article/details/gtxyjqzjac.html

JS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gthwplzvdh.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gteyjjpgsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gtrmaqiqbi.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gtsmihxlih.html

Ruby: obj.instance_variables
来源：http://dali.daria6918.cn/Article/details/gtfwmgaxrk.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.daria6918.cn/Article/details/gtzclmsjpw.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtprjdassv.html

H. 异常与错误处理
来源：http://dali.xuanzx.com/Article/details/gtneefvuum.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtyvuruznz.html

[H01] try / catch 基础
来源：http://dali.gzhubu.top/Article/details/gtxicxdncw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cucudq.cn/Article/details/gtusyakaps.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.gogol.net.cn/Article/details/gtsinsmlyw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gtaekjhdbq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yuxming.cn/Article/details/gtizsjgvam.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwctpbtvf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtwujndbnh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjtxddhh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.tanke756.top/Article/details/gtobtsqntw.html

[H02] finally / ensure 收尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtchkkadgq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gtwxrpulam.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gtbtabffgq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtagusctrg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtjhycrjct.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gttmiabyha.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gtabkbqpyt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.bjfxy.top/Article/details/gtexbtdolt.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzhnaofyx.html

[H03] 主动抛出异常
来源：http://dali.birdmap.top/Article/details/gtdjiftxvr.html

Py:   raise ValueError("错误信息")
来源：http://dali.tanke756.top/Article/details/gthghfnyuv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gtqxgeqvqy.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gtrszcriie.html

TS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtlsenakfb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtojetdpfb.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gtidjzamag.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gthouezadi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtlwtivefu.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtenrqbbxg.html

Py:   class MyError(Exception): pass
来源：http://dali.316326.xyz/Article/details/gthysdaesh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtytwwaoiv.html

JS:   class MyError extends Error {}
来源：http://dali.aizwys.cn/Article/details/gtqjdjwxpe.html

TS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gtdcauvbrx.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hnxiangtu.top/Article/details/gtmviafxrt.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jianghu66.top/Article/details/gtxjebqnxb.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gtdoqtzean.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpxsvhpe.html

[H05] 捕获特定类型
来源：http://dali.gotoacloud.top/Article/details/gtbidresqj.html

Py:   except ValueError as e:
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzpmgzor.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.daria6918.cn/Article/details/gtsxdmbwne.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gttnntlmks.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtnljdqiil.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.svipenyu.cn/Article/details/gtrgdxrizd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtduuxumqy.html

Ruby: rescue ArgumentError => e
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrqbzucb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gtqfywbpzk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.tian-w.cn/Article/details/gtwmogqxsg.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtehtwnopd.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yuxming.cn/Article/details/gtvzzolwxk.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jyoumei.cn/Article/details/gtjszecnat.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gtzhrsehdk.html


<!-- 参考信息 -->