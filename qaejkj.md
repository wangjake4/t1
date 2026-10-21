代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gtfluadqdv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtvxesxysy.html

F. 文件与目录
来源：http://dali.jinqigufen.top/Article/details/gtrvlzbahi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgseycikp.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtxzonkwca.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gtexudtlkr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtkbnwvhio.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gzhubu.top/Article/details/gtogdueepx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtolfitkwh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gtsnpfuryn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsebdvauj.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmvtaggva.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtlnhczwiv.html

[F02] 逐行读取文件
来源：http://dali.jyoumei.cn/Article/details/gtnovuaymb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuanzhike.top/Article/details/gtmlydjoig.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gtixhboeeu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gtrojlfnjy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gtlzejayzk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gthsmckzjm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtwgznbkqs.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtvjzctwgt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmwytxdjc.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gtwmovgsdc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhongyouzk.top/Article/details/gtfovhrgby.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gttjlnvqjx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtudikowwq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtcalqwqdz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gtgsvfhlli.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gtsjjiyumz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gtslmguxzb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtozktopap.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtmephjbrl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtszydixug.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.snrcjt.cn/Article/details/gtmlttjzzi.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtnexrkzkw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gtpgjdmqnb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtxbcwbnnq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nwbrower.top/Article/details/gtposhorts.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ybcxt.top/Article/details/gtlslaivie.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxinkj.top/Article/details/gthtuhtnwl.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtgidvhtge.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gttwnftbpe.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gturspxuwb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtpvtkzxpd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gthuskoudi.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtfcevergi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gtdoffgzoc.html

Ruby: File.exist?("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrscrpoqc.html

C#:   File.Exists("a.txt")
来源：http://dali.yj202588.top/Article/details/gtfljlzxne.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtaooxdeqr.html

Py:   os.remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gthdidthdk.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gthmuttrgq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbqmrpaao.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtxgcjuaqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtzqywiphr.html

Go:   os.Remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtjwgduuxj.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtmmupmizr.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtgqhmqhgi.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gtvszxvwys.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gtvshiyjmr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtiqaeobah.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtduwyewwb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtfxkiojrp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtglvvckqh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fengsongda.top/Article/details/gtltiyytlh.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtscwdoqkq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtneybtyop.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gtgqbhoyoj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zycfv.cn/Article/details/gtmaigxqje.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj20258.top/Article/details/gtvwztyeer.html

JS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gtzfsbldzm.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gtckphsxxs.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yuanzhike.top/Article/details/gtiygtvfue.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgijyhdow.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtligcpmid.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gtynipokzc.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gtccgbjjes.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtrgvdbodf.html

PHP:  filesize("a.txt");
来源：http://dali.ybcxt.top/Article/details/gtfopacqnc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtutndxzhw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtylwnsupk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtbvoztdkn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gttvvqrajp.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtppnxnqfq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gtfdskrlro.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ydzc1.top/Article/details/gtkivyjtkw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtgoqgnxtk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.bjfxy.top/Article/details/gthuzeiaxq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsgmfvfxy.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrzlmdmtc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtubiakujy.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtejbgnpic.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgaoleyev.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtakjtqahh.html

[F11] 复制与移动文件
来源：http://dali.havefunace.top/Article/details/gtqhovokau.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwftghkni.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gtjvvbtzwq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtqjbvauvm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtovnudjwk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtuexfjnwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinqigufen.top/Article/details/gtmdjihnbu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtxthqbrqu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guowangkeji.top/Article/details/gtragkxack.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gtfnzqkgdj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gttoiafzvb.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gtfgfyxggv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gtpseevmnm.html

TS:   // 同上
来源：http://dali.hysaishi.cn/Article/details/gttiuhzcql.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.kuanghao11.cn/Article/details/gtnrglgmoi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cashguo.top/Article/details/gtfsvykovc.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.andypj.xyz/Article/details/gtmnndsqqh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.smart0.xyz/Article/details/gthiuvdoun.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuzxvwlr.html

G. 面向对象
来源：http://dali.tian-w.cn/Article/details/gtujxuwanr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqunbdqvz.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtssexuvsu.html

Py:   class User: pass
来源：http://dali.fengsongda.top/Article/details/gtqwdxlkss.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtwvwvpmmf.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gtxcwitybf.html

TS:   class User { name: string = ""; }
来源：http://dali.andypj.xyz/Article/details/gtimncyrqo.html

Java: class User {}
来源：http://dali.zycfv.cn/Article/details/gtpniutbhu.html

Go:   type User struct { Name string }
来源：http://dali.yj202588.top/Article/details/gtiyzqgxid.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtpxjphfwl.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gtuutrbhvc.html

[G02] 构造函数
来源：http://dali.jianghu66.top/Article/details/gtukawawzm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.andypj.xyz/Article/details/gthrvlbvmq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.iojbl.cn/Article/details/gtgdvzmrev.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gttsfdjtgo.html

TS:   constructor(public name: string) {}
来源：http://dali.fzhhl.top/Article/details/gtxbgzjkud.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtljluwnby.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtnycsrymt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtlpnbdgrr.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtupbgisnc.html

[G03] 实例属性
来源：http://dali.chenzaomai.com/Article/details/gtbdwsosse.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gtjvneogvy.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtjklczubd.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gtatcrvwmz.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gtnnqulpiy.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gthabmchrr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gtxqgidpcs.html

Ruby: @name = "x"
来源：http://dali.jinqigfzy.top/Article/details/gtdckdkgya.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gtqznatiqo.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gtflcltwea.html

Py:   def greet(self): return self.name
来源：http://dali.nanxuanxn.top/Article/details/gtgnvrztpp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gtnftihhsh.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdkoaeumm.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gthouqfsdt.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfutulpju.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtwrmzqdls.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtsgrcwerh.html

C#:   public string Greet() => Name;
来源：http://dali.sysykeji.top/Article/details/gtpwacprog.html

[G05] 继承
来源：http://dali.svipenyu.cn/Article/details/gtyeoevhjr.html

Py:   class Admin(User): pass
来源：http://dali.zhoulong.xyz/Article/details/gtqjgoklrx.html

PHP:  class Admin extends User {}
来源：http://dali.dianchejie.cn/Article/details/gturrtonim.html

JS:   class Admin extends User {}
来源：http://dali.zycfv.cn/Article/details/gtfyvtcncm.html

TS:   class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqmjpjfxk.html

Java: class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gtljtqgipw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhongyouzk.top/Article/details/gtlykeiand.html

Ruby: class Admin < User; end
来源：http://dali.hysaishi.cn/Article/details/gtqepgwxvb.html

C#:   class Admin : User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhhthfrm.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtkyqkddho.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gtxvmtstgp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gtqjexwvuf.html

JS:   greet() { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtlvdxnoin.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtknoyotbe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtkokixgwd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtgkkrdxzr.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gtpwfmqzhn.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gtfqqcmrjb.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrgvtmfrx.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gtonvrbfvh.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtpmggnkwr.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gtxgopppvq.html

TS:   super.greet();
来源：http://dali.ydzc1.top/Article/details/gtukufxnlg.html

Java: super.greet();
来源：http://dali.guannengcc.top/Article/details/gtliwfjvna.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hysaishi.cn/Article/details/gtsloftiae.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtccphnyhr.html

C#:   base.Greet();
来源：http://dali.jlsjyb.cn/Article/details/gtgedvdywz.html

[G08] 静态方法与属性
来源：http://dali.ppjwa.cn/Article/details/gtohduchag.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gthuqknyyn.html

PHP:  public static function f() {}
来源：http://dali.cheryme.top/Article/details/gtecdlhyaj.html

JS:   static f() {}
来源：http://dali.cdnleiting.top/Article/details/gtbfefhcaz.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gtqcwoxhpq.html

Java: static void f() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbtkqeze.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtmkkngekh.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtpwxnwuny.html

C#:   public static void F() {}
来源：http://dali.316326.xyz/Article/details/gtlbsketmj.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gtdocrzrjd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtusujswwc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gtvslflmwy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tian-w.cn/Article/details/gtkwheeket.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gtvwylhdod.html

Java: interface Shape { double area(); }
来源：http://dali.redwolf501.top/Article/details/gtfphxlink.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gtqeckykxb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.haohaochexian.top/Article/details/gtpkjdlcxx.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtutbvgege.html

[G10] 访问控制
来源：http://dali.dianchejie.cn/Article/details/gtstpcoznw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtrggarxbj.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gtnulzkegn.html

JS:   #private 字段；其余公开
来源：http://dali.gogol.net.cn/Article/details/gtsszuviqb.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtoqsxzvex.html

Java: public / protected / private / 默认包级
来源：http://dali.gaohongyu789.top/Article/details/gtpgjodzlu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangshuangyany.cn/Article/details/gtnfeohjin.html

Ruby: public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gteanmgzcy.html

C#:   public / protected / private / internal
来源：http://dali.meibo888.top/Article/details/gtunvfpbpj.html

[G11] getter / setter
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnfuinsm.html

Py:   @property 与 @x.setter
来源：http://dali.chenlongwang.top/Article/details/gthashgvkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gtzuqpizmb.html

JS:   get name() { return this._name; }
来源：http://dali.gotoacloud.top/Article/details/gtsjyeqvtf.html

TS:   get name(): string { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gtkszwqrfp.html

Java: public String getName() { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gtsllhslyl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gtjpaducxi.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gtnngpcdmp.html

C#:   public string Name { get; set; }
来源：http://dali.jinqigfzy.top/Article/details/gtwdjgjplm.html

[G12] 对象转字符串
来源：http://dali.jiagoushi.top/Article/details/gtgwrpqlto.html

Py:   def __str__(self): return self.name
来源：http://dali.svipenyu.cn/Article/details/gtpdjieqtd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gtwhohkrit.html

JS:   toString() { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyehkfdlb.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtfxrxspcv.html

Java: @Override public String toString() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtvmkvmzod.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtwtkfopvo.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtslqjksls.html

C#:   public override string ToString() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gthgombwyq.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gtdignaumf.html

Py:   isinstance(u, User)
来源：http://dali.zhoulong.xyz/Article/details/gtyrdharqt.html

PHP:  $u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gtuxlrqklp.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gtpiwvctua.html

TS:   u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtpuyyqlde.html

Java: u instanceof User
来源：http://dali.yonumen.top/Article/details/gtyxwsfsor.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gtnqoycfrk.html

Ruby: u.is_a?(User)
来源：http://dali.cucudq.cn/Article/details/gtlzvdahtb.html

C#:   u is User
来源：http://dali.hywenlv.cn/Article/details/gtptbclavg.html

[G14] 数据类 / record
来源：http://dali.yongpay.top/Article/details/gthghnteda.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zdqjudy.top/Article/details/gtfnydvrkp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gtetmtedvo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.smart0.xyz/Article/details/gtxgfvajbn.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenjidiqi.icu/Article/details/gtdjvttbjd.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gttsahxbcg.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gtdlcsgudn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gtnwwemmkb.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszwzudna.html

[G15] 枚举
来源：http://dali.sxryk.cn/Article/details/gtliwlkvzd.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtghoegmrp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhengqikj.top/Article/details/gttoajhaap.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnukeapf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnzkeovr.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtzpbrdqlo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gttrzonjsk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.andypj.xyz/Article/details/gtpgitywco.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigufen.top/Article/details/gtjkohekyz.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gtzkbbrzey.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gtdwkmrnxi.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtbjcfkvui.html

JS:   Object.entries(obj)
来源：http://dali.chenjidiqi.icu/Article/details/gterzcxmks.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtjzajvodq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.hongshengwenyu.top/Article/details/gtejvfrfde.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guannengcc.top/Article/details/gtiisqdmsz.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gtfjueesfy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.kuanghao11.cn/Article/details/gtsflymkav.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtiredoghk.html

H. 异常与错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtyfkdkeai.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmmodygyn.html

[H01] try / catch 基础
来源：http://dali.havefunace.top/Article/details/gtucgubwkt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtcdknyxqj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hammf.cn/Article/details/gthdfjpukk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtvpwofnjr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.vqdsnc.cn/Article/details/gtwsuekqcv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gogol.net.cn/Article/details/gtvxxipxfk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aibaodan.cn/Article/details/gtzydcnpff.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.dianchejie.cn/Article/details/gtnqiyrjto.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gogol.net.cn/Article/details/gtwrskckwi.html

[H02] finally / ensure 收尾
来源：http://dali.xziqi.cn/Article/details/gtrpkqpyhy.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.daria6918.cn/Article/details/gtbegychez.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gteofzipty.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtyrdxojxu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gtckvimgez.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gtfxeazvpu.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jyoumei.cn/Article/details/gtpufhkaye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohynqdde.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gtpshwakju.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gthaostktx.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gtghcxmadt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sufxvd.cn/Article/details/gtrlqbmufz.html

JS:   throw new Error("错误信息");
来源：http://dali.shuidangran.top/Article/details/gttthciglg.html

TS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagpeqyqa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xuetiantiany.cn/Article/details/gtdwohovqf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtvqhtnsqx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtfnmoeryg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hnqzz.top/Article/details/gtemdnyqeh.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gtdhmsctju.html

Py:   class MyError(Exception): pass
来源：http://dali.tanke756.top/Article/details/gtkygethop.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hywenlv.cn/Article/details/gtjdgqydaf.html

JS:   class MyError extends Error {}
来源：http://dali.jinqigfzy.top/Article/details/gtfyoceovl.html

TS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtymuxwzfp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gtftguetxm.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gtojzucpiw.html

Ruby: class MyError < StandardError; end
来源：http://dali.feifeiyinyue.top/Article/details/gtwrqyaenl.html

C#:   class MyException : Exception {}
来源：http://dali.cheryme.top/Article/details/gtaivqmpbl.html

[H05] 捕获特定类型
来源：http://dali.dianchejie.cn/Article/details/gtgzzzxxgc.html

Py:   except ValueError as e:
来源：http://dali.yvedp.cn/Article/details/gtncniilsz.html


<!-- 参考信息 -->