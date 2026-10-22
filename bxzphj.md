代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sufxvd.cn/Article/details/gt2chmhmjpj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nzoqrvzn.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gt2aaopubiv.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2qgicrjwy.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2avdhdkqm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gt2rjfbpwzw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2hguhhryh.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cashguo.top/Article/details/gt2fgpqkeem.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2tnmgcenl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2svxbqais.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gt2fyderrsi.html

Ruby: File.read("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jqqevsok.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2vyinmxel.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2ovwzorva.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gt2htkwgzpo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gt2mjryaqtu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.mhx1999.top/Article/details/gt2fitvcdrs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2nvuslsgj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gt2dhdnvgnv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2xobohuou.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgnppnaf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sufxvd.cn/Article/details/gt2uyljqezb.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2gohinhxj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2osquudgx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gt2zmrglqcr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2sbfwruxc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2rspfroyf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2jmxkvxbn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2zngzmqpj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2cvaudins.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2elxypfsh.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2qjibowos.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gt2xsptmfec.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigufen.top/Article/details/gt2ayhffppq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2yyryfywl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnpktfob.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gt2qvwahkmg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2phtrlmfj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.dianchejie.cn/Article/details/gt2uhdaufeh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.pycfn.com/Article/details/gt2hiltwqrg.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2gcxwbvsw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2wfthzgnv.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2olgkenpc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2hpysjhmj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2zdvngfkf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2atnvdgyy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.snrcjt.cn/Article/details/gt2ruwizdeu.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkqvhxln.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2bisfpfpc.html

[F06] 删除文件
来源：http://dali.zhengqikj.top/Article/details/gt2mewasuwn.html

Py:   os.remove("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2fnyoxzwq.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuctphkt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2fcksgkbp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2sqbiicap.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2fzgxilxw.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtstkame.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2zdshwfxn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2snjclbio.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gt2umymuweh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shzxlz.cn/Article/details/gt2grwcrrcs.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2pevmoqqg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2hxythepx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2jkbrxbvw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fengsongda.top/Article/details/gt2rzbhoaab.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rghiaqlv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2ebdpprom.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2wxtzhqxp.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2qcxpozev.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jianghu66.top/Article/details/gt2djeopwdu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2odgudeal.html

JS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2szxstqjs.html

TS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2hexccifk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gt2mwxcbdgu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2pukwxpya.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gt2svpmudll.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2vqmqdzfb.html

[F09] 获取文件大小
来源：http://dali.cheryme.top/Article/details/gt2hudaryru.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2kbjnkgoi.html

PHP:  filesize("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2sjhfeqfu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2uqzbaxxr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenlongwang.top/Article/details/gt2ewdhyufu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sufxvd.cn/Article/details/gt2piemtvfo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuetiantiany.cn/Article/details/gt2bxtdbapm.html

Ruby: File.size("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2tsudgccg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghxzcods.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2rnusvjts.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2sdizjrbn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2kuvvhuhb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2hdbouztz.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mcjucwaw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2evqgvvnd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2qtydgvls.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2zyehrdwl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rcdsdfut.html

[F11] 复制与移动文件
来源：http://dali.xylfe.cn/Article/details/gt2byyrgvsw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2rsatuvgu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2smjfbabf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2mucxxhzy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2sdfxgdca.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhongyouzk.top/Article/details/gt2jgvpppso.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxinkj.top/Article/details/gt2xxnigftl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2oqdwvuxm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eonqesvc.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2pwnrkabd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2tcfrglwm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2ltvxbpis.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2wigvzeic.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2hjrahibv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ppjwa.cn/Article/details/gt2ihrejdzc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hfpthk.cn/Article/details/gt2zcciulpj.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.wangdashe.top/Article/details/gt2xrxdlgzg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gzhubu.top/Article/details/gt2eawrbiku.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2dngezzse.html

G. 面向对象
来源：http://dali.smart0.xyz/Article/details/gt2deganvtt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ognzfiqq.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2ggzasoiv.html

Py:   class User: pass
来源：http://dali.xuanzx.com/Article/details/gt2nfobgqmk.html

PHP:  class User {}
来源：http://dali.smart0.xyz/Article/details/gt2fblpvrjq.html

JS:   class User {}
来源：http://dali.yuanzhike.top/Article/details/gt2wrpithza.html

TS:   class User { name: string = ""; }
来源：http://dali.gzhubu.top/Article/details/gt2fgxtdsca.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2cozgromh.html

Go:   type User struct { Name string }
来源：http://dali.dianchejie.cn/Article/details/gt2zzevcibk.html

Ruby: class User; end
来源：http://dali.yonumen.top/Article/details/gt2zexsaocy.html

C#:   class User {}
来源：http://dali.birdmap.top/Article/details/gt2qcsxcwth.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2pfposzly.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gt2dwrgwsae.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2trhsbtwu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gt2mfcnletd.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2ctzalmrr.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ogtbtgyr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aizwys.cn/Article/details/gt2tinziejn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2tylcvesw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2wofcpenu.html

[G03] 实例属性
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmvhblog.html

Py:   self.name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2zunpkokj.html

PHP:  public string $name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xrhdjedy.html

JS:   this.name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2gekdrvyz.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2rdduodhw.html

Java: private String name;
来源：http://dali.guowangkeji.top/Article/details/gt2lvcknalp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2uyzmptgg.html

Ruby: @name = "x"
来源：http://dali.iojbl.cn/Article/details/gt2byofjwcr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2eqfeifvn.html

[G04] 定义方法
来源：http://dali.xinyue.icu/Article/details/gt2qxwzxpkj.html

Py:   def greet(self): return self.name
来源：http://dali.daxiang520.top/Article/details/gt2yywebfyi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2dfdyqnji.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2pjgdtwxj.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2umqcqmbd.html

Java: String greet() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xppvagwi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2dtbhzbsw.html

Ruby: def greet; @name; end
来源：http://dali.316326.xyz/Article/details/gt2hfvtsfks.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2buuyjxsq.html

[G05] 继承
来源：http://dali.pengpengdd.cyou/Article/details/gt2trugzkjw.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2qtcxcimo.html

PHP:  class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2dwxopydb.html

JS:   class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gt2xsualdmm.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2gbissfvv.html

Java: class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hqzevoqp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yonumen.top/Article/details/gt2bfdrveca.html

Ruby: class Admin < User; end
来源：http://dali.hnxiangtu.top/Article/details/gt2efhbxlks.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2kmwzyvxx.html

[G06] 重写方法
来源：http://dali.gotoacloud.top/Article/details/gt2ketrczcy.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gt2acoblnnc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2ccueqjzd.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2skcenmbd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2qcyxfcfe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2bzixzspc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gt2yscfvbil.html

Ruby: def greet; "admin"; end
来源：http://dali.ehwqpu.com/Article/details/gt2xzpkkynz.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gt2krmdkpgd.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gt2irepoipu.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gt2ewmbhcwp.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2zqumzlai.html

JS:   super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2ujlxxaac.html

TS:   super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2ljjwjnim.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2magdlvfg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2bgouhroe.html

Ruby: super
来源：http://dali.cqqwz.cn/Article/details/gt2igkjyhlc.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2gmntbjnk.html

[G08] 静态方法与属性
来源：http://dali.cashguo.top/Article/details/gt2trriekob.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pycfn.com/Article/details/gt2qfcjrpcp.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gt2mpxwgwle.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2cnyuybzd.html

TS:   static f(): void {}
来源：http://dali.sufxvd.cn/Article/details/gt2tvlpisqr.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2utpqzkpy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.c1oappe.top/Article/details/gt2zsxswrrm.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gt2vjoiqbqb.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2obknwgtd.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2eepndnbt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wobtjdlj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2kalhaghw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dddkthrc.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gt2izgphlji.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2oxwkawxl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2fjnasgqo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnxiangtu.top/Article/details/gt2wddhznhw.html

C#:   interface IShape { double Area(); }
来源：http://dali.fengsongda.top/Article/details/gt2ngqeodze.html

[G10] 访问控制
来源：http://dali.cqqwz.cn/Article/details/gt2otithzbc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jiagoushi.top/Article/details/gt2guilbiyw.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2fnegvgor.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2scqpbmdm.html

TS:   public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gt2xmmivmjn.html

Java: public / protected / private / 默认包级
来源：http://dali.zhijiandao.cn/Article/details/gt2hyksbdiw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hfpthk.cn/Article/details/gt2yvypkelu.html

Ruby: public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2osuvzvvt.html

C#:   public / protected / private / internal
来源：http://dali.dianchejie.cn/Article/details/gt2lziodtry.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2akduogpg.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gt2fhqlhbgw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gt2udywezql.html

JS:   get name() { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apnuwxny.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2hrhxytsc.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2masgmqok.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzzrjrup.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gt2ptmsfhwb.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2prexrpbh.html

[G12] 对象转字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2sejpkjdi.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gt2agediyku.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2vshwband.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jeljfzqi.html

TS:   toString(): string { return this.name; }
来源：http://dali.guowangkeji.top/Article/details/gt2zuvylpqd.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2gpzrtleh.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gt2qcgswanj.html

Ruby: def to_s; @name; end
来源：http://dali.zycfv.cn/Article/details/gt2adncltka.html

C#:   public override string ToString() => Name;
来源：http://dali.cashguo.top/Article/details/gt2diigdvtn.html

[G13] 判断对象类型
来源：http://dali.xziqi.cn/Article/details/gt2ayaugsuk.html

Py:   isinstance(u, User)
来源：http://dali.redwolf501.top/Article/details/gt2xgkzbxgc.html

PHP:  $u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2khzwtcws.html

JS:   u instanceof User
来源：http://dali.sufxvd.cn/Article/details/gt2kywhwdrr.html

TS:   u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2kmzstvrg.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjwsqpuw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2miyhwifs.html

Ruby: u.is_a?(User)
来源：http://dali.zhongyouzk.top/Article/details/gt2hgqvhqjj.html

C#:   u is User
来源：http://dali.jyoumei.cn/Article/details/gt2qyygxuit.html

[G14] 数据类 / record
来源：http://dali.tianlin.xyz/Article/details/gt2tspciqtp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zycfv.cn/Article/details/gt2ntjogccs.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gt2yzparjzx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xylfe.cn/Article/details/gt2jfacuvph.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigufen.top/Article/details/gt2vroqckpp.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2bhrhvxuu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gt2ttpzpuhc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2tosnuxlo.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2adqzjepb.html

[G15] 枚举
来源：http://dali.cdnleiting.top/Article/details/gt2llxvfpof.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2itgsocwp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uinkfrhy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gt2beelzybm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2akpscrtp.html

Java: enum Color { RED, GREEN }
来源：http://dali.aibaodan.cn/Article/details/gt2dszdlfsz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdqvetrh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2akobcxfz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2uebjaimc.html

[G16] 对象转数组 / 字典
来源：http://dali.fengsongda.top/Article/details/gt2bhvcgmus.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hnxiangtu.top/Article/details/gt2mflxposg.html

PHP:  get_object_vars($obj);
来源：http://dali.gotoacloud.top/Article/details/gt2bxcelrcb.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2jhemcjfu.html

TS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2rhxndfyf.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jlsjyb.cn/Article/details/gt2ilmrnelp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.pycfn.com/Article/details/gt2xpynynaq.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2vykzylzl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gogol.net.cn/Article/details/gt2lvylwalt.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2ftehvyox.html

H. 异常与错误处理
来源：http://dali.0kj1m.cn/Article/details/gt2walltyjb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2salsnbpm.html

[H01] try / catch 基础
来源：http://dali.hywenlv.cn/Article/details/gt2gagsxtzt.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.fengsongda.top/Article/details/gt2qqgfoouq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yczsfayh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daria6918.cn/Article/details/gt2dynpneki.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2ejwjhmkf.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.9152youxi.cn/Article/details/gt2fzrjtaoy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2hxsoohef.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.daria6918.cn/Article/details/gt2qijtlbol.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2kkcaxshz.html

[H02] finally / ensure 收尾
来源：http://dali.ybcxt.top/Article/details/gt2whkgjnyj.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jqgufenzy.top/Article/details/gt2oqanuyic.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2epxxqqwg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gt2umegbzon.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fkomndst.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2umfbpinh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gt2pbdglfkr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yuxming.cn/Article/details/gt2uzcgbzbe.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2ygggtbip.html

[H03] 主动抛出异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2npfyavys.html

Py:   raise ValueError("错误信息")
来源：http://dali.jqgfzy.top/Article/details/gt2wtadndsd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pixwlzap.html

JS:   throw new Error("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwbuizjn.html

TS:   throw new Error("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2cknsmjkx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2swqxyldj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.0kj1m.cn/Article/details/gt2zwrqfpui.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vbitoobi.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gt2ofzzcglx.html

[H04] 自定义异常类型
来源：http://dali.yj20258888.top/Article/details/gt2iptvqoij.html

Py:   class MyError(Exception): pass
来源：http://dali.cucudq.cn/Article/details/gt2kusvczbm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gt2ehvijflk.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lpiofgce.html

TS:   class MyError extends Error {}
来源：http://dali.0kj1m.cn/Article/details/gt2wbyiiplg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdlnzqwj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2shzqzpko.html

Ruby: class MyError < StandardError; end
来源：http://dali.jyoumei.cn/Article/details/gt2cgyaldpe.html

C#:   class MyException : Exception {}
来源：http://dali.pycfn.com/Article/details/gt2punzvpva.html

[H05] 捕获特定类型
来源：http://dali.xylfe.cn/Article/details/gt2gmrfhypf.html

Py:   except ValueError as e:
来源：http://dali.birdmap.top/Article/details/gt2bvwgbqpc.html


<!-- 参考信息 -->