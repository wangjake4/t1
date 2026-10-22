代发 wailian999

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2kyjbmzsd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gt2uzwqfoob.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2cdvjiswd.html

Ruby: s.bytesize;  s.length
来源：http://dali.316326.xyz/Article/details/gt2spshobek.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zspmkrzv.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wfpigflw.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2igvxrfex.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2dshhllzu.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2lbryghsb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gt2dkpyqbyb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2mrfpdlnt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2ttqqzirt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2mwwgsvzb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2wdxqkdjv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.andypj.xyz/Article/details/gt2tofpxceb.html

Ruby: File.read("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rypqpylu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2vchauxcq.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gt2fylscedp.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yangfankeji.com/Article/details/gt2kaiolnlk.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sweek.top/Article/details/gt2gkerjxpb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2czkubvqy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dianchejie.cn/Article/details/gt2lnpvtxvb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2yqnfgdac.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gt2ynshzpeh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gt2zuhlvmpz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuanzx.com/Article/details/gt2xfazbvjs.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2upjrakfv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hppxargw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gt2rjvmxsla.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwcaqoiu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqjdofez.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2edeivhhu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jianghu66.top/Article/details/gt2kvqxpobh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2ykooeqzs.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2dqpazbsu.html

[F04] 追加写入文件
来源：http://dali.shuidangran.top/Article/details/gt2frjwsaen.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gt2spfkukwx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkymjtv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2jywprwsa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2urjsyvau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2rmtxqopm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2mfuqpinr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj202588.top/Article/details/gt2oibctvnw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2fupnkdyv.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2slbowvvt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gt2sfbvesua.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2rodwnhan.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2cxuggkon.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fbjbdlzo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2pdugioew.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yongpay.top/Article/details/gt2ujkcmxwi.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2jtlnjfci.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2wilxkfgc.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2vodqzbxb.html

Py:   os.remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ngakyymc.html

PHP:  unlink("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2pjmpimri.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2ffncllit.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2jiydfetz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2lqkjwxoy.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hrynrnbb.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2sydtalcb.html

C#:   File.Delete("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2jhnqrenx.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2zsyslsuk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gt2zybefebt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gt2wzwuaryw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gt2zicvyvla.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2sodnliap.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.birdmap.top/Article/details/gt2yqpgqbtl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yonumen.top/Article/details/gt2rjskpcaq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gt2svputfny.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gt2rujgwclj.html

[F08] 遍历目录
来源：http://dali.sweek.top/Article/details/gt2ndpzvsmm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sxryk.cn/Article/details/gt2jdxovzsk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkdwjojy.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxnraofz.html

TS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2fsxjefhc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gt2qolkznja.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2gfhoyeau.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2miqbjjhz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gt2zgrrblys.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gt2ntsxrfgi.html

Py:   os.path.getsize("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2omkzipbf.html

PHP:  filesize("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2ihvomjwn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2nuajlidm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gt2qnnvrdes.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2zfubvpes.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odkfgorn.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2cuochhdo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.andypj.xyz/Article/details/gt2rxcjulxx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gt2nxxymiaj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2yiralfjk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2hilaalry.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlyrhrzd.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yizevssj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gt2baroutrw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpbkqjdb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2vtrpjsgo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2oinqblxp.html

[F11] 复制与移动文件
来源：http://dali.zycfv.cn/Article/details/gt2xvzsuzhx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gt2vojqjgoz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2fzhtyefe.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2akjybfyw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sssxqhvv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gt2niooitwp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.mhx1999.top/Article/details/gt2kbctulji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2lejydueo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hfpthk.cn/Article/details/gt2lobnokis.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gt2lwqpeaii.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gt2auxtuqne.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gt2jmqnjkjo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2zuuebkkt.html

TS:   // 同上
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nnrxhdjj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuanzx.com/Article/details/gt2wgpbdxyo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bfhjsrpa.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjjqioxh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcameynh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rkwmpeyw.html

G. 面向对象
来源：http://dali.zhengqikj.top/Article/details/gt2zwrlknrn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2zcxlylro.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gt2ryosqqzg.html

Py:   class User: pass
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lroheneo.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wikmsqyo.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2wjdnoiik.html

TS:   class User { name: string = ""; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvgqahee.html

Java: class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixlfptkb.html

Go:   type User struct { Name string }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yteaqjbf.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2vrzwyrun.html

C#:   class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2damtiayx.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gt2qzjwuzji.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.meibo888.top/Article/details/gt2etssxzop.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yueranfly.top/Article/details/gt2mmkoaelb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2knzjtdcc.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gt2mcvxxluy.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gt2sgzdqcyb.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.birdmap.top/Article/details/gt2olmvxysz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2vslbjlxy.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenlongwang.top/Article/details/gt2wrzowojn.html

[G03] 实例属性
来源：http://dali.andypj.xyz/Article/details/gt2bcgjhaqs.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2aheirekm.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2laapyths.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2uosvkarq.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2vdrggdia.html

Java: private String name;
来源：http://dali.havefunace.top/Article/details/gt2mkfhlrec.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gt2qdtmslua.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gt2fpjysjim.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hfpthk.cn/Article/details/gt2wyvikhjf.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymsmoelc.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjqypxbb.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2xhcueftc.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2bfiuqdjd.html

TS:   greet(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2zukxjjzz.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2izdkddii.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2ibgrmdov.html

Ruby: def greet; @name; end
来源：http://dali.9152youxi.cn/Article/details/gt2abfulrjn.html

C#:   public string Greet() => Name;
来源：http://dali.chenlongwang.top/Article/details/gt2zzajmelw.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obeupztm.html

Py:   class Admin(User): pass
来源：http://dali.hammf.cn/Article/details/gt2pmrmntaf.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2mjkkuppf.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2jbflfpve.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gt2hhlwhzcq.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2thhdbavz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2erfwwmhe.html

Ruby: class Admin < User; end
来源：http://dali.shzxlz.cn/Article/details/gt2hfbrpedp.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2erszblhy.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gt2gsmsldqt.html

Py:   def greet(self): return "admin"
来源：http://dali.hywenlv.cn/Article/details/gt2gkegmjbk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2tomzisol.html

JS:   greet() { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gt2jkiptqbl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gt2wjgkbvwy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2kodxzfsq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2ndbnawiy.html

Ruby: def greet; "admin"; end
来源：http://dali.ybcxt.top/Article/details/gt2sbvyjqpz.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gt2azwfqdsd.html

[G07] 调用父类方法
来源：http://dali.aibaodan.cn/Article/details/gt2pzocmarp.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hosueftt.html

PHP:  parent::greet();
来源：http://dali.chenzaomai.com/Article/details/gt2qqqhzhke.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2sbeyrxit.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2vwhqsdsi.html

Java: super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2kfetbtkz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tanke756.top/Article/details/gt2bevfecoe.html

Ruby: super
来源：http://dali.yj202588.top/Article/details/gt2kgfzxhre.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gt2uybihsae.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2nicahwqs.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gt2eugyyjar.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zmwlgerr.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evywahmt.html

TS:   static f(): void {}
来源：http://dali.aibaodan.cn/Article/details/gt2emehtyra.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2flboklmk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gt2hkuqgmfm.html

Ruby: def self.f; end
来源：http://dali.yanxiufei.cn/Article/details/gt2fwbiluuh.html

C#:   public static void F() {}
来源：http://dali.yueranfly.top/Article/details/gt2xgaqtwxm.html

[G09] 接口 / 抽象类
来源：http://dali.daxiang520.top/Article/details/gt2yldokkqi.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guannengcc.top/Article/details/gt2lrrqygxz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2obvuvmxv.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvhsgicf.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxyrqjam.html

Java: interface Shape { double area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzoblpxi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gt2cduizajj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yueranfly.top/Article/details/gt2enxtfsbl.html

C#:   interface IShape { double Area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2nttwimsk.html

[G10] 访问控制
来源：http://dali.hammf.cn/Article/details/gt2yuwxiwea.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2tipgjlfi.html

PHP:  public / protected / private
来源：http://dali.guannengcc.top/Article/details/gt2heaevicq.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gt2wcslaruc.html

TS:   public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2wmhdhltk.html

Java: public / protected / private / 默认包级
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mfgzmzhh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2vhkpjidg.html

Ruby: public / protected / private
来源：http://dali.daria6918.cn/Article/details/gt2ojmwdmih.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gt2wkkyqalw.html

[G11] getter / setter
来源：http://dali.ybcxt.top/Article/details/gt2zzisxlly.html

Py:   @property 与 @x.setter
来源：http://dali.bjfxy.top/Article/details/gt2zctyqtqh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2jxuhooiy.html

JS:   get name() { return this._name; }
来源：http://dali.jinqigufen.top/Article/details/gt2fzqumgre.html

TS:   get name(): string { return this._name; }
来源：http://dali.iojbl.cn/Article/details/gt2rznmgowt.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2yhjvzjxm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuanzx.com/Article/details/gt2ckulnvdc.html

Ruby: attr_accessor :name
来源：http://dali.yj20258888.top/Article/details/gt2nlemfvvc.html

C#:   public string Name { get; set; }
来源：http://dali.yj20258888.top/Article/details/gt2rgmgokbx.html

[G12] 对象转字符串
来源：http://dali.tian-w.cn/Article/details/gt2vhgjifzs.html

Py:   def __str__(self): return self.name
来源：http://dali.sweek.top/Article/details/gt2tmhldflb.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2lkkghtpv.html

JS:   toString() { return this.name; }
来源：http://dali.jianghu66.top/Article/details/gt2ubbzuuom.html

TS:   toString(): string { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2puqinxsh.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gt2zabekkau.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.cashguo.top/Article/details/gt2yzonlewc.html

Ruby: def to_s; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2lsieumjn.html

C#:   public override string ToString() => Name;
来源：http://dali.xziqi.cn/Article/details/gt2qsvdvwvu.html

[G13] 判断对象类型
来源：http://dali.hywenlv.cn/Article/details/gt2tmghxlpp.html

Py:   isinstance(u, User)
来源：http://dali.havefunace.top/Article/details/gt2ymvqkcfi.html

PHP:  $u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2qmhhqdin.html

JS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2glpfxigd.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2vsvumpzg.html

Java: u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2iedpcmxx.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sweek.top/Article/details/gt2spcpxhof.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gt2lmefrczo.html

C#:   u is User
来源：http://dali.xuetiantiany.cn/Article/details/gt2wvlwonsv.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyrmrboh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhengqikj.top/Article/details/gt2qcnwnrcw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gt2oqfxyhnd.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.guowangkeji.top/Article/details/gt2qdcxkqvd.html

TS:   type User = { name: string; age: number };
来源：http://dali.sysykeji.top/Article/details/gt2hszfplov.html

Java: record User(String name, int age) {}
来源：http://dali.havefunace.top/Article/details/gt2hppphfgt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.guowangkeji.top/Article/details/gt2avbjekdp.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2etiaufou.html

C#:   record User(string Name, int Age);
来源：http://dali.jqgufenzy.top/Article/details/gt2akhqzjyp.html

[G15] 枚举
来源：http://dali.xuanzx.com/Article/details/gt2mybxidjx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdhltqbw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.snrcjt.cn/Article/details/gt2ovlihogq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gt2etfdsxdo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xziqi.cn/Article/details/gt2obqxpkqm.html

Java: enum Color { RED, GREEN }
来源：http://dali.birdmap.top/Article/details/gt2htydgmqe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuotlsak.html

Ruby: Color = %i[red green].freeze
来源：http://dali.sxryk.cn/Article/details/gt2mounmtkq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fszntqkb.html

[G16] 对象转数组 / 字典
来源：http://dali.cqqwz.cn/Article/details/gt2cragjlsm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhixingplan.top/Article/details/gt2jvirqehc.html

PHP:  get_object_vars($obj);
来源：http://dali.kuanghao11.cn/Article/details/gt2blpvuxte.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gt2pzlyxcox.html

TS:   Object.entries(obj)
来源：http://dali.bjfxy.top/Article/details/gt2pxhkrhbs.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gt2jmnqoxlx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gotoacloud.top/Article/details/gt2yxaennnd.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gt2amlmcqrw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhixingplan.top/Article/details/gt2rrgrslrh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2cznqgoac.html

H. 异常与错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2srrfuxae.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2mhmqxeec.html

[H01] try / catch 基础
来源：http://dali.haohaochexian.top/Article/details/gt2hexhrkyw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2xsnukthj.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cheryme.top/Article/details/gt2dtbnzrcl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rchbdngl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gt2snqqosfm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hfpthk.cn/Article/details/gt2fmikoyud.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gt2wfzyjobt.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jlsjyb.cn/Article/details/gt2aukufdus.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2shoomrel.html

[H02] finally / ensure 收尾
来源：http://dali.aibaodan.cn/Article/details/gt2vueoikdu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rqowgskq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gt2wnifboae.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwzfcyjt.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2sxjmnawg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hgobcolf.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.birdmap.top/Article/details/gt2mkqmcdlv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangdashe.top/Article/details/gt2nuctimth.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2riqawsrf.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2eungxitz.html

Py:   raise ValueError("错误信息")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkulspdw.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.havefunace.top/Article/details/gt2ssoxndzp.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2zaqwhxye.html

TS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2xgakyotx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.0kj1m.cn/Article/details/gt2osjhxubl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2yjqmccfz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gt2cuveybcx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2xaifobue.html

[H04] 自定义异常类型
来源：http://dali.iojbl.cn/Article/details/gt2jzrftjjq.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ortgpyqe.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hammf.cn/Article/details/gt2gfidqamc.html

JS:   class MyError extends Error {}
来源：http://dali.zhongyouzk.top/Article/details/gt2ufupykoa.html

TS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gt2lgnvtnrq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenlongwang.top/Article/details/gt2frbrmjms.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shuidangran.top/Article/details/gt2mcpsqqpy.html


<!-- 参考信息 -->