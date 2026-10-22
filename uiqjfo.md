代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gt2oglbfwli.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gt2briyhpcj.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ytmmtwxv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daria6918.cn/Article/details/gt2uoroiygr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2womwtyix.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daria6918.cn/Article/details/gt2zmpantko.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmstwehe.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gt2shkecymj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqqqfwrt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2osffheig.html

F. 文件与目录
来源：http://dali.shzxlz.cn/Article/details/gt2xnysbozf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vststvfz.html

[F01] 读取整个文件
来源：http://dali.xuanzx.com/Article/details/gt2vqilwqbb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfbqupsa.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2aulyjsmq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.birdmap.top/Article/details/gt2zlxqmgkd.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2fimhnwut.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2maxochhl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gt2lkhyuixx.html

Ruby: File.read("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2sskkgjxh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2itbjsskp.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2stgncbhn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ppjwa.cn/Article/details/gt2mgzrhumy.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gt2pdzdfrtn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gt2opbbkema.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2vvkffqvo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxuanxn.top/Article/details/gt2topktzso.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ivegxsiq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2axhhllvc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2huqalybq.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gt2qmbcsjxb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2poajittc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2aanikaxo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxeqyido.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cdnleiting.top/Article/details/gt2rbgmpemv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gt2ajrrbfuu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gt2dauwaynm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzjzucqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gt2siorkgqh.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2bjqabtao.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2atzfmrki.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shangyingyoupin.top/Article/details/gt2gchhwhvx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2hkcmwhdc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gt2otffgogh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2axbmeepe.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.kuanghao11.cn/Article/details/gt2sicvbbbi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aizwys.cn/Article/details/gt2tmsdkeee.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2jvihuiir.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2qlbldokb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gt2bkavxikk.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2undpvcpx.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2jjdvsjlk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2tqxaxxlf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2xrgioafh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2lpwugsof.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbksazpi.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2twuvjghr.html

[F06] 删除文件
来源：http://dali.zycfv.cn/Article/details/gt2xqoyijkd.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2snasqkus.html

PHP:  unlink("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2xjikpkrt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lkfovodv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kkjuyncb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gt2obeimvkt.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2owmykzij.html

Ruby: File.delete("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2vygporii.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2ejdtbhlt.html

[F07] 创建目录（含多级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yaaqqefh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj202588.top/Article/details/gt2vzqpwklt.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gt2dkorxlwv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2jgzisxne.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqypwmzm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2ryzgteph.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hammf.cn/Article/details/gt2svytlfgn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.tian-w.cn/Article/details/gt2plvibbmr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gt2vldhimru.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2jtodqmqc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.smart0.xyz/Article/details/gt2wjolctuh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tian-w.cn/Article/details/gt2iycndlyr.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2mfpvkzqv.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ymevirts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2lktdjtsh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.birdmap.top/Article/details/gt2sjyimvkc.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gt2mbtrdlqz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2yewgfugw.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvaosvlu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2abdofamw.html

PHP:  filesize("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2uzhxpkfy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.0kj1m.cn/Article/details/gt2hyhwwrtr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gt2zhmerirt.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gklcaomx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guowangkeji.top/Article/details/gt2eapfkrnd.html

Ruby: File.size("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2pzuyniox.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.iojbl.cn/Article/details/gt2dhyqvtjf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2oedlfyjw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2lcypmdyj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2kkwbopbj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fluncywx.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2qhlxkgzb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dashuyun.cn/Article/details/gt2ojresolr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2judiaikr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bpbasafw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2xhjswoha.html

[F11] 复制与移动文件
来源：http://dali.ybcxt.top/Article/details/gt2vwbikczp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2qcfhkrng.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ughbjxme.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2mexncbcb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2xokkwrod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gt2gexwspsr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aibaodan.cn/Article/details/gt2rsrkxpzp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szdsorrj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gt2azihekah.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2qwvhqjsh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gt2eylqfcjs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2thdvcank.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2ydhmfgeh.html

TS:   // 同上
来源：http://dali.ppjwa.cn/Article/details/gt2azotzgbv.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gt2dwtodiib.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bqhywwjh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258.top/Article/details/gt2hippmguu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj202588.top/Article/details/gt2djvzrbpy.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2dzigpkzt.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2igypveig.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2ssltvfzm.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdmebqxa.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2orqyhwrc.html

PHP:  class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2pgntzoib.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alyeqzkr.html

TS:   class User { name: string = ""; }
来源：http://dali.cucudq.cn/Article/details/gt2mlsryira.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2xvwnijhc.html

Go:   type User struct { Name string }
来源：http://dali.snrcjt.cn/Article/details/gt2vdsgshyo.html

Ruby: class User; end
来源：http://dali.aibaodan.cn/Article/details/gt2zlxxmpkb.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2fquhhyan.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ucgfgkjr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.hywenlv.cn/Article/details/gt2sqoziuxk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.redwolf501.top/Article/details/gt2adgobrfu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2nrvstsiv.html

TS:   constructor(public name: string) {}
来源：http://dali.cqqwz.cn/Article/details/gt2hphfvbdt.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gtohrgxg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sweek.top/Article/details/gt2skbnewpf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.birdmap.top/Article/details/gt2kfezmmij.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gt2xhybbnhy.html

[G03] 实例属性
来源：http://dali.tian-w.cn/Article/details/gt2miklurgo.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2jlhvrvyf.html

PHP:  public string $name = "x";
来源：http://dali.jqgufenzy.top/Article/details/gt2fwclcaeh.html

JS:   this.name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lyystlua.html

TS:   name: string = "x";
来源：http://dali.zhoulong.xyz/Article/details/gt2ddobdorr.html

Java: private String name;
来源：http://dali.hnxiangtu.top/Article/details/gt2dqniwojz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gt2apbnljlc.html

Ruby: @name = "x"
来源：http://dali.yonumen.top/Article/details/gt2kowlkenz.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2aflnxgzx.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gt2yzuyuapq.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2ulkjcfdu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2qlwmgfsn.html

JS:   greet() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fsjonixg.html

TS:   greet(): string { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cgvgyvrg.html

Java: String greet() { return name; }
来源：http://dali.sweek.top/Article/details/gt2zkurcnlf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gt2icpwjlyw.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2qkyfondl.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzyctima.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2njlnuvip.html

Py:   class Admin(User): pass
来源：http://dali.daria6918.cn/Article/details/gt2trwclwsk.html

PHP:  class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2ertpvnut.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2lqefzbwe.html

TS:   class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2qdmcnged.html

Java: class Admin extends User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ibzakupn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guannengcc.top/Article/details/gt2gslcizok.html

Ruby: class Admin < User; end
来源：http://dali.316326.xyz/Article/details/gt2oluezcrz.html

C#:   class Admin : User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ccljxeqj.html

[G06] 重写方法
来源：http://dali.tianlin.xyz/Article/details/gt2quhmcbwj.html

Py:   def greet(self): return "admin"
来源：http://dali.zhengqikj.top/Article/details/gt2yrpnoosc.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2jezpofmq.html

JS:   greet() { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gt2guylvboo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2ajbummte.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbzihqhy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.iojbl.cn/Article/details/gt2uwofoiga.html

Ruby: def greet; "admin"; end
来源：http://dali.jlsjyb.cn/Article/details/gt2zbihnjne.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gt2gxjkkakn.html

[G07] 调用父类方法
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsrgxzgv.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2wohnzccf.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2krrfwpvi.html

JS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2xzrxtyti.html

TS:   super.greet();
来源：http://dali.svipenyu.cn/Article/details/gt2rfttziqr.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2moglpvbl.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gt2imiilrho.html

Ruby: super
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eupwtpzn.html

C#:   base.Greet();
来源：http://dali.chenlongwang.top/Article/details/gt2aehtjchy.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gt2lgxvxsru.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2ibygefkj.html

PHP:  public static function f() {}
来源：http://dali.mhx1999.top/Article/details/gt2jedqwvcr.html

JS:   static f() {}
来源：http://dali.svipenyu.cn/Article/details/gt2uxzctfal.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2qmkulvcm.html

Java: static void f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzcytucp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.meibo888.top/Article/details/gt2qfszwqty.html

Ruby: def self.f; end
来源：http://dali.ydzc1.top/Article/details/gt2bzwfckmm.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2tjxblwyt.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gt2orljwvju.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.havefunace.top/Article/details/gt2dmzgbnsx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guannengcc.top/Article/details/gt2zehlrujq.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jlsjyb.cn/Article/details/gt2jfgmrdnv.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhongyouzk.top/Article/details/gt2acwnfiqz.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2tmxecnye.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2croumlii.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.ivvv.top/Article/details/gt2rpjtzrwb.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vkmsfuci.html

[G10] 访问控制
来源：http://dali.mhx1999.top/Article/details/gt2bmgtvozv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.guannengcc.top/Article/details/gt2uhdrajwl.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2ljmgyggg.html

JS:   #private 字段；其余公开
来源：http://dali.xziqi.cn/Article/details/gt2fdltumhv.html

TS:   public / protected / private
来源：http://dali.gogol.net.cn/Article/details/gt2gfesnidg.html

Java: public / protected / private / 默认包级
来源：http://dali.birdmap.top/Article/details/gt2krqcumsa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aibaodan.cn/Article/details/gt2vsjtqmzc.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2rtvccorv.html

C#:   public / protected / private / internal
来源：http://dali.zhijiandao.cn/Article/details/gt2ehjnvcim.html

[G11] getter / setter
来源：http://dali.9152youxi.cn/Article/details/gt2xcyuzhnh.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gt2yibsyrjx.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xinyue.icu/Article/details/gt2tljkltoc.html

JS:   get name() { return this._name; }
来源：http://dali.gogol.net.cn/Article/details/gt2hadzupog.html

TS:   get name(): string { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2gnglrwdi.html

Java: public String getName() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2twuzndkf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zdqjudy.top/Article/details/gt2llpbtzpu.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2xeoouwjs.html

C#:   public string Name { get; set; }
来源：http://dali.yonumen.top/Article/details/gt2wrsnjkdf.html

[G12] 对象转字符串
来源：http://dali.gogol.net.cn/Article/details/gt2lpatviot.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2ujsijcvi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gt2hrvxdlau.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ymsglzfb.html

TS:   toString(): string { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2ankytwhj.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2ozvekfgu.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2jkhurdel.html

Ruby: def to_s; @name; end
来源：http://dali.hnxiangtu.top/Article/details/gt2gxojfmno.html

C#:   public override string ToString() => Name;
来源：http://dali.zycfv.cn/Article/details/gt2zdrodnil.html

[G13] 判断对象类型
来源：http://dali.jqgufenzy.top/Article/details/gt2ervqwzoz.html

Py:   isinstance(u, User)
来源：http://dali.tanke756.top/Article/details/gt2vumhecys.html

PHP:  $u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2fwhwzwxg.html

JS:   u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2otamdccf.html

TS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymeknxiq.html

Java: u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2ewpgwcgs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nwbrower.top/Article/details/gt2yysnuwoy.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqqctoeg.html

C#:   u is User
来源：http://dali.nanxuanxn.top/Article/details/gt2eqnqagpu.html

[G14] 数据类 / record
来源：http://dali.tanke756.top/Article/details/gt2ekqngwhj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gzhubu.top/Article/details/gt2glofiwbx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hywenlv.cn/Article/details/gt2ccweaiif.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgclllbh.html

TS:   type User = { name: string; age: number };
来源：http://dali.chenlongwang.top/Article/details/gt2yzfrlizm.html

Java: record User(String name, int age) {}
来源：http://dali.yongpay.top/Article/details/gt2fulmccrs.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ukyztugg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.snrcjt.cn/Article/details/gt2bsgepvah.html

C#:   record User(string Name, int Age);
来源：http://dali.shzxlz.cn/Article/details/gt2xivlfalc.html

[G15] 枚举
来源：http://dali.yonumen.top/Article/details/gt2dlwqxeqv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2tokhmiqv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guannengcc.top/Article/details/gt2ulsrjgyg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxinkj.top/Article/details/gt2ckievpta.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gt2sqhrmymc.html

Java: enum Color { RED, GREEN }
来源：http://dali.jianghu66.top/Article/details/gt2mnxgbxur.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxuanxn.top/Article/details/gt2ofcplkjt.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtvmxjnm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2yfpygxgg.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2oneeivpx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gt2kqhkdhpn.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gt2lkryxgfr.html

JS:   Object.entries(obj)
来源：http://dali.jinqigfzy.top/Article/details/gt2vpbngnos.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2qbvwxotx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qalauhir.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.vqdsnc.cn/Article/details/gt2pdptgjwo.html

Ruby: obj.instance_variables
来源：http://dali.jyoumei.cn/Article/details/gt2obqscgyt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.c1oappe.top/Article/details/gt2oaghzldw.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2zielwwqa.html

H. 异常与错误处理
来源：http://dali.hfpthk.cn/Article/details/gt2yclvuyqd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2bcezgwvu.html

[H01] try / catch 基础
来源：http://dali.c1oappe.top/Article/details/gt2icqbhern.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.cheryme.top/Article/details/gt2kpjgaibx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuxming.cn/Article/details/gt2uckjlhkb.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gt2zfqujurc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2zirzncki.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.tianlin.xyz/Article/details/gt2ghoxrbvd.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhixingplan.top/Article/details/gt2uumhhixf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2qxsfkucn.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenzaomai.com/Article/details/gt2kkowktjb.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2fjwzcbww.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2cyvbufpm.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daxiang520.top/Article/details/gt2pddfkugo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tathjzzj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2rxqcanlz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxuqiten.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xziqi.cn/Article/details/gt2xyhgufui.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hysaishi.cn/Article/details/gt2ikcjjhmc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2npgndmjd.html

[H03] 主动抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2ruguyhcs.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhongyouzk.top/Article/details/gt2diuapukx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xegmozef.html

JS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2qyvdcngr.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2zslvaqvl.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yongpay.top/Article/details/gt2ohipblic.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.dashuyun.cn/Article/details/gt2dbgmdqzd.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cbvofahv.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gt2palvfgrr.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gt2vhvqveeh.html

Py:   class MyError(Exception): pass
来源：http://dali.iojbl.cn/Article/details/gt2zrscwxxo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gt2wnzvosgy.html


<!-- 参考信息 -->