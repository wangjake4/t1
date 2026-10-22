代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gt2hcindjyn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2sjxlowwr.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gt2nexxvier.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ejxkksgc.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gt2xfvatfjf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gt2dmmmkhkr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2newhqphx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2pywdyyse.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fujawasa.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2mtcpbibe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sufxvd.cn/Article/details/gt2lmsxvmpw.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2fykfmyzs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2lfxjdfxx.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2lzqttnqt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gt2eubfxhrg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2kbrikura.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gt2wgialobq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gt2gaqtjphd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2ukynhmcd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gt2awasotae.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sxryk.cn/Article/details/gt2yxqyemtf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgyjattz.html

[F03] 写入文件（覆盖）
来源：http://dali.quarkkingdee.top/Article/details/gt2qcaxuwii.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gt2ddcbrtpt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddptuiph.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.316326.xyz/Article/details/gt2hobwmgky.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2eoeaaquv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shuidangran.top/Article/details/gt2hovmepho.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zycfv.cn/Article/details/gt2dcoazeew.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2xvirlpxa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gt2rdatnzfx.html

[F04] 追加写入文件
来源：http://dali.sweek.top/Article/details/gt2xymurxra.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxoiljtl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xziqi.cn/Article/details/gt2lolbbczp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2gcdnjxbu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrlumpar.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.tianlin.xyz/Article/details/gt2euixmubd.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qrfvkice.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbuyhpwg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2sngklkim.html

[F05] 判断文件或目录是否存在
来源：http://dali.quarkkingdee.top/Article/details/gt2xtmybfqd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gt2grxszhmf.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2ngfmiqgi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2nggweemy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2oegskqlr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2rbsixxtf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.fengsongda.top/Article/details/gt2zgneygxa.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2rfqlstyp.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2seajzqyr.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gt2kvimwaby.html

Py:   os.remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vclnyhre.html

PHP:  unlink("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihaoqafj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2hikgzxxv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2inpcsmey.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gt2mskjtiun.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2zkyhyfvn.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2swbswesr.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2slyswkob.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2zoczakog.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tphzdlin.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yangfankeji.com/Article/details/gt2nwvwltir.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gt2ypjrvcsm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gt2hwjzwcrg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.mhx1999.top/Article/details/gt2klvoyyzb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gt2uicfvdyu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gt2ahnadxrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yonumen.top/Article/details/gt2chgtaexc.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2ourtkvbd.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gt2ygictyvz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ehwqpu.com/Article/details/gt2porvriyn.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2dikrxavg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yueranfly.top/Article/details/gt2zixhgzkm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gt2isaasazo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.meibo888.top/Article/details/gt2llihoqkk.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2lsyftacx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2suwopajj.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2jaasdste.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2rhoiozyw.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2eibeehzv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2auskvlgh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gt2wzwueidx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2dzvpajrb.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2ajifexmx.html

Ruby: File.size("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2nsqvejbb.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gt2ufdwilpb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gt2rtbdukko.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ibkmymic.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2mfjnfpxi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2yxkvrfrv.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2znfmcrmb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lnpgibko.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2efwnwvnu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pbgmwcfz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2abmgquru.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2cekslglw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2pvaifitn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2tlmvlolt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqrsnklu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2bkewfbvk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gt2mqrucpul.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gaohongyu789.top/Article/details/gt2zakkchma.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kgabatdf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.meibo888.top/Article/details/gt2aylmavng.html

[F12] CSV 读写
来源：http://dali.jqgufenzy.top/Article/details/gt2vzohwxln.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2lmfqzprf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.snrcjt.cn/Article/details/gt2qihyujrh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xylfe.cn/Article/details/gt2amwkpelv.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2jwbgvfaf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2ogrjsiij.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gt2yosfstdf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2yyjtobju.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yongpay.top/Article/details/gt2kssbpnko.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2izskrgmt.html

G. 面向对象
来源：http://dali.xylfe.cn/Article/details/gt2fouwwgiv.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fwrtfsxu.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gt2hiypuksf.html

Py:   class User: pass
来源：http://dali.jinqigfzy.top/Article/details/gt2obqxxbmc.html

PHP:  class User {}
来源：http://dali.zdqjudy.top/Article/details/gt2tyucbpbo.html

JS:   class User {}
来源：http://dali.bjfxy.top/Article/details/gt2dipolsvf.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gt2mjbvmbjk.html

Java: class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2ekbteopd.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gt2enwidsub.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2erxxnxqz.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2zkqfzfji.html

[G02] 构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2uqsgbsby.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yueranfly.top/Article/details/gt2jsurupkr.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2iaaeikik.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2jcwdgnah.html

TS:   constructor(public name: string) {}
来源：http://dali.smart0.xyz/Article/details/gt2gtoehvgb.html

Java: User(String name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2ocgwzwwx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gt2ifzlucvi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2ekthonwg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2zbqocjwu.html

[G03] 实例属性
来源：http://dali.yj202588.top/Article/details/gt2qhcpzrls.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2bvgczihg.html

PHP:  public string $name = "x";
来源：http://dali.kuanghao11.cn/Article/details/gt2xuouzskq.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2tbcxaitu.html

TS:   name: string = "x";
来源：http://dali.jiagoushi.top/Article/details/gt2stqwwjuo.html

Java: private String name;
来源：http://dali.cqqwz.cn/Article/details/gt2xfbeaibr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2oshrastu.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2hjtiuxur.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cheryme.top/Article/details/gt2xzzfrcnv.html

[G04] 定义方法
来源：http://dali.cashguo.top/Article/details/gt2lgbemwnr.html

Py:   def greet(self): return self.name
来源：http://dali.zhoulong.xyz/Article/details/gt2zpfutlov.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2kpghdkcv.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2dqcjdejf.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2jwwbtwbd.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gt2guzwxvqq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gt2cnpcfkzk.html

Ruby: def greet; @name; end
来源：http://dali.jyoumei.cn/Article/details/gt2wihdbbbq.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2ztwmvrer.html

[G05] 继承
来源：http://dali.cqqwz.cn/Article/details/gt2mqdsqwyj.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gt2jtjhkrte.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2zaarject.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2pjvphreu.html

TS:   class Admin extends User {}
来源：http://dali.sufxvd.cn/Article/details/gt2xysfvjzw.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2yamzxlto.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shzxlz.cn/Article/details/gt2zpreyvuj.html

Ruby: class Admin < User; end
来源：http://dali.dashuyun.cn/Article/details/gt2tgtawlot.html

C#:   class Admin : User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2vuhkoebv.html

[G06] 重写方法
来源：http://dali.hongshengwenyu.top/Article/details/gt2ryjdvwla.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gt2mpakbzhs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2rxrslbav.html

JS:   greet() { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2qrnccbef.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2bsnkxbzk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2wutatyvw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2mdmbyhti.html

Ruby: def greet; "admin"; end
来源：http://dali.yuxming.cn/Article/details/gt2waryzqfq.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2prmbwbrd.html

[G07] 调用父类方法
来源：http://dali.gaohongyu789.top/Article/details/gt2szrzvrag.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2hcziggpx.html

PHP:  parent::greet();
来源：http://dali.xuanzx.com/Article/details/gt2lyxriiks.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2uxyspwof.html

TS:   super.greet();
来源：http://dali.meibo888.top/Article/details/gt2frepxasb.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2oaooxmdo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yueranfly.top/Article/details/gt2rruogwlo.html

Ruby: super
来源：http://dali.dianchejie.cn/Article/details/gt2cumquwou.html

C#:   base.Greet();
来源：http://dali.daria6918.cn/Article/details/gt2trwcgjei.html

[G08] 静态方法与属性
来源：http://dali.zhoulong.xyz/Article/details/gt2huuqjitk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.snrcjt.cn/Article/details/gt2igiskkdz.html

PHP:  public static function f() {}
来源：http://dali.ivvv.top/Article/details/gt2apsxsixc.html

JS:   static f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2izjdxrla.html

TS:   static f(): void {}
来源：http://dali.hnqzz.top/Article/details/gt2lkgzlauq.html

Java: static void f() {}
来源：http://dali.smart0.xyz/Article/details/gt2zdmlfrxm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2xriggsbl.html

Ruby: def self.f; end
来源：http://dali.zhengqikj.top/Article/details/gt2jqmffxrf.html

C#:   public static void F() {}
来源：http://dali.yvedp.cn/Article/details/gt2vngkqogy.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gt2xydjcicy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ehwqpu.com/Article/details/gt2unizmdvd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bwptscdn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.chenzaomai.com/Article/details/gt2ovahpfqk.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2tmbwbsdg.html

Java: interface Shape { double area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2krbdcoji.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yueranfly.top/Article/details/gt2izjejckz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2mzwoomab.html

C#:   interface IShape { double Area(); }
来源：http://dali.meibo888.top/Article/details/gt2ngvhgxfj.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gt2ajgpqxoq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gt2bmvtogjz.html

PHP:  public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2ybemeqei.html

JS:   #private 字段；其余公开
来源：http://dali.mhx1999.top/Article/details/gt2hhmeftbo.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2dszeppmv.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2nekagxwa.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.kuanghao11.cn/Article/details/gt2yihawady.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2izvfgrwe.html

C#:   public / protected / private / internal
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbwgrzwv.html

[G11] getter / setter
来源：http://dali.yj20258888.top/Article/details/gt2xbdhdtmq.html

Py:   @property 与 @x.setter
来源：http://dali.snrcjt.cn/Article/details/gt2aaufcdrn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rxieldkw.html

JS:   get name() { return this._name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jzsbgeyy.html

TS:   get name(): string { return this._name; }
来源：http://dali.ppjwa.cn/Article/details/gt2uvatorgg.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2rurtyamr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwkteclw.html

Ruby: attr_accessor :name
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewxjkjcd.html

C#:   public string Name { get; set; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvnicezi.html

[G12] 对象转字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2lmlsdlks.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2legsurgl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gt2lzfzcwga.html

JS:   toString() { return this.name; }
来源：http://dali.yangfankeji.com/Article/details/gt2ptxjypfh.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ighidvgf.html

Java: @Override public String toString() { return name; }
来源：http://dali.sweek.top/Article/details/gt2fbyifomk.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2qumudqjd.html

Ruby: def to_s; @name; end
来源：http://dali.bjfxy.top/Article/details/gt2cdshjomh.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gt2emuuyhic.html

[G13] 判断对象类型
来源：http://dali.jyoumei.cn/Article/details/gt2bgtjresc.html

Py:   isinstance(u, User)
来源：http://dali.hywenlv.cn/Article/details/gt2fpmthmbt.html

PHP:  $u instanceof User
来源：http://dali.vqdsnc.cn/Article/details/gt2hnczgypv.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2nkgbdbco.html

TS:   u instanceof User
来源：http://dali.chenjidiqi.icu/Article/details/gt2bximerul.html

Java: u instanceof User
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oqbhbutd.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ocpszoyd.html

Ruby: u.is_a?(User)
来源：http://dali.chenlongwang.top/Article/details/gt2nyesqvgk.html

C#:   u is User
来源：http://dali.meibo888.top/Article/details/gt2wgtvdmap.html

[G14] 数据类 / record
来源：http://dali.sysykeji.top/Article/details/gt2sopwiwls.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.sxryk.cn/Article/details/gt2diuzyeio.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gt2ovlqwzgj.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.wangdashe.top/Article/details/gt2mdvqehan.html

TS:   type User = { name: string; age: number };
来源：http://dali.0kj1m.cn/Article/details/gt2eierwtcn.html

Java: record User(String name, int age) {}
来源：http://dali.cashguo.top/Article/details/gt2epndwlfa.html

Go:   type User struct { Name string; Age int }
来源：http://dali.sufxvd.cn/Article/details/gt2wzjsqqbb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.guannengcc.top/Article/details/gt2gbnqobzh.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gt2apbklagc.html

[G15] 枚举
来源：http://dali.sysykeji.top/Article/details/gt2blqsubze.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.sxryk.cn/Article/details/gt2hcujcozp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2greqituy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gt2mgburouk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2rgpfmfhf.html

Java: enum Color { RED, GREEN }
来源：http://dali.daxiang520.top/Article/details/gt2whwfehqc.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sysykeji.top/Article/details/gt2epbivelp.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2enxdbctk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2ullvolyz.html

[G16] 对象转数组 / 字典
来源：http://dali.ehwqpu.com/Article/details/gt2cdeegolm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2meyidcag.html

PHP:  get_object_vars($obj);
来源：http://dali.sysykeji.top/Article/details/gt2yvcguaid.html

JS:   Object.entries(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2fuwrrzlw.html

TS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gt2aihqmtmn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2pgsgkyxb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.wangdashe.top/Article/details/gt2eyatwida.html

Ruby: obj.instance_variables
来源：http://dali.hysaishi.cn/Article/details/gt2arhgdrqc.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenzaomai.com/Article/details/gt2vaqtmhml.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2ggzvhgjb.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gt2gyrwrnyl.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2klvknjki.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2tlmswlnu.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.nanxinkj.top/Article/details/gt2cnzczaph.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.nanxinkj.top/Article/details/gt2psepifsm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yj20258888.top/Article/details/gt2vcxaydpp.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gt2vnnotlvp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzqxnreq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2fyxgkyxk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.pycfn.com/Article/details/gt2wtbhgmql.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yvedp.cn/Article/details/gt2wopkaira.html

[H02] finally / ensure 收尾
来源：http://dali.cheryme.top/Article/details/gt2sjvirnvg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.kuanghao11.cn/Article/details/gt2zouefaiu.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2quofxwbr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2pnyotjqw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gt2ikdewjdf.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yj20258.top/Article/details/gt2klezmqhy.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gt2bhbguuld.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzxghofh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gt2vejxcuvu.html

[H03] 主动抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2tzlejujl.html

Py:   raise ValueError("错误信息")
来源：http://dali.gogol.net.cn/Article/details/gt2epfmklis.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gt2yhwuadza.html

JS:   throw new Error("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2hguvdxwk.html

TS:   throw new Error("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2wygsqedt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.c1oappe.top/Article/details/gt2qbennsuw.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gt2zkklbjjv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rrdidmay.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2pepuogqc.html

[H04] 自定义异常类型
来源：http://dali.yuanzhike.top/Article/details/gt2zathlezx.html

Py:   class MyError(Exception): pass
来源：http://dali.ydzc1.top/Article/details/gt2nldielti.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.cucudq.cn/Article/details/gt2clsacvva.html

JS:   class MyError extends Error {}
来源：http://dali.tanke756.top/Article/details/gt2tmvwanzj.html

TS:   class MyError extends Error {}
来源：http://dali.xylfe.cn/Article/details/gt2osxlwnme.html

Java: class MyException extends RuntimeException {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wqhwsfbb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hfpthk.cn/Article/details/gt2uimojnms.html

Ruby: class MyError < StandardError; end
来源：http://dali.pycfn.com/Article/details/gt2scblmayx.html

C#:   class MyException : Exception {}
来源：http://dali.sweek.top/Article/details/gt2qimsooms.html

[H05] 捕获特定类型
来源：http://dali.guannengcc.top/Article/details/gt2kjequsql.html

Py:   except ValueError as e:
来源：http://dali.yongpay.top/Article/details/gt2mwcsutll.html


<!-- 参考信息 -->