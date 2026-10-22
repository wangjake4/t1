代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2vdmufmff.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2radctkyu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2iclnehyz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gt2eonplemt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gt2nxntplqn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.bjfxy.top/Article/details/gt2kcahxumu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2yisqakge.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gt2rywmyvwi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2hryulmyo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tian-w.cn/Article/details/gt2fqaalahb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gt2qynyrbnf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2dwbaesmm.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yongpay.top/Article/details/gt2wtftcaws.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gt2fnuenlvv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinqigfzy.top/Article/details/gt2rfzsntjr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhiwuduotai.top/Article/details/gt2tcjahseo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2ehwdaugd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2okepenmr.html

PHP:  file_exists("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2vfpwpjjz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2rclkllcd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2imerldxb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2cneftohf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yanxiufei.cn/Article/details/gt2xrunmqst.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2aytkatis.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2uqqyxpkd.html

[F06] 删除文件
来源：http://dali.cucudq.cn/Article/details/gt2xmysncwo.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2cgsjjlbf.html

PHP:  unlink("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2wnrzydra.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2brgcdybp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2unvjedmc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gt2niyhjufz.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nfkwhkpu.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2sbyhnjgq.html

C#:   File.Delete("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2ayouvxgr.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2jvwxtezh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2cyzadsnc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2pvesdqlc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2iwynxzqt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.feifeiyinyue.top/Article/details/gt2mesepmvf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2nhfxescv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2touolslv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2yfpxpwep.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gt2gvuoisoc.html

[F08] 遍历目录
来源：http://dali.ehwqpu.com/Article/details/gt2tpdlrjyl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gt2adkhubcw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zycfv.cn/Article/details/gt2fjpujqnr.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2aphfjozl.html

TS:   fs.readdirSync("dir")
来源：http://dali.sysykeji.top/Article/details/gt2cxvptzcc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gt2pgnahign.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2zfsnsglo.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2pqofpyqy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.meibo888.top/Article/details/gt2lpsizvxa.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2rnmnipid.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2kvwylbre.html

PHP:  filesize("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zlwiyfdb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdfkmhec.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gt2dgkheaza.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gt2rhvkjwfm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.iojbl.cn/Article/details/gt2ssgvszeq.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2ltxrpjuc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guannengcc.top/Article/details/gt2qlcvldlz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zdqjudy.top/Article/details/gt2mgtxtqnd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gt2cwlnrihb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2qfzdcclu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibpnuigj.html

TS:   path.extname("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2dnztbtty.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jianghu66.top/Article/details/gt2udhknkho.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ikemnjep.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2dubqqyny.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2atjrodgy.html

[F11] 复制与移动文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vfvkkbhm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnnmjebp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.aizwys.cn/Article/details/gt2cpybsojf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2lkodbeni.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubegkktg.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2aqkzljzc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2kalqnryx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2cwknxbti.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2ynvdbhdq.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2vsykmjnh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2ftflbjpj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.tanke756.top/Article/details/gt2cfsanjfn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2pyplcwzp.html

TS:   // 同上
来源：http://dali.ydzc1.top/Article/details/gt2iktisdky.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.316326.xyz/Article/details/gt2vzoadwvh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gt2ysxupriq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.0kj1m.cn/Article/details/gt2ihxjurvg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2debcwgux.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2rbcalhet.html

G. 面向对象
来源：http://dali.tanke756.top/Article/details/gt2esryicif.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2gbydizwf.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2kiibxqqw.html

Py:   class User: pass
来源：http://dali.svipenyu.cn/Article/details/gt2urobvvvn.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gt2mdipcrwn.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2dfhtblky.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgfzy.top/Article/details/gt2mzrmtulx.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gt2pymbnlrx.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gt2paxqeydp.html

Ruby: class User; end
来源：http://dali.yuanzhike.top/Article/details/gt2lmvjmmhk.html

C#:   class User {}
来源：http://dali.yonumen.top/Article/details/gt2ghpmzjun.html

[G02] 构造函数
来源：http://dali.yj20258888.top/Article/details/gt2pyldqqsd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.daxiang520.top/Article/details/gt2avjmclos.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuanzx.com/Article/details/gt2nrvtbrsn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2puawenin.html

TS:   constructor(public name: string) {}
来源：http://dali.gotoacloud.top/Article/details/gt2tuaktedb.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2enypnnun.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqesmvhg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gt2jqstasoa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2ljlfjczb.html

[G03] 实例属性
来源：http://dali.c1oappe.top/Article/details/gt2pkqymlri.html

Py:   self.name = "x"
来源：http://dali.ivvv.top/Article/details/gt2ocszbxfp.html

PHP:  public string $name = "x";
来源：http://dali.quarkkingdee.top/Article/details/gt2rvqpdbgm.html

JS:   this.name = "x";
来源：http://dali.xinyue.icu/Article/details/gt2rtokdczc.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2zpxlgcrr.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gt2muwxdzrq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gt2xkhtswqx.html

Ruby: @name = "x"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqiztais.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2bfwwemud.html

[G04] 定义方法
来源：http://dali.xuanzx.com/Article/details/gt2fcswuwfw.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2xkxixbre.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2oplpqmxb.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2duacvpcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.zycfv.cn/Article/details/gt2zgcgciaz.html

Java: String greet() { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2sogcvhcy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlhgqotk.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2hpotqkrn.html

C#:   public string Greet() => Name;
来源：http://dali.havefunace.top/Article/details/gt2bbswsatw.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2afxnyiao.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2xlpxuugm.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrllcbdp.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2wprndgad.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gldveadf.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2rshibnbt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.bjfxy.top/Article/details/gt2tlmnihbx.html

Ruby: class Admin < User; end
来源：http://dali.fzhhl.top/Article/details/gt2dixopahn.html

C#:   class Admin : User {}
来源：http://dali.gogol.net.cn/Article/details/gt2cojkjgqh.html

[G06] 重写方法
来源：http://dali.tian-w.cn/Article/details/gt2vdbezjmy.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2skkukzuz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2amopbmnf.html

JS:   greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2vipcijdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2gdqxexod.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2ikagbbio.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhengqikj.top/Article/details/gt2zkwbyeuj.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2qrdtcifz.html

C#:   public override string Greet() => "admin";
来源：http://dali.feifeiyinyue.top/Article/details/gt2xaoorkas.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2vakmupdb.html

Py:   super().greet()
来源：http://dali.hammf.cn/Article/details/gt2qukrjtpx.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gt2vawnlncb.html

JS:   super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2zupnspcp.html

TS:   super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2sfzzqjun.html

Java: super.greet();
来源：http://dali.0kj1m.cn/Article/details/gt2fuobfgjd.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gt2zsulhoop.html

Ruby: super
来源：http://dali.hongshengwenyu.top/Article/details/gt2uestfabc.html

C#:   base.Greet();
来源：http://dali.nwbrower.top/Article/details/gt2emaepewv.html

[G08] 静态方法与属性
来源：http://dali.sysykeji.top/Article/details/gt2ahwwhsnu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2ugeyiixb.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2mlejhjec.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2fzmrqstj.html

TS:   static f(): void {}
来源：http://dali.fengsongda.top/Article/details/gt2mkbdutdy.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2hqipgqam.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2amehhscp.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2cuqmavep.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2heyapusn.html

[G09] 接口 / 抽象类
来源：http://dali.0kj1m.cn/Article/details/gt2gsqvhooe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cucudq.cn/Article/details/gt2bvksrlov.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.nwbrower.top/Article/details/gt2kxzhrssh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ydzc1.top/Article/details/gt2ccsoilgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.hfpthk.cn/Article/details/gt2oowdmrus.html

Java: interface Shape { double area(); }
来源：http://dali.mhx1999.top/Article/details/gt2mqvndmqs.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gaohongyu789.top/Article/details/gt2vgycnnfl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hysaishi.cn/Article/details/gt2avmhrowo.html

C#:   interface IShape { double Area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2jhtyqdfc.html

[G10] 访问控制
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykiwirkl.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sxryk.cn/Article/details/gt2qadruger.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gt2lvzdrszw.html

JS:   #private 字段；其余公开
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rjuciobf.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2gsyiunig.html

Java: public / protected / private / 默认包级
来源：http://dali.xuanzx.com/Article/details/gt2frrfnnqv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dianchejie.cn/Article/details/gt2grmuyyfl.html

Ruby: public / protected / private
来源：http://dali.9152youxi.cn/Article/details/gt2hlgilcrs.html

C#:   public / protected / private / internal
来源：http://dali.iojbl.cn/Article/details/gt2ndbrlgvw.html

[G11] getter / setter
来源：http://dali.zhixingplan.top/Article/details/gt2kfpvfjpl.html

Py:   @property 与 @x.setter
来源：http://dali.cashguo.top/Article/details/gt2keufcdna.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2uffiuvfc.html

JS:   get name() { return this._name; }
来源：http://dali.9152youxi.cn/Article/details/gt2ovchklpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.aizwys.cn/Article/details/gt2mxncrxim.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2tfuoinlr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.meibo888.top/Article/details/gt2jopquvhp.html

Ruby: attr_accessor :name
来源：http://dali.pengpengdd.cyou/Article/details/gt2pabxlrdc.html

C#:   public string Name { get; set; }
来源：http://dali.zdqjudy.top/Article/details/gt2extklwvb.html

[G12] 对象转字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2jgbptvds.html

Py:   def __str__(self): return self.name
来源：http://dali.guowangkeji.top/Article/details/gt2kgvymldd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj20258.top/Article/details/gt2meeyadru.html

JS:   toString() { return this.name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oeokeeqk.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2hgptxlgy.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mtqseswa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gt2sxeqcsdg.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2wqxjvenz.html

C#:   public override string ToString() => Name;
来源：http://dali.daxiang520.top/Article/details/gt2dhlkmknl.html

[G13] 判断对象类型
来源：http://dali.svipenyu.cn/Article/details/gt2cmqvjvsg.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2dfbzjwsc.html

PHP:  $u instanceof User
来源：http://dali.fengsongda.top/Article/details/gt2ptefkdsl.html

JS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2lmigrebd.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2lrhtsuqx.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2hoviygex.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2nvdmczhz.html

Ruby: u.is_a?(User)
来源：http://dali.yonumen.top/Article/details/gt2mxtwytce.html

C#:   u is User
来源：http://dali.hnqzz.top/Article/details/gt2zozujfsr.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2tymaszed.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nanxinkj.top/Article/details/gt2fvnarsnk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gt2bpmsobhm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xinyue.icu/Article/details/gt2xipslegb.html

TS:   type User = { name: string; age: number };
来源：http://dali.yj20258.top/Article/details/gt2pfsmvnzb.html

Java: record User(String name, int age) {}
来源：http://dali.nwbrower.top/Article/details/gt2qzixdwjp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qomrixwi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangshuangyany.cn/Article/details/gt2aefsbcpg.html

C#:   record User(string Name, int Age);
来源：http://dali.zhongyouzk.top/Article/details/gt2lzxcgijn.html

[G15] 枚举
来源：http://dali.yvedp.cn/Article/details/gt2slcflafo.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gt2brmsnajb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ydzc1.top/Article/details/gt2esxnejlj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.xuetiantiany.cn/Article/details/gt2inppowcd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.birdmap.top/Article/details/gt2enzvnkgd.html

Java: enum Color { RED, GREEN }
来源：http://dali.pycfn.com/Article/details/gt2iakczdje.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.birdmap.top/Article/details/gt2hrjkofjv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zycfv.cn/Article/details/gt2xjaoxtpa.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gt2ykfsgmou.html

[G16] 对象转数组 / 字典
来源：http://dali.ybcxt.top/Article/details/gt2vabptdzq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2ablsdyqz.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxzzyqje.html

JS:   Object.entries(obj)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhtwjowg.html

TS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2zpzkflwa.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yvedp.cn/Article/details/gt2qfrmnhco.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2svqflcyp.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gt2atvmttfa.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yangfankeji.com/Article/details/gt2eqvpvsip.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2riwaicgo.html

H. 异常与错误处理
来源：http://dali.daria6918.cn/Article/details/gt2ebobytxm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rhorehqq.html

[H01] try / catch 基础
来源：http://dali.gaohongyu789.top/Article/details/gt2vpbdtolf.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnxiangtu.top/Article/details/gt2ugwnguhm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yuanzhike.top/Article/details/gt2mvocpocv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2netkzxju.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gt2gtjrqgec.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.havefunace.top/Article/details/gt2uomixcmc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhoulong.xyz/Article/details/gt2zaqaldgn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.smart0.xyz/Article/details/gt2wonjyevm.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kbvypjsk.html

[H02] finally / ensure 收尾
来源：http://dali.zhongyouzk.top/Article/details/gt2dcdeqsuu.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.jinqigufen.top/Article/details/gt2abmeekdv.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2qmfkqzkx.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2fixwcaln.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rpdzatyu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fojakfbl.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.yj20258.top/Article/details/gt2trhoozbl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gt2agvrnzxo.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2seikdeak.html

[H03] 主动抛出异常
来源：http://dali.svipenyu.cn/Article/details/gt2onurfckg.html

Py:   raise ValueError("错误信息")
来源：http://dali.cheryme.top/Article/details/gt2wdjmekkh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygkfendc.html

JS:   throw new Error("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gt2xupdogay.html

TS:   throw new Error("错误信息");
来源：http://dali.jinqigufen.top/Article/details/gt2rlzwcvfw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2exunatvx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.hywenlv.cn/Article/details/gt2puhiifco.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2azpdwkgx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gt2muvsqxoc.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2basuxyfe.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gt2xmlyncvg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gt2qeivbqpy.html

JS:   class MyError extends Error {}
来源：http://dali.sufxvd.cn/Article/details/gt2kdigqhae.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fdfcymbz.html

Java: class MyException extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gt2itkukklb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gt2fcgmhruf.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afwnyrdi.html

C#:   class MyException : Exception {}
来源：http://dali.bjfxy.top/Article/details/gt2bqkpyecm.html

[H05] 捕获特定类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbxzemfe.html

Py:   except ValueError as e:
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvaamiju.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ppjwa.cn/Article/details/gt2jznaqpgm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2rltpqnzn.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.hnqzz.top/Article/details/gt2lrwngabt.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yueranfly.top/Article/details/gt2gcfheuvn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yangfankeji.com/Article/details/gt2qhnqiuoz.html

Ruby: rescue ArgumentError => e
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cxdijffm.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qhfwbhjp.html

[H06] 可选值 / 空值安全访问
来源：http://dali.vqdsnc.cn/Article/details/gt2wdgoanwk.html

Py:   value = d.get("k") or default
来源：http://dali.yangfankeji.com/Article/details/gt2morbqrnq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xuanzx.com/Article/details/gt2vuzjewom.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.aizwys.cn/Article/details/gt2xpbpsngb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2ahozzqkh.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.fzhhl.top/Article/details/gt2cfakucrn.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.guowangkeji.top/Article/details/gt2blvjhlug.html

Ruby: d&.dig(:a, :b)
来源：http://dali.chenzaomai.com/Article/details/gt2kilqwgdl.html

C#:   obj?.A?.B ?? default
来源：http://dali.yuxming.cn/Article/details/gt2ynizucpk.html

[H07] 断言
来源：http://dali.cqqwz.cn/Article/details/gt2scyppokk.html

Py:   assert x > 0, "必须为正"
来源：http://dali.andypj.xyz/Article/details/gt2rsvgkiik.html

PHP:  assert($x > 0);
来源：http://dali.xinyue.icu/Article/details/gt2xzhdapxp.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2jlfquuyu.html

TS:   console.assert(x > 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wyucresq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ehwqpu.com/Article/details/gt2voqgdwuw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iifmnuam.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinghuilouyu.cn/Article/details/gt2erzonvfd.html


<!-- 参考信息 -->