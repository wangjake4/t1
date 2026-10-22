代发 wailian999

Go:   if s == "" {}
来源：http://dali.yongpay.top/Article/details/gt2dfgjyyvh.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2kkrhjyav.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2sedlvffx.html

[E21] 超长截断加省略号
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjjzgheh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2hvpikbha.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkkxclxs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gt2syzbkbnq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2kuysxulz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpustmcr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhixingplan.top/Article/details/gt2qdzckwxr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2xrvbdyhu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2bmsyygfb.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2qepyclgv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yj20258888.top/Article/details/gt2pfgadntn.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gt2arwlkpwt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gt2kwpstadd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gt2ahveakib.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2slpfunta.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gt2jplxbtak.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2fsacmyjw.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hammf.cn/Article/details/gt2nonzcbux.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2osdxefhz.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2duqrrrlg.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2hvunmboy.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gt2omzydwgy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2gpkyalii.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2jqjytpdx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gt2nprmoyzz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnqzz.top/Article/details/gt2bucmhyyi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xxocnzgd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2zxihtmdr.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2oaydzbnf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2hdzxrfdv.html

[F02] 逐行读取文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykbnlfpt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zdqjudy.top/Article/details/gt2fqgrxfod.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gt2ofkpbycm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gt2gupzwjme.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etndvwvr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2ihqenmjl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mpqpcqdx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jianghu66.top/Article/details/gt2apqrtosd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ybcxt.top/Article/details/gt2byixdkxy.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2ibyihjsw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ydzc1.top/Article/details/gt2mlepnjnk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2qudvusgv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gt2hdcockzc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2bonngknn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.birdmap.top/Article/details/gt2jlueluqi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sweek.top/Article/details/gt2lragqzxi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gt2tqvjrjcq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2kjgzwjki.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gt2nijmduqs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjrxaivm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daria6918.cn/Article/details/gt2zezahrkj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2cqmneaek.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2kqlqdxod.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gt2qllbzhbo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2mseypukr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2afckdqah.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gt2jaerpoyu.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2xeghnujx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zwvbohio.html

PHP:  file_exists("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2ymwbxubo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2zcsvtfpc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2fplsxdsr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2prdfncyx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gt2ihirqrir.html

Ruby: File.exist?("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2nwnltyvv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2rzlkwqhj.html

[F06] 删除文件
来源：http://dali.yuxming.cn/Article/details/gt2pielcoqo.html

Py:   os.remove("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2jhjwtlcf.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gt2byipgnch.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2frzjuoko.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2tatptrhs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2gwqcqecd.html

Go:   os.Remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2dijvturt.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2dflthali.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2rqxgkorr.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2dtcvnouu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2rqdmadre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2vsuzepqu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2jxyozucn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2ygnrcuih.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2govjcutu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gt2vgzxzoou.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.0kj1m.cn/Article/details/gt2krmkrmex.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gt2badxphek.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gt2ljlgtxih.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2reveliem.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gt2umyrpwfp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2wvpsjrgk.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2mcjuhokm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2wuyhfkmy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.iojbl.cn/Article/details/gt2cigxivni.html

Ruby: Dir.children("dir")
来源：http://dali.ivvv.top/Article/details/gt2aogqsgvp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2jfmyhevm.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwkcatfd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2obqgxktq.html

PHP:  filesize("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2qgcnammi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2iofjqooj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgufenzy.top/Article/details/gt2zddhemcw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2ybajjaqa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2djwlaiof.html

Ruby: File.size("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2ojluizvx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.nanxinkj.top/Article/details/gt2tzusbvvp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gt2hbwefkki.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iljvjrip.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2pvdsrhqt.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2okcewxko.html

TS:   path.extname("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2vndnfjwb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jyoumei.cn/Article/details/gt2favbmpsk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bbdfglqn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2toswdlxj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xzdyvnlb.html

[F11] 复制与移动文件
来源：http://dali.meibo888.top/Article/details/gt2awlewkud.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2zshtyolh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2yzmftogy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2yfibhhte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2oqbrfboy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecvvsjeq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2adkfnazv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2jyvrwmsq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.tian-w.cn/Article/details/gt2xdpnfuwn.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gt2ducgsagg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuxming.cn/Article/details/gt2kwuucqar.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2oznabhzq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2gvniofbh.html

TS:   // 同上
来源：http://dali.iojbl.cn/Article/details/gt2rkojdhqg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2rfcypynt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.fengsongda.top/Article/details/gt2ksqftpsz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gt2tbnxkeou.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gt2mtfxppld.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2gtduovwv.html

G. 面向对象
来源：http://dali.jqgufenzy.top/Article/details/gt2dgxabswa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2slboxjjx.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gt2dpslfkko.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gt2inicqzxt.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gt2wfhbzlyf.html

JS:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2sysgzwjd.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2uagmqwns.html

Java: class User {}
来源：http://dali.xinyue.icu/Article/details/gt2hucefzsk.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qhwzvgpn.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2ewsewdpa.html

C#:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2oucaqwph.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2okpqxcfb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dashuyun.cn/Article/details/gt2jgkbwdyo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2imxyxaey.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2bhpipwjo.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gt2bmmvyuma.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2zwkouctd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gt2uprrovjl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.svipenyu.cn/Article/details/gt2sjjtmgro.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cqqwz.cn/Article/details/gt2gqfwxcvj.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2gpgoscit.html

Py:   self.name = "x"
来源：http://dali.hnxiangtu.top/Article/details/gt2lpxbsuiv.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2jiltrtej.html

JS:   this.name = "x";
来源：http://dali.yj20258.top/Article/details/gt2zblbulhf.html

TS:   name: string = "x";
来源：http://dali.nwbrower.top/Article/details/gt2tagcgylv.html

Java: private String name;
来源：http://dali.9152youxi.cn/Article/details/gt2cjqhxdwp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkyrcmht.html

Ruby: @name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2cydoizid.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2nkbquspg.html

[G04] 定义方法
来源：http://dali.jianghu66.top/Article/details/gt2jupxjxjg.html

Py:   def greet(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gt2hfqpdxqo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gt2diqwkvtm.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rvehcedq.html

TS:   greet(): string { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nnqsdath.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2dedoqhmi.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2hnjqrnnz.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2cqnbrnog.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2mjjmsqpw.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsbhldyu.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gt2qsjeiwhj.html

PHP:  class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2bcxknbaq.html

JS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2wzjgscqk.html

TS:   class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2wwmpqdhu.html

Java: class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2rjlgrped.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2tgyokifw.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2huvptjhx.html

C#:   class Admin : User {}
来源：http://dali.hnqzz.top/Article/details/gt2pgzluxcp.html

[G06] 重写方法
来源：http://dali.hammf.cn/Article/details/gt2eguxgpio.html

Py:   def greet(self): return "admin"
来源：http://dali.guowangkeji.top/Article/details/gt2hjqvrdti.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rkxodufu.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2dwcwjnug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2vxhnvcqq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gt2vilgezxm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gt2hhtokoge.html

Ruby: def greet; "admin"; end
来源：http://dali.cucudq.cn/Article/details/gt2kkuhmtxf.html

C#:   public override string Greet() => "admin";
来源：http://dali.pycfn.com/Article/details/gt2yougmgzd.html

[G07] 调用父类方法
来源：http://dali.yongpay.top/Article/details/gt2hjudegii.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2dfwjhmbz.html

PHP:  parent::greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmxxvacf.html

JS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2embukgqk.html

TS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puxvlkaw.html

Java: super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2ebwjecvj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.9152youxi.cn/Article/details/gt2xkqoteyq.html

Ruby: super
来源：http://dali.tianlin.xyz/Article/details/gt2xrqdaphc.html

C#:   base.Greet();
来源：http://dali.birdmap.top/Article/details/gt2loualmre.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gt2mdujtwgc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2tgnowmfq.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gt2rlwozjfp.html

JS:   static f() {}
来源：http://dali.yueranfly.top/Article/details/gt2nlsmekgc.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2uofaczyr.html

Java: static void f() {}
来源：http://dali.daxiang520.top/Article/details/gt2wigkkjdg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfrmkwuv.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gt2zddbpiop.html

C#:   public static void F() {}
来源：http://dali.yongpay.top/Article/details/gt2npmcntrh.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2xysdmrjq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.pengpengdd.cyou/Article/details/gt2msubbmww.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crxxfkpj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ybcxt.top/Article/details/gt2qecialtv.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gt2jvbxghxf.html

Java: interface Shape { double area(); }
来源：http://dali.havefunace.top/Article/details/gt2gknbhnoo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.birdmap.top/Article/details/gt2mwtzzxfx.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yj20258.top/Article/details/gt2uriwdpfs.html

C#:   interface IShape { double Area(); }
来源：http://dali.jianghu66.top/Article/details/gt2pbfroozh.html

[G10] 访问控制
来源：http://dali.zhijiandao.cn/Article/details/gt2stszwezb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj20258888.top/Article/details/gt2nvapbzru.html

PHP:  public / protected / private
来源：http://dali.vqdsnc.cn/Article/details/gt2khwowszz.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gt2hipyujql.html

TS:   public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2kjnzzexv.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258.top/Article/details/gt2upzzqyth.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuetiantiany.cn/Article/details/gt2jtxfvome.html

Ruby: public / protected / private
来源：http://dali.svipenyu.cn/Article/details/gt2tekcaedv.html

C#:   public / protected / private / internal
来源：http://dali.snrcjt.cn/Article/details/gt2lihogxrm.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gt2acjbjxxl.html

Py:   @property 与 @x.setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnjkrsiq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2aqsmlpun.html

JS:   get name() { return this._name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2hzahqook.html

TS:   get name(): string { return this._name; }
来源：http://dali.yangfankeji.com/Article/details/gt2kiagfvil.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gt2uinivlbl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.shangyingyoupin.top/Article/details/gt2limywvul.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2vujihrgz.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bfpghxfw.html

[G12] 对象转字符串
来源：http://dali.hysaishi.cn/Article/details/gt2fbigrsgk.html

Py:   def __str__(self): return self.name
来源：http://dali.hfpthk.cn/Article/details/gt2pchgylxk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2zaysnshz.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2snjmxiue.html

TS:   toString(): string { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gt2mpsffqaf.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2tsaymmir.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2wyhxnfbe.html

Ruby: def to_s; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2skmsacoi.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gt2jqictdyo.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gt2rvaclefr.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gt2ruilzsbe.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2gshbrkpy.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2yztkcbjz.html

TS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqwijzt.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2fjjtlqgv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nohlatei.html

Ruby: u.is_a?(User)
来源：http://dali.cheryme.top/Article/details/gt2tyhafmdq.html

C#:   u is User
来源：http://dali.316326.xyz/Article/details/gt2vrroezyx.html

[G14] 数据类 / record
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kovubgxg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.zhijiandao.cn/Article/details/gt2rypqbziy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzbxzhvq.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2tghzagqu.html

TS:   type User = { name: string; age: number };
来源：http://dali.svipenyu.cn/Article/details/gt2nrzbymrp.html

Java: record User(String name, int age) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2dumotkfw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.0kj1m.cn/Article/details/gt2lioojkxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvdclwof.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gt2cqsqybhg.html

[G15] 枚举
来源：http://dali.chenlongwang.top/Article/details/gt2cnxijvle.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2jtprrfet.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2kboyfrkq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gt2rhdycati.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2cwsrbytr.html

Java: enum Color { RED, GREEN }
来源：http://dali.quarkkingdee.top/Article/details/gt2nkgajjfs.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bowzgyiz.html

Ruby: Color = %i[red green].freeze
来源：http://dali.smart0.xyz/Article/details/gt2fradxuiv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2qknapeag.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gt2uaoppchd.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yangfankeji.com/Article/details/gt2opjzvvjr.html

PHP:  get_object_vars($obj);
来源：http://dali.yuxming.cn/Article/details/gt2wjrjecci.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2offrnlak.html

TS:   Object.entries(obj)
来源：http://dali.zhijiandao.cn/Article/details/gt2akqpgmlw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bsuifvlc.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2xnafneke.html

Ruby: obj.instance_variables
来源：http://dali.haohaochexian.top/Article/details/gt2wsshqkqa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxujewp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2qyxrdrci.html

H. 异常与错误处理
来源：http://dali.haohaochexian.top/Article/details/gt2ijwrgwdw.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2kvrfinpw.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2tjpkztox.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.gotoacloud.top/Article/details/gt2ircpnhnl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tanke756.top/Article/details/gt2qhmjfqnx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gt2ymfeyxni.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gt2zzbefdab.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nsebfmcp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gt2gsiweebs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.svipenyu.cn/Article/details/gt2loarxdhu.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yj20258888.top/Article/details/gt2izusurio.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gt2uzpqbzqb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcmvitru.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2qfjkotyi.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ehwqpu.com/Article/details/gt2zscyvvxa.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2wdvalvji.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gt2xpquepmt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yonumen.top/Article/details/gt2wixwjaeb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2pcetepuh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eexvxzph.html


<!-- 参考信息 -->