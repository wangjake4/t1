代发 wailian999

[F01] 读取整个文件
来源：http://dali.jianghu66.top/Article/details/gt2usaywodr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2qzewopuo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2pwjvvhio.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2kkscphbi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2wsyjtfoa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2oedglbhe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnxiangtu.top/Article/details/gt2vyugquwp.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2unggqakr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2xcavlwbd.html

[F02] 逐行读取文件
来源：http://dali.sweek.top/Article/details/gt2pmmcwpqf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqtbkeij.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gt2jnfkyupr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gt2hlustmcc.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2dqmcicfm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.aizwys.cn/Article/details/gt2kuybnzni.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2khciftmv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgufenzy.top/Article/details/gt2ddwlaoxk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gt2ltqagznk.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2viyeself.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgekatoq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2hlnkbyrl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2jgxnbxez.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2cioqepvd.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2uqutubck.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2fdfbawty.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2awtbtard.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gt2gczilfrr.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gt2omekdcdv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ozlcmsqr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulrpsewj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2iqtdpnal.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2jwvbvgfp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ivvv.top/Article/details/gt2uvdcfyud.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2ighuotjx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2bynlmpub.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gt2udzfvwyb.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gt2uexozsrb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2nybnawxd.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2ciujtkrz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2sczcbszo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2mlzslhyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2lbdwysfy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ikqijhcr.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2jockobcr.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2lotibtcg.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gt2fctxhswb.html

Py:   os.remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2qzjtsghi.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2jxkymqqb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ttzbhzfx.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2svminbht.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2gklqlepi.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2gzsktwog.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2bnuxzxmw.html

C#:   File.Delete("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfufppwl.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2ihaxyqes.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2ubgezyqb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2airtgyty.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2qmbntbam.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2ftcmeflp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2qpovwxhn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jiagoushi.top/Article/details/gt2ztxjyfrm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2baoupjsc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gt2dricvbvi.html

[F08] 遍历目录
来源：http://dali.ppjwa.cn/Article/details/gt2lxktkzch.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gt2vkecdnam.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2zptgcrkq.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2virleztx.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2ehowarhn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhongyouzk.top/Article/details/gt2vwzggznn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2vqnrtbtp.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2junvtank.html

C#:   Directory.GetFiles("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gt2duyxpvcl.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2rcqweaac.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2jdpbklgd.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhhifvpz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2qrbpxmdd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2sjszgkgi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gt2pkyxawkd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gt2qrswudgd.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2rpgsddpd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmknlmwb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yanxiufei.cn/Article/details/gt2pujvlema.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtucsxuv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2gmjanslb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2wbdhuvlw.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2nxxuzyze.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuanzx.com/Article/details/gt2uqkqdwgv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2qqlayxqo.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2uwxeynlm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2qsqizhvm.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2ejriykon.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gt2rdarzrbe.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gzhubu.top/Article/details/gt2awcqcuqy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shuidangran.top/Article/details/gt2gqydhyyk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ytgvtagy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gt2nwlpleqs.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gt2intfbqrq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2iryuqhjj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nuwrcrfv.html

[F12] CSV 读写
来源：http://dali.yangfankeji.com/Article/details/gt2hhanoitl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gt2mibtiqjg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpiwcpsy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jqgufenzy.top/Article/details/gt2ldgvkags.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gt2nkjcyhan.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2redsrvbl.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenlongwang.top/Article/details/gt2pglydcbh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yj20258888.top/Article/details/gt2fiojajjc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tianlin.xyz/Article/details/gt2zuukkpqo.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2zdfcqtic.html

G. 面向对象
来源：http://dali.shangyingyoupin.top/Article/details/gt2flxnkeze.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2qwqtwnmo.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2lryvbibr.html

Py:   class User: pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcqdtxrx.html

PHP:  class User {}
来源：http://dali.bjfxy.top/Article/details/gt2apjcdmjv.html

JS:   class User {}
来源：http://dali.pycfn.com/Article/details/gt2dvjlhlnm.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ludzxnbr.html

Java: class User {}
来源：http://dali.sysykeji.top/Article/details/gt2edwmkwns.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2laezppar.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2zcxqkyiz.html

C#:   class User {}
来源：http://dali.redwolf501.top/Article/details/gt2frjgrzey.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2opprqblg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2wzpoeoxg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.316326.xyz/Article/details/gt2bsgcfegv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2xmzypbtr.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2whluohzv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2rxjuqwvs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gt2qbsocahj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yangfankeji.com/Article/details/gt2dibxydds.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zycfv.cn/Article/details/gt2xhxstofy.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2pbvwoyyq.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2zzxwmsbv.html

PHP:  public string $name = "x";
来源：http://dali.vqdsnc.cn/Article/details/gt2rujodfkg.html

JS:   this.name = "x";
来源：http://dali.cashguo.top/Article/details/gt2vewhllfq.html

TS:   name: string = "x";
来源：http://dali.smart0.xyz/Article/details/gt2luujautc.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gt2jmzzjapx.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihxtpkfz.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2feupcmib.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2wztxjrdu.html

[G04] 定义方法
来源：http://dali.xziqi.cn/Article/details/gt2imjbnvae.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2kzpenfgj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wiifksuq.html

JS:   greet() { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tgqyousq.html

TS:   greet(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2lkscukbv.html

Java: String greet() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2bwtfdupq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gt2zjmhqpdi.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2iztvobdn.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2ahgiadop.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gt2unntzfyn.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2rwmzprdl.html

PHP:  class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tbsgcgqg.html

JS:   class Admin extends User {}
来源：http://dali.hywenlv.cn/Article/details/gt2haoyedmn.html

TS:   class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gt2jcctwejb.html

Java: class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gt2fmfvevna.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gt2gmqunwse.html

Ruby: class Admin < User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqyapdbe.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gt2ocnfdjcj.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2htmemdnj.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2tmwegnad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2vxizlmbv.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2ozzcboau.html

TS:   greet(): string { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2qetuyycy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gt2omzximon.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.mhx1999.top/Article/details/gt2fccfxacl.html

Ruby: def greet; "admin"; end
来源：http://dali.meibo888.top/Article/details/gt2gvxxpqyy.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gt2iadedqbj.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2vngzwjvp.html

Py:   super().greet()
来源：http://dali.jinqigfzy.top/Article/details/gt2fmwguijv.html

PHP:  parent::greet();
来源：http://dali.sysykeji.top/Article/details/gt2vmlfxvbn.html

JS:   super.greet();
来源：http://dali.xziqi.cn/Article/details/gt2ugetmzrq.html

TS:   super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2hkikphpe.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2vllrbaou.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gzhubu.top/Article/details/gt2wrjbtnfg.html

Ruby: super
来源：http://dali.0kj1m.cn/Article/details/gt2fafecbew.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2oimiywgn.html

[G08] 静态方法与属性
来源：http://dali.zycfv.cn/Article/details/gt2mfgusres.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.guowangkeji.top/Article/details/gt2lhdsrver.html

PHP:  public static function f() {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jfypeuzc.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2tgxdcalm.html

TS:   static f(): void {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qfoykexs.html

Java: static void f() {}
来源：http://dali.yj20258.top/Article/details/gt2ndrzgprb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.tanke756.top/Article/details/gt2hloaknrw.html

Ruby: def self.f; end
来源：http://dali.redwolf501.top/Article/details/gt2vuflgdws.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gt2dhhxdzab.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ecjtjabo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.aizwys.cn/Article/details/gt2xoubsbhf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gt2ebfbqawj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2pzlxeixu.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2rzqtcgzl.html

Java: interface Shape { double area(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rqdhxjti.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daria6918.cn/Article/details/gt2fhxdidit.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gt2fgkznabw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gt2mirtqrid.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gt2ttpebvjk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cashguo.top/Article/details/gt2dezccpia.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gt2rbmhxqax.html

JS:   #private 字段；其余公开
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2etvvehku.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2hgfejjjm.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gt2npbkvrip.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.fengsongda.top/Article/details/gt2jhipgveq.html

Ruby: public / protected / private
来源：http://dali.iojbl.cn/Article/details/gt2tmkeyfsh.html

C#:   public / protected / private / internal
来源：http://dali.svipenyu.cn/Article/details/gt2yuwqujol.html

[G11] getter / setter
来源：http://dali.xuanzx.com/Article/details/gt2lceecwgo.html

Py:   @property 与 @x.setter
来源：http://dali.sufxvd.cn/Article/details/gt2eqslhdqq.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gt2fgvnpwqu.html

JS:   get name() { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2tkdxbfnb.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ftkizodi.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gt2xtzqgtxj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sxryk.cn/Article/details/gt2dcekhgqj.html

Ruby: attr_accessor :name
来源：http://dali.bjfxy.top/Article/details/gt2dgbxwshw.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocmbeves.html

[G12] 对象转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2nntplalh.html

Py:   def __str__(self): return self.name
来源：http://dali.yvedp.cn/Article/details/gt2waqjdeak.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gt2seqnjyac.html

JS:   toString() { return this.name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vlunrohx.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zplskfvf.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2bdujvnna.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gt2eudhwqfv.html

Ruby: def to_s; @name; end
来源：http://dali.quarkkingdee.top/Article/details/gt2ykhkuzgh.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gt2muleoglr.html

[G13] 判断对象类型
来源：http://dali.shzxlz.cn/Article/details/gt2ipryikyu.html

Py:   isinstance(u, User)
来源：http://dali.zhengqikj.top/Article/details/gt2tbsmvcii.html

PHP:  $u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2ayhbzqfr.html

JS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gt2pvgkpwmo.html

TS:   u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2hodayghz.html

Java: u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2jhfcqetp.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yj20258.top/Article/details/gt2qvxqmiic.html

Ruby: u.is_a?(User)
来源：http://dali.aibaodan.cn/Article/details/gt2bksiwnbv.html

C#:   u is User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrcsarnb.html

[G14] 数据类 / record
来源：http://dali.aizwys.cn/Article/details/gt2zovfuudd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2zquhsivd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yueranfly.top/Article/details/gt2zlpervrp.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.iojbl.cn/Article/details/gt2sjqkewke.html

TS:   type User = { name: string; age: number };
来源：http://dali.feifeiyinyue.top/Article/details/gt2xeslzhil.html

Java: record User(String name, int age) {}
来源：http://dali.gzhubu.top/Article/details/gt2bnzmwzej.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxinkj.top/Article/details/gt2dsgeixaq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.mhx1999.top/Article/details/gt2qgexylsm.html

C#:   record User(string Name, int Age);
来源：http://dali.meibo888.top/Article/details/gt2rjzsnggv.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2obhloopj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.dashuyun.cn/Article/details/gt2fhjccude.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gt2sjihdqvx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ydzc1.top/Article/details/gt2hgoyfkqw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2xqjqgmbl.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiqjwuzi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yangfankeji.com/Article/details/gt2aznakgie.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2smzggwyp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ivvv.top/Article/details/gt2dbrkddrm.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gt2lzqmppnw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2tsncgmbv.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gt2rhqsihhk.html

JS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcocfybe.html

TS:   Object.entries(obj)
来源：http://dali.xuanzx.com/Article/details/gt2repmqnpw.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yangfankeji.com/Article/details/gt2ukwhadmp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yuanzhike.top/Article/details/gt2xdwqxank.html

Ruby: obj.instance_variables
来源：http://dali.fengsongda.top/Article/details/gt2tgpqfswm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2wdloptjk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqidkgci.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gt2qnxsbroe.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2miuspqmp.html

[H01] try / catch 基础
来源：http://dali.vqdsnc.cn/Article/details/gt2aeaxgync.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2dcbgqgfz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gt2hknlmfdo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2xbsfkayq.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2fqlozzje.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhixingplan.top/Article/details/gt2cdkoalbr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nwbrower.top/Article/details/gt2ryjdinls.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxinkj.top/Article/details/gt2mipxfvfl.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gt2kdspjkwg.html

[H02] finally / ensure 收尾
来源：http://dali.havefunace.top/Article/details/gt2ltapggoz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2alfjbyft.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2oxgvotgr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cheryme.top/Article/details/gt2yunkgdoe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2lcjqpkvs.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2qfbaalru.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bimktigy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuanzx.com/Article/details/gt2xfbbforj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gt2grugjayf.html

[H03] 主动抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gt2zniyedbw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hysaishi.cn/Article/details/gt2ihqzytzv.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lboctiwb.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2fdvokxei.html

TS:   throw new Error("错误信息");
来源：http://dali.zycfv.cn/Article/details/gt2fzifwmvt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.cdnleiting.top/Article/details/gt2xcnbkabl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.xinyue.icu/Article/details/gt2czciuedk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gt2kavvxolm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gt2lfrdjrhd.html

[H04] 自定义异常类型
来源：http://dali.cashguo.top/Article/details/gt2hnfgbxtn.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2mdpqdapn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqufwphl.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gt2hptamujj.html

TS:   class MyError extends Error {}
来源：http://dali.redwolf501.top/Article/details/gt2byenlggd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2kpwcpqyl.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwclhgti.html

Ruby: class MyError < StandardError; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emlkbgxv.html

C#:   class MyException : Exception {}
来源：http://dali.svipenyu.cn/Article/details/gt2kogknewp.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2zfpldtef.html

Py:   except ValueError as e:
来源：http://dali.zhixingplan.top/Article/details/gt2qybwqhkx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.redwolf501.top/Article/details/gt2zpqmqliz.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2raeooqkg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2xxgtmalz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vupvapbq.html


<!-- 参考信息 -->