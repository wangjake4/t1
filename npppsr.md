代发 wailian999

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2wcobqzas.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2vqxyitmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2mmvmulsl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gt2ooywjyus.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2fcouuueb.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2avecxrba.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2hrxulixb.html

Ruby: File.read("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2kjntfsrj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2hxbyzfzt.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lvzxxukw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ysawhohj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hammf.cn/Article/details/gt2eyifltlu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sxryk.cn/Article/details/gt2mwxrewep.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2hchsfsov.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2zqefjxas.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eubdproz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sufxvd.cn/Article/details/gt2hvkbxcfw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uddsxpbi.html

[F03] 写入文件（覆盖）
来源：http://dali.haohaochexian.top/Article/details/gt2ctijequb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgspsbmk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2nczlbxqj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gzhubu.top/Article/details/gt2xrwdeiqh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2yygfzxtr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gogol.net.cn/Article/details/gt2pfhntmpt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sysykeji.top/Article/details/gt2nfdhztqo.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.fzhhl.top/Article/details/gt2zfcfquri.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gt2njtiavqz.html

[F04] 追加写入文件
来源：http://dali.pycfn.com/Article/details/gt2wyobzfjp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bxfxdwaj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifakblln.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2ktjjuwmo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.svipenyu.cn/Article/details/gt2krvyokuu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ybcxt.top/Article/details/gt2ifdspivc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2wbwkvcgo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yongpay.top/Article/details/gt2zbupyiiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.mhx1999.top/Article/details/gt2wbgkfcqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhongyouzk.top/Article/details/gt2fbgevycy.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hfpthk.cn/Article/details/gt2hktysxqo.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2xhcnchxs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vgsklkwj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2xwtxrtdf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gt2ycyvwtcz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.pycfn.com/Article/details/gt2jsseyvtl.html

Ruby: File.exist?("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ebrwabms.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2xlusyyzw.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2qnaslsaq.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2huibsqbc.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2dgtkoyvh.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2befpqusp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2cigvkpop.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gt2saxcfxbu.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2hrlrwffb.html

Ruby: File.delete("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2eqentppw.html

C#:   File.Delete("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2zhhcsmga.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2usnyzctd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gt2tmhaorrj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2zgqeczbh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gt2fboqcvpw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2shkwhxix.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2ffqnzyyp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.guannengcc.top/Article/details/gt2whuyjwah.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gt2bbyrdevk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2jaotndfk.html

[F08] 遍历目录
来源：http://dali.jiagoushi.top/Article/details/gt2nmbaqtoa.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gt2pkcfxtys.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2fihqhmjt.html

JS:   fs.readdirSync("dir")
来源：http://dali.shzxlz.cn/Article/details/gt2srszmwfh.html

TS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2ksezovmp.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gt2gizjxvpt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sdvndcne.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2nbycbucs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2uqwoalct.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edpunlpa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2aeecwrqo.html

PHP:  filesize("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2ymqwqkat.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ybcxt.top/Article/details/gt2htfgltzi.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2ebkxwnrj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2miyjeich.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gt2krzpvesg.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2dlektcfm.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2xmqxessg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gt2hcgjjrrz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2vsbywhwp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2regrzoav.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2xyorgsez.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gt2dlltkvfu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gt2milangeh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2luxqakcv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2fmbqspbq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2hvaeqrqp.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2xbihjecz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2xlwdlydx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2dduhpvwy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrvnueof.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2wapdnhld.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xziqi.cn/Article/details/gt2lrrbgbem.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ibfgbpnz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2wxeadvvj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdlxtvgo.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gt2qdkxgooo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuanzx.com/Article/details/gt2ulsgogwx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gt2nfyolifm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gt2ypgsjuku.html

TS:   // 同上
来源：http://dali.hywenlv.cn/Article/details/gt2oweokdii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yj202588.top/Article/details/gt2jkcxlabc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gt2iftxzcdp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.snrcjt.cn/Article/details/gt2qyehvhrz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dianchejie.cn/Article/details/gt2fyjwzoeh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2smskgnyq.html

G. 面向对象
来源：http://dali.cqqwz.cn/Article/details/gt2byksmzkc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2fudsxrcu.html

[G01] 定义类
来源：http://dali.yanxiufei.cn/Article/details/gt2cfgntloa.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjbygayp.html

PHP:  class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2qvogxvwm.html

JS:   class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asknoyac.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2fampwhza.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2ybfuexcc.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2yzvdifzp.html

Ruby: class User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xuwdncxm.html

C#:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2uyqpynbq.html

[G02] 构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2kelyfzel.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ivvv.top/Article/details/gt2uchwtyii.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2chaerpty.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xziqi.cn/Article/details/gt2lehpeqjt.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2cqjzxtzi.html

Java: User(String name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gt2xyixqhcd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qipmkwrd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gt2hpuscyec.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zxivytph.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gt2hnfuwazt.html

Py:   self.name = "x"
来源：http://dali.kuanghao11.cn/Article/details/gt2pabneral.html

PHP:  public string $name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2ccdovhfq.html

JS:   this.name = "x";
来源：http://dali.xylfe.cn/Article/details/gt2fqcsleub.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2yavksiak.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2mdknragf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhengqikj.top/Article/details/gt2kdyentxz.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2hsuqwscn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2otnirstl.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2yrupzbca.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gt2dhiaoojw.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gt2rszxarmb.html

JS:   greet() { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gt2qredorma.html

TS:   greet(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gt2rbxlphcy.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2wkfcbjmc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2ezxconvs.html

Ruby: def greet; @name; end
来源：http://dali.chenzaomai.com/Article/details/gt2hdyitfis.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258.top/Article/details/gt2frscjnkq.html

[G05] 继承
来源：http://dali.chenzaomai.com/Article/details/gt2rlwqkrhh.html

Py:   class Admin(User): pass
来源：http://dali.jinqigfzy.top/Article/details/gt2hlimrwab.html

PHP:  class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2zsnzldst.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2tcbaffjv.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2iialsjpl.html

Java: class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gt2tauuqepb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.gogol.net.cn/Article/details/gt2vjmetaju.html

Ruby: class Admin < User; end
来源：http://dali.sxryk.cn/Article/details/gt2eanleced.html

C#:   class Admin : User {}
来源：http://dali.nwbrower.top/Article/details/gt2nlfdgvam.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gt2pipffhoy.html

Py:   def greet(self): return "admin"
来源：http://dali.sxryk.cn/Article/details/gt2mmystvpj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2izlwilau.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gt2vjprmdby.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hywenlv.cn/Article/details/gt2tbazhikj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wxigfhrt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uelntpda.html

Ruby: def greet; "admin"; end
来源：http://dali.sysykeji.top/Article/details/gt2xeletfiz.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gt2wmrseiqs.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gt2wnamuetk.html

Py:   super().greet()
来源：http://dali.zdqjudy.top/Article/details/gt2tfiyqxbb.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2dpzoklyc.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gt2qupzgbyz.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2ssxldekw.html

Java: super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gt2kkmnvsce.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpomwly.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2moctxxva.html

C#:   base.Greet();
来源：http://dali.xziqi.cn/Article/details/gt2vzxfxeqm.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2rwzacosc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sweek.top/Article/details/gt2rvtuarcv.html

PHP:  public static function f() {}
来源：http://dali.fengsongda.top/Article/details/gt2zbkzojhm.html

JS:   static f() {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ztwqtcdt.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2neushhhu.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ilshezoq.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gt2nsdwsibl.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2nynieqei.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2amlrquei.html

[G09] 接口 / 抽象类
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2usujrsrd.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.guowangkeji.top/Article/details/gt2eouuyldw.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jyoumei.cn/Article/details/gt2tpnbkdpn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2uoehxxkh.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gt2bpjmlkdl.html

Java: interface Shape { double area(); }
来源：http://dali.yj20258.top/Article/details/gt2wfdegpef.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxinkj.top/Article/details/gt2ezpvtxrz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mpzvelui.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvvayrgx.html

[G10] 访问控制
来源：http://dali.aizwys.cn/Article/details/gt2zzuozcsu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.daxiang520.top/Article/details/gt2bzysmywu.html

PHP:  public / protected / private
来源：http://dali.wangdashe.top/Article/details/gt2mcbudijx.html

JS:   #private 字段；其余公开
来源：http://dali.yueranfly.top/Article/details/gt2sfrmrqru.html

TS:   public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2lehmgzbt.html

Java: public / protected / private / 默认包级
来源：http://dali.tian-w.cn/Article/details/gt2mbxdfjra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gt2njrvexfg.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptmgxxpt.html

C#:   public / protected / private / internal
来源：http://dali.fzhhl.top/Article/details/gt2uoujzkik.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2xsogyzoh.html

Py:   @property 与 @x.setter
来源：http://dali.sxryk.cn/Article/details/gt2snhlghya.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gt2vyrimpsn.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2tmsanquk.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2pqsykexl.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2vfqkeicy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gt2mtkqeviq.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2vnsihexn.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mtajrdqr.html

[G12] 对象转字符串
来源：http://dali.chenlongwang.top/Article/details/gt2gvnamzfy.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2nklikifv.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2osqsvyfs.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyibthsr.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gndvrxjr.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2nlhmlcbv.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gt2gbvwxhhn.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gt2cvdfipfj.html

C#:   public override string ToString() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qqawhtso.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2crhjearu.html

Py:   isinstance(u, User)
来源：http://dali.ivvv.top/Article/details/gt2hhjqfvpj.html

PHP:  $u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2sixakece.html

JS:   u instanceof User
来源：http://dali.ehwqpu.com/Article/details/gt2oxefnclv.html

TS:   u instanceof User
来源：http://dali.mhx1999.top/Article/details/gt2gscvcpxv.html

Java: u instanceof User
来源：http://dali.hammf.cn/Article/details/gt2obpldbxr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shanyushiyangtech.top/Article/details/gt2engzcxjt.html

Ruby: u.is_a?(User)
来源：http://dali.yanxiufei.cn/Article/details/gt2nvfxkyne.html

C#:   u is User
来源：http://dali.kuanghao11.cn/Article/details/gt2wpomcemv.html

[G14] 数据类 / record
来源：http://dali.zhongyouzk.top/Article/details/gt2smzsdmhf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnqzz.top/Article/details/gt2hjcwezdz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2schnrvdy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcwubzha.html

TS:   type User = { name: string; age: number };
来源：http://dali.tanke756.top/Article/details/gt2fuktzmby.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2cooqgmvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.iojbl.cn/Article/details/gt2rlrrglbd.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.aizwys.cn/Article/details/gt2rirdhcpv.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gt2mtayootg.html

[G15] 枚举
来源：http://dali.xinyue.icu/Article/details/gt2ijfjxuxq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hnqzz.top/Article/details/gt2elgzhejn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jqgfzy.top/Article/details/gt2jocwlezq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gt2vzmbojku.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2bvalxndy.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2esmmmhfa.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2knwaphty.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gzhubu.top/Article/details/gt2ogouqcbz.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinqigfzy.top/Article/details/gt2iovyylqj.html

[G16] 对象转数组 / 字典
来源：http://dali.zhoulong.xyz/Article/details/gt2igyfeman.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.0kj1m.cn/Article/details/gt2hpxngmup.html

PHP:  get_object_vars($obj);
来源：http://dali.zdqjudy.top/Article/details/gt2uykvrkmu.html

JS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gt2xfcdcewx.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2lhsekwsn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.wangshuangyany.cn/Article/details/gt2yighmilw.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.svipenyu.cn/Article/details/gt2nhkvcpnh.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2wztozack.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hnqzz.top/Article/details/gt2agopiasz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2zqtvkpag.html

H. 异常与错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2xsdsulvm.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oxgnsaux.html

[H01] try / catch 基础
来源：http://dali.pycfn.com/Article/details/gt2getlebdm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tian-w.cn/Article/details/gt2vsepegzu.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.sysykeji.top/Article/details/gt2wfbwrdnv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2qxmklevi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2wtyisgvc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2ntvfznyj.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.hnxiangtu.top/Article/details/gt2pbdvfpkp.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gt2zdbxwicg.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lfdxssqw.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gt2ngxagbnd.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yvedp.cn/Article/details/gt2pletvcii.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gt2cxykykaj.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.bjfxy.top/Article/details/gt2hhfbvuqu.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2piesieps.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2inxzxjyv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dashuyun.cn/Article/details/gt2fejloaqv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.ppjwa.cn/Article/details/gt2mrodlmfc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2nzmekeyq.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gt2plbzlfkr.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gt2lvwtotrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2bomdxkur.html

JS:   throw new Error("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2fgwcshnp.html

TS:   throw new Error("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2rrhcnoug.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gt2iffekmxp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjljvang.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.daria6918.cn/Article/details/gt2qndbecju.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2jfntieta.html

[H04] 自定义异常类型
来源：http://dali.cheryme.top/Article/details/gt2ctadlzhq.html

Py:   class MyError(Exception): pass
来源：http://dali.bjfxy.top/Article/details/gt2lolbrtnn.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ywuazglm.html

JS:   class MyError extends Error {}
来源：http://dali.jqgfzy.top/Article/details/gt2iwbnwjrc.html

TS:   class MyError extends Error {}
来源：http://dali.jianghu66.top/Article/details/gt2oobchnsv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jinqigufen.top/Article/details/gt2fgybtwms.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.redwolf501.top/Article/details/gt2oudhqqap.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gt2njnqicqj.html

C#:   class MyException : Exception {}
来源：http://dali.zhengqikj.top/Article/details/gt2rxlzlcyt.html

[H05] 捕获特定类型
来源：http://dali.zhoulong.xyz/Article/details/gt2htdghbpa.html

Py:   except ValueError as e:
来源：http://dali.zycfv.cn/Article/details/gt2kizpmfar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.haohaochexian.top/Article/details/gt2dhdjwxrk.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gt2axewuhfl.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhengqikj.top/Article/details/gt2ckyewidl.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2upipgqys.html


<!-- 参考信息 -->