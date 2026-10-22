代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2mtrgpxyh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gt2qqmfjiol.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2tayjskpo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2kenheeyf.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gt2ndndbkoy.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hammf.cn/Article/details/gt2aeoxzhie.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2nrtnxqcg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2qxqpqsxt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.meibo888.top/Article/details/gt2itjpanmr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gotoacloud.top/Article/details/gt2anwclrbr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dianchejie.cn/Article/details/gt2cycyyvqs.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2qriysvve.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shzxlz.cn/Article/details/gt2akyxhrms.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqfxqwbk.html

F. 文件与目录
来源：http://dali.yj20258888.top/Article/details/gt2ryogibtm.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2uqhtezys.html

[F01] 读取整个文件
来源：http://dali.jqgfzy.top/Article/details/gt2ychtjacy.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2hnhjqxwr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2woakrfjf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.pycfn.com/Article/details/gt2kfbayrun.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpdhthif.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2ibfkynfs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gt2rbnulvzs.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2uhsibvds.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2myrtuplw.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2zymhziej.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2ganwoemv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xziqi.cn/Article/details/gt2ypyrwoai.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2okkyythd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yueranfly.top/Article/details/gt2ajkbfcen.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2xbnddomg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ycknsetk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2zgjqxvlc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ivvv.top/Article/details/gt2koxdzdzh.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2ilpfknwh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2dazgkegf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2gulmiksm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2bnoejqcv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2bxyperzq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.havefunace.top/Article/details/gt2qotwcidb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2rdpmjgzz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gt2dlydaklu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gt2vvbsgfdi.html

[F04] 追加写入文件
来源：http://dali.cdnleiting.top/Article/details/gt2qihzmtsz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2uwsiqjth.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zdqjudy.top/Article/details/gt2tktaityl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsifrlnh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysyzyixo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2rhtakmpo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gt2bqmdkefg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhoulong.xyz/Article/details/gt2dcnffzll.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2wfzgeczg.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2bqyfmbjc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gt2njdqzsqv.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2cdpnjijm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2totcljfh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2gxyrxbzg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2nvvqydsu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gt2rtwtcbkc.html

Ruby: File.exist?("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2zpplkljs.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2hftemvqm.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsirhhf.html

Py:   os.remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ofysdbfu.html

PHP:  unlink("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2jiicmaxb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2yvsfbpan.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2uqhgfokl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2qcifwrqw.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2jbnwhgse.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndlpbwly.html

C#:   File.Delete("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2nfjjoxef.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gt2jhkykmni.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gt2dlotrpmf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2shjiukma.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gt2llzwfzqc.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2dqkpfghl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.316326.xyz/Article/details/gt2wykghuhq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2iwkjuqgw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ppjwa.cn/Article/details/gt2hmuywwom.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gt2wzfcrkcn.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2znuaeivp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gt2pygcitet.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjzhbnbz.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2lzmwvlce.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2aivtihdc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2loakspbl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sweek.top/Article/details/gt2stjhghpo.html

Ruby: Dir.children("dir")
来源：http://dali.jqgfzy.top/Article/details/gt2znayquzn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2ketlgiih.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2ivdwkqmd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ritutldn.html

PHP:  filesize("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2uxkfalut.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2nkxmdkdz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gt2synbbwui.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gt2qltpgksd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2pmzqrmdf.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2wayxqxtf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gt2gpgirysw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ggljgvkr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2hwnxkxlr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2lfjszknw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2rbigbigk.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2rlyeyofz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jiagoushi.top/Article/details/gt2rjpizsgb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2xtaxtuwz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gt2yxlyaujj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2howrexhx.html

[F11] 复制与移动文件
来源：http://dali.gogol.net.cn/Article/details/gt2ktjofacq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2islebnzf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2joyuctsl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2dmelpghr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2lxslsaez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2llhdnfnc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ybcxt.top/Article/details/gt2bkfxxgat.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2bgtcqtyn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2yzjqjnwn.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2uwdgguzi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ivvv.top/Article/details/gt2nffghdrf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jiagoushi.top/Article/details/gt2jeheyhiq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gt2bcjjhoqa.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghjkssaj.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xylfe.cn/Article/details/gt2wjsknxnm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2upnoxvzd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zycfv.cn/Article/details/gt2plzvmhxl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2jqnydgua.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2lcoqzlgk.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gt2fteqiwxy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ahgthzsr.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gt2gklalknr.html

Py:   class User: pass
来源：http://dali.shuidangran.top/Article/details/gt2indmgdrn.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2ahpkhqbo.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2hujkgkcq.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yogfwqxm.html

Java: class User {}
来源：http://dali.haohaochexian.top/Article/details/gt2ancwwozk.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gt2vdfajovm.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gt2psdeiabz.html

C#:   class User {}
来源：http://dali.gogol.net.cn/Article/details/gt2ioydcgsz.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2gvvllala.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tian-w.cn/Article/details/gt2lklksuwv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gt2bbvtjkit.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gt2fflqwxkt.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ezssemvb.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ctekdozm.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gt2kmolylmk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gt2rqtbsjvl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gt2dpukzuus.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2cjlmyddw.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2rbqltfog.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2fbeungkx.html

JS:   this.name = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2sjhcdwxn.html

TS:   name: string = "x";
来源：http://dali.cucudq.cn/Article/details/gt2pvttbcbf.html

Java: private String name;
来源：http://dali.hnqzz.top/Article/details/gt2lylhmecf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.gogol.net.cn/Article/details/gt2ciustklj.html

Ruby: @name = "x"
来源：http://dali.yj202588.top/Article/details/gt2knotpbvd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ppjwa.cn/Article/details/gt2xxwxvgxn.html

[G04] 定义方法
来源：http://dali.bjfxy.top/Article/details/gt2phzgqzbb.html

Py:   def greet(self): return self.name
来源：http://dali.jiagoushi.top/Article/details/gt2wllotrxg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gt2rxeiuauf.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2odaxlqlx.html

TS:   greet(): string { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2jkmtenoa.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2mwpyftjl.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.guowangkeji.top/Article/details/gt2qvmnyjea.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2wdfgsacy.html

C#:   public string Greet() => Name;
来源：http://dali.redwolf501.top/Article/details/gt2pnxcgasl.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gt2qolvwpfk.html

Py:   class Admin(User): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2rttndfdn.html

PHP:  class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2zlqjkzku.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2plnomire.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2jukzvbvi.html

Java: class Admin extends User {}
来源：http://dali.cucudq.cn/Article/details/gt2suopvnnn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2rhwfwcfg.html

Ruby: class Admin < User; end
来源：http://dali.yongpay.top/Article/details/gt2sbemovbd.html

C#:   class Admin : User {}
来源：http://dali.haohaochexian.top/Article/details/gt2asnfwhpp.html

[G06] 重写方法
来源：http://dali.cqqwz.cn/Article/details/gt2kzcgxcim.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigufen.top/Article/details/gt2ugmeqhfg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2sxhooonr.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfhzzokj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2qaghzgum.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2ffcydtty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhixingplan.top/Article/details/gt2sbsxadga.html

Ruby: def greet; "admin"; end
来源：http://dali.havefunace.top/Article/details/gt2ctdcpsav.html

C#:   public override string Greet() => "admin";
来源：http://dali.jianghu66.top/Article/details/gt2jufsjnsq.html

[G07] 调用父类方法
来源：http://dali.hammf.cn/Article/details/gt2howwsnku.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2cadorqxg.html

PHP:  parent::greet();
来源：http://dali.hysaishi.cn/Article/details/gt2msjdksvq.html

JS:   super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2ptuiveqe.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2jcmgtssl.html

Java: super.greet();
来源：http://dali.sufxvd.cn/Article/details/gt2bwdjljww.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gt2qdwdfegx.html

Ruby: super
来源：http://dali.xuetiantiany.cn/Article/details/gt2mzmqlflq.html

C#:   base.Greet();
来源：http://dali.xinyue.icu/Article/details/gt2sjyvgqto.html

[G08] 静态方法与属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2neakfjts.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.c1oappe.top/Article/details/gt2jatfyhii.html

PHP:  public static function f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wfirvqas.html

JS:   static f() {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uotpedtm.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gt2zonqqdqz.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2vkwvslfa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.vqdsnc.cn/Article/details/gt2vpcpfpjs.html

Ruby: def self.f; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmatlpl.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gt2cieucfns.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gt2ldktvuyz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.snrcjt.cn/Article/details/gt2ppnyuass.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gt2jmksbeoy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.smart0.xyz/Article/details/gt2tlqlzebk.html

TS:   interface Shape { area(): number; }
来源：http://dali.tianlin.xyz/Article/details/gt2lipvymul.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2qhfkkpnl.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gt2qmrgusnk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gt2xpgjjthi.html

C#:   interface IShape { double Area(); }
来源：http://dali.snrcjt.cn/Article/details/gt2ycstusrm.html

[G10] 访问控制
来源：http://dali.tanke756.top/Article/details/gt2vbfhzzcv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwmsuf.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2dzoffkfr.html

JS:   #private 字段；其余公开
来源：http://dali.ydzc1.top/Article/details/gt2rlkqjsza.html

TS:   public / protected / private
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzzwnkgm.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2advfeuwl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2cgndzleh.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gt2lieufrqu.html

C#:   public / protected / private / internal
来源：http://dali.wangdashe.top/Article/details/gt2ijpjywwd.html

[G11] getter / setter
来源：http://dali.ydzc1.top/Article/details/gt2jauzvlfe.html

Py:   @property 与 @x.setter
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkitwcik.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yuxming.cn/Article/details/gt2ayaqzpgf.html

JS:   get name() { return this._name; }
来源：http://dali.daxiang520.top/Article/details/gt2dngeflsa.html

TS:   get name(): string { return this._name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2oyqshkqe.html

Java: public String getName() { return name; }
来源：http://dali.hammf.cn/Article/details/gt2opebuqwf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.haohaochexian.top/Article/details/gt2qxyuftph.html

Ruby: attr_accessor :name
来源：http://dali.jqgfzy.top/Article/details/gt2piamwqlo.html

C#:   public string Name { get; set; }
来源：http://dali.aibaodan.cn/Article/details/gt2bbovfomu.html

[G12] 对象转字符串
来源：http://dali.havefunace.top/Article/details/gt2hzdfunkt.html

Py:   def __str__(self): return self.name
来源：http://dali.zhongyouzk.top/Article/details/gt2evinjqet.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.snrcjt.cn/Article/details/gt2zhxzutsp.html

JS:   toString() { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2zvamzvep.html

TS:   toString(): string { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rlfsmysr.html

Java: @Override public String toString() { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2houqizeq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2dgjwflvy.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2cweolagq.html

C#:   public override string ToString() => Name;
来源：http://dali.jinqigufen.top/Article/details/gt2rlpcgxxq.html

[G13] 判断对象类型
来源：http://dali.jinqigfzy.top/Article/details/gt2odtibfjo.html

Py:   isinstance(u, User)
来源：http://dali.jinqigfzy.top/Article/details/gt2bqhmxsrd.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gt2bhxwaawj.html

JS:   u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2sewhgiuh.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2vfxohvcg.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2nqkdyofz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shuidangran.top/Article/details/gt2gqdsqshw.html

Ruby: u.is_a?(User)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prhddrkg.html

C#:   u is User
来源：http://dali.fzhhl.top/Article/details/gt2licpidgr.html

[G14] 数据类 / record
来源：http://dali.guowangkeji.top/Article/details/gt2gjdamedw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sweek.top/Article/details/gt2ngcdrzon.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sysykeji.top/Article/details/gt2vunwxsrm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gt2kvuleewt.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gt2lxeeypev.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2tspjwots.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenlongwang.top/Article/details/gt2gewwjolr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yvedp.cn/Article/details/gt2hndotfcb.html

C#:   record User(string Name, int Age);
来源：http://dali.aizwys.cn/Article/details/gt2cvnitmsi.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2kfzrcjux.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2zynmviyx.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jkyydaky.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2fcgmzgyd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.shuidangran.top/Article/details/gt2evcassgo.html

Java: enum Color { RED, GREEN }
来源：http://dali.zdqjudy.top/Article/details/gt2vlmgvvai.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.9152youxi.cn/Article/details/gt2wjwlttrf.html

Ruby: Color = %i[red green].freeze
来源：http://dali.haohaochexian.top/Article/details/gt2lofvibmv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuanzhike.top/Article/details/gt2sbvdwtxi.html

[G16] 对象转数组 / 字典
来源：http://dali.sweek.top/Article/details/gt2aoxlrbcl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinqigfzy.top/Article/details/gt2wjlqreki.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2hdptsjnh.html

JS:   Object.entries(obj)
来源：http://dali.xylfe.cn/Article/details/gt2pwyurcqj.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2lvtxgoct.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangdashe.top/Article/details/gt2tskcjkwp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2zrwejgoc.html

Ruby: obj.instance_variables
来源：http://dali.cashguo.top/Article/details/gt2whmavani.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2qxkhddnt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2dvcvujqg.html

H. 异常与错误处理
来源：http://dali.nanxuanxn.top/Article/details/gt2jsaktvnj.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2kbzedwpt.html

[H01] try / catch 基础
来源：http://dali.xylfe.cn/Article/details/gt2qqbzmzeh.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2anknlgyb.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2bonyldhv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2kfxbzqji.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2ukcopyug.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daria6918.cn/Article/details/gt2nhtmfzio.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2ktuoyzcs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aibaodan.cn/Article/details/gt2ahnctqly.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.fengsongda.top/Article/details/gt2uoarxuzt.html

[H02] finally / ensure 收尾
来源：http://dali.xylfe.cn/Article/details/gt2yxsjkwrr.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pycfn.com/Article/details/gt2kkhgqaqv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.wangdashe.top/Article/details/gt2hsqmkppy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2bvybggtv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yongpay.top/Article/details/gt2ywolyybp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gt2mzepmbyb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.andypj.xyz/Article/details/gt2ewxqqoie.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naqzhnhz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ymbsxcik.html

[H03] 主动抛出异常
来源：http://dali.dashuyun.cn/Article/details/gt2qizvncks.html

Py:   raise ValueError("错误信息")
来源：http://dali.hnxiangtu.top/Article/details/gt2toipmdbz.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2zvmnnkam.html

JS:   throw new Error("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2jufxsgba.html

TS:   throw new Error("错误信息");
来源：http://dali.aizwys.cn/Article/details/gt2knotunwa.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cashguo.top/Article/details/gt2txurnaiu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2jwecrzpw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbklslqy.html


<!-- 参考信息 -->