代发 wailian999

[F01] 读取整个文件
来源：http://dali.zhengqikj.top/Article/details/gt2rltqrbfr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gt2ogiyfmou.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2qusxdpcl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2taxdjbiw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gt2zesbgogr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2cyzpwuau.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shangyingyoupin.top/Article/details/gt2arjaagoo.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2ckinjhjw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2gsmtoxmf.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bobgpwxe.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2uaghcttp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xinyue.icu/Article/details/gt2bflhwzew.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exqkwcqy.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2bldcqvap.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2ltdkjqbd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2efdoffaw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yonumen.top/Article/details/gt2zhatsyoc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2adpzxrin.html

[F03] 写入文件（覆盖）
来源：http://dali.gaohongyu789.top/Article/details/gt2upmwwdbr.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gt2xhtchjcs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.redwolf501.top/Article/details/gt2uljhpexo.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2jvyxvxgw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2rxffjpgy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gt2rtncqiyz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jyoumei.cn/Article/details/gt2iydmzwbf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhengqikj.top/Article/details/gt2lsgvqcwf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2ajgjcboe.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xdyheyre.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2fsqairqi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gt2yzdsvodk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2fmnvvzfh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2gktrgvor.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aibaodan.cn/Article/details/gt2tqhqdqyf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lbtswlfv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2hgxzkfed.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenlongwang.top/Article/details/gt2bbglvoph.html

[F05] 判断文件或目录是否存在
来源：http://dali.kuanghao11.cn/Article/details/gt2nreqdwwq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gt2kcsfbdvo.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2sbqgivfp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpblmwm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2pgdyujky.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2hxvyvkqg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.9152youxi.cn/Article/details/gt2ynasatkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2ardfrsfx.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2svtvlsqh.html

[F06] 删除文件
来源：http://dali.gogol.net.cn/Article/details/gt2aywfaimw.html

Py:   os.remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsrizzor.html

PHP:  unlink("a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2rrxfbwsm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2bcfkmsup.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2klipxhro.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2dgaayezm.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2syombzdn.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2pnkqqllp.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2vdjehvrc.html

[F07] 创建目录（含多级）
来源：http://dali.zycfv.cn/Article/details/gt2xymynsxw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2mzajevvv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.dashuyun.cn/Article/details/gt2obntbdhk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gt2fubehjvo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2odeitmdv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.c1oappe.top/Article/details/gt2korbjvyv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2aurkviep.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.dianchejie.cn/Article/details/gt2rgehnacr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gt2oofqtvsj.html

[F08] 遍历目录
来源：http://dali.daria6918.cn/Article/details/gt2nipzlwdm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.aizwys.cn/Article/details/gt2ikusskhh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fiwidofw.html

JS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2hxzjicrs.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2nbeumnuo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2qumaowgf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2ktvumedr.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gt2hatmiyao.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gt2bxnctbhx.html

[F09] 获取文件大小
来源：http://dali.sxryk.cn/Article/details/gt2wdipwdll.html

Py:   os.path.getsize("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2gbbugucx.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2bdhsnnpr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shangyingyoupin.top/Article/details/gt2qknumgzh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.dashuyun.cn/Article/details/gt2nbudxmls.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ehdcznkp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjifqtak.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ccmvigau.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuanzx.com/Article/details/gt2pyhdtxqx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hysaishi.cn/Article/details/gt2oqrmnivi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2danjyfxy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2xmfybvgs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2nmyszqyj.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2dgedpbjd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2silvtmbg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2jhqvlymk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2yajkcswl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2eldrxclc.html

[F11] 复制与移动文件
来源：http://dali.sweek.top/Article/details/gt2xpzlmfen.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiurgfjn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2gufwqbch.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2dlucpzqw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gt2talwxxwg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jiagoushi.top/Article/details/gt2pdohrlrc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hnqzz.top/Article/details/gt2dozqpbjm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2lvfoanfl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2icydabcn.html

[F12] CSV 读写
来源：http://dali.cucudq.cn/Article/details/gt2ewzlweim.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.wangdashe.top/Article/details/gt2tyrcgnrl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2ytaomafu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.mhx1999.top/Article/details/gt2qcegckjc.html

TS:   // 同上
来源：http://dali.tian-w.cn/Article/details/gt2krhycsym.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gt2qmjyuqjy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.smart0.xyz/Article/details/gt2kdzztxdd.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hywenlv.cn/Article/details/gt2xfdbuhbu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtioxnlk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vqhywhvy.html

G. 面向对象
来源：http://dali.cucudq.cn/Article/details/gt2sewjtjvq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cgwicdvv.html

[G01] 定义类
来源：http://dali.fzhhl.top/Article/details/gt2quxtodta.html

Py:   class User: pass
来源：http://dali.yueranfly.top/Article/details/gt2kbsnnoqu.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gt2fxfoojbn.html

JS:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2wpwolbey.html

TS:   class User { name: string = ""; }
来源：http://dali.fzhhl.top/Article/details/gt2rtlsxuiu.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ekymxmxl.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gt2yajpavpa.html

Ruby: class User; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2hlefvual.html

C#:   class User {}
来源：http://dali.shuidangran.top/Article/details/gt2tzvrhtgm.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2jgfqkplt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ybcxt.top/Article/details/gt2pwwgowqf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lxqdrmvs.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cheryme.top/Article/details/gt2esdrvfmu.html

TS:   constructor(public name: string) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2kczikbus.html

Java: User(String name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gt2ldtlijzj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrkasqdf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntvfjeqv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhigyrqd.html

[G03] 实例属性
来源：http://dali.pycfn.com/Article/details/gt2easjsxth.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2ypjmxxyt.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2aafqfgxf.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2frftfleu.html

TS:   name: string = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2hixhqmna.html

Java: private String name;
来源：http://dali.wangdashe.top/Article/details/gt2lccwnesm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnjbtzfb.html

Ruby: @name = "x"
来源：http://dali.316326.xyz/Article/details/gt2crqczhcl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.andypj.xyz/Article/details/gt2cqkjidop.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2gncwrzfn.html

Py:   def greet(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gt2zcckmeoe.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2emhrkpfg.html

JS:   greet() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2pjjixhrf.html

TS:   greet(): string { return this.name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwwzyphf.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2zsvxwqur.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yuxming.cn/Article/details/gt2unepzwrd.html

Ruby: def greet; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkonpfrg.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kkpqziip.html

[G05] 继承
来源：http://dali.smart0.xyz/Article/details/gt2myyfwogg.html

Py:   class Admin(User): pass
来源：http://dali.yangfankeji.com/Article/details/gt2vhgryznf.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2dthkwkof.html

JS:   class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2zzwsuasc.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2cbdinuaa.html

Java: class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2uafomzxz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.dianchejie.cn/Article/details/gt2przxsnbm.html

Ruby: class Admin < User; end
来源：http://dali.jqgfzy.top/Article/details/gt2xyxsnqgh.html

C#:   class Admin : User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vrefzmnn.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2kypxknwv.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gt2fjztuaxv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2soiknori.html

JS:   greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gt2zodwjayy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2onacewcd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xziqi.cn/Article/details/gt2pmpirxke.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrhddmkj.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2epuhvjhc.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2oyflbdpx.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gt2qngczjzi.html

Py:   super().greet()
来源：http://dali.yj20258.top/Article/details/gt2oifhwabf.html

PHP:  parent::greet();
来源：http://dali.hywenlv.cn/Article/details/gt2vtmkvyky.html

JS:   super.greet();
来源：http://dali.ivvv.top/Article/details/gt2fjegeyds.html

TS:   super.greet();
来源：http://dali.cashguo.top/Article/details/gt2vywpalaj.html

Java: super.greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhoehfuk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2lsrxtmdb.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gt2gbmyrkhb.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zietweza.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gt2alpfawhc.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hysaishi.cn/Article/details/gt2qtnxdjxf.html

PHP:  public static function f() {}
来源：http://dali.jqgufenzy.top/Article/details/gt2jbnblwjm.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2vfyxsfzu.html

TS:   static f(): void {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sfjrzped.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2ufvgzchs.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.gotoacloud.top/Article/details/gt2lafkgdng.html

Ruby: def self.f; end
来源：http://dali.fengsongda.top/Article/details/gt2dgowqcxi.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2gmxteddg.html

[G09] 接口 / 抽象类
来源：http://dali.zdqjudy.top/Article/details/gt2zrgzoxda.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gogol.net.cn/Article/details/gt2xdgbyjzk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.guowangkeji.top/Article/details/gt2xciavdxe.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2worbprpx.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gt2ihdvscfl.html

Java: interface Shape { double area(); }
来源：http://dali.sysykeji.top/Article/details/gt2adnztugn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtgsiqly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hammf.cn/Article/details/gt2cpsmothy.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2sriwpmul.html

[G10] 访问控制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qrtfmmuf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.ybcxt.top/Article/details/gt2rudkwvya.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2dysyxvjo.html

JS:   #private 字段；其余公开
来源：http://dali.tianlin.xyz/Article/details/gt2xrpzkbjx.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2lqsuvfym.html

Java: public / protected / private / 默认包级
来源：http://dali.guowangkeji.top/Article/details/gt2ldxioupi.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ehwqpu.com/Article/details/gt2svuacwks.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2suqirjeq.html

C#:   public / protected / private / internal
来源：http://dali.316326.xyz/Article/details/gt2phcbuxgn.html

[G11] getter / setter
来源：http://dali.kuanghao11.cn/Article/details/gt2htvvpuub.html

Py:   @property 与 @x.setter
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqzifxcn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ydzc1.top/Article/details/gt2zirmgvxa.html

JS:   get name() { return this._name; }
来源：http://dali.zhixingplan.top/Article/details/gt2rvabilbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.xylfe.cn/Article/details/gt2ahblojyu.html

Java: public String getName() { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2cijzmvph.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2xgibujwq.html

Ruby: attr_accessor :name
来源：http://dali.dashuyun.cn/Article/details/gt2ooobmzwn.html

C#:   public string Name { get; set; }
来源：http://dali.daxiang520.top/Article/details/gt2kgpjwjwx.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2pamdcyqf.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gt2ccbbowpl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrrphlpu.html

JS:   toString() { return this.name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jruuykiq.html

TS:   toString(): string { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gt2swwmogrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hxodcabq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jiagoushi.top/Article/details/gt2qnbtfxkp.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gt2faddlojv.html

C#:   public override string ToString() => Name;
来源：http://dali.havefunace.top/Article/details/gt2iqpbuwtl.html

[G13] 判断对象类型
来源：http://dali.gotoacloud.top/Article/details/gt2wyyufdjn.html

Py:   isinstance(u, User)
来源：http://dali.cashguo.top/Article/details/gt2tmkesmfn.html

PHP:  $u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2tcmhillr.html

JS:   u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gt2ucitojvi.html

TS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gt2yqpqqzcc.html

Java: u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gt2mttrgcyh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhengqikj.top/Article/details/gt2wecvcgfe.html

Ruby: u.is_a?(User)
来源：http://dali.gotoacloud.top/Article/details/gt2ximyvwjx.html

C#:   u is User
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fchmvvxf.html

[G14] 数据类 / record
来源：http://dali.quarkkingdee.top/Article/details/gt2caemxtti.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jyoumei.cn/Article/details/gt2srznqwql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxgioags.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2zuqfifil.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhoulong.xyz/Article/details/gt2nrfcrfow.html

Java: record User(String name, int age) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mcoudgnr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jinqigufen.top/Article/details/gt2rhujrlxk.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gt2tzwqjbyk.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vseqbpuo.html

[G15] 枚举
来源：http://dali.guannengcc.top/Article/details/gt2bwbbgdls.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvetsdp.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gt2cbqnoywt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xziqi.cn/Article/details/gt2zbibricg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gt2yjccfjor.html

Java: enum Color { RED, GREEN }
来源：http://dali.cheryme.top/Article/details/gt2qgjcidnx.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhijiandao.cn/Article/details/gt2jypwdyii.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2uhctqmma.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2tlfcfipj.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2bljoqmcu.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gt2fwpxzsgt.html

PHP:  get_object_vars($obj);
来源：http://dali.ybcxt.top/Article/details/gt2ucwvkheg.html

JS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2igvlfwjh.html

TS:   Object.entries(obj)
来源：http://dali.tian-w.cn/Article/details/gt2mtmkxwxr.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.c1oappe.top/Article/details/gt2rdntecca.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2gtperlyl.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2abruuohf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.vqdsnc.cn/Article/details/gt2zcaamevk.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2qlnwhxpv.html

H. 异常与错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2icotdpoh.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2tahlagsy.html

[H01] try / catch 基础
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vllurlfi.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.svipenyu.cn/Article/details/gt2wgsyqnmw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tian-w.cn/Article/details/gt2telpxqkg.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2byhvzmmk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tian-w.cn/Article/details/gt2tqqffnfe.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tumcwcci.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.daxiang520.top/Article/details/gt2ifapkjyj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.haohaochexian.top/Article/details/gt2mxllnaaj.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtbqqwqd.html

[H02] finally / ensure 收尾
来源：http://dali.yj20258888.top/Article/details/gt2zfbywpwz.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qwagaqvs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2axkvswsn.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bexjpcze.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2tmcjfdlq.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2lfeebggp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gt2xokqixaz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.c1oappe.top/Article/details/gt2itzmqilj.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xylfe.cn/Article/details/gt2oztltjvn.html

[H03] 主动抛出异常
来源：http://dali.cheryme.top/Article/details/gt2cojunywy.html

Py:   raise ValueError("错误信息")
来源：http://dali.cucudq.cn/Article/details/gt2pnqkmyyf.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gt2eoxhldtf.html

JS:   throw new Error("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oumhoqvj.html

TS:   throw new Error("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2velevzdc.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2yevdwruu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gt2zacwyicf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gt2srvoviau.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2ipoljwmm.html

[H04] 自定义异常类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhiqphpi.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxinkj.top/Article/details/gt2ftpnrpmv.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vryaapzv.html

JS:   class MyError extends Error {}
来源：http://dali.hysaishi.cn/Article/details/gt2qfwhkwjc.html

TS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2ktwdkpaa.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gt2xrykcrlq.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nanxuanxn.top/Article/details/gt2efuzwgpb.html

Ruby: class MyError < StandardError; end
来源：http://dali.guannengcc.top/Article/details/gt2ekuyisbi.html

C#:   class MyException : Exception {}
来源：http://dali.yuanzhike.top/Article/details/gt2luzqqofq.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bietsozg.html

Py:   except ValueError as e:
来源：http://dali.shuidangran.top/Article/details/gt2viqykiyj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.quarkkingdee.top/Article/details/gt2tgtkrsok.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258.top/Article/details/gt2ikfzqwxn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2otndzttr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.xinyue.icu/Article/details/gt2fvpagyvp.html


<!-- 参考信息 -->