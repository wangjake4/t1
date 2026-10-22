代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2dvjoqpws.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ssrljqgo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cashguo.top/Article/details/gt2dxeoethr.html

Ruby: s.bytesize;  s.length
来源：http://dali.dashuyun.cn/Article/details/gt2hlweeqbd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jqgufenzy.top/Article/details/gt2dxbqhxdh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2mjqfpygd.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2udqlqzgj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ieagxqcc.html

[F01] 读取整个文件
来源：http://dali.hammf.cn/Article/details/gt2gptmmppn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2pfavoenf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2xkaakbod.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2jvledptm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnbnsylb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2obpphpwk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.nwbrower.top/Article/details/gt2ahdkzinm.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2riidubor.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ivvv.top/Article/details/gt2tuiknihf.html

[F02] 逐行读取文件
来源：http://dali.svipenyu.cn/Article/details/gt2ygknvokx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2ivowiadt.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gaohongyu789.top/Article/details/gt2juljsftz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gt2dtmggeef.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2afbikijx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sufxvd.cn/Article/details/gt2ukealoah.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlgkmbwz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jomjggbd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fzhhl.top/Article/details/gt2bkgqlnas.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gt2aejrkzbd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gt2wmrsndmt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2kgzfmyyi.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2scjetyqc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2fahlflcp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2uhqtcdks.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gt2otemqiel.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gt2nccnskiv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2fynehtvh.html

[F04] 追加写入文件
来源：http://dali.guannengcc.top/Article/details/gt2lmlewasr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xziqi.cn/Article/details/gt2ktxyhpzp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gt2bkdpgobq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2bevnyhfa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2xgmfgzgg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2lvxzxkdu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gt2jobtgtjl.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gt2cvdhxlih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gt2jiztgqvh.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2ukkejxim.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euvnulqq.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2manszcds.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ibyvowwh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2jbelrvlw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2tmhyrkzi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.iojbl.cn/Article/details/gt2ezxfxlna.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2crncfcxy.html

C#:   File.Exists("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2efwjujte.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvahcomq.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jtbsnmut.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2nisthuhe.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2xfgqjpnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2npocgwpz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2ngjckenk.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2haphents.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2kffpppkd.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2dzzolokc.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2djkbtspw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gt2uwmgnguo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gt2gcbhqkpw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2tzwjneii.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2qikcbowc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gt2unxoswog.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhongyouzk.top/Article/details/gt2pytnzpjd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gt2pzlpkrgs.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2omuayhqw.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gt2ypanzlft.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2invbulqu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gt2rbgnvwat.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2hzitppvl.html

TS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2jttjvwwz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2btdmonko.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.fzhhl.top/Article/details/gt2bnxhrdmx.html

Ruby: Dir.children("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2oyvjzfaw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2sxyqjldy.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gt2lnhoihdm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2mgkhjrrb.html

PHP:  filesize("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2elbchbuy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2ehbeptdq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2uhlvwwzx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2pndvujkj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2oahxinkt.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yithlfoe.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2iuvzndqb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2jpcuspgb.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2uartjwel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gt2hsfemoev.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2dcctkpbv.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ydfwvizc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2avgytxgk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2dwicydhf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2shthagoq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2plhpqwdo.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2kcagmjxl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2pyzgwkis.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zycfv.cn/Article/details/gt2qcplkcwe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2cazdawzb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2rmjmxiuo.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukxmwrsy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2gnnudldr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xmflubip.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gt2yqoygbaa.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gt2exsameod.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sxryk.cn/Article/details/gt2kzatbeox.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vdxiwonl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2jkrfkmkt.html

TS:   // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2vbvzabvv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvmtjyne.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gt2brimpftf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daxiang520.top/Article/details/gt2dzsvybyn.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.gotoacloud.top/Article/details/gt2stuwygqk.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2uvqnazrl.html

G. 面向对象
来源：http://dali.yuanzhike.top/Article/details/gt2zzanlham.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xzctnkmx.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2prdcskql.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gt2ancixlsy.html

PHP:  class User {}
来源：http://dali.yuxming.cn/Article/details/gt2xdgvuqfd.html

JS:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wjvzyosh.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2zibkpxur.html

Java: class User {}
来源：http://dali.hnqzz.top/Article/details/gt2vhoyjyhw.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gt2micslfgu.html

Ruby: class User; end
来源：http://dali.9152youxi.cn/Article/details/gt2pngxewbs.html

C#:   class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2cidoqnfc.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2oohrgaiz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guowangkeji.top/Article/details/gt2pejvgnlw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj202588.top/Article/details/gt2mvmqodng.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2icfcvpdw.html

TS:   constructor(public name: string) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yemzgucy.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gt2fhlmgspl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenzaomai.com/Article/details/gt2lgrqbgyn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.fengsongda.top/Article/details/gt2iqqohamb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wlnrnbth.html

[G03] 实例属性
来源：http://dali.gaohongyu789.top/Article/details/gt2egqgljby.html

Py:   self.name = "x"
来源：http://dali.aibaodan.cn/Article/details/gt2gubkyoxa.html

PHP:  public string $name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2uqnpechw.html

JS:   this.name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2ilighjxz.html

TS:   name: string = "x";
来源：http://dali.jqgfzy.top/Article/details/gt2jegzxufx.html

Java: private String name;
来源：http://dali.aibaodan.cn/Article/details/gt2ktzrmmoz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ivvv.top/Article/details/gt2lgyefmmz.html

Ruby: @name = "x"
来源：http://dali.svipenyu.cn/Article/details/gt2wcathess.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2scwrwgpe.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gt2ussbjmmd.html

Py:   def greet(self): return self.name
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlvwycek.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.mhx1999.top/Article/details/gt2fdituubn.html

JS:   greet() { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2nqubsldg.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gt2snhzjrzs.html

Java: String greet() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2qtudtkho.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2fbixtbgj.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2vyernxlm.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gt2ctnqlogv.html

[G05] 继承
来源：http://dali.jqgfzy.top/Article/details/gt2susobrjj.html

Py:   class Admin(User): pass
来源：http://dali.dashuyun.cn/Article/details/gt2pauintqk.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2fwohiddm.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2aiypkdap.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zvenctzj.html

Java: class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mgcxurva.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gt2mtpujmva.html

Ruby: class Admin < User; end
来源：http://dali.chenzaomai.com/Article/details/gt2lxgkcijm.html

C#:   class Admin : User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2axsmnlyh.html

[G06] 重写方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlafweno.html

Py:   def greet(self): return "admin"
来源：http://dali.shuidangran.top/Article/details/gt2zqyppbtc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2tpsynlsz.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2lwxfagcu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2arsbeimn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2jxnjbnof.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jianghu66.top/Article/details/gt2lhzpnfko.html

Ruby: def greet; "admin"; end
来源：http://dali.0kj1m.cn/Article/details/gt2udkxmxcc.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ahcnawms.html

[G07] 调用父类方法
来源：http://dali.yvedp.cn/Article/details/gt2sfsbvtdp.html

Py:   super().greet()
来源：http://dali.yangfankeji.com/Article/details/gt2pmjoknro.html

PHP:  parent::greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvdfjyaz.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oiigjmsi.html

TS:   super.greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2mvcumyug.html

Java: super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2eyuztwdr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2flmarvlq.html

Ruby: super
来源：http://dali.nanxuanxn.top/Article/details/gt2tlpwvykw.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2ujavjgnu.html

[G08] 静态方法与属性
来源：http://dali.snrcjt.cn/Article/details/gt2zydtocol.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2havngqyz.html

PHP:  public static function f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2esnoutti.html

JS:   static f() {}
来源：http://dali.sufxvd.cn/Article/details/gt2qmdjizpa.html

TS:   static f(): void {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2odweshew.html

Java: static void f() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2khomwqed.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shangyingyoupin.top/Article/details/gt2crmhwcgc.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2hyxnaufq.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuqiafyb.html

[G09] 接口 / 抽象类
来源：http://dali.yanxiufei.cn/Article/details/gt2htdnkgbf.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2jabfklnw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2ezglmdic.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhtaaawx.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vogobypy.html

Java: interface Shape { double area(); }
来源：http://dali.nwbrower.top/Article/details/gt2gjjlsrin.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2odmiduks.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.kuanghao11.cn/Article/details/gt2knalcoiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2yokqcexm.html

[G10] 访问控制
来源：http://dali.daxiang520.top/Article/details/gt2hccazrqo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fzhhl.top/Article/details/gt2zgmljsef.html

PHP:  public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2gqdglljs.html

JS:   #private 字段；其余公开
来源：http://dali.smart0.xyz/Article/details/gt2cagemyed.html

TS:   public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2aidpmtyj.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2ngpeqnit.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2ugcodtpz.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2jmjzsdsv.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gt2cfagdtiz.html

[G11] getter / setter
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmbufhhl.html

Py:   @property 与 @x.setter
来源：http://dali.havefunace.top/Article/details/gt2htlkrllj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.sxryk.cn/Article/details/gt2pzbbaazf.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xnsdywqy.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2unvivanr.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2wvdrnvea.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhscslwi.html

Ruby: attr_accessor :name
来源：http://dali.yj202588.top/Article/details/gt2ixnsxlye.html

C#:   public string Name { get; set; }
来源：http://dali.gogol.net.cn/Article/details/gt2mvnmthji.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gt2ifqmnpkc.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2mfylipjt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2mgidcvtw.html

JS:   toString() { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2euijhnlj.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2pjfeojrs.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2abctgaxm.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhengqikj.top/Article/details/gt2qfrmoaok.html

Ruby: def to_s; @name; end
来源：http://dali.svipenyu.cn/Article/details/gt2sgfamlkp.html

C#:   public override string ToString() => Name;
来源：http://dali.gogol.net.cn/Article/details/gt2nbtpvxyz.html

[G13] 判断对象类型
来源：http://dali.quarkkingdee.top/Article/details/gt2eslrnrlm.html

Py:   isinstance(u, User)
来源：http://dali.yj20258888.top/Article/details/gt2zgzcvses.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2xqszpyfy.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gt2izefoyyo.html

TS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2idxohkgu.html

Java: u instanceof User
来源：http://dali.ivvv.top/Article/details/gt2psjdsuyv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.vqdsnc.cn/Article/details/gt2fftscttw.html

Ruby: u.is_a?(User)
来源：http://dali.yongpay.top/Article/details/gt2dewhrfll.html

C#:   u is User
来源：http://dali.jqgfzy.top/Article/details/gt2vgjsvcck.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2ezpymane.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2kopdxxlp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvheqkfp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gt2loxutaiw.html

TS:   type User = { name: string; age: number };
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjqhhqzf.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2bkdneptl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigfzy.top/Article/details/gt2vgeoqauf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jyoumei.cn/Article/details/gt2abisghig.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2bozacoxz.html

[G15] 枚举
来源：http://dali.jqgfzy.top/Article/details/gt2wcpujxcl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2axbofkcn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.9152youxi.cn/Article/details/gt2muoipvkt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ehwqpu.com/Article/details/gt2dnclotuf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sweek.top/Article/details/gt2escdhtkx.html

Java: enum Color { RED, GREEN }
来源：http://dali.kuanghao11.cn/Article/details/gt2xsmvocvu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.havefunace.top/Article/details/gt2rwirulub.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuanzhike.top/Article/details/gt2fhnqxpvx.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2dhqckmbe.html

[G16] 对象转数组 / 字典
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmiexnnf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jqgufenzy.top/Article/details/gt2dnabmuvw.html

PHP:  get_object_vars($obj);
来源：http://dali.jyoumei.cn/Article/details/gt2psvkxbtl.html

JS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugwakoxw.html

TS:   Object.entries(obj)
来源：http://dali.hnqzz.top/Article/details/gt2pmuvzfki.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddfunkbz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gt2vvjuskas.html

Ruby: obj.instance_variables
来源：http://dali.zhijiandao.cn/Article/details/gt2qjerpzmr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ydzc1.top/Article/details/gt2ixjbljml.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ftprfyal.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2mawzqapv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2hgaxaktp.html

[H01] try / catch 基础
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xakwkuse.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjitxfjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gt2hraahoua.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gt2gdugzahi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gt2gmtvuqkp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gt2qegrulsn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2vizafucm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigufen.top/Article/details/gt2rigxmjnc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2udpfkcaz.html

[H02] finally / ensure 收尾
来源：http://dali.guannengcc.top/Article/details/gt2cxnffjfo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qnyukvef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ediuzdni.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2osxijmfs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gt2aydatfli.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2izaddfpb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sufxvd.cn/Article/details/gt2tjhmxjsu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2yzxuifiu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2ukmijnko.html

[H03] 主动抛出异常
来源：http://dali.jqgfzy.top/Article/details/gt2brmqnxrm.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2psyeftsc.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ixevkdcd.html

JS:   throw new Error("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gt2oivtrjis.html

TS:   throw new Error("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2kagfusex.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2oyapioxr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yonumen.top/Article/details/gt2iukvkjyw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.wangshuangyany.cn/Article/details/gt2srgtpowo.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gt2stvndwhi.html

[H04] 自定义异常类型
来源：http://dali.hnqzz.top/Article/details/gt2uifvvccn.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gt2tulwetii.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gt2lbgeoanb.html

JS:   class MyError extends Error {}
来源：http://dali.dianchejie.cn/Article/details/gt2arwdbuwa.html

TS:   class MyError extends Error {}
来源：http://dali.snrcjt.cn/Article/details/gt2zfakuqdg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.xuanzx.com/Article/details/gt2rfspqkly.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.dashuyun.cn/Article/details/gt2ifycftrj.html


<!-- 参考信息 -->