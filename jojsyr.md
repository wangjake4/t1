代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.fengsongda.top/Article/details/gt2ymckoqzs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eavpmeqh.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2znzpfqxf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2rmnwndjn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2trnunxch.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gt2lrtshgfy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2woaoplmv.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2xrolouuy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2basirbxm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhawdjwd.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gt2ciguqgtm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2ihzurgmv.html

[F01] 读取整个文件
来源：http://dali.mhx1999.top/Article/details/gt2oziwolfx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hongshengwenyu.top/Article/details/gt2skwivtrz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2ldpyewkn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hongshengwenyu.top/Article/details/gt2lpzffzyc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xtdojzoi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2zqrnvayg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gt2shfdvgnt.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qhgvvdft.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2cxhrotrf.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2zrenrbwc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2txjaseka.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hnxiangtu.top/Article/details/gt2cmrsbtiu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lembticp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gt2mubaeprb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gt2uypivtea.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.quarkkingdee.top/Article/details/gt2xdarfpfj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hysaishi.cn/Article/details/gt2jtghkenf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmtmguwj.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2nuhgvvcq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2uamfsipx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ofszutni.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuanzhike.top/Article/details/gt2sxdxaaid.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2xjqzrmdw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gt2owaoqdyz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2puomhivk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2ydpqxgng.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2ocrlehwl.html

[F04] 追加写入文件
来源：http://dali.birdmap.top/Article/details/gt2kubwpnps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2fnvfglzw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2todsktim.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2tfhmqfms.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvpbguxu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.birdmap.top/Article/details/gt2cilsfdvz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2lacwubuz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elyapopq.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2vgmibgvn.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gt2apwjjsch.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.c1oappe.top/Article/details/gt2kybkfpjn.html

PHP:  file_exists("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2gdhljarh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2leczhiya.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xezsxedq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gt2rvakeeki.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ohggpoue.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2nvpmkjcg.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2gppdhocu.html

[F06] 删除文件
来源：http://dali.sysykeji.top/Article/details/gt2jhladmjp.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xfarilqj.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2fucewnvg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2hyzgfuen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2mkxkgcjr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2mvczdohl.html

Go:   os.Remove("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fuxtansk.html

Ruby: File.delete("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pctgydnv.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2cymcnblx.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2kfhtoeov.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2egmwewba.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shzxlz.cn/Article/details/gt2rpdjmqsp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2kodhbzlw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2rkbgphxo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2aapngbur.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tianlin.xyz/Article/details/gt2djgylvqx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2afknasnb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.dianchejie.cn/Article/details/gt2jckjcuhv.html

[F08] 遍历目录
来源：http://dali.jinqigufen.top/Article/details/gt2ouhibboo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gt2igdmbtnx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2glmsecoe.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2vtrjrrkg.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2gdjmdppe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2qsrgiixw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daria6918.cn/Article/details/gt2zcntyrkm.html

Ruby: Dir.children("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wpoohszr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpytepsf.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2ixjkzspn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2edyaijkr.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2wpdauega.html

JS:   fs.statSync("a.txt").size
来源：http://dali.andypj.xyz/Article/details/gt2zjuumjrq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yesifjeo.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2gpngzvao.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xuanzx.com/Article/details/gt2pwamsfna.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2cdligefk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2erosrzbm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gt2radoafje.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2yafkcpaz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2kvmigkim.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2gygfztvu.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2yyzraqml.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.aibaodan.cn/Article/details/gt2ivfukwwm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qbqqniwf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oazcssia.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2mngeleje.html

[F11] 复制与移动文件
来源：http://dali.pycfn.com/Article/details/gt2mvkdyntl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2yolgxfxc.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ytzqrfzi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gt2fqhwlmpk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2wcnznadw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.snrcjt.cn/Article/details/gt2lpllfrqv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gt2layqhgcw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2wovzlyvr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.svipenyu.cn/Article/details/gt2hrrxjvaj.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gt2pwjshlhx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj20258.top/Article/details/gt2jkqvoyai.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.dashuyun.cn/Article/details/gt2cpmdjgbe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gt2pjihzrxm.html

TS:   // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2zyftdjpu.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hysaishi.cn/Article/details/gt2vvhvsjjh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gt2enjvlchp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.bjfxy.top/Article/details/gt2uwstuwba.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2fwyqevdt.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2tatxcmrh.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gt2zedewojt.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2xvvpvgnr.html

[G01] 定义类
来源：http://dali.chenjidiqi.icu/Article/details/gt2ngoywunk.html

Py:   class User: pass
来源：http://dali.andypj.xyz/Article/details/gt2jvtoreko.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gkbnledn.html

JS:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2scocmlsi.html

TS:   class User { name: string = ""; }
来源：http://dali.guannengcc.top/Article/details/gt2kkmttvru.html

Java: class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvdntcie.html

Go:   type User struct { Name string }
来源：http://dali.hysaishi.cn/Article/details/gt2wesdvqym.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gt2okfasxga.html

C#:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2qgdyqgym.html

[G02] 构造函数
来源：http://dali.cashguo.top/Article/details/gt2tkzscytm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yangfankeji.com/Article/details/gt2eftqclcj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2apgfxpjy.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hjblcuoh.html

TS:   constructor(public name: string) {}
来源：http://dali.guowangkeji.top/Article/details/gt2oxcogmzz.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2vxgqsslp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xuduziag.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ufhmmkkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2etdftpag.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gt2shjpdeat.html

Py:   self.name = "x"
来源：http://dali.yvedp.cn/Article/details/gt2psszjatm.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2vffaktoe.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2iqenogia.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2hajjkjct.html

Java: private String name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2euyarsfb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnqzz.top/Article/details/gt2sqvorqeu.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gt2zmhmeeol.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2gmavgvba.html

[G04] 定义方法
来源：http://dali.wangdashe.top/Article/details/gt2yaczjaqs.html

Py:   def greet(self): return self.name
来源：http://dali.birdmap.top/Article/details/gt2zoxpfzan.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2ktagoupw.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tmjhjnxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2zajwdhtu.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2mstsbivv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2icggteol.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ykodwady.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2igtydjik.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gt2noqwhwci.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2fxivjmyu.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2ddfpuunc.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2wvolcxpc.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2tmxrhmxw.html

Java: class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2ndvtdrat.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2phswituz.html

Ruby: class Admin < User; end
来源：http://dali.yuanzhike.top/Article/details/gt2myovlisp.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2xpgyelvm.html

[G06] 重写方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnfomxnb.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2oisxyjsv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2wwwlvfrv.html

JS:   greet() { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2jyergvwz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujlkjcrv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qyzauzbl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2mkygwxjl.html

Ruby: def greet; "admin"; end
来源：http://dali.dianchejie.cn/Article/details/gt2ccvhpudz.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2ctnrprnl.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2ukexgaob.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2sfbhcknf.html

PHP:  parent::greet();
来源：http://dali.birdmap.top/Article/details/gt2vuywugnr.html

JS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2cjfvcyyk.html

TS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mabclhjm.html

Java: super.greet();
来源：http://dali.jianghu66.top/Article/details/gt2hriyapis.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.quarkkingdee.top/Article/details/gt2qorqzjao.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gt2gtyhqpcw.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2shhuxoav.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2vjmkkcwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.havefunace.top/Article/details/gt2dxzherhv.html

PHP:  public static function f() {}
来源：http://dali.zdqjudy.top/Article/details/gt2ljxwmdfc.html

JS:   static f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2mawcpvid.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gt2ckvslghb.html

Java: static void f() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vfvbclug.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zdqjudy.top/Article/details/gt2wrvbvyjc.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2sixkjucq.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqktfnpf.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2muqrulaq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yonumen.top/Article/details/gt2dzmvvinf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ppjwa.cn/Article/details/gt2dkvbamml.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrtswari.html

TS:   interface Shape { area(): number; }
来源：http://dali.xylfe.cn/Article/details/gt2iwynuxkb.html

Java: interface Shape { double area(); }
来源：http://dali.316326.xyz/Article/details/gt2jdvgvtek.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.haohaochexian.top/Article/details/gt2cyhmxkjn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hnqzz.top/Article/details/gt2sgpvfqpl.html

C#:   interface IShape { double Area(); }
来源：http://dali.smart0.xyz/Article/details/gt2chyaaxml.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2fobgywxp.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2gadrfngg.html

PHP:  public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2usmlgorn.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gt2ogxcsawg.html

TS:   public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gt2hafscqce.html

Java: public / protected / private / 默认包级
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnygttzk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2muotkdap.html

Ruby: public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2wcoxiykp.html

C#:   public / protected / private / internal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvcymuia.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2psajifyn.html

Py:   @property 与 @x.setter
来源：http://dali.wangshuangyany.cn/Article/details/gt2yljhtjyy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibptbqhc.html

JS:   get name() { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gt2ssasonkl.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jalrtniq.html

Java: public String getName() { return name; }
来源：http://dali.yonumen.top/Article/details/gt2mphztbzp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shzxlz.cn/Article/details/gt2flffiazt.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gt2yopisxjy.html

C#:   public string Name { get; set; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vltaglvo.html

[G12] 对象转字符串
来源：http://dali.mhx1999.top/Article/details/gt2ncbfljoc.html

Py:   def __str__(self): return self.name
来源：http://dali.cqqwz.cn/Article/details/gt2jcsdxrcq.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aizwys.cn/Article/details/gt2ruyvzyew.html

JS:   toString() { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2cxbmqpqc.html

TS:   toString(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2axscxbmp.html

Java: @Override public String toString() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2sdmtfuqy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2oxgfmimn.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2achqoxhy.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2gqbqxbgy.html

[G13] 判断对象类型
来源：http://dali.nanxinkj.top/Article/details/gt2akatwnrn.html

Py:   isinstance(u, User)
来源：http://dali.aizwys.cn/Article/details/gt2waokhsim.html

PHP:  $u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2ydetyqpe.html

JS:   u instanceof User
来源：http://dali.nanxinkj.top/Article/details/gt2fqwcjtff.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2ciujolqa.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhrrnilm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj202588.top/Article/details/gt2aicuznfa.html

Ruby: u.is_a?(User)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oasofudt.html

C#:   u is User
来源：http://dali.sweek.top/Article/details/gt2tlorfkkg.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzkzucci.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.iojbl.cn/Article/details/gt2hoexzhhf.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jlsjyb.cn/Article/details/gt2xfsycyps.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gt2hhjbqpux.html

TS:   type User = { name: string; age: number };
来源：http://dali.yueranfly.top/Article/details/gt2bbamxhuk.html

Java: record User(String name, int age) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgxjvpk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.wangdashe.top/Article/details/gt2qaokfkbt.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daxiang520.top/Article/details/gt2vnbkmili.html

C#:   record User(string Name, int Age);
来源：http://dali.shuidangran.top/Article/details/gt2tzhnymhg.html

[G15] 枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ceqofiba.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pzeuxeez.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gt2alqghjij.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2dzshbste.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2jgpltjla.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2saxvymih.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gt2afapvlcs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.chenjidiqi.icu/Article/details/gt2xicacpog.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2lbwdmkqn.html

[G16] 对象转数组 / 字典
来源：http://dali.shzxlz.cn/Article/details/gt2rxjhjfog.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2zsltjouq.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2pozunstq.html

JS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2jedqakih.html

TS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2rqwtwiaj.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2mhfrhoqx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.dashuyun.cn/Article/details/gt2vqltxoug.html

Ruby: obj.instance_variables
来源：http://dali.ehwqpu.com/Article/details/gt2ssywbmwx.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gt2irpjbrzd.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2qgpuiook.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2qvsxcjbz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pefdtfcz.html

[H01] try / catch 基础
来源：http://dali.smart0.xyz/Article/details/gt2dfwrhcag.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.aibaodan.cn/Article/details/gt2ffutpjpx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yj202588.top/Article/details/gt2trjpyoyc.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2mmgprich.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2dpkqcbrt.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2opluizos.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ppjwa.cn/Article/details/gt2bgqgjyng.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gt2sjnjlzmq.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrsegbc.html

[H02] finally / ensure 收尾
来源：http://dali.meibo888.top/Article/details/gt2vbnqbeso.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2yfzsbfma.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2jhbyfdlt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hfpthk.cn/Article/details/gt2qiknxflk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gt2scvtbvon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2olnvofxs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2jnxkkyfo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2yotmlazz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2sdwdqdbw.html

[H03] 主动抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2ytlwvkgx.html

Py:   raise ValueError("错误信息")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eolzxqhg.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2lfsdsegf.html

JS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2agmlztui.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2dpfewvwx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2hulpseis.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gt2kfnvzlgl.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.tian-w.cn/Article/details/gt2zquhwnmc.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2mtydcjgb.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gt2qldpeyom.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gt2mnepvcpz.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sweek.top/Article/details/gt2cuxztjcb.html


<!-- 参考信息 -->