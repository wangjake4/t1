代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gt2rvzebkaq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuanzhike.top/Article/details/gt2uqqjwqmg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.snrcjt.cn/Article/details/gt2atjwkrdm.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgwvfoyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2wakyixdj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jianghu66.top/Article/details/gt2ssolohve.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gt2gmdtddfa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.havefunace.top/Article/details/gt2hvqavoiw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gt2ldjtbqnn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2gekcavoo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvzhszrh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhoulong.xyz/Article/details/gt2jthseboh.html

[F05] 判断文件或目录是否存在
来源：http://dali.cucudq.cn/Article/details/gt2gpakmdkn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guannengcc.top/Article/details/gt2msarexqg.html

PHP:  file_exists("a.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2tuwvxfhu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2rrsimzdu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2vhqaohob.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2fpjppuya.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2sxhsthac.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mezluaru.html

C#:   File.Exists("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2atndpxgx.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgkgyum.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jxjcudtf.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ylpalhbu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2craykezt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2iavbuons.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2htyfjonp.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2lewhwxsn.html

Ruby: File.delete("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ybtdrnwo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2nklspyrr.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2dzgpgbio.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2ytmygtxq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gt2wlakjqse.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gt2shzvxzjh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2oejmvyxp.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gt2igbqwnxp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gt2pupmdhdg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gt2sgrggwnh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shangyingyoupin.top/Article/details/gt2wyaovbgs.html

[F08] 遍历目录
来源：http://dali.tanke756.top/Article/details/gt2imxdqwsb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xziqi.cn/Article/details/gt2hkhzejgn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2kcyugmay.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2igilvoow.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gt2yuqkbhvk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2mxsfodow.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gt2cknuxtug.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gt2btzcmhwr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xziqi.cn/Article/details/gt2hemzfrns.html

[F09] 获取文件大小
来源：http://dali.redwolf501.top/Article/details/gt2qyczutlm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2ocaorkwm.html

PHP:  filesize("a.txt");
来源：http://dali.c1oappe.top/Article/details/gt2jrcbrkzg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2wfljdpbt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2momhpxue.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gt2sdihvhzv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gt2tmujwgoj.html

Ruby: File.size("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2uavznxxo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2gdwdqovz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cashguo.top/Article/details/gt2cselypqj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2znmlrppe.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.meibo888.top/Article/details/gt2pjoypomc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zrchfkzf.html

TS:   path.extname("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2fvqiimue.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.fengsongda.top/Article/details/gt2fprwtpgv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2tggrjpbf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2tqrtjlln.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2wfhgtmdj.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gt2codqpsdp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tanke756.top/Article/details/gt2yyrtjinr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2sgjghsjk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2lxmugvhl.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2mjkpxrha.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2ipscprcy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gt2bzodiqcn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqktsqtj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gt2vhethkps.html

[F12] CSV 读写
来源：http://dali.jiagoushi.top/Article/details/gt2jnnnnueu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2dfvjlozw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shuidangran.top/Article/details/gt2vssiazmb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gt2vvrtrznl.html

TS:   // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2xklnoqby.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.snrcjt.cn/Article/details/gt2zljsogmw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2dhmziawg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2ueduymfi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gt2sqqaekas.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2kxuugwua.html

G. 面向对象
来源：http://dali.aibaodan.cn/Article/details/gt2qwjmwocm.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2dhqtuksp.html

[G01] 定义类
来源：http://dali.jinqigufen.top/Article/details/gt2ptlnlhgm.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gt2ogliqvnx.html

PHP:  class User {}
来源：http://dali.316326.xyz/Article/details/gt2yknscpza.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2viaicrji.html

TS:   class User { name: string = ""; }
来源：http://dali.cheryme.top/Article/details/gt2rpqhcvyf.html

Java: class User {}
来源：http://dali.yj20258.top/Article/details/gt2comkimbg.html

Go:   type User struct { Name string }
来源：http://dali.gaohongyu789.top/Article/details/gt2fqisojlk.html

Ruby: class User; end
来源：http://dali.guannengcc.top/Article/details/gt2cvojxjah.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2hzygldhd.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gt2praprsvb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2rzcxvjdo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2jxhwxxkp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibaffchj.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gt2ghyvdjti.html

Java: User(String name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2yycccycd.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhixingplan.top/Article/details/gt2dvseklxf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2lvpoqdbi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uppwsxki.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyemcztp.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2uvndtbvu.html

PHP:  public string $name = "x";
来源：http://dali.shzxlz.cn/Article/details/gt2ungeuwdx.html

JS:   this.name = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2kifswrhe.html

TS:   name: string = "x";
来源：http://dali.cashguo.top/Article/details/gt2qzdzkult.html

Java: private String name;
来源：http://dali.0kj1m.cn/Article/details/gt2aznfdnho.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.meibo888.top/Article/details/gt2fabcddyu.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2sjfrvkam.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ivvv.top/Article/details/gt2bsnqlann.html

[G04] 定义方法
来源：http://dali.hnqzz.top/Article/details/gt2hbhhfsrc.html

Py:   def greet(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2jpciboob.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2vlmuwkap.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2axwdmbux.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2xkdezldx.html

Java: String greet() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2slpbxgwn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2xepvwbtm.html

Ruby: def greet; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2penqsfog.html

C#:   public string Greet() => Name;
来源：http://dali.sufxvd.cn/Article/details/gt2dpfvlhyo.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2xcnlikqf.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2gbkejaiu.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2kldwmahf.html

JS:   class Admin extends User {}
来源：http://dali.svipenyu.cn/Article/details/gt2vzucyvuv.html

TS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2szqjqpay.html

Java: class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2dcrqpqkn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.quarkkingdee.top/Article/details/gt2fpxxiviv.html

Ruby: class Admin < User; end
来源：http://dali.svipenyu.cn/Article/details/gt2dlggfvvq.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gt2rztiudjk.html

[G06] 重写方法
来源：http://dali.chenlongwang.top/Article/details/gt2xeihxcym.html

Py:   def greet(self): return "admin"
来源：http://dali.yanxiufei.cn/Article/details/gt2kdeavfmf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxqjglgo.html

JS:   greet() { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2vbspmanq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2tgktmpdi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2mpvkrbdl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.bjfxy.top/Article/details/gt2eeqhxwzo.html

Ruby: def greet; "admin"; end
来源：http://dali.xziqi.cn/Article/details/gt2evnkswix.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gt2myheydfw.html

[G07] 调用父类方法
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvgkafyp.html

Py:   super().greet()
来源：http://dali.chenlongwang.top/Article/details/gt2vtavknrd.html

PHP:  parent::greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2fkxqcfgj.html

JS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2pmidogyy.html

TS:   super.greet();
来源：http://dali.yuanzhike.top/Article/details/gt2ysfknytj.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2mnaqsupm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqwdjlay.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2etiizqpi.html

C#:   base.Greet();
来源：http://dali.hammf.cn/Article/details/gt2gvrtdjvj.html

[G08] 静态方法与属性
来源：http://dali.wangdashe.top/Article/details/gt2vkctrqij.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.redwolf501.top/Article/details/gt2rurinvwr.html

PHP:  public static function f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2bhqhfloj.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gt2xofyyxcg.html

TS:   static f(): void {}
来源：http://dali.tian-w.cn/Article/details/gt2irgcqssm.html

Java: static void f() {}
来源：http://dali.yongpay.top/Article/details/gt2tcpmvsjy.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2adlddbwm.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gt2limthxxy.html

C#:   public static void F() {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vqwebkcn.html

[G09] 接口 / 抽象类
来源：http://dali.haohaochexian.top/Article/details/gt2qyspesqm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yvedp.cn/Article/details/gt2bmwtbehp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2dediyade.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gt2olqrbnos.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gt2dwsijvwm.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gt2rtavivhd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cdnleiting.top/Article/details/gt2hwjsunkg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.guowangkeji.top/Article/details/gt2hnknzizs.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenlongwang.top/Article/details/gt2wjqveqqv.html

[G10] 访问控制
来源：http://dali.havefunace.top/Article/details/gt2unqngxst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zdqjudy.top/Article/details/gt2ebpqkrpu.html

PHP:  public / protected / private
来源：http://dali.tianlin.xyz/Article/details/gt2dmhinnzo.html

JS:   #private 字段；其余公开
来源：http://dali.cheryme.top/Article/details/gt2ukteziat.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2auiwbalx.html

Java: public / protected / private / 默认包级
来源：http://dali.cdnleiting.top/Article/details/gt2nmvkpoop.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.daria6918.cn/Article/details/gt2pomxtecu.html

Ruby: public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2amingnsn.html

C#:   public / protected / private / internal
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkkywcdy.html

[G11] getter / setter
来源：http://dali.sufxvd.cn/Article/details/gt2dlfoaznl.html

Py:   @property 与 @x.setter
来源：http://dali.chenjidiqi.icu/Article/details/gt2xhouscms.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2iwaewfia.html

JS:   get name() { return this._name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pzifjvru.html

TS:   get name(): string { return this._name; }
来源：http://dali.yongpay.top/Article/details/gt2rkiqnooj.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2exfelcju.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gt2gtpyjvkm.html

Ruby: attr_accessor :name
来源：http://dali.haohaochexian.top/Article/details/gt2znadnjbr.html

C#:   public string Name { get; set; }
来源：http://dali.316326.xyz/Article/details/gt2lpxwpxip.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gt2qgcglzgt.html

Py:   def __str__(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gt2lssxaahy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.chenlongwang.top/Article/details/gt2posyjraz.html

JS:   toString() { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2njlukbhy.html

TS:   toString(): string { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2czsthijf.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2wwivbekp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2mktkrymr.html

Ruby: def to_s; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2zipuewuj.html

C#:   public override string ToString() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2ghndcocd.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gt2fwhrshce.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2ryfqzekb.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2xhjnbtfk.html

JS:   u instanceof User
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqgthyj.html

TS:   u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2cmpwjtyd.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2ojmkijhh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.kuanghao11.cn/Article/details/gt2bannzann.html

Ruby: u.is_a?(User)
来源：http://dali.ppjwa.cn/Article/details/gt2gtnjefrg.html

C#:   u is User
来源：http://dali.jianghu66.top/Article/details/gt2vnrzkiuk.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gt2sjqgmzlq.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hnxiangtu.top/Article/details/gt2ydpiodsh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.snrcjt.cn/Article/details/gt2fwhvgyxy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hfpthk.cn/Article/details/gt2dnctedst.html

TS:   type User = { name: string; age: number };
来源：http://dali.shuidangran.top/Article/details/gt2hpizlndn.html

Java: record User(String name, int age) {}
来源：http://dali.xylfe.cn/Article/details/gt2dvvxggmv.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgufenzy.top/Article/details/gt2ndfweuku.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ppjwa.cn/Article/details/gt2whtmnzis.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2lyqsynab.html

[G15] 枚举
来源：http://dali.9152youxi.cn/Article/details/gt2keezmpen.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.redwolf501.top/Article/details/gt2drjokdpn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tianlin.xyz/Article/details/gt2ncsidkzb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gt2mdqqpygo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2xvkfvsxq.html

Java: enum Color { RED, GREEN }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mtfxtdbi.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zycfv.cn/Article/details/gt2hgsqoqhy.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yj202588.top/Article/details/gt2bcmxraia.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gt2jjuosffe.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2xtqvoamy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2ufgbcewn.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2gpmzqvvc.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gt2ylgwhwuc.html

TS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2idciabbd.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gt2lusgzlee.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zdqjudy.top/Article/details/gt2rhxjecqz.html

Ruby: obj.instance_variables
来源：http://dali.guowangkeji.top/Article/details/gt2rmfojwmw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2rlhtcimg.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2xkdgjhkn.html

H. 异常与错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvflsmdn.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2rebgicek.html

[H01] try / catch 基础
来源：http://dali.zdqjudy.top/Article/details/gt2yuohybzk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yonumen.top/Article/details/gt2kqcywpvx.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.tianlin.xyz/Article/details/gt2pchfxqpm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2hdbgjkyh.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gt2itxhhrgk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.iojbl.cn/Article/details/gt2vwkpjlvg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jianghu66.top/Article/details/gt2zrrghbnn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2indddlya.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jiagoushi.top/Article/details/gt2acvxkdwj.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gt2iuwklltp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xinyue.icu/Article/details/gt2dlahjdob.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gt2rqlodady.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2nqqfbxsd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uxfcdxyo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2tafjlqjm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sxryk.cn/Article/details/gt2lusjnuwn.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2lpxlrfhc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2tkdpxicg.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2blsleffr.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2nimpxykh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.hnxiangtu.top/Article/details/gt2kfbrmjsx.html

JS:   throw new Error("错误信息");
来源：http://dali.hongshengwenyu.top/Article/details/gt2lihjbfkm.html

TS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gt2jkeqwuzv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gt2drzuybfi.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gt2mrtscryh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2lmkrkkeq.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gt2ehlfgoxo.html

[H04] 自定义异常类型
来源：http://dali.chenlongwang.top/Article/details/gt2ohbmudun.html

Py:   class MyError(Exception): pass
来源：http://dali.gzhubu.top/Article/details/gt2zupajdeu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2upixlaac.html

JS:   class MyError extends Error {}
来源：http://dali.yj20258888.top/Article/details/gt2oensnbjb.html

TS:   class MyError extends Error {}
来源：http://dali.hammf.cn/Article/details/gt2gcxlpizj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2crlsiehv.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwoldjmu.html

Ruby: class MyError < StandardError; end
来源：http://dali.hywenlv.cn/Article/details/gt2osmwygnk.html

C#:   class MyException : Exception {}
来源：http://dali.gogol.net.cn/Article/details/gt2icshvafj.html

[H05] 捕获特定类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2lvjoddoo.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gt2mhwrkldm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.iojbl.cn/Article/details/gt2ttcsvfme.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kxfpifzs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.ydzc1.top/Article/details/gt2ythyuayf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2hpguhkps.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sysykeji.top/Article/details/gt2gzgxjfim.html

Ruby: rescue ArgumentError => e
来源：http://dali.andypj.xyz/Article/details/gt2nwjsxncc.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yvedp.cn/Article/details/gt2ozngplap.html

[H06] 可选值 / 空值安全访问
来源：http://dali.dashuyun.cn/Article/details/gt2fzchdujz.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gt2lczzaitc.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ruwmzhwy.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sxryk.cn/Article/details/gt2hrlfdssl.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.redwolf501.top/Article/details/gt2nhctsgwo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sovmirco.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gt2fhckehkt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.kuanghao11.cn/Article/details/gt2hygxmzge.html

C#:   obj?.A?.B ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uterjzne.html

[H07] 断言
来源：http://dali.zhiwuduotai.top/Article/details/gt2svmubnkd.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yueranfly.top/Article/details/gt2opjwbqkc.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2mhnnbuld.html

JS:   console.assert(x > 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2iqsysybm.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gt2tdewgwjn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2knghrvmf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jinqigfzy.top/Article/details/gt2brhkhabs.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.zdqjudy.top/Article/details/gt2vfwuilqp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjbvhoes.html

[H08] 获取错误信息与堆栈
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpsppucd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yvedp.cn/Article/details/gt2lmehjgsq.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuanzx.com/Article/details/gt2bzjnewyw.html


<!-- 参考信息 -->