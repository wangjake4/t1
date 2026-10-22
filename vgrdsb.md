代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yongpay.top/Article/details/gt2rgrwaiyl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2musyuvqw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2eprhtekq.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gt2rydmrzth.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jelrdasd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2hbzgemha.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gt2pmvotuja.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2anvmjmfd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gt2dpdkngiw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2utkjztax.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2srvlbxfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2vdtggbgt.html

[F05] 判断文件或目录是否存在
来源：http://dali.guowangkeji.top/Article/details/gt2hobvepob.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.svipenyu.cn/Article/details/gt2xyyyblov.html

PHP:  file_exists("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2qedtoyoc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2dysxprqe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2yipnjeze.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2fjqeqnzv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gt2nitvjmqa.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybqvjaqv.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2zxaoudqx.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gt2idzesldk.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2xkbonnme.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2ikcgeufb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2jiouunou.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2wuvxcyny.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2ajhzifdh.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2gvatjigo.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ziefxbpw.html

C#:   File.Delete("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2tboaaazm.html

[F07] 创建目录（含多级）
来源：http://dali.hywenlv.cn/Article/details/gt2ohlplybh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2ccgrdnaw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gt2hfoxodms.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2mmcmdths.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2hagwojtt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2itpzqgio.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ydzc1.top/Article/details/gt2djjhdqdl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.smart0.xyz/Article/details/gt2prkzacae.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhixingplan.top/Article/details/gt2ezfeixzl.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gt2erqdajnt.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gt2puqqtpal.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhixingplan.top/Article/details/gt2crhhjlit.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gt2ggimzrcn.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2rgovpttl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2nvsmoqep.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.316326.xyz/Article/details/gt2tcakngcy.html

Ruby: Dir.children("dir")
来源：http://dali.sweek.top/Article/details/gt2ksvktuku.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2tpiihvdk.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2yowwyzgq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2adrkqbbh.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ferczxbq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinqigfzy.top/Article/details/gt2dqyjyqrw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2wtehkfvg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2ppuekqov.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ppjwa.cn/Article/details/gt2alxcytsu.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2qzpujiyj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gt2frpcfexk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gt2xegmonui.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2iqebgqxm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.birdmap.top/Article/details/gt2pvrjocpr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2gvnsojdd.html

TS:   path.extname("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ysqbmjnz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2lshlltmd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2xqnoscmp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2hpmwgihf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2yjnlqxaj.html

[F11] 复制与移动文件
来源：http://dali.guowangkeji.top/Article/details/gt2akzlxpka.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2dxupxczg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jianghu66.top/Article/details/gt2oarswebg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2giqkbhpw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2hespaypc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2levqljbo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.gogol.net.cn/Article/details/gt2guyxkzdi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2trugiees.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ivvv.top/Article/details/gt2tbkettiw.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gt2cyjnousg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2zjlmemzc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gt2ujdfhxes.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shuidangran.top/Article/details/gt2ogzsmwqt.html

TS:   // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2fjambgnp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gt2oeropeei.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2waxrbjri.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2zgfnhhes.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2untmecjt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2mwrrjxtp.html

G. 面向对象
来源：http://dali.chenlongwang.top/Article/details/gt2toahbwss.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2omrehbau.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypauxfbc.html

Py:   class User: pass
来源：http://dali.aizwys.cn/Article/details/gt2rlcxgird.html

PHP:  class User {}
来源：http://dali.daria6918.cn/Article/details/gt2ojnjxxtf.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2asggoifq.html

TS:   class User { name: string = ""; }
来源：http://dali.cdnleiting.top/Article/details/gt2igmpsahy.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gt2ianayknd.html

Go:   type User struct { Name string }
来源：http://dali.ydzc1.top/Article/details/gt2olcxkfvy.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2vpjqcvjh.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2uhunnxkw.html

[G02] 构造函数
来源：http://dali.zycfv.cn/Article/details/gt2dtlrhfsh.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gt2xtgdbtmt.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gt2yoidbxnq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.pycfn.com/Article/details/gt2khkmvaar.html

TS:   constructor(public name: string) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzkqnqyo.html

Java: User(String name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2ldetjvik.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gt2kerrxlkp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwvzhahn.html

C#:   public User(string name) { Name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2cjalisbm.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2xswmqrva.html

Py:   self.name = "x"
来源：http://dali.yj20258.top/Article/details/gt2jyrensyx.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2vmxiqrqx.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2qnorbnvt.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2dyvohbkr.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2hetkutjj.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xziqi.cn/Article/details/gt2giithkjn.html

Ruby: @name = "x"
来源：http://dali.dianchejie.cn/Article/details/gt2tdexfody.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.feifeiyinyue.top/Article/details/gt2gekorozw.html

[G04] 定义方法
来源：http://dali.yanxiufei.cn/Article/details/gt2cmyjdgyi.html

Py:   def greet(self): return self.name
来源：http://dali.chenjidiqi.icu/Article/details/gt2gxtumgwk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbqclhig.html

JS:   greet() { return this.name; }
来源：http://dali.cqqwz.cn/Article/details/gt2vgjhdldx.html

TS:   greet(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2noztomvz.html

Java: String greet() { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2twsbjcic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nelpqmhd.html

Ruby: def greet; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2kcqukyvz.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2hchyhtxk.html

[G05] 继承
来源：http://dali.cucudq.cn/Article/details/gt2lsqvjrdw.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gt2rrbuddzc.html

PHP:  class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gt2iyhkvtwa.html

JS:   class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2vaxywpnx.html

TS:   class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2kujwalji.html

Java: class Admin extends User {}
来源：http://dali.tianlin.xyz/Article/details/gt2tivxctzh.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jyoumei.cn/Article/details/gt2ijkzfjae.html

Ruby: class Admin < User; end
来源：http://dali.yj20258.top/Article/details/gt2cllwvptf.html

C#:   class Admin : User {}
来源：http://dali.yongpay.top/Article/details/gt2ubptmszz.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gt2kujlntyf.html

Py:   def greet(self): return "admin"
来源：http://dali.birdmap.top/Article/details/gt2droyedhe.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcvmohtt.html

JS:   greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wwtjrrdf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ohsuxhdl.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2hxcybxfs.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gt2fxprnpzb.html

Ruby: def greet; "admin"; end
来源：http://dali.yj202588.top/Article/details/gt2oxfwzpkl.html

C#:   public override string Greet() => "admin";
来源：http://dali.hysaishi.cn/Article/details/gt2etuzatko.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gt2fbwagrgv.html

Py:   super().greet()
来源：http://dali.fengsongda.top/Article/details/gt2tmrjvtzh.html

PHP:  parent::greet();
来源：http://dali.haohaochexian.top/Article/details/gt2impbbgtk.html

JS:   super.greet();
来源：http://dali.hammf.cn/Article/details/gt2iffaqaxw.html

TS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2bptbfezd.html

Java: super.greet();
来源：http://dali.zhixingplan.top/Article/details/gt2rnpvgrge.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jianghu66.top/Article/details/gt2brihzjvn.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gt2uaxrpjvc.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iaaphgcp.html

[G08] 静态方法与属性
来源：http://dali.gaohongyu789.top/Article/details/gt2jvgvssqb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jyoumei.cn/Article/details/gt2vbsimedr.html

PHP:  public static function f() {}
来源：http://dali.yonumen.top/Article/details/gt2hlansldq.html

JS:   static f() {}
来源：http://dali.daxiang520.top/Article/details/gt2eyjhdaxg.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2cfhtbagt.html

Java: static void f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2pbxcdlhp.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2ccfkfvwp.html

Ruby: def self.f; end
来源：http://dali.jiagoushi.top/Article/details/gt2zvbyxmxg.html

C#:   public static void F() {}
来源：http://dali.ehwqpu.com/Article/details/gt2pcatoreo.html

[G09] 接口 / 抽象类
来源：http://dali.hfpthk.cn/Article/details/gt2ghuwbduw.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2hsysrusz.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2pmmzaglz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gogol.net.cn/Article/details/gt2sablutwx.html

TS:   interface Shape { area(): number; }
来源：http://dali.tian-w.cn/Article/details/gt2pbkfwdbf.html

Java: interface Shape { double area(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ewkdmidy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.nanxuanxn.top/Article/details/gt2gxwfkpts.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gt2oveojpma.html

C#:   interface IShape { double Area(); }
来源：http://dali.tian-w.cn/Article/details/gt2woyqcucp.html

[G10] 访问控制
来源：http://dali.tianlin.xyz/Article/details/gt2tqpolsuc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.haohaochexian.top/Article/details/gt2npxozxee.html

PHP:  public / protected / private
来源：http://dali.tanke756.top/Article/details/gt2dubtpvkk.html

JS:   #private 字段；其余公开
来源：http://dali.ybcxt.top/Article/details/gt2iiffvqdz.html

TS:   public / protected / private
来源：http://dali.hysaishi.cn/Article/details/gt2kykganze.html

Java: public / protected / private / 默认包级
来源：http://dali.zdqjudy.top/Article/details/gt2qcfozkzp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2veawixrc.html

Ruby: public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gt2euykavht.html

C#:   public / protected / private / internal
来源：http://dali.zhongyouzk.top/Article/details/gt2dgltzlwe.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2drdrsmka.html

Py:   @property 与 @x.setter
来源：http://dali.0kj1m.cn/Article/details/gt2ttcdmysr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2bvqixvds.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gt2qecbtbnx.html

TS:   get name(): string { return this._name; }
来源：http://dali.dashuyun.cn/Article/details/gt2lfnluvhd.html

Java: public String getName() { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2qrntenri.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2iwdzytmz.html

Ruby: attr_accessor :name
来源：http://dali.zhixingplan.top/Article/details/gt2xxlleuep.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gt2pigbwfeb.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2gculgicp.html

Py:   def __str__(self): return self.name
来源：http://dali.hysaishi.cn/Article/details/gt2rmfkuhoh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2rimjglfe.html

JS:   toString() { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2drhainvj.html

TS:   toString(): string { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2uzwbkzgf.html

Java: @Override public String toString() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcrmkcov.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2sonljgfj.html

Ruby: def to_s; @name; end
来源：http://dali.fengsongda.top/Article/details/gt2codzbboq.html

C#:   public override string ToString() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2nkxmwlej.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekdwtjgx.html

Py:   isinstance(u, User)
来源：http://dali.zhongyouzk.top/Article/details/gt2agaxzezk.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2trpxorkm.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2pcptfopv.html

TS:   u instanceof User
来源：http://dali.yongpay.top/Article/details/gt2xarezkfd.html

Java: u instanceof User
来源：http://dali.meibo888.top/Article/details/gt2lvpgjloq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ybcxt.top/Article/details/gt2yhjlvbbp.html

Ruby: u.is_a?(User)
来源：http://dali.yvedp.cn/Article/details/gt2qtvfccxu.html

C#:   u is User
来源：http://dali.redwolf501.top/Article/details/gt2vgdyotxz.html

[G14] 数据类 / record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtlfubhh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yanxiufei.cn/Article/details/gt2cjybdnsh.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.birdmap.top/Article/details/gt2nqbfbzyv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yj20258888.top/Article/details/gt2acoutshu.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gt2tocwboja.html

Java: record User(String name, int age) {}
来源：http://dali.jiagoushi.top/Article/details/gt2nozpfcdw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2ltbbapbl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cqqwz.cn/Article/details/gt2xifsoahq.html

C#:   record User(string Name, int Age);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bgxamoxv.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gt2ixppmvei.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.mhx1999.top/Article/details/gt2ggwilfbj.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2pbjbcpdf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jianghu66.top/Article/details/gt2uzzjikpj.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.316326.xyz/Article/details/gt2dgvrftgp.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gt2vopztqmm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gt2ecydtcek.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yueranfly.top/Article/details/gt2mhaekmmq.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2vhdnodha.html

[G16] 对象转数组 / 字典
来源：http://dali.gogol.net.cn/Article/details/gt2xhkgdvzf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hywenlv.cn/Article/details/gt2jinhpwyy.html

PHP:  get_object_vars($obj);
来源：http://dali.tian-w.cn/Article/details/gt2cxhmqhtx.html

JS:   Object.entries(obj)
来源：http://dali.yj202588.top/Article/details/gt2erlbjptr.html

TS:   Object.entries(obj)
来源：http://dali.yuxming.cn/Article/details/gt2agvyyrda.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.9152youxi.cn/Article/details/gt2enagwssk.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bprqdkav.html

Ruby: obj.instance_variables
来源：http://dali.jlsjyb.cn/Article/details/gt2flwpliel.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.nanxinkj.top/Article/details/gt2ihgauges.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2mpaidjfc.html

H. 异常与错误处理
来源：http://dali.yongpay.top/Article/details/gt2graqasmo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2iguwbjex.html

[H01] try / catch 基础
来源：http://dali.aibaodan.cn/Article/details/gt2gwwcfsbk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.c1oappe.top/Article/details/gt2lsehscep.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2tehrwjpd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gt2kbfcsosl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gt2xgeufrcs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.hammf.cn/Article/details/gt2ktmsyrjt.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cqqwz.cn/Article/details/gt2dvoaqqxu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sysykeji.top/Article/details/gt2wahedjpt.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shuidangran.top/Article/details/gt2lfuxeuix.html

[H02] finally / ensure 收尾
来源：http://dali.jqgufenzy.top/Article/details/gt2aywtrdjp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gt2ijvpgacn.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gt2ghwxtdca.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yvedp.cn/Article/details/gt2sifcllai.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gt2fzzpgmjh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gt2nshxqjyh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhiwuduotai.top/Article/details/gt2hyldiobq.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aibaodan.cn/Article/details/gt2jwerpmtx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2ageuibxm.html

[H03] 主动抛出异常
来源：http://dali.nwbrower.top/Article/details/gt2wuhwdmdw.html

Py:   raise ValueError("错误信息")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zlvnmgts.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2yacdhmif.html

JS:   throw new Error("错误信息");
来源：http://dali.ybcxt.top/Article/details/gt2drxfjfqm.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2thdqvwsd.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gt2rpwjtrjp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gt2sdbdicam.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cwtxqxao.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gt2txledcfw.html

[H04] 自定义异常类型
来源：http://dali.9152youxi.cn/Article/details/gt2auyziezd.html

Py:   class MyError(Exception): pass
来源：http://dali.jqgfzy.top/Article/details/gt2fbyvyeqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2wlgbyaod.html

JS:   class MyError extends Error {}
来源：http://dali.yuanzhike.top/Article/details/gt2uhwuwavu.html

TS:   class MyError extends Error {}
来源：http://dali.aibaodan.cn/Article/details/gt2gnhiogys.html

Java: class MyException extends RuntimeException {}
来源：http://dali.wangdashe.top/Article/details/gt2lfowynlx.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gt2sarvyucy.html

Ruby: class MyError < StandardError; end
来源：http://dali.havefunace.top/Article/details/gt2vqwhaagd.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gt2thrzfrmb.html

[H05] 捕获特定类型
来源：http://dali.yuxming.cn/Article/details/gt2ylprtihh.html

Py:   except ValueError as e:
来源：http://dali.zhoulong.xyz/Article/details/gt2xwlyultp.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.nanxinkj.top/Article/details/gt2kxfixhtc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.cqqwz.cn/Article/details/gt2tipooqwi.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.chenzaomai.com/Article/details/gt2rkceydkn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2kldqurbn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.jianghu66.top/Article/details/gt2btuxyqpi.html

Ruby: rescue ArgumentError => e
来源：http://dali.sysykeji.top/Article/details/gt2skmylmqp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zycfv.cn/Article/details/gt2hxcdnbzk.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnbrpids.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2tjxkhxsq.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yangfankeji.com/Article/details/gt2cdvnocez.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yueranfly.top/Article/details/gt2nwrpvqyg.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhiwuduotai.top/Article/details/gt2yynjprau.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hywenlv.cn/Article/details/gt2zzhmdbhm.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fzhhl.top/Article/details/gt2bzuffldg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jqgfzy.top/Article/details/gt2zxtrglln.html

C#:   obj?.A?.B ?? default
来源：http://dali.tian-w.cn/Article/details/gt2vftsazub.html

[H07] 断言
来源：http://dali.daria6918.cn/Article/details/gt2kpunxkfx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.daxiang520.top/Article/details/gt2uckooari.html

PHP:  assert($x > 0);
来源：http://dali.yongpay.top/Article/details/gt2brpgdctw.html

JS:   console.assert(x > 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qsncisvn.html

TS:   console.assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2xvlynneg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrwstajk.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gt2vkauigwa.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.xinyue.icu/Article/details/gt2cuqorjtv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guowangkeji.top/Article/details/gt2mlsbsuxx.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gt2viaulvxh.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.gaohongyu789.top/Article/details/gt2qxqktcns.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yongpay.top/Article/details/gt2doderxuk.html


<!-- 参考信息 -->