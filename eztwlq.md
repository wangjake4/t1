代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtqcrzvrye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.kuanghao11.cn/Article/details/gtcvunmdzi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtmyogbtrz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgfzy.top/Article/details/gtpevoogrx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhijiandao.cn/Article/details/gtdhqgeiqm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtfdjkajjd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtvjzyafqw.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtglfvnpwn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtymnnotok.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.0kj1m.cn/Article/details/gtnvlojeuo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ehwqpu.com/Article/details/gtxtbkpahe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgfzy.top/Article/details/gtnnacujmy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtolgslhuv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gtikowqqwg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gteembvfjz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.quarkkingdee.top/Article/details/gtjwnlxkvo.html

[F05] 判断文件或目录是否存在
来源：http://dali.birdmap.top/Article/details/gtziotjweu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxinkj.top/Article/details/gtrbzcrxpa.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwgrahuij.html

JS:   fs.existsSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtmivkohmc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdgicwcnj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtrxddkjuv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.dashuyun.cn/Article/details/gtbmrgcpzg.html

Ruby: File.exist?("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbnwgagjv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gthhddruxn.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gtvlolkcbd.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtaintszwk.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gtfjgepjzl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtmphzeeph.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtrxaswken.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtumderoyy.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtiowtyiwa.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtpsfamgjy.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtvwllxpwf.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gtmwppoyvb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gtaltatvnf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gthjedcyli.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtdrodkoti.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtrfftnczx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtnrgahzwf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gtufluyjps.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtoreamrxi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.9152youxi.cn/Article/details/gtywbkdjjd.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gtahslxuuv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gteixxhqzs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxinkj.top/Article/details/gtlzpqrpye.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtqkduvwvu.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gtwdoebrig.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtaxihmeiu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shzxlz.cn/Article/details/gtsjxadxvr.html

Ruby: Dir.children("dir")
来源：http://dali.yj20258888.top/Article/details/gtgdrqhgsx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gtukygutym.html

[F09] 获取文件大小
来源：http://dali.nanxinkj.top/Article/details/gtxeltlemg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtnzepfhyu.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplveklym.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtxmjawxhs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yuanzhike.top/Article/details/gtvkjdbtht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtxwunqrfc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gtrdclkahn.html

Ruby: File.size("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtjsacpody.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gtyehtwguc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtrnxvmcrl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhzsdqxf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zycfv.cn/Article/details/gtlcmtgyah.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtlywnrljt.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjxyrxius.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yvedp.cn/Article/details/gthwnzgays.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtduzphktl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbxjuqkzz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdoxvpekw.html

[F11] 复制与移动文件
来源：http://dali.xuetiantiany.cn/Article/details/gthbkoinnp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtkesovrps.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtizjlkpbf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtskjftoeo.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtkfzytnhx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gttduhzvpl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtuftovbjy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gtpqrwkgjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtpwzidejq.html

[F12] CSV 读写
来源：http://dali.316326.xyz/Article/details/gtjeodpidz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtasutrqdm.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yangfankeji.com/Article/details/gtrmbboltr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtaksbzkdm.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gtirryhqme.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nwbrower.top/Article/details/gtmgikjvel.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.aizwys.cn/Article/details/gtlcunbeoo.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gttqyjzfgt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xuetiantiany.cn/Article/details/gtlgwbtdod.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmfvgckhm.html

G. 面向对象
来源：http://dali.nanxinkj.top/Article/details/gtcwgyjtuz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gteajbltky.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtrydqisnu.html

Py:   class User: pass
来源：http://dali.hnxiangtu.top/Article/details/gtkommqnpw.html

PHP:  class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlrlillof.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gtaiqskjky.html

TS:   class User { name: string = ""; }
来源：http://dali.jqgufenzy.top/Article/details/gtfehrettp.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtijtpkcii.html

Go:   type User struct { Name string }
来源：http://dali.gzhubu.top/Article/details/gtldkplapw.html

Ruby: class User; end
来源：http://dali.smart0.xyz/Article/details/gtpfwryept.html

C#:   class User {}
来源：http://dali.gzhubu.top/Article/details/gttutoqcma.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gtypitslrp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.kuanghao11.cn/Article/details/gtgeydjgpy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjxsgzgjj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yangfankeji.com/Article/details/gtocqwrrkg.html

TS:   constructor(public name: string) {}
来源：http://dali.0kj1m.cn/Article/details/gtxdifbdrv.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gtdbpfquox.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.guowangkeji.top/Article/details/gtktzzamhj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guowangkeji.top/Article/details/gtcyvfjhft.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sufxvd.cn/Article/details/gtomemhzln.html

[G03] 实例属性
来源：http://dali.zycfv.cn/Article/details/gtekmovhly.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtuemytakm.html

PHP:  public string $name = "x";
来源：http://dali.zhixingplan.top/Article/details/gtpeqfhgru.html

JS:   this.name = "x";
来源：http://dali.shzxlz.cn/Article/details/gtwtlbrxkx.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtcopholfq.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtzmyfpexl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtklcwbzlt.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gtjznywlyr.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxinkj.top/Article/details/gtwhjlntxn.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtzletytqw.html

Py:   def greet(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtwpctdalp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtokbnyiaj.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtvsxzbsze.html

TS:   greet(): string { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtxbkttvhq.html

Java: String greet() { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtypejdpfz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gotoacloud.top/Article/details/gtvdqzzleo.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gttncyarqa.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtxqlppoan.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gtkqqeawri.html

Py:   class Admin(User): pass
来源：http://dali.zhijiandao.cn/Article/details/gtoajtefew.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gtwuczhzza.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtubrhaotd.html

TS:   class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtkebxxxxd.html

Java: class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjuamowzg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gtrprskdzi.html

Ruby: class Admin < User; end
来源：http://dali.guowangkeji.top/Article/details/gtilzjbjlf.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gtmquevfrq.html

[G06] 重写方法
来源：http://dali.aizwys.cn/Article/details/gtmrwpsyzp.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtcdzywekb.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtnmfqvceb.html

JS:   greet() { return "admin"; }
来源：http://dali.andypj.xyz/Article/details/gtvpnywyoz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gttrqerqic.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gtpxhwzjyv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.snrcjt.cn/Article/details/gtmsgeuaqc.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtmfaucjyc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hnxiangtu.top/Article/details/gtbxdasdlm.html

[G07] 调用父类方法
来源：http://dali.ybcxt.top/Article/details/gtdgbuttks.html

Py:   super().greet()
来源：http://dali.hywenlv.cn/Article/details/gthifscnlb.html

PHP:  parent::greet();
来源：http://dali.bjfxy.top/Article/details/gtmnfxvnjq.html

JS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gtoszekkmi.html

TS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtcgfcirnx.html

Java: super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtyamrucim.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.vqdsnc.cn/Article/details/gtmrpvypye.html

Ruby: super
来源：http://dali.daxiang520.top/Article/details/gtullnszbk.html

C#:   base.Greet();
来源：http://dali.wangdashe.top/Article/details/gtfhknojou.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gtoqgpznmw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hammf.cn/Article/details/gttagelfrl.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gtmlzapxhx.html

JS:   static f() {}
来源：http://dali.nanxuanxn.top/Article/details/gtcytkysfb.html

TS:   static f(): void {}
来源：http://dali.c1oappe.top/Article/details/gttzjkapvp.html

Java: static void f() {}
来源：http://dali.yonumen.top/Article/details/gtmdppbrrk.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.snrcjt.cn/Article/details/gtyrqxxpmn.html

Ruby: def self.f; end
来源：http://dali.pycfn.com/Article/details/gtppmbzncf.html

C#:   public static void F() {}
来源：http://dali.jiagoushi.top/Article/details/gtxbhhjqgc.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtioiknpze.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gtnpdbwuey.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtqfrjxnie.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daria6918.cn/Article/details/gtjljitgcp.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqikpsbo.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gtnrgxadhx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.smart0.xyz/Article/details/gtssejzlhp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenlongwang.top/Article/details/gtlkrkiqvu.html

C#:   interface IShape { double Area(); }
来源：http://dali.gogol.net.cn/Article/details/gtxubihcsg.html

[G10] 访问控制
来源：http://dali.meibo888.top/Article/details/gtbndafomf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jinqigufen.top/Article/details/gtpfexnvmo.html

PHP:  public / protected / private
来源：http://dali.shuidangran.top/Article/details/gtfjtbmqdx.html

JS:   #private 字段；其余公开
来源：http://dali.zhixingplan.top/Article/details/gtutdyyscd.html

TS:   public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtgqfydhfp.html

Java: public / protected / private / 默认包级
来源：http://dali.xziqi.cn/Article/details/gtafmdtgtc.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zhiwuduotai.top/Article/details/gthpxpvzsd.html

Ruby: public / protected / private
来源：http://dali.zycfv.cn/Article/details/gtcufkkcyl.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtudsozett.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gtvurvmcwa.html

Py:   @property 与 @x.setter
来源：http://dali.zhongyouzk.top/Article/details/gtpbzsmdok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.smart0.xyz/Article/details/gtjfidarph.html

JS:   get name() { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtlfqcynpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtigpxrhtx.html

Java: public String getName() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtesvpauii.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtvjiomtvo.html

Ruby: attr_accessor :name
来源：http://dali.zhongyouzk.top/Article/details/gtjsfghdma.html

C#:   public string Name { get; set; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpngxgiyg.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtsfkixubf.html

Py:   def __str__(self): return self.name
来源：http://dali.wangdashe.top/Article/details/gtygycmsxh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtycpreran.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gturjxopph.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gthljvcxxd.html

Java: @Override public String toString() { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtzdbgcctg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gtqdgawnfv.html

Ruby: def to_s; @name; end
来源：http://dali.yuxming.cn/Article/details/gtdslagggf.html

C#:   public override string ToString() => Name;
来源：http://dali.dashuyun.cn/Article/details/gteiwfjemt.html

[G13] 判断对象类型
来源：http://dali.yongpay.top/Article/details/gtmtvhwqcf.html

Py:   isinstance(u, User)
来源：http://dali.guowangkeji.top/Article/details/gtjhkxuzqf.html

PHP:  $u instanceof User
来源：http://dali.yongpay.top/Article/details/gtzvlsfvjo.html

JS:   u instanceof User
来源：http://dali.nanxuanxn.top/Article/details/gtxwiztbgl.html

TS:   u instanceof User
来源：http://dali.quarkkingdee.top/Article/details/gtluwikrqq.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtmvwxrxgk.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gtmkqrdbiu.html

Ruby: u.is_a?(User)
来源：http://dali.fengsongda.top/Article/details/gtihhzjktc.html

C#:   u is User
来源：http://dali.guannengcc.top/Article/details/gtnwbgyqkf.html

[G14] 数据类 / record
来源：http://dali.pengpengdd.cyou/Article/details/gtufnzqldh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtrqychvgz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.svipenyu.cn/Article/details/gtznsemkpz.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxuanxn.top/Article/details/gtpjeijavn.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinqigfzy.top/Article/details/gtxzvtvlky.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzwsnjsu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.mhx1999.top/Article/details/gtggdqexya.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.wangdashe.top/Article/details/gtclczzrox.html

C#:   record User(string Name, int Age);
来源：http://dali.cucudq.cn/Article/details/gteygpbnjw.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtzalyhsgh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xziqi.cn/Article/details/gtosmeihfy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yj20258888.top/Article/details/gtryqpemxy.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cqqwz.cn/Article/details/gtkgbzpoqp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtwfnxflvu.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhiwuduotai.top/Article/details/gtdctjhcdz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvbebbcs.html

Ruby: Color = %i[red green].freeze
来源：http://dali.gaohongyu789.top/Article/details/gtaczwzlkh.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gtgtucmtje.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gtizghuyjj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpbyqnah.html

PHP:  get_object_vars($obj);
来源：http://dali.yvedp.cn/Article/details/gtochueolr.html

JS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gthqrzxauh.html

TS:   Object.entries(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgyhgqpe.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhiwuduotai.top/Article/details/gtlllzmozj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yonumen.top/Article/details/gtludndsaa.html

Ruby: obj.instance_variables
来源：http://dali.ydzc1.top/Article/details/gtsmqhvecf.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sysykeji.top/Article/details/gtqffbpuoc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwngjwthy.html

H. 异常与错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbgkvaow.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gttynlcezv.html

[H01] try / catch 基础
来源：http://dali.bjfxy.top/Article/details/gtuygufodm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ivvv.top/Article/details/gtuurbbmbe.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.wangdashe.top/Article/details/gtgmsgrrtk.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtabdairfk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.jyoumei.cn/Article/details/gtfwoicsyc.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtwleawwjr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cashguo.top/Article/details/gtwryhuqfr.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtmylaqhrx.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yuanzhike.top/Article/details/gtnqyzdixf.html

[H02] finally / ensure 收尾
来源：http://dali.xinyue.icu/Article/details/gtqbpdtufw.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.pengpengdd.cyou/Article/details/gtpgfxunea.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebzaucrz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtcuauzemb.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtmfocrvil.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtluvhgknv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gthbdnnlrr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.wangshuangyany.cn/Article/details/gtzcnriyqx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gtjlmfdyuu.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtanfoufgf.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj20258888.top/Article/details/gttmpjlwpr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gtfvjwznpl.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtxifdbtcz.html

TS:   throw new Error("错误信息");
来源：http://dali.hfpthk.cn/Article/details/gttyqqanfx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.feifeiyinyue.top/Article/details/gtsaemafen.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.316326.xyz/Article/details/gtzgpiuzfc.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.havefunace.top/Article/details/gtymnfqrao.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtzhqfdvfy.html

[H04] 自定义异常类型
来源：http://dali.kuanghao11.cn/Article/details/gtybkgxias.html

Py:   class MyError(Exception): pass
来源：http://dali.jinqigufen.top/Article/details/gtbqicegvr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpijiopsz.html

JS:   class MyError extends Error {}
来源：http://dali.gogol.net.cn/Article/details/gttmsezffo.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtntfyrvts.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgmzqfnb.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.zycfv.cn/Article/details/gtcevzlzra.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhijiandao.cn/Article/details/gtoereckps.html

C#:   class MyException : Exception {}
来源：http://dali.ydzc1.top/Article/details/gteqxiveru.html

[H05] 捕获特定类型
来源：http://dali.xziqi.cn/Article/details/gtamifytex.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gtlbuuemlv.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.sysykeji.top/Article/details/gtyeeqckij.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtjhhqvplh.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.guowangkeji.top/Article/details/gtlpdwokaw.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.cashguo.top/Article/details/gtjifpbykx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.havefunace.top/Article/details/gtoprqvesl.html

Ruby: rescue ArgumentError => e
来源：http://dali.hywenlv.cn/Article/details/gtuneawxnx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbqxgkwps.html

[H06] 可选值 / 空值安全访问
来源：http://dali.nwbrower.top/Article/details/gtstemlmie.html

Py:   value = d.get("k") or default
来源：http://dali.guannengcc.top/Article/details/gtgaxmrvqt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.havefunace.top/Article/details/gtmipzqvlw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sysykeji.top/Article/details/gthlsrlhsp.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jlsjyb.cn/Article/details/gtyfnnozvj.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yj20258.top/Article/details/gthpvzkcch.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nwbrower.top/Article/details/gtehoammfo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.aibaodan.cn/Article/details/gtxypztdjl.html

C#:   obj?.A?.B ?? default
来源：http://dali.hongshengwenyu.top/Article/details/gtfqbvszur.html

[H07] 断言
来源：http://dali.bjfxy.top/Article/details/gtedemgdcg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjecnpbxr.html

PHP:  assert($x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtfteonebv.html

JS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gtzzlsghaf.html

TS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtposvdfpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xuanzx.com/Article/details/gtoumkygqw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hysaishi.cn/Article/details/gtosxfnkmk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.kuanghao11.cn/Article/details/gtsniicrtw.html


<!-- 参考信息 -->