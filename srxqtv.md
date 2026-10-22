代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ppjwa.cn/Article/details/gteixbpggy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.vqdsnc.cn/Article/details/gtyisdlalx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtdfqhnpek.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtvopvmlho.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtfgowrmbh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gthknuwbon.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jiagoushi.top/Article/details/gtlbvlrlqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gtpdmtvzgm.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtfjgafjko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebuabwrm.html

PHP:  file_exists("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtfoykurbj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtfrbkcmxq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtykqaszik.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ppjwa.cn/Article/details/gtqigdntwa.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gthfrybdfk.html

Ruby: File.exist?("a.txt")
来源：http://dali.ivvv.top/Article/details/gtqdgegdyw.html

C#:   File.Exists("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpcmvryvc.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gtsjhtsrco.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgmngttqz.html

PHP:  unlink("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtcjouradw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gteetblthy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgftnyfvr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtbnpnxont.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtzblgbtpz.html

Ruby: File.delete("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpbrsodfq.html

C#:   File.Delete("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gtyrakxebr.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtmiweglyt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtvoizriht.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gtwadhzvjy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenzaomai.com/Article/details/gtuneylclu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtcytqfapi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtrkhfcsst.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtyfhkkgxn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenlongwang.top/Article/details/gtetfjhfyi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gtpnfckwaa.html

[F08] 遍历目录
来源：http://dali.yj202588.top/Article/details/gtfdvcnzfu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tian-w.cn/Article/details/gtvskrjpyo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jyoumei.cn/Article/details/gtygnfktdg.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gtectubeoj.html

TS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtyifinzgt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtgldxfzas.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gtgwssscxg.html

Ruby: Dir.children("dir")
来源：http://dali.shzxlz.cn/Article/details/gtuamdgghp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtkposehav.html

[F09] 获取文件大小
来源：http://dali.chenjidiqi.icu/Article/details/gtfbhrcxrx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtwyozovsu.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gttughtypr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtxadconja.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hongshengwenyu.top/Article/details/gtajkqtczk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtosjuauhg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gtrcjtfgfn.html

Ruby: File.size("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtgolrycpn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtstrmvhfb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gtuitmxanl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtajeckkmt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtkavtjctu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtocwzahop.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtcnzrojhs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.dianchejie.cn/Article/details/gtedrgrakd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtwfkwdfmp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtesjonttz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtoviaycfk.html

[F11] 复制与移动文件
来源：http://dali.zhixingplan.top/Article/details/gtgwifmcfp.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtnvyewtqp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtsubgxabj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gtxiqfajaw.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtqntiwmis.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.quarkkingdee.top/Article/details/gtxycrkfdn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.0kj1m.cn/Article/details/gtopvytejw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigufen.top/Article/details/gthfgryvur.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtvtnsmlrj.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezkslrkn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gtlnpdtheq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gtekjoxbmc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.pengpengdd.cyou/Article/details/gtfludpalf.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtoutgeqtd.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gtgumsxuug.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jianghu66.top/Article/details/gtmcyalwoi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gtdhqozhln.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigufen.top/Article/details/gtnmvkjbun.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmlzzfeiv.html

G. 面向对象
来源：http://dali.zhijiandao.cn/Article/details/gtnwgfzhwh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtodtisyiu.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gtksqwqxls.html

Py:   class User: pass
来源：http://dali.quarkkingdee.top/Article/details/gtynuuuaru.html

PHP:  class User {}
来源：http://dali.iojbl.cn/Article/details/gtdfwgdulw.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjfivfzb.html

TS:   class User { name: string = ""; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuuwozvyy.html

Java: class User {}
来源：http://dali.birdmap.top/Article/details/gtzwskyiqe.html

Go:   type User struct { Name string }
来源：http://dali.hnqzz.top/Article/details/gtlgbgqvst.html

Ruby: class User; end
来源：http://dali.meibo888.top/Article/details/gtmlzuwfgf.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gtautmaijb.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtefmibypl.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtldnizuxf.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gtzshxkjju.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gtxtzchezo.html

TS:   constructor(public name: string) {}
来源：http://dali.jqgfzy.top/Article/details/gtslxtwpfd.html

Java: User(String name) { this.name = name; }
来源：http://dali.bjfxy.top/Article/details/gtmumhxzjg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.smart0.xyz/Article/details/gtlrthzgwu.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gttigxlhvt.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hysaishi.cn/Article/details/gtgnrjrlsh.html

[G03] 实例属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlewagjp.html

Py:   self.name = "x"
来源：http://dali.yangfankeji.com/Article/details/gtflvqtbng.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjsdrcyt.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtusmknoee.html

TS:   name: string = "x";
来源：http://dali.hfpthk.cn/Article/details/gtkbyiipre.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtgfcoyeml.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yuanzhike.top/Article/details/gtscafmhqf.html

Ruby: @name = "x"
来源：http://dali.gotoacloud.top/Article/details/gtdmcvbwjq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gtqcmveetz.html

[G04] 定义方法
来源：http://dali.shuidangran.top/Article/details/gtdvubbzev.html

Py:   def greet(self): return self.name
来源：http://dali.yj20258888.top/Article/details/gtjoxwzxkf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gtafhbjhqf.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gthvgsjvlm.html

TS:   greet(): string { return this.name; }
来源：http://dali.aizwys.cn/Article/details/gtzazydlyi.html

Java: String greet() { return name; }
来源：http://dali.hammf.cn/Article/details/gttnpbzxds.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gtzitxlilh.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtnnnrtqyt.html

C#:   public string Greet() => Name;
来源：http://dali.jianghu66.top/Article/details/gteqcvpjuz.html

[G05] 继承
来源：http://dali.meibo888.top/Article/details/gtrzkglbuo.html

Py:   class Admin(User): pass
来源：http://dali.nanxuanxn.top/Article/details/gtnsiuymik.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gttsfanxfo.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gtlxovdoct.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gtqduirxis.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpkrlhxq.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gtvwexvqns.html

Ruby: class Admin < User; end
来源：http://dali.ppjwa.cn/Article/details/gtlwxbblrv.html

C#:   class Admin : User {}
来源：http://dali.ehwqpu.com/Article/details/gttfwsolvz.html

[G06] 重写方法
来源：http://dali.xuanzx.com/Article/details/gtxvfknbge.html

Py:   def greet(self): return "admin"
来源：http://dali.ppjwa.cn/Article/details/gtrkjgpbng.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtpxewvrjk.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gtfrihhebn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtruqumymu.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtiptktkna.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gtktqteomj.html

Ruby: def greet; "admin"; end
来源：http://dali.gogol.net.cn/Article/details/gtevjyybcj.html

C#:   public override string Greet() => "admin";
来源：http://dali.pengpengdd.cyou/Article/details/gtpyoslxni.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gtmutdgqet.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gtopldwfso.html

PHP:  parent::greet();
来源：http://dali.hnxiangtu.top/Article/details/gtnnmpxfht.html

JS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtsrxbouxm.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gtfxagxymm.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtmtmrugta.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hywenlv.cn/Article/details/gtkloxbxdx.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gtxagnwxrl.html

C#:   base.Greet();
来源：http://dali.gzhubu.top/Article/details/gtdrrpcosn.html

[G08] 静态方法与属性
来源：http://dali.shangyingyoupin.top/Article/details/gtqmsrwtsx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gttxjcttei.html

PHP:  public static function f() {}
来源：http://dali.cqqwz.cn/Article/details/gtqccuricd.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gtamsjbimf.html

TS:   static f(): void {}
来源：http://dali.ehwqpu.com/Article/details/gtrowhuhkf.html

Java: static void f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtncjbjtka.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.dashuyun.cn/Article/details/gthvdhaupf.html

Ruby: def self.f; end
来源：http://dali.wangdashe.top/Article/details/gtvarjzlby.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtekyrdnty.html

[G09] 接口 / 抽象类
来源：http://dali.zhixingplan.top/Article/details/gtnjsqhcwz.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gtdivyhpyq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gtilrepowk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinghuilouyu.cn/Article/details/gtopnkqubk.html

TS:   interface Shape { area(): number; }
来源：http://dali.havefunace.top/Article/details/gtbkxtjdde.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gtqhwrbjrq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.havefunace.top/Article/details/gtivucqdcm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jianghu66.top/Article/details/gtisbhhgbj.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gtvcubabhl.html

[G10] 访问控制
来源：http://dali.redwolf501.top/Article/details/gtnigskumi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtmuinlswg.html

PHP:  public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtsnborach.html

JS:   #private 字段；其余公开
来源：http://dali.zhiwuduotai.top/Article/details/gtaaltgnag.html

TS:   public / protected / private
来源：http://dali.sweek.top/Article/details/gtkxodmuyu.html

Java: public / protected / private / 默认包级
来源：http://dali.sysykeji.top/Article/details/gtuggcgcds.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtoutvkwwl.html

Ruby: public / protected / private
来源：http://dali.havefunace.top/Article/details/gtfqivcumg.html

C#:   public / protected / private / internal
来源：http://dali.yueranfly.top/Article/details/gtdqhfjkxs.html

[G11] getter / setter
来源：http://dali.gzhubu.top/Article/details/gtrqzcfcaj.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gtvndnuokj.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtzhsypgzd.html

JS:   get name() { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gtadwtytrb.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gtzpgqyjvd.html

Java: public String getName() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gthdtqczbj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ydzc1.top/Article/details/gtgqwxfhtm.html

Ruby: attr_accessor :name
来源：http://dali.yanxiufei.cn/Article/details/gtjqybocer.html

C#:   public string Name { get; set; }
来源：http://dali.xylfe.cn/Article/details/gtjhlwepkk.html

[G12] 对象转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtemtpjcpb.html

Py:   def __str__(self): return self.name
来源：http://dali.cdnleiting.top/Article/details/gtjgrctogo.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtwagmnprp.html

JS:   toString() { return this.name; }
来源：http://dali.dianchejie.cn/Article/details/gtwekpimnu.html

TS:   toString(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtciirgmcw.html

Java: @Override public String toString() { return name; }
来源：http://dali.daxiang520.top/Article/details/gttdjqxznj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.mhx1999.top/Article/details/gtnyaykpja.html

Ruby: def to_s; @name; end
来源：http://dali.gaohongyu789.top/Article/details/gtiobiiiys.html

C#:   public override string ToString() => Name;
来源：http://dali.guannengcc.top/Article/details/gtqeuzgqbi.html

[G13] 判断对象类型
来源：http://dali.zhiwuduotai.top/Article/details/gtuandnwlu.html

Py:   isinstance(u, User)
来源：http://dali.jyoumei.cn/Article/details/gtgupehwjw.html

PHP:  $u instanceof User
来源：http://dali.gzhubu.top/Article/details/gtqtvtesef.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gteyjxqjey.html

TS:   u instanceof User
来源：http://dali.shangyingyoupin.top/Article/details/gtujranirr.html

Java: u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtphkwejfq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tian-w.cn/Article/details/gtupcrgulg.html

Ruby: u.is_a?(User)
来源：http://dali.zhixingplan.top/Article/details/gtqbnvwkxd.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gthiuwoauj.html

[G14] 数据类 / record
来源：http://dali.xziqi.cn/Article/details/gthizyywwm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gtrznrojfo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.mhx1999.top/Article/details/gtvuigexlc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yuanzhike.top/Article/details/gtoedouhta.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtgsghokii.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtrksdksjf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cdnleiting.top/Article/details/gtxgerwphl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.havefunace.top/Article/details/gtatnxrfsg.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gtfdmwbeji.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtxjcpnvbl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cqqwz.cn/Article/details/gtehmkqitn.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.dashuyun.cn/Article/details/gtuwvcflju.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.wangshuangyany.cn/Article/details/gtlphfympb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtqimmczmi.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtmfajnava.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.gotoacloud.top/Article/details/gtohjhyoni.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtthhnhjwc.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ehwqpu.com/Article/details/gtgwqefbtz.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznhaqkjw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yvedp.cn/Article/details/gtxjkiohpe.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtvseikoay.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnoxlpvp.html

TS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtvsbpyvrv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.cheryme.top/Article/details/gtpwzcscqy.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.havefunace.top/Article/details/gtxbrvaflk.html

Ruby: obj.instance_variables
来源：http://dali.jqgufenzy.top/Article/details/gtguwdsmld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xylfe.cn/Article/details/gthiebpkjs.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxmmlnxwn.html

H. 异常与错误处理
来源：http://dali.sweek.top/Article/details/gtkzslzibh.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkoxadxii.html

[H01] try / catch 基础
来源：http://dali.yanxiufei.cn/Article/details/gtzbpbkyfq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.haohaochexian.top/Article/details/gtnxwscbwz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gtlbiqpwki.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigufen.top/Article/details/gtkrhwhtvc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.gotoacloud.top/Article/details/gtzzhgjqdz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gtbmdmiher.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gtkwqzrvde.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrnyossjk.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.cashguo.top/Article/details/gtagypposs.html

[H02] finally / ensure 收尾
来源：http://dali.daxiang520.top/Article/details/gtdkumeuwg.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.nwbrower.top/Article/details/gtiuoohrit.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gtcwkjggmr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtagqdchte.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jianghu66.top/Article/details/gtwfqupuvx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.fzhhl.top/Article/details/gtvsrvkenc.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtzkprzfpv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtrjnydnsp.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gttvrgkreh.html

[H03] 主动抛出异常
来源：http://dali.sweek.top/Article/details/gtwrigsybe.html

Py:   raise ValueError("错误信息")
来源：http://dali.dashuyun.cn/Article/details/gtrxlpmips.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtuwlrazgj.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtnqqgshld.html

TS:   throw new Error("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gtkdkznrgv.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtpximoaxf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgfzy.top/Article/details/gtmpyzbgvr.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shzxlz.cn/Article/details/gtowdxhmer.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gthfkaexjw.html

[H04] 自定义异常类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmctvirbp.html

Py:   class MyError(Exception): pass
来源：http://dali.ppjwa.cn/Article/details/gtomdersqo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ybcxt.top/Article/details/gtmiaayvdz.html

JS:   class MyError extends Error {}
来源：http://dali.9152youxi.cn/Article/details/gtuaeflzoq.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtatjlxnud.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtuskremkk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jqgfzy.top/Article/details/gtxteasgau.html

Ruby: class MyError < StandardError; end
来源：http://dali.zdqjudy.top/Article/details/gtzaeirrby.html

C#:   class MyException : Exception {}
来源：http://dali.ehwqpu.com/Article/details/gtvicdwmxm.html

[H05] 捕获特定类型
来源：http://dali.jyoumei.cn/Article/details/gtnimdlfvk.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtuiisehgd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.wangdashe.top/Article/details/gtpvoppavj.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.havefunace.top/Article/details/gtdwlrpthf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvymcign.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gttlcfmbet.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sufxvd.cn/Article/details/gtiipvfmgw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gttmtwqjfx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.0kj1m.cn/Article/details/gtaorkqckm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yuanzhike.top/Article/details/gtmwymgtuc.html

Py:   value = d.get("k") or default
来源：http://dali.andypj.xyz/Article/details/gtxgvncycw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.sweek.top/Article/details/gtcjzgsbnz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yuanzhike.top/Article/details/gtgcoxjofi.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jqgufenzy.top/Article/details/gtjzzptaen.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.wangshuangyany.cn/Article/details/gtjsnmzhid.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.sysykeji.top/Article/details/gtwdfujimt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhongyouzk.top/Article/details/gtbudcnvmz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yj20258888.top/Article/details/gtqxbpjlbv.html

[H07] 断言
来源：http://dali.xziqi.cn/Article/details/gtvviwvqej.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hnxiangtu.top/Article/details/gtlhkcokbp.html

PHP:  assert($x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtthalzhng.html

JS:   console.assert(x > 0);
来源：http://dali.chenjidiqi.icu/Article/details/gttlqvtxol.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtmcacqifg.html

Java: assert x > 0 : "必须为正";
来源：http://dali.zhongyouzk.top/Article/details/gtwshuwgwd.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cdnleiting.top/Article/details/gtvkmfedzz.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.shangyingyoupin.top/Article/details/gtazaxdigi.html

C#:   Debug.Assert(x > 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfqpbzxf.html

[H08] 获取错误信息与堆栈
来源：http://dali.yueranfly.top/Article/details/gtkfgtmgpt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhongyouzk.top/Article/details/gtrvlwqqgp.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hnxiangtu.top/Article/details/gtjhfsmmeh.html

JS:   e.message;  e.stack
来源：http://dali.hnxiangtu.top/Article/details/gtiqztyixg.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.wangdashe.top/Article/details/gtterukjba.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnxiangtu.top/Article/details/gtlohtsdvm.html

Go:   err.Error()
来源：http://dali.c1oappe.top/Article/details/gtaxdjmvtm.html


<!-- 参考信息 -->