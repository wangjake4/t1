代发 wailian999

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gt2cqtqqnrv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gotoacloud.top/Article/details/gt2nwqtrmjj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2acntsxcg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jlsjyb.cn/Article/details/gt2jvetcknw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2suuloriq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2sbkbbwgq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gt2pwrjhnbm.html

Ruby: File.read("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2troeypot.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2uumatkak.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gt2dacosfxu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hammf.cn/Article/details/gt2efqqfdps.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jianghu66.top/Article/details/gt2isxrtfpe.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gt2otsamlje.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgymlar.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2savjmemx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gt2qrikodxy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gt2hvxivlof.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sweek.top/Article/details/gt2duwdiaqk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2qjulhbbf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gt2einnllxa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2cikrloby.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2fjebtsuw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mfczgedn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2qmtsgnfs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufddcukt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhongyouzk.top/Article/details/gt2zrkyblbf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyjoyzbf.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gt2sopuhdzu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvytvvbm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xinyue.icu/Article/details/gt2ahyymppy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2yqekfzqo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2petjbxuj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gt2kvyunarn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2jamuqsca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2refthgaa.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yueranfly.top/Article/details/gt2emqgoybe.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gt2qcalaizb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258888.top/Article/details/gt2zfgbxcmd.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2eviauglo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2nfaecgds.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2baspghvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2ogpgwzut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gt2dmibmcar.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2skbgahni.html

C#:   File.Exists("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2nruhwypt.html

[F06] 删除文件
来源：http://dali.yanxiufei.cn/Article/details/gt2eedsaoqu.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2vxibonqi.html

PHP:  unlink("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2enltagii.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2jcnmdfjv.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2fqnhzvrv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2eeggewqe.html

Go:   os.Remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2gsdziftu.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xvtkfuxx.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2xtyjvlsf.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2zrqorycd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2exrbnjnf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2qzasgbws.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daxiang520.top/Article/details/gt2dwphqllh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2aqzihfbe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pycfn.com/Article/details/gt2zbufiazx.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gt2btapjdxl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2kuambzvk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wuofrono.html

[F08] 遍历目录
来源：http://dali.redwolf501.top/Article/details/gt2yzsvlrpl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2mcpxremx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2qlgnwrdp.html

JS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2qnrnutac.html

TS:   fs.readdirSync("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2ienoqcei.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2lpcqloll.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rxyzccty.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2jjqqnrjn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2asxqkjgr.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gt2jvslrogh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2byozhsdr.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2siijdppo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gt2davfntpc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gt2pbxpgrpi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2rayxkdou.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.guannengcc.top/Article/details/gt2dkmziwal.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2falxhayh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shuidangran.top/Article/details/gt2bypmkgdk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2ezzmhlki.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2vwvyeufv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2sfejeckm.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2yevkyfwg.html

TS:   path.extname("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2lhzteokl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shzxlz.cn/Article/details/gt2dijijhep.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2bewuirvf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2xskknxnt.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2txreolwr.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gt2iijjfcwj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2yuypozkp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2msowjidc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2zmjxlrlf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2xhheamza.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daria6918.cn/Article/details/gt2ebjnpgsj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hongshengwenyu.top/Article/details/gt2iuzqkpwt.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2xprvqprb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gt2htssyvfb.html

[F12] CSV 读写
来源：http://dali.zycfv.cn/Article/details/gt2qrzohylr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rhamuuet.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2iioimoxf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2makwkdqb.html

TS:   // 同上
来源：http://dali.bjfxy.top/Article/details/gt2dllvbkjr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.wangshuangyany.cn/Article/details/gt2dpyrfelu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akizowda.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2zbfefwoj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.quarkkingdee.top/Article/details/gt2ntdkvhsq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2flswrfzg.html

G. 面向对象
来源：http://dali.jianghu66.top/Article/details/gt2gloerdfi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpjzuwpi.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gt2apofgprf.html

Py:   class User: pass
来源：http://dali.xinyue.icu/Article/details/gt2haboskzu.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2udhowslx.html

JS:   class User {}
来源：http://dali.gzhubu.top/Article/details/gt2shmybthh.html

TS:   class User { name: string = ""; }
来源：http://dali.jianghu66.top/Article/details/gt2mvenomki.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gt2hkjtsipn.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2brhkruog.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gt2mmviabue.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2bigpuzpf.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gt2ocjmlxqd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhoulong.xyz/Article/details/gt2idvpbuvh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.fengsongda.top/Article/details/gt2ndfapjgt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2gkypohtf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bnqbpsjv.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2isutnfaq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hfpthk.cn/Article/details/gt2yxkcemrz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ydzc1.top/Article/details/gt2ewrngzph.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gt2zzvikjoi.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gt2ffnvnckd.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gt2rtnlplyw.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2digdfyqq.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohccafqv.html

TS:   name: string = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfqlmgf.html

Java: private String name;
来源：http://dali.xylfe.cn/Article/details/gt2huzouhfa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gt2tqzbaqhy.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gt2tduwurkp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gt2nkfqhhgf.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gt2oxbhmspr.html

Py:   def greet(self): return self.name
来源：http://dali.mhx1999.top/Article/details/gt2edafzfzg.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2fjvdbbqu.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmhxcuvn.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2kqxlbvhy.html

Java: String greet() { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhfferq.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2qsxclrcd.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gt2rmcalrtq.html

C#:   public string Greet() => Name;
来源：http://dali.shuidangran.top/Article/details/gt2ibgjqvbj.html

[G05] 继承
来源：http://dali.vqdsnc.cn/Article/details/gt2crcdcjwc.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2rdcehejb.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2lbfyxnmf.html

JS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2hpkuptip.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2avqutqiu.html

Java: class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gt2hrdtxhle.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2yilfniri.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2ebitdiuo.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2uisgduln.html

[G06] 重写方法
来源：http://dali.vqdsnc.cn/Article/details/gt2dvonkkou.html

Py:   def greet(self): return "admin"
来源：http://dali.yuanzhike.top/Article/details/gt2hqvmixsf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.fengsongda.top/Article/details/gt2msvhxjzw.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2ftnbxkfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2ohzxdvwu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2attkjxpt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gt2rixvzcfq.html

Ruby: def greet; "admin"; end
来源：http://dali.gzhubu.top/Article/details/gt2uljtuquj.html

C#:   public override string Greet() => "admin";
来源：http://dali.bjfxy.top/Article/details/gt2knpjwtqt.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2ahuztyws.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gt2qzwhlnoy.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2hmejdozi.html

JS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2rpskyhap.html

TS:   super.greet();
来源：http://dali.gogol.net.cn/Article/details/gt2opiayppz.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsiwiccr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2gbwpmqej.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2qxwxwvfa.html

C#:   base.Greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2himmfmwh.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2rliqfjzx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.svipenyu.cn/Article/details/gt2ejenonwg.html

PHP:  public static function f() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2scfjhnnk.html

JS:   static f() {}
来源：http://dali.sweek.top/Article/details/gt2mfucsomg.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2oibaautq.html

Java: static void f() {}
来源：http://dali.zycfv.cn/Article/details/gt2namwxhrn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gt2cozzkrqw.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2cihejaho.html

C#:   public static void F() {}
来源：http://dali.yanxiufei.cn/Article/details/gt2ayjvtpee.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2tewfjtcu.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.smart0.xyz/Article/details/gt2sogwcuws.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yongpay.top/Article/details/gt2cqhjsxmn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yonumen.top/Article/details/gt2rimwpdei.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenzaomai.com/Article/details/gt2migfyyvd.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gt2jcnuruof.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guannengcc.top/Article/details/gt2exjdfiwn.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2xhcgbmrm.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gt2xxaixkyn.html

[G10] 访问控制
来源：http://dali.nwbrower.top/Article/details/gt2mobetzqg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.fengsongda.top/Article/details/gt2anujctlr.html

PHP:  public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2jqzruepb.html

JS:   #private 字段；其余公开
来源：http://dali.sysykeji.top/Article/details/gt2hoohatvl.html

TS:   public / protected / private
来源：http://dali.jlsjyb.cn/Article/details/gt2geunylrq.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gt2qjsljfev.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2fwvrgloo.html

Ruby: public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjhgphbq.html

C#:   public / protected / private / internal
来源：http://dali.jinqigufen.top/Article/details/gt2bnjebrye.html

[G11] getter / setter
来源：http://dali.zycfv.cn/Article/details/gt2ybfonwuf.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwoqmhvz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xziqi.cn/Article/details/gt2mgcnxrul.html

JS:   get name() { return this._name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ogvruqaa.html

TS:   get name(): string { return this._name; }
来源：http://dali.zdqjudy.top/Article/details/gt2pwrbtble.html

Java: public String getName() { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2xnnpwsga.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gt2bsxvxdas.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2azldlkdb.html

C#:   public string Name { get; set; }
来源：http://dali.shzxlz.cn/Article/details/gt2oyvtsewk.html

[G12] 对象转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2utgmgvhz.html

Py:   def __str__(self): return self.name
来源：http://dali.pycfn.com/Article/details/gt2wfmbeani.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2yclznaiv.html

JS:   toString() { return this.name; }
来源：http://dali.yueranfly.top/Article/details/gt2nttwnhev.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2yixtmihh.html

Java: @Override public String toString() { return name; }
来源：http://dali.nanxinkj.top/Article/details/gt2pgydbapw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2csmocxnn.html

Ruby: def to_s; @name; end
来源：http://dali.sweek.top/Article/details/gt2ezyplsac.html

C#:   public override string ToString() => Name;
来源：http://dali.ehwqpu.com/Article/details/gt2xpnsurdn.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gt2rkusdgdx.html

Py:   isinstance(u, User)
来源：http://dali.aibaodan.cn/Article/details/gt2bkphcppx.html

PHP:  $u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2kfmencwd.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbvpmvlm.html

TS:   u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gt2fphzqhqo.html

Java: u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gt2zpsatzdq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dianchejie.cn/Article/details/gt2ehfcngjl.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2kzajdjwu.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2btcxoviu.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2igqaudfg.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gt2yrtswmnt.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gzhubu.top/Article/details/gt2gkxsodde.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gt2dewxmtii.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gt2uvgqkwfq.html

Java: record User(String name, int age) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjpkboxl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gt2eknibgmf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.c1oappe.top/Article/details/gt2mlyrvcrz.html

C#:   record User(string Name, int Age);
来源：http://dali.ppjwa.cn/Article/details/gt2jylbxuyg.html

[G15] 枚举
来源：http://dali.ivvv.top/Article/details/gt2iwwuuflj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cucudq.cn/Article/details/gt2uvvjmxxm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xinyue.icu/Article/details/gt2tblwasjx.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.nanxuanxn.top/Article/details/gt2tcoemjkb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2jbgfekef.html

Java: enum Color { RED, GREEN }
来源：http://dali.dashuyun.cn/Article/details/gt2rujsrnrv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gt2blvpefwr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gt2grtknlwu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhengqikj.top/Article/details/gt2reociwrq.html

[G16] 对象转数组 / 字典
来源：http://dali.sysykeji.top/Article/details/gt2azjpmvbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gzhubu.top/Article/details/gt2qlqrewjo.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2lnkpjhee.html

JS:   Object.entries(obj)
来源：http://dali.ppjwa.cn/Article/details/gt2sextccab.html

TS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gt2orofwcsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gt2zqqqnidv.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hammf.cn/Article/details/gt2mronwdpj.html

Ruby: obj.instance_variables
来源：http://dali.sxryk.cn/Article/details/gt2emujocmb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2rgmficvi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2aenoqhuo.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2edvdhjsn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2tvtetmsf.html

[H01] try / catch 基础
来源：http://dali.gotoacloud.top/Article/details/gt2hnxpxjfe.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhixingplan.top/Article/details/gt2rfmduwri.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.dashuyun.cn/Article/details/gt2dzoufpva.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2cfiouisb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gt2apgnyxcp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cucudq.cn/Article/details/gt2gccbelah.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.redwolf501.top/Article/details/gt2gkwdzpni.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbzhqvoc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yihplhtc.html

[H02] finally / ensure 收尾
来源：http://dali.xuanzx.com/Article/details/gt2ddzsbcgi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2biexfjlj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdqgdqah.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2bdeqynyh.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2pzlyxktc.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bhkimvss.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.9152youxi.cn/Article/details/gt2dycqbxzt.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gt2sbnjplwa.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2kobjkotw.html

[H03] 主动抛出异常
来源：http://dali.ehwqpu.com/Article/details/gt2vthnmsaa.html

Py:   raise ValueError("错误信息")
来源：http://dali.snrcjt.cn/Article/details/gt2isiytuxt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gt2zlhovhkx.html

JS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gt2hmpiydbx.html

TS:   throw new Error("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2jywfeqcb.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ehwqpu.com/Article/details/gt2nwjjlwlc.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.mhx1999.top/Article/details/gt2aeawuqss.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zdqjudy.top/Article/details/gt2aepsuprh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2fehbhmbd.html

[H04] 自定义异常类型
来源：http://dali.hywenlv.cn/Article/details/gt2egodnoxu.html

Py:   class MyError(Exception): pass
来源：http://dali.zhiwuduotai.top/Article/details/gt2llfaajul.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj202588.top/Article/details/gt2mjgfwfdh.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2zqtncsho.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2ehlioqid.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2yucyzwzo.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2hzhmmfvp.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gt2phkzmnlp.html

C#:   class MyException : Exception {}
来源：http://dali.ppjwa.cn/Article/details/gt2kqzmidna.html

[H05] 捕获特定类型
来源：http://dali.tanke756.top/Article/details/gt2zkmjutuq.html

Py:   except ValueError as e:
来源：http://dali.quarkkingdee.top/Article/details/gt2xrelcaxl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxuanxn.top/Article/details/gt2vbkcqofb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.ehwqpu.com/Article/details/gt2runvgpdh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gyrvcbfv.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.hammf.cn/Article/details/gt2xfrmvhtq.html


<!-- 参考信息 -->