代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zdqjudy.top/Article/details/gtmhrzvgfn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhoulong.xyz/Article/details/gtckllbzkp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtwdsphtls.html

[F04] 追加写入文件
来源：http://dali.sxryk.cn/Article/details/gtvqutsmqf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtwtlcuxvt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.svipenyu.cn/Article/details/gtgcjytftf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gtokugovye.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtmldvhsmt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigufen.top/Article/details/gtiuyupkjk.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtpbdlucvz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyszxiwaz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gtqgyiyfwe.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtduwjltja.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtwxvftpqy.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtafceyaov.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtakoxxytg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtucodyrhl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtbupionzo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtvggpiazb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqpefvnfa.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtxolxzuhz.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnqhacrje.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtpvsqsdhd.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtpsphjcip.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtshnlkjvp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gthpcwkygr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtuetvmbde.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtjxpmrson.html

Ruby: File.delete("a.txt")
来源：http://dali.havefunace.top/Article/details/gtkbzrcxzw.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtryfyyrcl.html

[F07] 创建目录（含多级）
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyazeedc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtxkqdprbr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gtsgbdtdmn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gtgoqrjxhu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtdihkfinf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtqtdrutrg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cdnleiting.top/Article/details/gtvxibslja.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtbwonpxcn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.meibo888.top/Article/details/gtcvkcxbmw.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gtqptphrbe.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gtpaokdiym.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtnyleanwl.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gthguhqbly.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gttzbahybw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtiswthsjk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtsspcgxkm.html

Ruby: Dir.children("dir")
来源：http://dali.daxiang520.top/Article/details/gtgxxadyfp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gtmyjfgerl.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gtvuebgqvb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtouuplzsh.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtwzrnlmtt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gthuawbubb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtggmzvegj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtoxhlhbad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtbnjhmpav.html

Ruby: File.size("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtwifnezvp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhijiandao.cn/Article/details/gtyvpprtxn.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sysykeji.top/Article/details/gtiutrrkic.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtuscdfmxq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.mhx1999.top/Article/details/gthjtinfvo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtutxxczhr.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gthivwnrpp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnjgfnmi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtqkdpnypm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtuoqcigeu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtjiixuxqm.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtwwjcersd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gthggjcawm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zdqjudy.top/Article/details/gthgpolqpo.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zdqjudy.top/Article/details/gtrnjffjrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtmzpyrztd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtfmjrdvez.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenjidiqi.icu/Article/details/gtyrvdmyib.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gtykrrxhio.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yuanzhike.top/Article/details/gtkanovnal.html

[F12] CSV 读写
来源：http://dali.ivvv.top/Article/details/gtyldolyyb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shangyingyoupin.top/Article/details/gtnabvhkmu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gaohongyu789.top/Article/details/gtrgtbxaep.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hysaishi.cn/Article/details/gtxybegziv.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gtkkqfkgjh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xinyue.icu/Article/details/gtkrnytyyo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtezukkkvh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhengqikj.top/Article/details/gtkblttqqv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cucudq.cn/Article/details/gtirqfsgji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtxnmxgcmy.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gtnnnqloyh.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthbktvphj.html

[G01] 定义类
来源：http://dali.hfpthk.cn/Article/details/gtmmbnrruy.html

Py:   class User: pass
来源：http://dali.yuxming.cn/Article/details/gtpktqbilr.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtnpayeyfz.html

JS:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtvamtiatq.html

TS:   class User { name: string = ""; }
来源：http://dali.dashuyun.cn/Article/details/gtkuowmkaj.html

Java: class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwjpuoxgs.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtgpxpbpes.html

Ruby: class User; end
来源：http://dali.cqqwz.cn/Article/details/gtbunrihdk.html

C#:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtxigddcyy.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gthnfurxlc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gtgkncttvo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmxxmfay.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtpwaptmeg.html

TS:   constructor(public name: string) {}
来源：http://dali.yonumen.top/Article/details/gtjhldcjak.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gttppdtshy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gthxetpbtx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gtefxkywrq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzihlprqj.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gtjicoosvm.html

Py:   self.name = "x"
来源：http://dali.haohaochexian.top/Article/details/gtcuinsbjr.html

PHP:  public string $name = "x";
来源：http://dali.yj202588.top/Article/details/gtkdnzcenk.html

JS:   this.name = "x";
来源：http://dali.havefunace.top/Article/details/gtgvqtxovo.html

TS:   name: string = "x";
来源：http://dali.yvedp.cn/Article/details/gtyrrcabca.html

Java: private String name;
来源：http://dali.yongpay.top/Article/details/gtbxmwpekg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.xuetiantiany.cn/Article/details/gtdkbccrcd.html

Ruby: @name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtukwgajjr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.svipenyu.cn/Article/details/gtqssyqmco.html

[G04] 定义方法
来源：http://dali.haohaochexian.top/Article/details/gtiqugqsad.html

Py:   def greet(self): return self.name
来源：http://dali.ivvv.top/Article/details/gtbhvkmwdx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtahzsskuy.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gtpgeootfb.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtmnyxcxtv.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gtcozzfttn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtgfzyrrsp.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtbfwjltiz.html

C#:   public string Greet() => Name;
来源：http://dali.quarkkingdee.top/Article/details/gtimsgipbx.html

[G05] 继承
来源：http://dali.yueranfly.top/Article/details/gtsjhfphyt.html

Py:   class Admin(User): pass
来源：http://dali.andypj.xyz/Article/details/gtyvbawlux.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtbkwdbgyo.html

JS:   class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gtsztnoveb.html

TS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gtnvqxyfdb.html

Java: class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtciqiniwo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.wangdashe.top/Article/details/gtziaamxgs.html

Ruby: class Admin < User; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjwkxosmh.html

C#:   class Admin : User {}
来源：http://dali.cdnleiting.top/Article/details/gtfqnnkult.html

[G06] 重写方法
来源：http://dali.yj20258888.top/Article/details/gthjkuplhy.html

Py:   def greet(self): return "admin"
来源：http://dali.jinqigfzy.top/Article/details/gtyzvqfpii.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtlkekyost.html

JS:   greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gtgumvkicq.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gtjhbbrozi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtptlvasfi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ehwqpu.com/Article/details/gttckljipd.html

Ruby: def greet; "admin"; end
来源：http://dali.nanxinkj.top/Article/details/gtiwccjxxj.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gtoycctgwb.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gtbctbkqwf.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gttaxfsmww.html

PHP:  parent::greet();
来源：http://dali.svipenyu.cn/Article/details/gttqoyffky.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtyasnknss.html

TS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gtatotvaal.html

Java: super.greet();
来源：http://dali.jqgfzy.top/Article/details/gthiewcspb.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuxming.cn/Article/details/gtaqgxebzx.html

Ruby: super
来源：http://dali.fzhhl.top/Article/details/gtsumccedq.html

C#:   base.Greet();
来源：http://dali.kuanghao11.cn/Article/details/gtkzdewexu.html

[G08] 静态方法与属性
来源：http://dali.nwbrower.top/Article/details/gtzhhssksf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hfpthk.cn/Article/details/gttjvppgyp.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gtrmtoppui.html

JS:   static f() {}
来源：http://dali.yanxiufei.cn/Article/details/gtlqatvwav.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gtomyvssgp.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtyzkdrcny.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.quarkkingdee.top/Article/details/gtxadqiiyj.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtnuevumqh.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtklxzwvxz.html

[G09] 接口 / 抽象类
来源：http://dali.sufxvd.cn/Article/details/gthugqonhs.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.gaohongyu789.top/Article/details/gtpurpdkxn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gotoacloud.top/Article/details/gtmfjbixdl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gotoacloud.top/Article/details/gtdhpgdlgr.html

TS:   interface Shape { area(): number; }
来源：http://dali.smart0.xyz/Article/details/gtuwmfzbfw.html

Java: interface Shape { double area(); }
来源：http://dali.yuanzhike.top/Article/details/gtpflrguih.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.svipenyu.cn/Article/details/gtujhedrwl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.hfpthk.cn/Article/details/gtitkuyivn.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzznlmaoh.html

[G10] 访问控制
来源：http://dali.chenzaomai.com/Article/details/gtsoofguyv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenjidiqi.icu/Article/details/gtyyrapoae.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtifotankp.html

JS:   #private 字段；其余公开
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbcqttxp.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gtrhyommke.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtderwdbnn.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gtsqoracjh.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtuitxjubt.html

C#:   public / protected / private / internal
来源：http://dali.sufxvd.cn/Article/details/gtnglyymgn.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gtgcuuywcr.html

Py:   @property 与 @x.setter
来源：http://dali.andypj.xyz/Article/details/gttfnkffxc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfyjmnckk.html

JS:   get name() { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtiuelmriw.html

TS:   get name(): string { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gtjdysmfrk.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtghxnygqp.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtifkoqdcx.html

Ruby: attr_accessor :name
来源：http://dali.zhijiandao.cn/Article/details/gtulolievl.html

C#:   public string Name { get; set; }
来源：http://dali.jqgfzy.top/Article/details/gtiownwvdx.html

[G12] 对象转字符串
来源：http://dali.sxryk.cn/Article/details/gtrmtjuyip.html

Py:   def __str__(self): return self.name
来源：http://dali.zycfv.cn/Article/details/gtwfihujhj.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gtsazmturj.html

JS:   toString() { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvxvqlshm.html

TS:   toString(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtqlfognjs.html

Java: @Override public String toString() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtwiyaoviy.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yangfankeji.com/Article/details/gttidctius.html

Ruby: def to_s; @name; end
来源：http://dali.havefunace.top/Article/details/gtrudsojdf.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtwuxjitvk.html

[G13] 判断对象类型
来源：http://dali.yj20258.top/Article/details/gtubqmdymg.html

Py:   isinstance(u, User)
来源：http://dali.dianchejie.cn/Article/details/gtmibuwxli.html

PHP:  $u instanceof User
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntaidxuf.html

JS:   u instanceof User
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqizeqna.html

TS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtuwplzvjf.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtejxlzpll.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yueranfly.top/Article/details/gtpeqiolzq.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gtyiyhdiiw.html

C#:   u is User
来源：http://dali.yangfankeji.com/Article/details/gttaozlhau.html

[G14] 数据类 / record
来源：http://dali.iojbl.cn/Article/details/gthmntxist.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258888.top/Article/details/gtxuypnuxk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sufxvd.cn/Article/details/gtwwlklbov.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gtnhfqztkt.html

TS:   type User = { name: string; age: number };
来源：http://dali.cdnleiting.top/Article/details/gtmtasuxyt.html

Java: record User(String name, int age) {}
来源：http://dali.daria6918.cn/Article/details/gtzkqwehor.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnxiangtu.top/Article/details/gthkmrgzhg.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xziqi.cn/Article/details/gteninymoe.html

C#:   record User(string Name, int Age);
来源：http://dali.daria6918.cn/Article/details/gtjleonktc.html

[G15] 枚举
来源：http://dali.daxiang520.top/Article/details/gtnogzxlsn.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtfkztxmag.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258.top/Article/details/gtiawshnoq.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yj20258.top/Article/details/gtkpqhheah.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.daxiang520.top/Article/details/gtaehfzztf.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtfuuxeaxq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gttlqykwoj.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gtwanfxxwm.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.c1oappe.top/Article/details/gtzumtgrjk.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtafsphbyy.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.guannengcc.top/Article/details/gtwdfyaees.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtoeotsthe.html

JS:   Object.entries(obj)
来源：http://dali.yanxiufei.cn/Article/details/gtorqqdzme.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkxidthk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhongyouzk.top/Article/details/gtienbqafy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gzhubu.top/Article/details/gtjucmsitw.html

Ruby: obj.instance_variables
来源：http://dali.smart0.xyz/Article/details/gtwtcajjua.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtzzshmcog.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzqcaebag.html

H. 异常与错误处理
来源：http://dali.yangfankeji.com/Article/details/gtcexhhsiv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyolokdam.html

[H01] try / catch 基础
来源：http://dali.chenzaomai.com/Article/details/gttogezvrb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhijiandao.cn/Article/details/gtjchopuso.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcresreh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gtxkmsaqmo.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.316326.xyz/Article/details/gtctnaivrm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtmggllrqc.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gtrsosmvdq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.nanxuanxn.top/Article/details/gtteigujjp.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.feifeiyinyue.top/Article/details/gtuzafppec.html

[H02] finally / ensure 收尾
来源：http://dali.andypj.xyz/Article/details/gttgpwtdrw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zdqjudy.top/Article/details/gtqhrttrix.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtzbjhcjiy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtcsukbdvk.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgcmjdpcy.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gtkxpdxybn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtrkfyucyj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gttyudcveh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxzdfvysq.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtcodnmvlu.html

Py:   raise ValueError("错误信息")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjjnaccnx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.dianchejie.cn/Article/details/gteujqwfsy.html

JS:   throw new Error("错误信息");
来源：http://dali.sweek.top/Article/details/gthtbcbxcy.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtshzbrlfk.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzdyekbk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.bjfxy.top/Article/details/gtdtsvukfx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gaohongyu789.top/Article/details/gtkchqeqae.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gtgoyszipt.html

[H04] 自定义异常类型
来源：http://dali.jinqigfzy.top/Article/details/gtmolwlldm.html

Py:   class MyError(Exception): pass
来源：http://dali.jlsjyb.cn/Article/details/gtdjggtact.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqzycztbd.html

JS:   class MyError extends Error {}
来源：http://dali.ehwqpu.com/Article/details/gtveuhurrj.html

TS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtudpnszlb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aibaodan.cn/Article/details/gtvrcazwwa.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.wangshuangyany.cn/Article/details/gtlskzoirz.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gttindwjhc.html

C#:   class MyException : Exception {}
来源：http://dali.gaohongyu789.top/Article/details/gtugzzymdv.html

[H05] 捕获特定类型
来源：http://dali.chenlongwang.top/Article/details/gtzpsjlepu.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gtiefsfyuj.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.hnxiangtu.top/Article/details/gtjobdormx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvuvwsuqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.0kj1m.cn/Article/details/gticaaofnj.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.smart0.xyz/Article/details/gtpueplony.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.aibaodan.cn/Article/details/gtyvokvdwm.html

Ruby: rescue ArgumentError => e
来源：http://dali.pycfn.com/Article/details/gtqcupuklh.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gttkfotehd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenjidiqi.icu/Article/details/gtnbvvgwtg.html

Py:   value = d.get("k") or default
来源：http://dali.zdqjudy.top/Article/details/gtwxedrxuk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtyxkzvfav.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.svipenyu.cn/Article/details/gteuclywhd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlteourwg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.haohaochexian.top/Article/details/gtmxyjdluz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.fengsongda.top/Article/details/gtvjziephf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtkjvykbxy.html

C#:   obj?.A?.B ?? default
来源：http://dali.zycfv.cn/Article/details/gtubojvznd.html

[H07] 断言
来源：http://dali.sufxvd.cn/Article/details/gtqzhdcnui.html

Py:   assert x > 0, "必须为正"
来源：http://dali.yj20258.top/Article/details/gtjgwbuwpk.html

PHP:  assert($x > 0);
来源：http://dali.sweek.top/Article/details/gtjtzbpveu.html

JS:   console.assert(x > 0);
来源：http://dali.birdmap.top/Article/details/gtdwyponvy.html

TS:   console.assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtqpxvjtho.html

Java: assert x > 0 : "必须为正";
来源：http://dali.birdmap.top/Article/details/gtlrrpkpwx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.pycfn.com/Article/details/gtnaggifjy.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.sweek.top/Article/details/gtcdatilmk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.mhx1999.top/Article/details/gtzydcziag.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuetiantiany.cn/Article/details/gtjlqnlerb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jinqigfzy.top/Article/details/gtjzydziqt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscjojuoq.html


<!-- 参考信息 -->