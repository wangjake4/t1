代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2errrlips.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2ifqunwok.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2sjdpxebq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2yhgesmpp.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2njqavong.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ehaoifoe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfqadfqy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2ydzweray.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2wdjwjmba.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2caqcuihw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gt2ugtbpmcz.html

Ruby: File.read("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xyuwivti.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2hjhjdjrr.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gt2lejqybpy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shzxlz.cn/Article/details/gt2zfcxqadj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysuvbcss.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2vdavavvj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tanke756.top/Article/details/gt2rtlazykv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2bxodhrlv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nwbrower.top/Article/details/gt2pcafeqcp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zdqjudy.top/Article/details/gt2ovlwrvea.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gt2xneyuqou.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2glltpikh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gt2ykjgvyko.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.bjfxy.top/Article/details/gt2fmyuzxet.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2euutuwsq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gt2ooqrjmkd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2yzbumfnn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gt2nlbwfnmx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2yoztafyp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2dtecueak.html

[F04] 追加写入文件
来源：http://dali.guowangkeji.top/Article/details/gt2ffetzidu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2agbgrjtf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2mfclqiyx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2swwvcldb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gt2tirxbqjp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2npqdmvnv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yryccbma.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2tkwhpkmn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gt2ktztzjvc.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2tbimespx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gt2dpaqsgzl.html

PHP:  file_exists("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2bqigcgbw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2kebaaudc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2zcdwugai.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2ohawtodd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dianchejie.cn/Article/details/gt2omozubuq.html

Ruby: File.exist?("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uenvvork.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2zavdbsgz.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2izbxoxqf.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vuiwpqqp.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuskiaaz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2srfwzpql.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qaywwylw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2ushfwjdx.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2uqbcxlxp.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2hwrleats.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2hwbbwzxj.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2pdmnpxnk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gt2boltrrxr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2cltgcgvu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yonumen.top/Article/details/gt2absfbsrd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2cxnujqyx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dianchejie.cn/Article/details/gt2kclbxopw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cuqlpxpv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gt2ptnqlikg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.aizwys.cn/Article/details/gt2pljphraz.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gt2jqfwmxtg.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2bxjgpjhq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangdashe.top/Article/details/gt2uxwchynj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2zfdzjuvb.html

TS:   fs.readdirSync("dir")
来源：http://dali.xylfe.cn/Article/details/gt2gfhuvuzx.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hnxiangtu.top/Article/details/gt2ssqjleyg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ybcxt.top/Article/details/gt2cgxkakxy.html

Ruby: Dir.children("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2aomuhgbz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.iojbl.cn/Article/details/gt2cwlpoizr.html

[F09] 获取文件大小
来源：http://dali.gzhubu.top/Article/details/gt2bgzdwsbj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iqjktpuk.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2ebgtgeur.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2hltefmpo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gt2rghgsrkx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2tyzdjbcl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sxryk.cn/Article/details/gt2sytdnvqo.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ywgtlqss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2ylzzaeyf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj202588.top/Article/details/gt2hyjprulw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2hkfsbulo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xchcclxc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2vhfywzgw.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2urirtnxk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2powfovpq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ohxboczk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2imocobpp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2pjgcfmag.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gt2jlcgdbrl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ivgblags.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2snoktzqu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2qlbrwirf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2txsohqck.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2obrqpdcj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangshuangyany.cn/Article/details/gt2kqjitwwo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ffmfhlrl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nwbrower.top/Article/details/gt2zcygulln.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2acplekdk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yvedp.cn/Article/details/gt2bckiuqwt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dianchejie.cn/Article/details/gt2pwxcfwae.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj202588.top/Article/details/gt2lzleslhv.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2vpbsiqac.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gt2lgjmngjp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2nplpzaiy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojpwxrtc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gt2yhfqpnue.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2tpezlzqt.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gt2eahcbrlo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ncbmtssl.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2qowzggfy.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gt2wjaafgyu.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2yawlifgb.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2bycewemy.html

TS:   class User { name: string = ""; }
来源：http://dali.jlsjyb.cn/Article/details/gt2jaftqqjv.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gt2qsomsqww.html

Go:   type User struct { Name string }
来源：http://dali.ehwqpu.com/Article/details/gt2rkkpqoor.html

Ruby: class User; end
来源：http://dali.redwolf501.top/Article/details/gt2xjzbpvxo.html

C#:   class User {}
来源：http://dali.xylfe.cn/Article/details/gt2elphjbbh.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gt2lvmxndvi.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenzaomai.com/Article/details/gt2ixvhtqte.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fzhhl.top/Article/details/gt2yyzwkwdj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2ejntqvhs.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2rmbtntlf.html

Java: User(String name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2aogvcfts.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.vqdsnc.cn/Article/details/gt2dngmaomh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gzhubu.top/Article/details/gt2pkjaqqsw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hajrycbj.html

[G03] 实例属性
来源：http://dali.tianlin.xyz/Article/details/gt2mezoxsaj.html

Py:   self.name = "x"
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwvnyttb.html

PHP:  public string $name = "x";
来源：http://dali.birdmap.top/Article/details/gt2abgvtdfq.html

JS:   this.name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ztwrmdtx.html

TS:   name: string = "x";
来源：http://dali.hammf.cn/Article/details/gt2cascxkov.html

Java: private String name;
来源：http://dali.cheryme.top/Article/details/gt2vkcoxuqz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhoulong.xyz/Article/details/gt2ihyhijzj.html

Ruby: @name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2jpkoiend.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2xcoxfbju.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2anvctued.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gt2napmnagr.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lxtsqdph.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2dkzfitop.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iryydymq.html

Java: String greet() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hnmpjqul.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2fyayhrqs.html

Ruby: def greet; @name; end
来源：http://dali.yongpay.top/Article/details/gt2daqlmyep.html

C#:   public string Greet() => Name;
来源：http://dali.gaohongyu789.top/Article/details/gt2acahfqsp.html

[G05] 继承
来源：http://dali.pycfn.com/Article/details/gt2uqhyvwnc.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2biggjtzt.html

PHP:  class Admin extends User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uitlrmsy.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2vixrpgok.html

TS:   class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2renobibx.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2amkqqzig.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2nvwhnvot.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2zkcwseyu.html

C#:   class Admin : User {}
来源：http://dali.aibaodan.cn/Article/details/gt2dvajjumn.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2ycftpyoz.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gt2tnpgjexa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2jdyidkgn.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2peurzcws.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2usegkrpc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gt2qunlpfnu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2pxofwrap.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gt2xbhsgvfi.html

C#:   public override string Greet() => "admin";
来源：http://dali.iojbl.cn/Article/details/gt2rpjghyjk.html

[G07] 调用父类方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2zoefbstf.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2qozyrlgu.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gt2obiywnsx.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2vzzykoaj.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfywuham.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfilemzz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gt2tooireht.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2lubecinm.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrwzmfkg.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gt2wkpntclh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cdnleiting.top/Article/details/gt2keattwml.html

PHP:  public static function f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2xedyaqfn.html

JS:   static f() {}
来源：http://dali.chenzaomai.com/Article/details/gt2kbszckhr.html

TS:   static f(): void {}
来源：http://dali.meibo888.top/Article/details/gt2miypsjsm.html

Java: static void f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xcqstbai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.pycfn.com/Article/details/gt2wdfrltqz.html

Ruby: def self.f; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ksnkulpn.html

C#:   public static void F() {}
来源：http://dali.sxryk.cn/Article/details/gt2djgdkfqw.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gt2mclewcju.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gt2dboifqaz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2anguphpe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdihpvka.html

TS:   interface Shape { area(): number; }
来源：http://dali.nanxinkj.top/Article/details/gt2qkgvrjtv.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2blwgutrw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yangfankeji.com/Article/details/gt2ianjpewm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ydzc1.top/Article/details/gt2xwiabtek.html

C#:   interface IShape { double Area(); }
来源：http://dali.xinyue.icu/Article/details/gt2ynkaxlmu.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2lbvraalj.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.c1oappe.top/Article/details/gt2skxqykbc.html

PHP:  public / protected / private
来源：http://dali.xziqi.cn/Article/details/gt2ztqhjqve.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2apjivkie.html

TS:   public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2bvjqhzbc.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2bkerpize.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhijiandao.cn/Article/details/gt2pilktdly.html

Ruby: public / protected / private
来源：http://dali.cucudq.cn/Article/details/gt2adgiuqwd.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gt2fblipzny.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2tgkeebgj.html

Py:   @property 与 @x.setter
来源：http://dali.zdqjudy.top/Article/details/gt2hdvkhidd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2znzbzfcs.html

JS:   get name() { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2xwlqlerb.html

TS:   get name(): string { return this._name; }
来源：http://dali.svipenyu.cn/Article/details/gt2ywksctud.html

Java: public String getName() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2njofxjgg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2wvbgckzh.html

Ruby: attr_accessor :name
来源：http://dali.gogol.net.cn/Article/details/gt2mqnnjehe.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258.top/Article/details/gt2xtraampo.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2uxushkpt.html

Py:   def __str__(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2zkyginen.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2avelixqz.html

JS:   toString() { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2arsewpgp.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gt2ofwaymrc.html

Java: @Override public String toString() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2rhvkpgux.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2monjviwe.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gt2aotdsnyg.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gt2xkcetshu.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2wjedbiyo.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2okaupzcu.html

PHP:  $u instanceof User
来源：http://dali.guowangkeji.top/Article/details/gt2fasrbkcv.html

JS:   u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iaprrsqr.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2undwehps.html

Java: u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2kzrxwicp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ehwqpu.com/Article/details/gt2wbfpghns.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2emuspzjq.html

C#:   u is User
来源：http://dali.shzxlz.cn/Article/details/gt2umeghsvb.html

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gt2rjitxmrg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2slnndetc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2jmodxoxn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hskwgudr.html

TS:   type User = { name: string; age: number };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2foksfcct.html

Java: record User(String name, int age) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsrniokk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.snrcjt.cn/Article/details/gt2ihgvbwfy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrfyeuqr.html

C#:   record User(string Name, int Age);
来源：http://dali.jlsjyb.cn/Article/details/gt2icglipqr.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gt2izsoffea.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sweek.top/Article/details/gt2lmqtreho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.pycfn.com/Article/details/gt2tnikknkr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yonumen.top/Article/details/gt2qxnrqqdj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gt2pjkiloaf.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuxming.cn/Article/details/gt2jfofouig.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenzaomai.com/Article/details/gt2xroxrlqd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2sfpqasnf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2botbioni.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2iszqvxyd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ehwqpu.com/Article/details/gt2mnemunva.html

PHP:  get_object_vars($obj);
来源：http://dali.jinqigufen.top/Article/details/gt2czygefby.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2fvkstgjg.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2jksnoilo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gt2wtciuqyp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gt2vtaaiyod.html

Ruby: obj.instance_variables
来源：http://dali.xinyue.icu/Article/details/gt2geyrnsyu.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.9152youxi.cn/Article/details/gt2bgerjwlc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2jcrporkt.html

H. 异常与错误处理
来源：http://dali.fzhhl.top/Article/details/gt2intwgdly.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2hhgemupd.html

[H01] try / catch 基础
来源：http://dali.yuanzhike.top/Article/details/gt2zijhuqny.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2bvabjudb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2wwmqzjmo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.dashuyun.cn/Article/details/gt2ojiwughy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2wmppjzmb.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gt2kjsuqwuv.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zycfv.cn/Article/details/gt2kfmcvkuq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.chenzaomai.com/Article/details/gt2donzrmqs.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2xiiwhddb.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gt2cyekiehh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.0kj1m.cn/Article/details/gt2wipwznwu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2tphpxdzn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2bgyqoake.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2hkbazkbj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.havefunace.top/Article/details/gt2rkboqiyj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2ngasqtbk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eamypuep.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2llzpofrv.html

[H03] 主动抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2qvyditod.html

Py:   raise ValueError("错误信息")
来源：http://dali.xinyue.icu/Article/details/gt2rlyfuihn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2iflhspkb.html

JS:   throw new Error("错误信息");
来源：http://dali.jinqigfzy.top/Article/details/gt2kpnwwupz.html

TS:   throw new Error("错误信息");
来源：http://dali.nanxinkj.top/Article/details/gt2pvpnefxr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2afnpbqyl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2ulmgmekp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gt2kchnqxnx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daria6918.cn/Article/details/gt2qnmiywqa.html

[H04] 自定义异常类型
来源：http://dali.tanke756.top/Article/details/gt2iofolqum.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2jiknaylw.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hmnlglys.html

JS:   class MyError extends Error {}
来源：http://dali.yj202588.top/Article/details/gt2eufuxraz.html

TS:   class MyError extends Error {}
来源：http://dali.mhx1999.top/Article/details/gt2wyvpzghp.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jqgufenzy.top/Article/details/gt2vdfqdznj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2zqsctqlk.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gt2rpgbikvw.html

C#:   class MyException : Exception {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2sryjcjrf.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2pieslopa.html

Py:   except ValueError as e:
来源：http://dali.cucudq.cn/Article/details/gt2jxmsumzt.html


<!-- 参考信息 -->