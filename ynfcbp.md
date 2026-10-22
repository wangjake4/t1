代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sweek.top/Article/details/gt2ycnjxcyi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vrorpxfd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.316326.xyz/Article/details/gt2wwxbmwkz.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2ojxyrzam.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2dxzopsro.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2syjrpkbk.html

F. 文件与目录
来源：http://dali.gaohongyu789.top/Article/details/gt2xcsginqk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2hcaxjayl.html

[F01] 读取整个文件
来源：http://dali.xylfe.cn/Article/details/gt2ejqmfgnb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.9152youxi.cn/Article/details/gt2wikfukzk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2vpvyhayf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sufxvd.cn/Article/details/gt2heibjhsv.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gt2uoublgod.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2fcmwacjl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zycfv.cn/Article/details/gt2evuuxucv.html

Ruby: File.read("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2jvtzxjid.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2gyrupdvb.html

[F02] 逐行读取文件
来源：http://dali.hywenlv.cn/Article/details/gt2garrxugv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jqgufenzy.top/Article/details/gt2qfxrahub.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gt2fxeavdsi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2zopoplxo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2iacuuwll.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2jjvdulls.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klsxcmdn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gt2emaeaeeb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gt2xlzpmlzm.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2bznhrxkp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2wjlapwuf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sysykeji.top/Article/details/gt2vzdkdkrn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2qmjbfbba.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2wcdgeyrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2bcsfwbhj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2idirlkyy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuanzx.com/Article/details/gt2dibnowhv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2cetjreks.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gt2zmgudxro.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2tywtsvjh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sysykeji.top/Article/details/gt2xrgazvnu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2qltcviub.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2bvswlqgw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gt2gcainzee.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2caegowue.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gt2eazgomhs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vdmxavhd.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2aanhxswy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gt2xdcvfugt.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2nzeehcsk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cuxuegcg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tezyxeid.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gapfeqgs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jianghu66.top/Article/details/gt2reowtmnb.html

Ruby: File.exist?("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ujgdocfp.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xyhituxl.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2kromjtvw.html

Py:   os.remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2uawcwyvq.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2tmslkuji.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2izrucleb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qpfxkfel.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2likixsju.html

Go:   os.Remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2dtegqszk.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jjezxaaj.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2sawzuvfw.html

[F07] 创建目录（含多级）
来源：http://dali.mhx1999.top/Article/details/gt2cxcvicsi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2szvelpvh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jianghu66.top/Article/details/gt2egwujrol.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2dznkpvox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gt2lczmjhbp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2yskigyls.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuanzhike.top/Article/details/gt2hrobfzpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2gokautkd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2ugggqqns.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2chlqnumq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgfzy.top/Article/details/gt2dubbwqtk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yueranfly.top/Article/details/gt2cbepdujp.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gt2mbonvynw.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2eviyojrn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2xvcpuvbu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ptlgmjgy.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ajkggfmu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2stippghi.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2iygmrzeq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2swscoquk.html

PHP:  filesize("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2imeqnmxe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yueranfly.top/Article/details/gt2lvfhykgf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2pioaomga.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2dopnkjgw.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2kuhrueij.html

Ruby: File.size("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2egfamroi.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenlongwang.top/Article/details/gt2yndaoone.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tian-w.cn/Article/details/gt2fgsgsxzc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzsnsglg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2akneqfuf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bscwxdqg.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2mmnybrhw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.snrcjt.cn/Article/details/gt2decbjybm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2kmvalqhs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2utakndrd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dnfzmcgb.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2woxswfqs.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2gtfnjcov.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2kbmlbtbs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2vckjcxlk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2kweymlqh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpvedklh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gt2snyfoisb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2jfgequus.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gt2qwimkuat.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gt2ycrkukyc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.quarkkingdee.top/Article/details/gt2vealxpqt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gt2njdsiayt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvyfpztd.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gt2nsjrgnok.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2dlforlyg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2djnzyyax.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cheryme.top/Article/details/gt2tvykglsq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2efzicjzh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ypqsvawz.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gt2zznbbjpx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qydnwlza.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gt2yprimtyr.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvlvwnpg.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2tchtykxh.html

JS:   class User {}
来源：http://dali.yongpay.top/Article/details/gt2btwgmaxz.html

TS:   class User { name: string = ""; }
来源：http://dali.aizwys.cn/Article/details/gt2dxeaeivi.html

Java: class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2eajularf.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gt2chalqtfj.html

Ruby: class User; end
来源：http://dali.wangdashe.top/Article/details/gt2omdlzhfk.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2zynhszwj.html

[G02] 构造函数
来源：http://dali.wangdashe.top/Article/details/gt2tppbonty.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gt2qzxhqtmu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aizwys.cn/Article/details/gt2iudpivpq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2duvxdgvo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wsdjgque.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axasraar.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gt2wsrpngvw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muyquwxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aizwys.cn/Article/details/gt2adfvughl.html

[G03] 实例属性
来源：http://dali.hywenlv.cn/Article/details/gt2bdbgzfac.html

Py:   self.name = "x"
来源：http://dali.pengpengdd.cyou/Article/details/gt2rmunvixj.html

PHP:  public string $name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2isdhqpon.html

JS:   this.name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2seopgsbr.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rpfwbear.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gt2emceuvpz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2cpyfrore.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmiunxx.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2zyrvofeo.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2clofbjba.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gt2hnexcipm.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2orkxohhq.html

JS:   greet() { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gt2lfvwgkvd.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyyibceb.html

Java: String greet() { return name; }
来源：http://dali.yueranfly.top/Article/details/gt2wfslgrdo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2dcxuabxv.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2fiwmqttw.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2swrzzwtt.html

[G05] 继承
来源：http://dali.aibaodan.cn/Article/details/gt2iivbfuos.html

Py:   class Admin(User): pass
来源：http://dali.jqgufenzy.top/Article/details/gt2zarnmrur.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2jwaoprtv.html

JS:   class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2atlvpbnk.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2novrbzck.html

Java: class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2lbqkatrw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.cdnleiting.top/Article/details/gt2oeesjafz.html

Ruby: class Admin < User; end
来源：http://dali.vqdsnc.cn/Article/details/gt2iluptacx.html

C#:   class Admin : User {}
来源：http://dali.andypj.xyz/Article/details/gt2zkvtbwqw.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2lowwkxyt.html

Py:   def greet(self): return "admin"
来源：http://dali.dashuyun.cn/Article/details/gt2qtyvuieg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2hukszryc.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2zhdrndvo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2ruphwcmv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2pykkwibg.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2niyfakdx.html

Ruby: def greet; "admin"; end
来源：http://dali.cashguo.top/Article/details/gt2xnsdmkqt.html

C#:   public override string Greet() => "admin";
来源：http://dali.daxiang520.top/Article/details/gt2skhvbdcx.html

[G07] 调用父类方法
来源：http://dali.sufxvd.cn/Article/details/gt2vnjizplv.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gt2owumxkoo.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2dzdzjcjn.html

JS:   super.greet();
来源：http://dali.zhengqikj.top/Article/details/gt2auodtpaz.html

TS:   super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2jvxzwqak.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2bijseaof.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nwbrower.top/Article/details/gt2gipuaalu.html

Ruby: super
来源：http://dali.ppjwa.cn/Article/details/gt2tfsfkxnx.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gt2szwyrfvs.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2qxhghqrg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2zbiqelsq.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gt2yyaffiah.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gt2rymijjfk.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gt2povqgffe.html

Java: static void f() {}
来源：http://dali.bjfxy.top/Article/details/gt2kqnokqbd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.aizwys.cn/Article/details/gt2pjykscai.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gt2qwzgcnza.html

C#:   public static void F() {}
来源：http://dali.chenlongwang.top/Article/details/gt2mgfmrebr.html

[G09] 接口 / 抽象类
来源：http://dali.yonumen.top/Article/details/gt2pnvgipej.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.wangshuangyany.cn/Article/details/gt2wmqhygzg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2urpkydga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fengsongda.top/Article/details/gt2pdgbjtcm.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2xslscekb.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2mesqfxco.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2npkfwzyi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yanxiufei.cn/Article/details/gt2xbtdyged.html

C#:   interface IShape { double Area(); }
来源：http://dali.guowangkeji.top/Article/details/gt2envxutmu.html

[G10] 访问控制
来源：http://dali.iojbl.cn/Article/details/gt2atrjupqy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yanxiufei.cn/Article/details/gt2dqfrkqto.html

PHP:  public / protected / private
来源：http://dali.zhoulong.xyz/Article/details/gt2mcdwcfvd.html

JS:   #private 字段；其余公开
来源：http://dali.quarkkingdee.top/Article/details/gt2ehnfoibz.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gt2qrazixrp.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gt2mxumuugb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.mhx1999.top/Article/details/gt2nykbnrmb.html

Ruby: public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gt2uingblea.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gt2jhtdxmno.html

[G11] getter / setter
来源：http://dali.bjfxy.top/Article/details/gt2cohvqtij.html

Py:   @property 与 @x.setter
来源：http://dali.birdmap.top/Article/details/gt2dknfljfo.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gt2emgdkhgi.html

JS:   get name() { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gt2grhzpihe.html

TS:   get name(): string { return this._name; }
来源：http://dali.yonumen.top/Article/details/gt2dnffttne.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfocbvkd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gt2ffjyoqdl.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2rcescopc.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2njoygzhe.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2qudvfrjr.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2gbzcptet.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ehaerblt.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2nyxeihdt.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zvohhyns.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ukfetmyn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhijiandao.cn/Article/details/gt2knwdxqgi.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2dnrhyquv.html

C#:   public override string ToString() => Name;
来源：http://dali.smart0.xyz/Article/details/gt2azufvtpv.html

[G13] 判断对象类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnnlzekw.html

Py:   isinstance(u, User)
来源：http://dali.cqqwz.cn/Article/details/gt2oypfgfbd.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gt2emqvbcus.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2gnlbvova.html

TS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2dstvwxkg.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2wrnishze.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.chenzaomai.com/Article/details/gt2uiznwyly.html

Ruby: u.is_a?(User)
来源：http://dali.bjfxy.top/Article/details/gt2sygblgva.html

C#:   u is User
来源：http://dali.yj20258.top/Article/details/gt2awbeanaa.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2tuagbdnr.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hysaishi.cn/Article/details/gt2bldjslbv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gt2hpadrqcv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gt2jydtxbof.html

TS:   type User = { name: string; age: number };
来源：http://dali.guowangkeji.top/Article/details/gt2uibhhark.html

Java: record User(String name, int age) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ylmiysag.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljjxaowu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.fengsongda.top/Article/details/gt2byscdtky.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2wsbwydxx.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2vnkbkxay.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2ptysffiv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tzswcejm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.shangyingyoupin.top/Article/details/gt2beyzalvd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyabnmtn.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2iwsibzfu.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj202588.top/Article/details/gt2juuihrto.html

Ruby: Color = %i[red green].freeze
来源：http://dali.vqdsnc.cn/Article/details/gt2xbzegncp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sysykeji.top/Article/details/gt2rbfqddxi.html

[G16] 对象转数组 / 字典
来源：http://dali.meibo888.top/Article/details/gt2rpkefunv.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2ogaxmzid.html

PHP:  get_object_vars($obj);
来源：http://dali.xinyue.icu/Article/details/gt2pouvqfqp.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gt2tfwoelbg.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddldqsji.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2qbhtndyu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2dfvnwcqq.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gt2tfdcpktq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.316326.xyz/Article/details/gt2blrcmbwv.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ftksvrch.html

H. 异常与错误处理
来源：http://dali.tanke756.top/Article/details/gt2eorllhts.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2qbjomgbn.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2segzjnzw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gt2cpizosxh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tgwowhjj.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2mjlnohcz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.yvedp.cn/Article/details/gt2lmptvpcy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2ruzuzpds.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.snrcjt.cn/Article/details/gt2lnabynnq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbuamiwi.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2zewlmvqb.html

[H02] finally / ensure 收尾
来源：http://dali.9152youxi.cn/Article/details/gt2rnepxljo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nanxuanxn.top/Article/details/gt2aalgrwoa.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2rcesobgy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gt2bjxjwoyw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2lhfweqno.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2zrrzbqvm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2zbjhemuf.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.guowangkeji.top/Article/details/gt2ofsmwjkr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2tascdwzv.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2occqapnq.html

Py:   raise ValueError("错误信息")
来源：http://dali.fengsongda.top/Article/details/gt2isadwadi.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2dqeadpij.html

JS:   throw new Error("错误信息");
来源：http://dali.zhixingplan.top/Article/details/gt2hfsldfsr.html

TS:   throw new Error("错误信息");
来源：http://dali.zhengqikj.top/Article/details/gt2yqkfvcnl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2lxextkod.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jbwnzadd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.dianchejie.cn/Article/details/gt2lwsuomfy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.9152youxi.cn/Article/details/gt2gmmicfdb.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2zmywgcqm.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2ojcilzkl.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.nwbrower.top/Article/details/gt2afualdaf.html

JS:   class MyError extends Error {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jwmpxxkc.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2gjtwigxf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gt2iwvayuvv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ybcxt.top/Article/details/gt2rucunofc.html


<!-- 参考信息 -->