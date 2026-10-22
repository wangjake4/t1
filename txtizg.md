代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2grkzuyld.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zwjszltc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xrnogngr.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2glhqkxsc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gt2bqpwnink.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2fidvljmu.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gt2ifbqnhho.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2hdrtudwh.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bcijlvdf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gt2zogrjxjx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2yndfilum.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qeaffndj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cqqwz.cn/Article/details/gt2dcmapeuu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2jtjsqshj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2mejhriwv.html

Ruby: File.read("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2swyudsaw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2wpqlzsuu.html

[F02] 逐行读取文件
来源：http://dali.nanxuanxn.top/Article/details/gt2certzyjv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2grvdbzfa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2turyegep.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtodtyeq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjhoabxz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aikldisr.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2rpsuukvu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fzhhl.top/Article/details/gt2blrvsovd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2daruezmr.html

[F03] 写入文件（覆盖）
来源：http://dali.yj202588.top/Article/details/gt2ghfoshvr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2dcxayaxe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukbaumrk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2rkxrokbd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2fqltldsr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2riakxyht.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangdashe.top/Article/details/gt2yjtszklt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2khmgyniw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2wjpqoxwa.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2fxklxbgn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2xrwbobba.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2pkqtywiv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpwexbgu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjqbrsnp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gt2jzgkzmyi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnxiangtu.top/Article/details/gt2waumovca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guowangkeji.top/Article/details/gt2bqwwpwth.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xylfe.cn/Article/details/gt2foqovlyb.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2kaysxrqb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tian-w.cn/Article/details/gt2clpaceic.html

PHP:  file_exists("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gt2stulmpkp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2rcukxazh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2papvmmss.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efoxqfai.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jlsjyb.cn/Article/details/gt2nxzvxynp.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2mfchmzdt.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2sfasmzmk.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2dljpghgj.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2awlonkhj.html

PHP:  unlink("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppufvnrs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2dtgtkogh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2jqygqgku.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2jgwokivx.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2xrxoctbh.html

Ruby: File.delete("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2rnccaywa.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2faybwrrg.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2qeglqgmh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gt2dvdwcotx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gt2vnmxyrgz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sufxvd.cn/Article/details/gt2izuvigay.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2cndtrqus.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2soarwcsb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gt2bcpzloco.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sufxvd.cn/Article/details/gt2qrokuurr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2jsegkapz.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gt2nwxhgbvz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gt2sjxcobnw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.bjfxy.top/Article/details/gt2wkcvevov.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2kqebcwgd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jianghu66.top/Article/details/gt2uyvopvse.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2nokoygky.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdarzdbz.html

Ruby: Dir.children("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2vogyoshz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2fscvykhq.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gt2tbotmxtr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ekvuwbty.html

PHP:  filesize("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2cflenefr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2raeqxgpo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2ugsakumo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2ldpisrin.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxuanxn.top/Article/details/gt2srfftvvj.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2lcmgxinv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gt2isifpuqk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2rlzdavon.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2zgqialzu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajvzokck.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qghfggvr.html

TS:   path.extname("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vhqagaeu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gt2rrmpfdua.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2ejsjrhks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2vbopgatw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wjirdtfv.html

[F11] 复制与移动文件
来源：http://dali.jqgfzy.top/Article/details/gt2dqnuovxb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2tzjyuejj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2xwazppfg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2verjyrgv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znsrakxd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vklgezch.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuanzhike.top/Article/details/gt2jxffkgrw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2mszokdhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqlznmsv.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2drayzsox.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gt2rkfirgql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xinyue.icu/Article/details/gt2kgndtbcc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gt2wcnmyssi.html

TS:   // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2jstmkhup.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2qffhlzfw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gt2xpbpjlpq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gt2naffjbhy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cqqwz.cn/Article/details/gt2xwcnmnsk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2arwaujmz.html

G. 面向对象
来源：http://dali.yj202588.top/Article/details/gt2lhsrhvwf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2bjwnqjby.html

[G01] 定义类
来源：http://dali.ehwqpu.com/Article/details/gt2isnkmlwl.html

Py:   class User: pass
来源：http://dali.gzhubu.top/Article/details/gt2rexsuhuu.html

PHP:  class User {}
来源：http://dali.daxiang520.top/Article/details/gt2lmbxawel.html

JS:   class User {}
来源：http://dali.cucudq.cn/Article/details/gt2bpuhwozp.html

TS:   class User { name: string = ""; }
来源：http://dali.316326.xyz/Article/details/gt2fqttrgdv.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2bghmrocj.html

Go:   type User struct { Name string }
来源：http://dali.xinyue.icu/Article/details/gt2roufkeim.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2hutgljhg.html

C#:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2gznhuwwz.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2vhumawcj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxinkj.top/Article/details/gt2jrqsebaf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xmppemtv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2aagwhbry.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaxbsnmv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2mquqotkj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gt2wclnwphh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xkgpsjsv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ethiwjcl.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2jnvomafw.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gt2bgetaxgy.html

PHP:  public string $name = "x";
来源：http://dali.yvedp.cn/Article/details/gt2tnnflutn.html

JS:   this.name = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2isxichew.html

TS:   name: string = "x";
来源：http://dali.yj20258.top/Article/details/gt2ouvlbdew.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2gooouzxx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2bofuhxio.html

Ruby: @name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ekfopuww.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2fbdlcbac.html

[G04] 定义方法
来源：http://dali.yonumen.top/Article/details/gt2uknqmuoo.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2uomcsagv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gotoacloud.top/Article/details/gt2pempfhqd.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2anucqija.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvdhjehk.html

Java: String greet() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2uflgfmqw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.vqdsnc.cn/Article/details/gt2nknbdnqg.html

Ruby: def greet; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2fojpqazh.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2qjhglsrs.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2eudmdjyg.html

Py:   class Admin(User): pass
来源：http://dali.ivvv.top/Article/details/gt2ykmmhgjo.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2bexvvetv.html

JS:   class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2eonlmpin.html

TS:   class Admin extends User {}
来源：http://dali.gogol.net.cn/Article/details/gt2hyocxemp.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jarolxje.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2lvcopbuc.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2vqibkuvt.html

C#:   class Admin : User {}
来源：http://dali.smart0.xyz/Article/details/gt2lqupenix.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2jjhqywvv.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2zrtgtonf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2rbhvmbnf.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2svvflovz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.guowangkeji.top/Article/details/gt2kaeuucla.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2flfdrehl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hysaishi.cn/Article/details/gt2ktaxrfdl.html

Ruby: def greet; "admin"; end
来源：http://dali.ivvv.top/Article/details/gt2prlgeiqh.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gt2koflknqn.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2cxizhwrg.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2uywbqepx.html

PHP:  parent::greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vneqybmv.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2jfzxqcxz.html

TS:   super.greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2djqbhkyv.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2jfyxjaej.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.andypj.xyz/Article/details/gt2rxwnlzry.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gt2njgcdccj.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2ahvpgojo.html

[G08] 静态方法与属性
来源：http://dali.sweek.top/Article/details/gt2ozeodapf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2rrzsvsji.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gt2uhghsrlb.html

JS:   static f() {}
来源：http://dali.meibo888.top/Article/details/gt2dxjewfri.html

TS:   static f(): void {}
来源：http://dali.birdmap.top/Article/details/gt2qbqvmsqv.html

Java: static void f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2iikmduer.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agpbegob.html

Ruby: def self.f; end
来源：http://dali.ehwqpu.com/Article/details/gt2cpecpzdo.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gt2smoozybl.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gt2hecgkdcd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gt2jobrgecs.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ivvv.top/Article/details/gt2njkmfnbn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cqqwz.cn/Article/details/gt2dhyqlwhv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zycfv.cn/Article/details/gt2qokfeftz.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2iaahcxii.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2inxezwxq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.wangdashe.top/Article/details/gt2joitgcyi.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gt2tqguhhbc.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2vemekxrg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2iiocxuui.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2odjdrtvf.html

JS:   #private 字段；其余公开
来源：http://dali.tanke756.top/Article/details/gt2qjaawnwc.html

TS:   public / protected / private
来源：http://dali.xinyue.icu/Article/details/gt2vbwpgsoj.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2onswnswe.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daxiang520.top/Article/details/gt2yglcjnhh.html

Ruby: public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2efzijpyy.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2dpgwvvdq.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2ztxoiqec.html

Py:   @property 与 @x.setter
来源：http://dali.cheryme.top/Article/details/gt2eslvdpnv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jyoumei.cn/Article/details/gt2rwbegxda.html

JS:   get name() { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ihkobwlc.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2jflpkzmy.html

Java: public String getName() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2capytngm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.havefunace.top/Article/details/gt2rpwbueqn.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2vrfschpz.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfezavsp.html

[G12] 对象转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2cnjywcmz.html

Py:   def __str__(self): return self.name
来源：http://dali.aibaodan.cn/Article/details/gt2dzzampxu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sufxvd.cn/Article/details/gt2kvffnxbk.html

JS:   toString() { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2vqjmmnmj.html

TS:   toString(): string { return this.name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jusmhdtl.html

Java: @Override public String toString() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2pmlpipnb.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2oqafzghv.html

Ruby: def to_s; @name; end
来源：http://dali.316326.xyz/Article/details/gt2twpicgzi.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2nyzuzlyn.html

[G13] 判断对象类型
来源：http://dali.jqgfzy.top/Article/details/gt2xrolwmcd.html

Py:   isinstance(u, User)
来源：http://dali.xuetiantiany.cn/Article/details/gt2olwxrnip.html

PHP:  $u instanceof User
来源：http://dali.sxryk.cn/Article/details/gt2emldeucd.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gt2urrndcmb.html

TS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2comamufr.html

Java: u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2rhxoywyn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2zqahdilz.html

Ruby: u.is_a?(User)
来源：http://dali.nanxinkj.top/Article/details/gt2fqhmpgkl.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2vvvxmqzq.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2vzjrwdfi.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gt2xjsrytzf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hnxiangtu.top/Article/details/gt2padhlzsl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuxming.cn/Article/details/gt2bbiqukia.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj202588.top/Article/details/gt2kxdnttpr.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2noepnvqa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syrsdfkg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.redwolf501.top/Article/details/gt2obqmtpag.html

C#:   record User(string Name, int Age);
来源：http://dali.ydzc1.top/Article/details/gt2ptueaztc.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gt2gijxsdfh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gt2sxfmzfjp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tanke756.top/Article/details/gt2xgauaaaz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nwbrower.top/Article/details/gt2cyucrinq.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2thcjdrqr.html

Java: enum Color { RED, GREEN }
来源：http://dali.fengsongda.top/Article/details/gt2ijzfowch.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.hammf.cn/Article/details/gt2neyijgwu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.pycfn.com/Article/details/gt2fndbpzsv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuanzx.com/Article/details/gt2jxgluizx.html

[G16] 对象转数组 / 字典
来源：http://dali.yonumen.top/Article/details/gt2rewwkdmm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tian-w.cn/Article/details/gt2juqthunt.html

PHP:  get_object_vars($obj);
来源：http://dali.yj202588.top/Article/details/gt2tipnnnnr.html

JS:   Object.entries(obj)
来源：http://dali.cdnleiting.top/Article/details/gt2admillte.html

TS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2oqjlobiu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2ltngptsh.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2qjlwsmqm.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gt2clxmmuuv.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhengqikj.top/Article/details/gt2ujdqtvwy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yngqecwf.html

H. 异常与错误处理
来源：http://dali.fengsongda.top/Article/details/gt2gqpkepuk.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2raqolesa.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2adiqfkcd.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gogol.net.cn/Article/details/gt2lqnllwpq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gt2asopgyqs.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.shuidangran.top/Article/details/gt2jsgrufrr.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2zxvozhxd.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2evtmbfuk.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258.top/Article/details/gt2jjvivsvr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nwbrower.top/Article/details/gt2hjgaowxh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.nwbrower.top/Article/details/gt2xflmktrz.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gt2ktnjxgse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj202588.top/Article/details/gt2wkhysuhc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyzhlmba.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2tuyidwss.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2tslqasml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2qqxtgows.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258888.top/Article/details/gt2ngbkjhvj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.smart0.xyz/Article/details/gt2sxedsvak.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2hmvpmqqi.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gt2ozhgkzhv.html

Py:   raise ValueError("错误信息")
来源：http://dali.hywenlv.cn/Article/details/gt2kjfffpym.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2intgcoya.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2pxnkbsff.html

TS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2uxueogai.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2wlyugtqu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bautpgwu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gotoacloud.top/Article/details/gt2mbqlskca.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnscpqwj.html

[H04] 自定义异常类型
来源：http://dali.andypj.xyz/Article/details/gt2qbbduyeb.html

Py:   class MyError(Exception): pass
来源：http://dali.xinyue.icu/Article/details/gt2dbwtwcoc.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.0kj1m.cn/Article/details/gt2xipgagwj.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2yasdoiyk.html

TS:   class MyError extends Error {}
来源：http://dali.cqqwz.cn/Article/details/gt2yndnjqda.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svrxkwhe.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.yvedp.cn/Article/details/gt2vjdwtafc.html


<!-- 参考信息 -->