代发 wailian999

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2hjztyyif.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2hpjgpcgl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2cjoctibm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gt2smeekwig.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2rvpeptkk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayclnqgx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gt2owpnbmuk.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxuuqted.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2yrjbgytu.html

[F02] 逐行读取文件
来源：http://dali.guannengcc.top/Article/details/gt2afuhnjie.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.0kj1m.cn/Article/details/gt2tcmxhzqq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2xsvrwdxk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uymmmtiz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2ojrrnbps.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjaoqfza.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gt2ekuhaata.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhengqikj.top/Article/details/gt2ojknsbya.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gt2gcqfoitp.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lnjitjzl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gt2doysmstu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2dwfpfcuz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tpmgkfxj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2zyjhrpxo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2eimzrpje.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nwbrower.top/Article/details/gt2kcqackir.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tclotpjt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2thjldvkv.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gt2fvgqdomb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2qvitznxe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2joxlgoyz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2kyubazkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2syxnwkzt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gt2chhcdjot.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xwlmgmot.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2syccwuvv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gt2fmfxtpnj.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxuanxn.top/Article/details/gt2ehxnoaye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gt2okkizthe.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2dgyutxof.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2eiachydq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2cngrgwmg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gt2vriyolyg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gt2xlzastih.html

Ruby: File.exist?("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2ardjgrzu.html

C#:   File.Exists("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2mzbqqqwg.html

[F06] 删除文件
来源：http://dali.yongpay.top/Article/details/gt2uscbtcxd.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2vwoefzjp.html

PHP:  unlink("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2wviujuzr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2wjapqmna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vbqxbuie.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2dfneokyc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eztyjvju.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2lepfqjmh.html

C#:   File.Delete("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2wdhcdrha.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jjmwnxds.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cucudq.cn/Article/details/gt2bsqoctmn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xinyue.icu/Article/details/gt2usyipzgq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gt2bgercevx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gt2rwvlaztd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2kwowjagg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hfpthk.cn/Article/details/gt2ypgbgqet.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gt2bgpdxkrc.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yvedp.cn/Article/details/gt2gidbfnws.html

[F08] 遍历目录
来源：http://dali.chenlongwang.top/Article/details/gt2rpqadpdb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2uijxbcau.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2jvjabrnb.html

JS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2xolsivbo.html

TS:   fs.readdirSync("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2zcbaoyxr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2dxruxzzb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2dkdovudt.html

Ruby: Dir.children("dir")
来源：http://dali.havefunace.top/Article/details/gt2ckushgoy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.pycfn.com/Article/details/gt2bpayyuhu.html

[F09] 获取文件大小
来源：http://dali.hammf.cn/Article/details/gt2kmkkneml.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2sajocjsg.html

PHP:  filesize("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2rdxluqdx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2ddkozjvo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gt2tjhifoiy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2mrslebfp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2fpbjpfji.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gqwqkiki.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gt2xrxljtps.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuanzx.com/Article/details/gt2xkkrybsa.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cpmdqqwp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2qccgmwqe.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2umskmvli.html

TS:   path.extname("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2nrqyoeem.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sivajgkd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2raydmiyv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ndmqpzwp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zjyxrojs.html

[F11] 复制与移动文件
来源：http://dali.cashguo.top/Article/details/gt2ukflcuet.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2mzigegbs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2ipzfpexp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2jrioklca.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gt2tvmtoekw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cufsttlb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gotoacloud.top/Article/details/gt2lojqotqq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2xqeibljk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2zexupjdc.html

[F12] CSV 读写
来源：http://dali.daxiang520.top/Article/details/gt2mdbonacc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.birdmap.top/Article/details/gt2pfphoafd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2zwgjiihl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2bhbasxie.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoqwwtlw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2nkbuwnaw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.bjfxy.top/Article/details/gt2mdkrkpri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ehwqpu.com/Article/details/gt2tvqkkrsi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.redwolf501.top/Article/details/gt2yrxmaikg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2pxvxlcax.html

G. 面向对象
来源：http://dali.jqgfzy.top/Article/details/gt2mcpwanem.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2bmunawha.html

[G01] 定义类
来源：http://dali.xziqi.cn/Article/details/gt2xtorwegm.html

Py:   class User: pass
来源：http://dali.aibaodan.cn/Article/details/gt2kmcpvijp.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2edhteyxd.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2xckkpqtd.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2gepckzxb.html

Java: class User {}
来源：http://dali.aibaodan.cn/Article/details/gt2xteyutmt.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2kyqejypn.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gt2keqlsuet.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2wtctnspf.html

[G02] 构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2idrmdybt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daria6918.cn/Article/details/gt2ucwnlclo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qoskrijr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2uwhctrdf.html

TS:   constructor(public name: string) {}
来源：http://dali.c1oappe.top/Article/details/gt2stqauamx.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ctllfkvt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.0kj1m.cn/Article/details/gt2wyrngiis.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2bccjdnmk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmzbctqh.html

[G03] 实例属性
来源：http://dali.cucudq.cn/Article/details/gt2pdnqwadr.html

Py:   self.name = "x"
来源：http://dali.xziqi.cn/Article/details/gt2rpbbiflk.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gt2qhwqsriq.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gt2ifobgpww.html

TS:   name: string = "x";
来源：http://dali.pycfn.com/Article/details/gt2deqvcnuk.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2rbjjebpz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gt2gmspvhqu.html

Ruby: @name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2ahnzknmh.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gt2xoqfmabb.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2dcblncio.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkcpsub.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vemvjnck.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2rlywrrsu.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2srsgtigg.html

Java: String greet() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rthlixsv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2amourqoc.html

Ruby: def greet; @name; end
来源：http://dali.hnqzz.top/Article/details/gt2lrrbjivf.html

C#:   public string Greet() => Name;
来源：http://dali.vqdsnc.cn/Article/details/gt2kvvqzyct.html

[G05] 继承
来源：http://dali.hongshengwenyu.top/Article/details/gt2lmhzlkrc.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2lstmeedd.html

PHP:  class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iaswlsoi.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2tgxmndkw.html

TS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gt2vlfnsnya.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jlvrjmfh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.guowangkeji.top/Article/details/gt2gjtmgbip.html

Ruby: class Admin < User; end
来源：http://dali.c1oappe.top/Article/details/gt2qtvlxnwi.html

C#:   class Admin : User {}
来源：http://dali.zhixingplan.top/Article/details/gt2zzhzpxlo.html

[G06] 重写方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2icvncvkl.html

Py:   def greet(self): return "admin"
来源：http://dali.kuanghao11.cn/Article/details/gt2ovpnjkwb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2emyzprcy.html

JS:   greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2onzcmbpx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2zllrrhbm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2esjidpxu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gt2nvyhxtrn.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2qwsdtore.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdywoupk.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2ixftbqlk.html

Py:   super().greet()
来源：http://dali.sufxvd.cn/Article/details/gt2rxiqtitd.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gt2yiygxjxw.html

JS:   super.greet();
来源：http://dali.cqqwz.cn/Article/details/gt2olqoqodx.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gt2xvitacfw.html

Java: super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2uqlrnouc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nygvdnyx.html

Ruby: super
来源：http://dali.nwbrower.top/Article/details/gt2vbxcuegd.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gt2bxmtjswz.html

[G08] 静态方法与属性
来源：http://dali.hywenlv.cn/Article/details/gt2ztibcljq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2hiofmvgb.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2rexstlpx.html

JS:   static f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2zfuwxawo.html

TS:   static f(): void {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjkaiqtz.html

Java: static void f() {}
来源：http://dali.ydzc1.top/Article/details/gt2dtorcxsv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2rkyrgafl.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2hfgmrfhu.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hhcgtjdz.html

[G09] 接口 / 抽象类
来源：http://dali.xuanzx.com/Article/details/gt2utyhchsh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.vqdsnc.cn/Article/details/gt2rwaqgzep.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2becdhttw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gt2eayaojij.html

TS:   interface Shape { area(): number; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dxckduhu.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2hktykoeu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cheryme.top/Article/details/gt2ortqysob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.smart0.xyz/Article/details/gt2lgkcbowy.html

C#:   interface IShape { double Area(); }
来源：http://dali.xylfe.cn/Article/details/gt2kegxuwgy.html

[G10] 访问控制
来源：http://dali.kuanghao11.cn/Article/details/gt2gbyytzxy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gt2ecnvrupx.html

PHP:  public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gt2lgynfvqj.html

JS:   #private 字段；其余公开
来源：http://dali.ppjwa.cn/Article/details/gt2vezliuyd.html

TS:   public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2fmidxcvy.html

Java: public / protected / private / 默认包级
来源：http://dali.yangfankeji.com/Article/details/gt2elunvgpu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xinyue.icu/Article/details/gt2rewwljbh.html

Ruby: public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2jihmvwah.html

C#:   public / protected / private / internal
来源：http://dali.c1oappe.top/Article/details/gt2gwbrtjmj.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2ntmuqxbo.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2kodytioi.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgfzy.top/Article/details/gt2jmmxqdvj.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2jbymixqx.html

TS:   get name(): string { return this._name; }
来源：http://dali.nwbrower.top/Article/details/gt2njsafsdy.html

Java: public String getName() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2vlzvaabd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2dptazllp.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2arqfyfst.html

C#:   public string Name { get; set; }
来源：http://dali.nanxinkj.top/Article/details/gt2hkhxbuim.html

[G12] 对象转字符串
来源：http://dali.jianghu66.top/Article/details/gt2mndburrt.html

Py:   def __str__(self): return self.name
来源：http://dali.havefunace.top/Article/details/gt2xymwphmn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gt2jyihvwyi.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2adplyopr.html

TS:   toString(): string { return this.name; }
来源：http://dali.cashguo.top/Article/details/gt2xvpeltmm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2cmohgbec.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2ewzetzaa.html

Ruby: def to_s; @name; end
来源：http://dali.mhx1999.top/Article/details/gt2vjbrlquu.html

C#:   public override string ToString() => Name;
来源：http://dali.meibo888.top/Article/details/gt2yrqdzxjt.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2nwhqnkkw.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2yzchvptz.html

PHP:  $u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gt2iracmcdj.html

JS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2xenyebdz.html

TS:   u instanceof User
来源：http://dali.yonumen.top/Article/details/gt2zcdsmgkk.html

Java: u instanceof User
来源：http://dali.jqgufenzy.top/Article/details/gt2aebbgcau.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cashguo.top/Article/details/gt2kynzhwau.html

Ruby: u.is_a?(User)
来源：http://dali.nwbrower.top/Article/details/gt2lkrntxzt.html

C#:   u is User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2edwdfhep.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rfhrxsqw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shzxlz.cn/Article/details/gt2pyivdnsn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.smart0.xyz/Article/details/gt2rvgxmznx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cheryme.top/Article/details/gt2yxbioinf.html

TS:   type User = { name: string; age: number };
来源：http://dali.bjfxy.top/Article/details/gt2uyxroaha.html

Java: record User(String name, int age) {}
来源：http://dali.jianghu66.top/Article/details/gt2tuzbqqfk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lctlmqfr.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cashguo.top/Article/details/gt2difaqegs.html

C#:   record User(string Name, int Age);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fthfoszt.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2qrthvxzp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.aibaodan.cn/Article/details/gt2yidddkul.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhyokzxg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jqgufenzy.top/Article/details/gt2zwudfmmm.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daria6918.cn/Article/details/gt2mdhxayxi.html

Java: enum Color { RED, GREEN }
来源：http://dali.xziqi.cn/Article/details/gt2ltcievld.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.tanke756.top/Article/details/gt2gburnudm.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbbxspmf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2vdlclyhv.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhrmkmba.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.daxiang520.top/Article/details/gt2cyilhwcw.html

PHP:  get_object_vars($obj);
来源：http://dali.aizwys.cn/Article/details/gt2kvgybmil.html

JS:   Object.entries(obj)
来源：http://dali.sxryk.cn/Article/details/gt2vybmscvt.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gt2pnntzncq.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2xhjgwvjx.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gt2wmqhohna.html

Ruby: obj.instance_variables
来源：http://dali.cdnleiting.top/Article/details/gt2yblaykxw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.jlsjyb.cn/Article/details/gt2ukdhomvp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2ifqyhzjn.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2fwyrwcef.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylrddvhb.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gt2azimslcv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mysddvmi.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cimupbpk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gt2scqwrcib.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gt2kjojmfik.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cashguo.top/Article/details/gt2pixeomjl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.andypj.xyz/Article/details/gt2cvigcele.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cqqwz.cn/Article/details/gt2szuzizsy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuxming.cn/Article/details/gt2wnwvnrqm.html

[H02] finally / ensure 收尾
来源：http://dali.haohaochexian.top/Article/details/gt2nkgedcxz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tanke756.top/Article/details/gt2pgewhiwx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gt2uybqebfj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ysxoyduj.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2rkiherej.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2hlqhxymj.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2vrmisvtj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gzhubu.top/Article/details/gt2lqfedwhi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.pycfn.com/Article/details/gt2ouapekqt.html

[H03] 主动抛出异常
来源：http://dali.cucudq.cn/Article/details/gt2grpdwkgn.html

Py:   raise ValueError("错误信息")
来源：http://dali.svipenyu.cn/Article/details/gt2yekdkdim.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2wpqugnfm.html

JS:   throw new Error("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2pccqcykp.html

TS:   throw new Error("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2egkmedie.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2rtvmegrt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gt2tztonbtj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.haohaochexian.top/Article/details/gt2ugnxcriy.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gt2kuhcgavr.html

[H04] 自定义异常类型
来源：http://dali.hammf.cn/Article/details/gt2kqwvdvnc.html

Py:   class MyError(Exception): pass
来源：http://dali.9152youxi.cn/Article/details/gt2betmvgke.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhengqikj.top/Article/details/gt2prwgaumy.html

JS:   class MyError extends Error {}
来源：http://dali.yongpay.top/Article/details/gt2ujszqfsz.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gt2nqzmfnzc.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gt2uuioumgc.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jinqigufen.top/Article/details/gt2podntfbn.html

Ruby: class MyError < StandardError; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tihzsplm.html

C#:   class MyException : Exception {}
来源：http://dali.daxiang520.top/Article/details/gt2wdgbnmsz.html

[H05] 捕获特定类型
来源：http://dali.shuidangran.top/Article/details/gt2tymhcdxl.html

Py:   except ValueError as e:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2novbcfsv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2asjpiezy.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jyoumei.cn/Article/details/gt2mtpaliob.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2srzqbucd.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ewinoimo.html


<!-- 参考信息 -->