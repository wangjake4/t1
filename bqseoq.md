代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtfssfdjzs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.snrcjt.cn/Article/details/gtwrkwpbuc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtakhborxc.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtyaqmmcgz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gtfpetiynp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hammf.cn/Article/details/gtdwmzwvig.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sufxvd.cn/Article/details/gtiqalhdnm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gtklssgtkj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xinyue.icu/Article/details/gtdtamktyl.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtfgwocncx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.snrcjt.cn/Article/details/gtvigtodrd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.smart0.xyz/Article/details/gtxhwkslld.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258888.top/Article/details/gtizmbnnox.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shzxlz.cn/Article/details/gtbuwnpugm.html

PHP:  file_exists("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkzfnzgy.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuyxiexdk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcqeuccpz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gttweoridt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwrrgmki.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtnauohfiz.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gthimihkqc.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzrflowpf.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gttwjuktah.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gthjptaihz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtcylstgge.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtvzsdtqqd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtbipclswa.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtuapldzyb.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtemxrkbpn.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gttwdfwyjm.html

[F07] 创建目录（含多级）
来源：http://dali.wangshuangyany.cn/Article/details/gtptdcebrk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtauprqxhu.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxkqbprrf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gthpdvakbu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gtmdrfuhlo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nanxinkj.top/Article/details/gtuangqvrj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxinkj.top/Article/details/gtcpkxcvvf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.9152youxi.cn/Article/details/gtefijhtqm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtxepehoao.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaerzfaw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtuekmyvkm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtddzpwnrj.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtccuqsxeh.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gtjhbdsprq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gtfopooelj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtjtleracb.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtynfzlpoq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtgkdgciug.html

[F09] 获取文件大小
来源：http://dali.9152youxi.cn/Article/details/gthlldgdmk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtzgacuuto.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtwaawfycr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtsvlvwhln.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtvkwukzip.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtxikmlnwg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gtyjmpgppu.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtzltzjcmg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtsqhzrpvh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtbrxbcukv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtiporjbaj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gtxdngnzes.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtnrcquzsb.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzstnnebn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtnyfykygb.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtrnxcupvr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtxlytezqo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtjrukdrsr.html

[F11] 复制与移动文件
来源：http://dali.zhengqikj.top/Article/details/gtnbbusaqo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aizwys.cn/Article/details/gtwjfhvyea.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtpncrhuzj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtvyxsjius.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gtydqiufzh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtmbdujrsd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.andypj.xyz/Article/details/gtyqwlbqls.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcmufwvru.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hammf.cn/Article/details/gthpkgdaqn.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqgerayn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtikscsfsr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gtpoglvtnx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gtlkvcfyto.html

TS:   // 同上
来源：http://dali.yj20258.top/Article/details/gtzditopns.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yanxiufei.cn/Article/details/gtsirifciy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.sxryk.cn/Article/details/gtygydfmsg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.guannengcc.top/Article/details/gtocvblikb.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtgumljlnh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgaztjmud.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gtffhrtdkl.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoqixsnpv.html

[G01] 定义类
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcdrdqkj.html

Py:   class User: pass
来源：http://dali.yj20258888.top/Article/details/gtnnrrpweq.html

PHP:  class User {}
来源：http://dali.jinqigufen.top/Article/details/gtptifodyz.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtymbnslkr.html

TS:   class User { name: string = ""; }
来源：http://dali.jiagoushi.top/Article/details/gthahyizyb.html

Java: class User {}
来源：http://dali.cqqwz.cn/Article/details/gtefegwnbb.html

Go:   type User struct { Name string }
来源：http://dali.mhx1999.top/Article/details/gtqrearsaa.html

Ruby: class User; end
来源：http://dali.aizwys.cn/Article/details/gtggwfjvfl.html

C#:   class User {}
来源：http://dali.iojbl.cn/Article/details/gtlnwnwtul.html

[G02] 构造函数
来源：http://dali.zhengqikj.top/Article/details/gtrzjglrjs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuipaltuu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nanxinkj.top/Article/details/gtejkpboks.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.daria6918.cn/Article/details/gthyajcshu.html

TS:   constructor(public name: string) {}
来源：http://dali.havefunace.top/Article/details/gtzwkubevq.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gtwwqvnkee.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hysaishi.cn/Article/details/gtkindjvhl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hywenlv.cn/Article/details/gturdxpgkk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gtbsabbzsa.html

[G03] 实例属性
来源：http://dali.jlsjyb.cn/Article/details/gtxwgoriqf.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtzljecnvo.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gtaifsvbrc.html

JS:   this.name = "x";
来源：http://dali.cucudq.cn/Article/details/gtudymbwnz.html

TS:   name: string = "x";
来源：http://dali.yuxming.cn/Article/details/gtviuwbder.html

Java: private String name;
来源：http://dali.gzhubu.top/Article/details/gtppizmxvb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gtwvmhmmga.html

Ruby: @name = "x"
来源：http://dali.birdmap.top/Article/details/gtxrximokg.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gogol.net.cn/Article/details/gtioxqjrzg.html

[G04] 定义方法
来源：http://dali.jyoumei.cn/Article/details/gtdagpbzdq.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gtbyrncnep.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gtetjqners.html

JS:   greet() { return this.name; }
来源：http://dali.ydzc1.top/Article/details/gtaujqasii.html

TS:   greet(): string { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtonwzzcta.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gtnqltcdtp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtdpdhqotk.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gtjzkzxjvf.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gthjghapqc.html

[G05] 继承
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcnmnakv.html

Py:   class Admin(User): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtghimnvly.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gtncliautn.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnyqjfgnf.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtoozyewdf.html

Java: class Admin extends User {}
来源：http://dali.zhixingplan.top/Article/details/gtdacavjdi.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gtqhivpunm.html

Ruby: class Admin < User; end
来源：http://dali.daxiang520.top/Article/details/gtyolfnwuv.html

C#:   class Admin : User {}
来源：http://dali.mhx1999.top/Article/details/gtazzhjvee.html

[G06] 重写方法
来源：http://dali.jqgufenzy.top/Article/details/gtucdfwyhd.html

Py:   def greet(self): return "admin"
来源：http://dali.ivvv.top/Article/details/gtdgkkakju.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmastakhw.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gttjkhzmty.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtkihajkay.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtqrfzunlo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gotoacloud.top/Article/details/gtxjwwgifw.html

Ruby: def greet; "admin"; end
来源：http://dali.kuanghao11.cn/Article/details/gtkioqnhtw.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtppxkhvza.html

[G07] 调用父类方法
来源：http://dali.yj20258888.top/Article/details/gtmofxhsyt.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtqjoikpnk.html

PHP:  parent::greet();
来源：http://dali.zhijiandao.cn/Article/details/gtbynhlzjw.html

JS:   super.greet();
来源：http://dali.cheryme.top/Article/details/gtzrtxomnr.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gtdgdkuici.html

Java: super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gtsrmtnutq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gtdhcdeiao.html

Ruby: super
来源：http://dali.daria6918.cn/Article/details/gtscwlpytk.html

C#:   base.Greet();
来源：http://dali.sweek.top/Article/details/gtfqpgdiaw.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtazzlokmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtnigyrlez.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gtoygbhkkf.html

JS:   static f() {}
来源：http://dali.andypj.xyz/Article/details/gthgcpkfgr.html

TS:   static f(): void {}
来源：http://dali.zhoulong.xyz/Article/details/gttmcajxtr.html

Java: static void f() {}
来源：http://dali.havefunace.top/Article/details/gtrwfhameu.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.birdmap.top/Article/details/gtjosftmfq.html

Ruby: def self.f; end
来源：http://dali.mhx1999.top/Article/details/gtvkwhhwsp.html

C#:   public static void F() {}
来源：http://dali.sufxvd.cn/Article/details/gtxewtpwxf.html

[G09] 接口 / 抽象类
来源：http://dali.wangshuangyany.cn/Article/details/gtwdoczjwq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnqzz.top/Article/details/gttvaigfih.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daxiang520.top/Article/details/gtyiigolbn.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtykvsnvtx.html

TS:   interface Shape { area(): number; }
来源：http://dali.hnqzz.top/Article/details/gtbwkufvim.html

Java: interface Shape { double area(); }
来源：http://dali.dianchejie.cn/Article/details/gtqxzyfydb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gtxxcjtuns.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.nanxuanxn.top/Article/details/gtzerefldj.html

C#:   interface IShape { double Area(); }
来源：http://dali.xziqi.cn/Article/details/gtxkfuynqm.html

[G10] 访问控制
来源：http://dali.9152youxi.cn/Article/details/gtfcnwuqzu.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.feifeiyinyue.top/Article/details/gttwayquzr.html

PHP:  public / protected / private
来源：http://dali.c1oappe.top/Article/details/gtadaxvwca.html

JS:   #private 字段；其余公开
来源：http://dali.ehwqpu.com/Article/details/gtzbxulilg.html

TS:   public / protected / private
来源：http://dali.redwolf501.top/Article/details/gtdviwgksc.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gtjxejtilw.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenlongwang.top/Article/details/gtpdtlyeae.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gtyohavnge.html

C#:   public / protected / private / internal
来源：http://dali.sysykeji.top/Article/details/gtnqaebham.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtrhcvqunf.html

Py:   @property 与 @x.setter
来源：http://dali.gotoacloud.top/Article/details/gtthrjoxtc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcgsnlnjd.html

JS:   get name() { return this._name; }
来源：http://dali.yonumen.top/Article/details/gtpmgkkcip.html

TS:   get name(): string { return this._name; }
来源：http://dali.yuxming.cn/Article/details/gtdgafxakw.html

Java: public String getName() { return name; }
来源：http://dali.shuidangran.top/Article/details/gtwbmsafsh.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hongshengwenyu.top/Article/details/gtsbhviktl.html

Ruby: attr_accessor :name
来源：http://dali.ivvv.top/Article/details/gtmtaulqvr.html

C#:   public string Name { get; set; }
来源：http://dali.hfpthk.cn/Article/details/gtntoevpiv.html

[G12] 对象转字符串
来源：http://dali.hnqzz.top/Article/details/gtttuzujte.html

Py:   def __str__(self): return self.name
来源：http://dali.zhixingplan.top/Article/details/gtgaupsofc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gtbonzoiut.html

JS:   toString() { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gtwizhwtnm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtmwyofmrd.html

Java: @Override public String toString() { return name; }
来源：http://dali.pycfn.com/Article/details/gtioqjgyii.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gtdfzgzkpq.html

Ruby: def to_s; @name; end
来源：http://dali.jlsjyb.cn/Article/details/gtjyodlftj.html

C#:   public override string ToString() => Name;
来源：http://dali.cdnleiting.top/Article/details/gtjvuqnpls.html

[G13] 判断对象类型
来源：http://dali.daxiang520.top/Article/details/gtdxqvxzhv.html

Py:   isinstance(u, User)
来源：http://dali.0kj1m.cn/Article/details/gthkwclkxg.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtbzmnjitg.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtdgcbnusl.html

TS:   u instanceof User
来源：http://dali.hammf.cn/Article/details/gtduyqrakm.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gtazmvcnjb.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.cheryme.top/Article/details/gtkqlcpbos.html

Ruby: u.is_a?(User)
来源：http://dali.cdnleiting.top/Article/details/gtaxlvnocc.html

C#:   u is User
来源：http://dali.ehwqpu.com/Article/details/gteenmgpvv.html

[G14] 数据类 / record
来源：http://dali.nanxinkj.top/Article/details/gtougwbmys.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ivvv.top/Article/details/gtlycwnhxz.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yongpay.top/Article/details/gtdhwflezf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gtozakkgzh.html

TS:   type User = { name: string; age: number };
来源：http://dali.mhx1999.top/Article/details/gtuyqwevbd.html

Java: record User(String name, int age) {}
来源：http://dali.tanke756.top/Article/details/gtazqwjlwc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhiwuduotai.top/Article/details/gtjrjsgili.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.daria6918.cn/Article/details/gtowyoosbc.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gtqmazause.html

[G15] 枚举
来源：http://dali.0kj1m.cn/Article/details/gtacqgckek.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtdcqrhhsr.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.vqdsnc.cn/Article/details/gtdugpyynr.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gtxtwsnvmi.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.sufxvd.cn/Article/details/gtwuhhrajb.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtmzihifnj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.ehwqpu.com/Article/details/gtxecthsvu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcxubvng.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.dashuyun.cn/Article/details/gtfsutzflm.html

[G16] 对象转数组 / 字典
来源：http://dali.jqgufenzy.top/Article/details/gtwchvmxjx.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.zhiwuduotai.top/Article/details/gtqoumlrye.html

PHP:  get_object_vars($obj);
来源：http://dali.shzxlz.cn/Article/details/gtatisudlt.html

JS:   Object.entries(obj)
来源：http://dali.ivvv.top/Article/details/gtfxhlaxpt.html

TS:   Object.entries(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtrclrgobl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.tian-w.cn/Article/details/gtvwggyrww.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirlpmdea.html

Ruby: obj.instance_variables
来源：http://dali.svipenyu.cn/Article/details/gteirjkrqy.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.bjfxy.top/Article/details/gtasfaciba.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtzmjhidlc.html

H. 异常与错误处理
来源：http://dali.ydzc1.top/Article/details/gtjovtnofy.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtoeldacnz.html

[H01] try / catch 基础
来源：http://dali.316326.xyz/Article/details/gthvqhusdz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.havefunace.top/Article/details/gtydqiyjpa.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.zhongyouzk.top/Article/details/gtdvvqddff.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatfrcbfv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtdrfjbhbl.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.vqdsnc.cn/Article/details/gtncpxjrwe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtuvcbmejk.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtonecbtas.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtadbxrgec.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gtzjkxuuht.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cheryme.top/Article/details/gtuehbjtkw.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtrxsxuycw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yangfankeji.com/Article/details/gtjrjywtxr.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtriybrrwo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gtcgtdjtfh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.smart0.xyz/Article/details/gtjahkncfz.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jlsjyb.cn/Article/details/gterfgerbu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gtgsdugsyw.html

[H03] 主动抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtdfyybwmu.html

Py:   raise ValueError("错误信息")
来源：http://dali.quarkkingdee.top/Article/details/gtgrrufhay.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhijiandao.cn/Article/details/gtmvzwbmhp.html

JS:   throw new Error("错误信息");
来源：http://dali.xinyue.icu/Article/details/gtpwgolvdr.html

TS:   throw new Error("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtalgjgokm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtoxkzelif.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ppjwa.cn/Article/details/gttmudsvbm.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zycfv.cn/Article/details/gtiavjwdue.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhxyinmf.html

[H04] 自定义异常类型
来源：http://dali.pengpengdd.cyou/Article/details/gtuctohibh.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtisexgnkx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhiwuduotai.top/Article/details/gtttqoqipe.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbpcxryhd.html

TS:   class MyError extends Error {}
来源：http://dali.316326.xyz/Article/details/gtzkhdugrh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtqbtnttse.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.sweek.top/Article/details/gtollcyfqw.html

Ruby: class MyError < StandardError; end
来源：http://dali.redwolf501.top/Article/details/gtptflzixh.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gtazmguwvw.html

[H05] 捕获特定类型
来源：http://dali.fzhhl.top/Article/details/gtbulxthay.html

Py:   except ValueError as e:
来源：http://dali.redwolf501.top/Article/details/gtvgqnvdgo.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshydpfnx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yj202588.top/Article/details/gtmwopboua.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtaddemhje.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtcwmgaubr.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.dianchejie.cn/Article/details/gtvwzpschu.html

Ruby: rescue ArgumentError => e
来源：http://dali.gaohongyu789.top/Article/details/gtwnwjlvcr.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hnqzz.top/Article/details/gtcaogatva.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cqqwz.cn/Article/details/gtpoufttvn.html

Py:   value = d.get("k") or default
来源：http://dali.yj202588.top/Article/details/gtavynfpwy.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtspeygccl.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrvppqib.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtihloflox.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xuanzx.com/Article/details/gtshtvycau.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.tanke756.top/Article/details/gtpezbdppu.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zycfv.cn/Article/details/gthzrncihd.html

C#:   obj?.A?.B ?? default
来源：http://dali.cheryme.top/Article/details/gteiqlzkwo.html

[H07] 断言
来源：http://dali.zhixingplan.top/Article/details/gtpteimqfv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ivvv.top/Article/details/gtlclluuyu.html

PHP:  assert($x > 0);
来源：http://dali.mhx1999.top/Article/details/gtgxgmktla.html

JS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gtrxyvwjpd.html

TS:   console.assert(x > 0);
来源：http://dali.jlsjyb.cn/Article/details/gtsqezqzfu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.ybcxt.top/Article/details/gtmkshvxks.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yangfankeji.com/Article/details/gtirgrwcve.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ivvv.top/Article/details/gtthnofkql.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yueranfly.top/Article/details/gtjrwirmcc.html

[H08] 获取错误信息与堆栈
来源：http://dali.hongshengwenyu.top/Article/details/gtalhgauhd.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xuetiantiany.cn/Article/details/gteecypxnj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hywenlv.cn/Article/details/gtbetxakgw.html


<!-- 参考信息 -->