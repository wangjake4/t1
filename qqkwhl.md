代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2fsxlolvj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bchuybyx.html

F. 文件与目录
来源：http://dali.guannengcc.top/Article/details/gt2hunnmdbz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2heekdwwl.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2zqhdmovw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gt2llsneiiu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2uccbuibm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gt2wseqdyon.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ppjwa.cn/Article/details/gt2mhlhpnyc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2jjsznwgb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.meibo888.top/Article/details/gt2zsasajck.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2wwnrjbib.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ymsnlibr.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gt2cahnplbc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.guannengcc.top/Article/details/gt2tksqxcre.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sxryk.cn/Article/details/gt2erzgcynb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gt2wftmdxoc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kyvxyqyp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2ppndsdop.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aibaodan.cn/Article/details/gt2kyqwduqm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kugcnsbq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gt2qispcqod.html

[F03] 写入文件（覆盖）
来源：http://dali.jqgfzy.top/Article/details/gt2zigpvrvk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bksoqhnp.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dianchejie.cn/Article/details/gt2hoxlbkwr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2kxfpxucc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gt2xspzsljz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nyaagpdy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gt2alnmuhqf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2jsklwesm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2rkswneoy.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2vvejjebt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wgqmvmiq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gt2yfikiren.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gt2arqqxuac.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gt2oqsyscrg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.nanxinkj.top/Article/details/gt2xlmftxnt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sweek.top/Article/details/gt2uozzpypi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhongyouzk.top/Article/details/gt2bveubpkc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.andypj.xyz/Article/details/gt2ngnedseu.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gt2sihdkqtt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xuanzx.com/Article/details/gt2jbwhqfnu.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2muywkhxa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvrkvflw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2ncfzcvok.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2ukuidcuq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rotjvfbt.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2wmnsncls.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2gahayrwx.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2nehlatoo.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2wtukaeww.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2bdniibcg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2sfacergz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uoucpdat.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2kgxaasco.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2rkgxdlqi.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2abohbuyr.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2rpewqjel.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gt2edtsvpgi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gt2djmvysef.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgufenzy.top/Article/details/gt2xhvjgcei.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2sfgrjcfx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2iemhixph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2zgelhjbj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gt2zktlffde.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2zlfwbbrv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnxiangtu.top/Article/details/gt2aarifyzq.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gt2ljdkbwpm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gt2plfddiie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shzxlz.cn/Article/details/gt2oupzahzk.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2idsubjlx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gt2diugnyyj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.fzhhl.top/Article/details/gt2fisexptr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2majozrtb.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2juzlthsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gaohongyu789.top/Article/details/gt2xtpldnwm.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gt2zoiafuie.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2trpatweu.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2izijagmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2obpwthaw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gt2urjjatxs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2gnbezsmp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhengqikj.top/Article/details/gt2mhqctaja.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2hrsdxlmy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfhgerjd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2olomlhas.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2dyxljdig.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2fvthqwvh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2bejdqvzg.html

TS:   path.extname("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncrgtbim.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.smart0.xyz/Article/details/gt2epkqergn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqazesmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2zjumuoie.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2nylaaqpg.html

[F11] 复制与移动文件
来源：http://dali.ydzc1.top/Article/details/gt2uvyubswj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jbaovoqj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odwdyuyv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gt2grszhxuj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfzdybmy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2gibduewo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gt2qqpfqpfc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gt2fkskyrsu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2dfsmtzqe.html

[F12] CSV 读写
来源：http://dali.jianghu66.top/Article/details/gt2kpuxgtye.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yueranfly.top/Article/details/gt2rbwgkhkt.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.chenzaomai.com/Article/details/gt2tdfheyrd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gt2ycfhwkqz.html

TS:   // 同上
来源：http://dali.hnqzz.top/Article/details/gt2olmfvrlc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tanke756.top/Article/details/gt2vaoizfre.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gt2bdzquuez.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gt2qeryupja.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tanke756.top/Article/details/gt2aflppbbc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2cdlpaoxa.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2luvimxxe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hsdnzztg.html

[G01] 定义类
来源：http://dali.feifeiyinyue.top/Article/details/gt2bivgctdc.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gt2msgmhkqm.html

PHP:  class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2miateate.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2pabednwd.html

TS:   class User { name: string = ""; }
来源：http://dali.havefunace.top/Article/details/gt2gynwxfxf.html

Java: class User {}
来源：http://dali.yvedp.cn/Article/details/gt2fdylaosa.html

Go:   type User struct { Name string }
来源：http://dali.zhixingplan.top/Article/details/gt2hmryngnu.html

Ruby: class User; end
来源：http://dali.jqgfzy.top/Article/details/gt2qxhbnyts.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2lfyzfqea.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2xwcjcaij.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258888.top/Article/details/gt2ppkhuhto.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sufxvd.cn/Article/details/gt2mkeixyge.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gt2ssfvrxrt.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2dtenbboa.html

Java: User(String name) { this.name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2uzyrssao.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2mxjkymlg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gt2twzxbbfp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2jvguvhna.html

[G03] 实例属性
来源：http://dali.iojbl.cn/Article/details/gt2bcckqvkb.html

Py:   self.name = "x"
来源：http://dali.jqgfzy.top/Article/details/gt2ovgexqlx.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gt2zjcxdmdg.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2gfcnagnv.html

TS:   name: string = "x";
来源：http://dali.jianghu66.top/Article/details/gt2fykwaixe.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gt2rznpmqty.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzyqnokn.html

Ruby: @name = "x"
来源：http://dali.yj20258.top/Article/details/gt2avzprltk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.wangdashe.top/Article/details/gt2pnzolqzl.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2lgxkrkuj.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2yomwgfnj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2ufmtgwch.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xplvuzve.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gt2mikdgpao.html

Java: String greet() { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dzzenslg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2tdqzkpei.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2trbdumxa.html

C#:   public string Greet() => Name;
来源：http://dali.tanke756.top/Article/details/gt2yntsqxya.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gt2laxmdlqw.html

Py:   class Admin(User): pass
来源：http://dali.dianchejie.cn/Article/details/gt2znjuqhka.html

PHP:  class Admin extends User {}
来源：http://dali.ybcxt.top/Article/details/gt2phovjjpk.html

JS:   class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wofgzaet.html

TS:   class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2kchuwrot.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2btnqveor.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gotoacloud.top/Article/details/gt2gxpmbqau.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gt2qknklhxq.html

C#:   class Admin : User {}
来源：http://dali.birdmap.top/Article/details/gt2potuffuc.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gt2hiqfqgpt.html

Py:   def greet(self): return "admin"
来源：http://dali.hongshengwenyu.top/Article/details/gt2bjlqmgrl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gt2xzveqxbq.html

JS:   greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2zkwlract.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gt2wewmfymx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbogxfrc.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.9152youxi.cn/Article/details/gt2vjsmzzqw.html

Ruby: def greet; "admin"; end
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvfmymq.html

C#:   public override string Greet() => "admin";
来源：http://dali.kuanghao11.cn/Article/details/gt2kadviynv.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gt2hdjjvxgc.html

Py:   super().greet()
来源：http://dali.gotoacloud.top/Article/details/gt2iutwnukt.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2rqotspll.html

JS:   super.greet();
来源：http://dali.bjfxy.top/Article/details/gt2joqdmdav.html

TS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2cdujlwar.html

Java: super.greet();
来源：http://dali.hnqzz.top/Article/details/gt2suhgwykm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.aibaodan.cn/Article/details/gt2noyovrxe.html

Ruby: super
来源：http://dali.feifeiyinyue.top/Article/details/gt2unluogjd.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gt2eenytpci.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2rekpmoqp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhengqikj.top/Article/details/gt2kacrpfyi.html

PHP:  public static function f() {}
来源：http://dali.yj20258888.top/Article/details/gt2wrmtcwle.html

JS:   static f() {}
来源：http://dali.iojbl.cn/Article/details/gt2tixqijhu.html

TS:   static f(): void {}
来源：http://dali.yj20258888.top/Article/details/gt2cglvkebr.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2xlqlspxu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gt2rkkaivrl.html

Ruby: def self.f; end
来源：http://dali.sysykeji.top/Article/details/gt2yrpwlpni.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2yzljodix.html

[G09] 接口 / 抽象类
来源：http://dali.jianghu66.top/Article/details/gt2ovdepune.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2hzkbbutq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenzaomai.com/Article/details/gt2khuxlycg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2oshvxjgf.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gt2vxdlqwwa.html

Java: interface Shape { double area(); }
来源：http://dali.xziqi.cn/Article/details/gt2exkszdnj.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.tanke756.top/Article/details/gt2ogcjjeaz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2lofwtoac.html

C#:   interface IShape { double Area(); }
来源：http://dali.yj20258.top/Article/details/gt2eklxxqxh.html

[G10] 访问控制
来源：http://dali.yuxming.cn/Article/details/gt2jecrvfyh.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.kuanghao11.cn/Article/details/gt2zzseiqsa.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2yhgoqpsh.html

JS:   #private 字段；其余公开
来源：http://dali.jqgufenzy.top/Article/details/gt2wwdokpml.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gt2pqbptadx.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gt2oglauuwu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yangfankeji.com/Article/details/gt2jbaqnazm.html

Ruby: public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2fkambqcp.html

C#:   public / protected / private / internal
来源：http://dali.jianghu66.top/Article/details/gt2nrsbgmbp.html

[G11] getter / setter
来源：http://dali.nwbrower.top/Article/details/gt2owcawxed.html

Py:   @property 与 @x.setter
来源：http://dali.cqqwz.cn/Article/details/gt2uvjobqdd.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xrssqupv.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eljefdwl.html

TS:   get name(): string { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pzsogwgq.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2vxhtmrro.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.zhixingplan.top/Article/details/gt2htsybdzg.html

Ruby: attr_accessor :name
来源：http://dali.birdmap.top/Article/details/gt2scpdxtxr.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gpekidtk.html

[G12] 对象转字符串
来源：http://dali.jyoumei.cn/Article/details/gt2sbndoorh.html

Py:   def __str__(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2jqsqtase.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2gbrkfwmf.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cizchrzt.html

TS:   toString(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2sofcrxux.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gt2puiqseuf.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gt2ndvwpcsn.html

Ruby: def to_s; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdyxjqah.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2txevxbca.html

[G13] 判断对象类型
来源：http://dali.jlsjyb.cn/Article/details/gt2fbcxstae.html

Py:   isinstance(u, User)
来源：http://dali.jqgfzy.top/Article/details/gt2vmtlpcnl.html

PHP:  $u instanceof User
来源：http://dali.cdnleiting.top/Article/details/gt2bkffazid.html

JS:   u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2wltmqmsv.html

TS:   u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2jmzyzebs.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gt2pnaumocf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gt2bolwpvfv.html

Ruby: u.is_a?(User)
来源：http://dali.quarkkingdee.top/Article/details/gt2atqdvgwc.html

C#:   u is User
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnwjcrnk.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2bbevqhki.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.fengsongda.top/Article/details/gt2mvjirnau.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gt2vzdbrxqn.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj202588.top/Article/details/gt2wejrznhp.html

TS:   type User = { name: string; age: number };
来源：http://dali.316326.xyz/Article/details/gt2btrjahmb.html

Java: record User(String name, int age) {}
来源：http://dali.yj20258.top/Article/details/gt2qmbrvnyi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.c1oappe.top/Article/details/gt2cuiqbzgx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jlsjyb.cn/Article/details/gt2icjjmknz.html

C#:   record User(string Name, int Age);
来源：http://dali.jiagoushi.top/Article/details/gt2itukjntb.html

[G15] 枚举
来源：http://dali.hnxiangtu.top/Article/details/gt2rphthnzx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2wfzycsaq.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sweek.top/Article/details/gt2rjwgktzf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gaohongyu789.top/Article/details/gt2kosqwimo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxdwccf.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2ltcgnymy.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rljvorvw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.tian-w.cn/Article/details/gt2jjholwed.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2vqqrdbgb.html

[G16] 对象转数组 / 字典
来源：http://dali.guannengcc.top/Article/details/gt2jxfztjqq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenlongwang.top/Article/details/gt2ztjewcep.html

PHP:  get_object_vars($obj);
来源：http://dali.ehwqpu.com/Article/details/gt2cncyjjpx.html

JS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2wmthyqxw.html

TS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2fnqiribr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.nwbrower.top/Article/details/gt2kftzjlja.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yj20258888.top/Article/details/gt2ltryuluk.html

Ruby: obj.instance_variables
来源：http://dali.cucudq.cn/Article/details/gt2tzzaexje.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zycfv.cn/Article/details/gt2gwpvyynf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ehvyiluo.html

H. 异常与错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2tsoeyrdm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2clppgkxh.html

[H01] try / catch 基础
来源：http://dali.zhengqikj.top/Article/details/gt2rnmtremf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.iojbl.cn/Article/details/gt2akninfkb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2zwhiiqqa.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yonumen.top/Article/details/gt2ulzpwsok.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhytjqjv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2ovjofxgy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2eftghhsk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.gzhubu.top/Article/details/gt2llvhjkmu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gotoacloud.top/Article/details/gt2guhbuflo.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2rxbattkt.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.vqdsnc.cn/Article/details/gt2kzqlxucp.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hdmzdriq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.haohaochexian.top/Article/details/gt2enknlfhd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2difetlml.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gt2vroomuhc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.pycfn.com/Article/details/gt2gzcezsqq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mdzewgvq.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2lmfhmgrj.html

[H03] 主动抛出异常
来源：http://dali.xuanzx.com/Article/details/gt2sphidwcv.html

Py:   raise ValueError("错误信息")
来源：http://dali.yangfankeji.com/Article/details/gt2jvzcqiwd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fxenpwlr.html

JS:   throw new Error("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyimcmgj.html

TS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ydydkujb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2oqwhalbr.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xcfpwbme.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2tdycmsxz.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2zoxelili.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2hslonkgx.html

Py:   class MyError(Exception): pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2duxlulal.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.birdmap.top/Article/details/gt2mdirparn.html

JS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gt2cdfrokpi.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2jtjkyuwf.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gt2sxbunrpx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.xuanzx.com/Article/details/gt2vmausivl.html

Ruby: class MyError < StandardError; end
来源：http://dali.wangdashe.top/Article/details/gt2krmqlrnx.html

C#:   class MyException : Exception {}
来源：http://dali.zhongyouzk.top/Article/details/gt2cowaodkp.html

[H05] 捕获特定类型
来源：http://dali.iojbl.cn/Article/details/gt2tkarhbxd.html

Py:   except ValueError as e:
来源：http://dali.gogol.net.cn/Article/details/gt2bjdusoun.html


<!-- 参考信息 -->