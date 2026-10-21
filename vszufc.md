代发 wailian999

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gtojinuiiq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pengpengdd.cyou/Article/details/gtrkddlrut.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtigkgzcup.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gaohongyu789.top/Article/details/gtlpgoaztm.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.316326.xyz/Article/details/gtwzuolghe.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtbbwzztax.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtohyanqvp.html

[F04] 追加写入文件
来源：http://dali.wangshuangyany.cn/Article/details/gtokhmuueu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteedshqsz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtovawhctu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtloritjkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpocjjmhh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gtkddyyhca.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cucudq.cn/Article/details/gtqclsecae.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gteoafsvhv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtugknvjtm.html

[F05] 判断文件或目录是否存在
来源：http://dali.c1oappe.top/Article/details/gtyzthysvu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.0kj1m.cn/Article/details/gtomgqtaoc.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtfouctlzi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuthddfhr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtwsxxjpsu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtgoglcgch.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gtwoxlybtu.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gtakgdehcp.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtjicytnyn.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtvovhkgto.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtqrhmdqbu.html

PHP:  unlink("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtkqbnkhvy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttzlxkjsi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtngmtktjf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtsguuzwht.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfinqvkhk.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqigvkfri.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrkftjbxv.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gthnqvmmsw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtxuzqgcrc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hywenlv.cn/Article/details/gtevqkmyzn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtfvfyxfyg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtfknqodjn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gtjsqhzhwq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhengqikj.top/Article/details/gtilvvrvyv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gteyistzin.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtanwpgzxm.html

[F08] 遍历目录
来源：http://dali.aibaodan.cn/Article/details/gtbymhptxw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.havefunace.top/Article/details/gteuqtmjzl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gtqufhubxm.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtdqlrofdw.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfrkmxyxm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yanxiufei.cn/Article/details/gtblqgbmcy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgfzy.top/Article/details/gttumgrtyj.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacuzxvzs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gtdxaownrx.html

[F09] 获取文件大小
来源：http://dali.yvedp.cn/Article/details/gtpyixehie.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtqmxoggqi.html

PHP:  filesize("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtqlthsezp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzsgegrpq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gtexeasbwc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtzlkuvuse.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtwrrhnixe.html

Ruby: File.size("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtrhkmcpby.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtiorzgkvk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jyoumei.cn/Article/details/gtojedjfpy.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtsztmajey.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gthywbojzg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtwueebobn.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtzmhezbco.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gtjmshoqgr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtstaqgvhi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtukenmaaz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtmytraadz.html

[F11] 复制与移动文件
来源：http://dali.9152youxi.cn/Article/details/gtjxasawsc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gtdyhjidvj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cashguo.top/Article/details/gtytvermtl.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gtvfebdctn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtistdibvh.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtnoqvnivv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj20258888.top/Article/details/gtezefcsub.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtkjvcyidf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sysykeji.top/Article/details/gtfmcenibp.html

[F12] CSV 读写
来源：http://dali.andypj.xyz/Article/details/gtjbbzbihl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.mhx1999.top/Article/details/gthesmemye.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtiynkaykz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hfpthk.cn/Article/details/gtbeovbakv.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtlbpopbrr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gaohongyu789.top/Article/details/gtuyeposlu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.andypj.xyz/Article/details/gtdhptzpbu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtmkpwsfzp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nwbrower.top/Article/details/gtviafigcb.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtnxiuwkex.html

G. 面向对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqgdagim.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmmfyyaet.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtuzxufxiu.html

Py:   class User: pass
来源：http://dali.hysaishi.cn/Article/details/gtbmjrspnd.html

PHP:  class User {}
来源：http://dali.shzxlz.cn/Article/details/gtfdqsayeg.html

JS:   class User {}
来源：http://dali.9152youxi.cn/Article/details/gtcuierlsd.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gtucysbxya.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtjmtfjakd.html

Go:   type User struct { Name string }
来源：http://dali.cashguo.top/Article/details/gtjrqijtce.html

Ruby: class User; end
来源：http://dali.jiagoushi.top/Article/details/gttecwkiko.html

C#:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtnhzbyxsx.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkxhtgooj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jianghu66.top/Article/details/gtsyhshsdg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.kuanghao11.cn/Article/details/gthswiqpwj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gttifcykbl.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtlepmqcjh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhongyouzk.top/Article/details/gtdnmcurmf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yueranfly.top/Article/details/gtcrqecetg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtpkgeuune.html

C#:   public User(string name) { Name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtcgqugjke.html

[G03] 实例属性
来源：http://dali.jyoumei.cn/Article/details/gtvtyxfwer.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtmxnngssu.html

PHP:  public string $name = "x";
来源：http://dali.tian-w.cn/Article/details/gtliirrnzr.html

JS:   this.name = "x";
来源：http://dali.gogol.net.cn/Article/details/gtwnhnorza.html

TS:   name: string = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtudoykott.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtwlmkehhz.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gtraxnefcr.html

Ruby: @name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gtuhupcdop.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.vqdsnc.cn/Article/details/gtwckiomzg.html

[G04] 定义方法
来源：http://dali.cheryme.top/Article/details/gtfvicqunh.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtsqphmbfj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gtroebbpoy.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtatgyaiyq.html

TS:   greet(): string { return this.name; }
来源：http://dali.smart0.xyz/Article/details/gttmjurodb.html

Java: String greet() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtipdyvafh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenjidiqi.icu/Article/details/gtfkvaggvo.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmibpaoul.html

C#:   public string Greet() => Name;
来源：http://dali.yj20258888.top/Article/details/gtcvlnvadg.html

[G05] 继承
来源：http://dali.dianchejie.cn/Article/details/gtokvczdfd.html

Py:   class Admin(User): pass
来源：http://dali.cqqwz.cn/Article/details/gtrjhwfnqd.html

PHP:  class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtrystqqjx.html

JS:   class Admin extends User {}
来源：http://dali.c1oappe.top/Article/details/gtzxxzqzzh.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxkiwdsfu.html

Java: class Admin extends User {}
来源：http://dali.316326.xyz/Article/details/gtpxoelxsn.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.iojbl.cn/Article/details/gtptigfwvd.html

Ruby: class Admin < User; end
来源：http://dali.zycfv.cn/Article/details/gtrjwztkvg.html

C#:   class Admin : User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyenrhmh.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtctwnpyms.html

Py:   def greet(self): return "admin"
来源：http://dali.pengpengdd.cyou/Article/details/gtaljpjzdl.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtlhvfphdc.html

JS:   greet() { return "admin"; }
来源：http://dali.nwbrower.top/Article/details/gteydchszs.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gtgydlcvqc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gtvqoazeoi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gturcssnaj.html

Ruby: def greet; "admin"; end
来源：http://dali.quarkkingdee.top/Article/details/gthsblhdqr.html

C#:   public override string Greet() => "admin";
来源：http://dali.chenjidiqi.icu/Article/details/gtfixkofvf.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gtdeiizcov.html

Py:   super().greet()
来源：http://dali.xinyue.icu/Article/details/gthucclvdq.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtdsreizuw.html

JS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gtkyqyxpah.html

TS:   super.greet();
来源：http://dali.quarkkingdee.top/Article/details/gtdcaeunph.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gtkmumsbha.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.feifeiyinyue.top/Article/details/gtxefijixz.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gtxhffiqvy.html

C#:   base.Greet();
来源：http://dali.quarkkingdee.top/Article/details/gtqekxfnkl.html

[G08] 静态方法与属性
来源：http://dali.zhengqikj.top/Article/details/gtqnbbodph.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gtygmhxskj.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtubdfsszd.html

JS:   static f() {}
来源：http://dali.fzhhl.top/Article/details/gtauxeqmkf.html

TS:   static f(): void {}
来源：http://dali.gzhubu.top/Article/details/gtgzquyceu.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gtnohdkifm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xylfe.cn/Article/details/gttcmakabp.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gtnbrkgdfc.html

C#:   public static void F() {}
来源：http://dali.sweek.top/Article/details/gtcwvzgles.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbkhitux.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yuanzhike.top/Article/details/gtgzflqqxd.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.dashuyun.cn/Article/details/gtbfumbgxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yj20258888.top/Article/details/gtinjnvqme.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gtsiedapzz.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtnucpldsa.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hnxiangtu.top/Article/details/gtyivpvzob.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenjidiqi.icu/Article/details/gtrekgmsph.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtbzkmclmq.html

[G10] 访问控制
来源：http://dali.shzxlz.cn/Article/details/gtfqtugfnv.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhiwuduotai.top/Article/details/gtezmhvtlf.html

PHP:  public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtrcvdqjxj.html

JS:   #private 字段；其余公开
来源：http://dali.bjfxy.top/Article/details/gtilgubfop.html

TS:   public / protected / private
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlmzgfez.html

Java: public / protected / private / 默认包级
来源：http://dali.wangshuangyany.cn/Article/details/gtrymuezac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gtbhokzneg.html

Ruby: public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtfyobozrf.html

C#:   public / protected / private / internal
来源：http://dali.gotoacloud.top/Article/details/gtafleviql.html

[G11] getter / setter
来源：http://dali.yanxiufei.cn/Article/details/gtwxmzblco.html

Py:   @property 与 @x.setter
来源：http://dali.yonumen.top/Article/details/gterwyebht.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yonumen.top/Article/details/gtbudzrhds.html

JS:   get name() { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbincwaf.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruvzfkkt.html

Java: public String getName() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzuawymt.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuewnicvp.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gtzdpkupgm.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtuunshqot.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtraiduorj.html

Py:   def __str__(self): return self.name
来源：http://dali.guannengcc.top/Article/details/gtklnifole.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gtbtxcmxoq.html

JS:   toString() { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gtueoeiqqu.html

TS:   toString(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtxbpbrqox.html

Java: @Override public String toString() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtkfaiwdia.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gtbzvkjlcw.html

Ruby: def to_s; @name; end
来源：http://dali.yj20258.top/Article/details/gtrlmahdkk.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gtlicvfrkj.html

[G13] 判断对象类型
来源：http://dali.chenlongwang.top/Article/details/gtvkjqltxf.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtshphczqj.html

PHP:  $u instanceof User
来源：http://dali.andypj.xyz/Article/details/gtjfqpmoog.html

JS:   u instanceof User
来源：http://dali.yangfankeji.com/Article/details/gtjptvqatp.html

TS:   u instanceof User
来源：http://dali.yueranfly.top/Article/details/gttecikpjz.html

Java: u instanceof User
来源：http://dali.jinqigufen.top/Article/details/gtfnrqvlrw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gogol.net.cn/Article/details/gtlzruqexr.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgdzokvhm.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtwdmztzza.html

[G14] 数据类 / record
来源：http://dali.316326.xyz/Article/details/gtangjomaz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.wangshuangyany.cn/Article/details/gthngllxei.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gtrfuukmzy.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tian-w.cn/Article/details/gtnsoctqlf.html

TS:   type User = { name: string; age: number };
来源：http://dali.hywenlv.cn/Article/details/gtltwseypu.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtqtglcekc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tanke756.top/Article/details/gtsubxzlib.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtgpfckqec.html

C#:   record User(string Name, int Age);
来源：http://dali.nanxinkj.top/Article/details/gtqtqfprzl.html

[G15] 枚举
来源：http://dali.jinqigufen.top/Article/details/gtdaddklba.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gtpgxswoqm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.smart0.xyz/Article/details/gtofzorcxn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daxiang520.top/Article/details/gtpzcvnlvw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hysaishi.cn/Article/details/gtpjhbhxiq.html

Java: enum Color { RED, GREEN }
来源：http://dali.zycfv.cn/Article/details/gtfwsrncls.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.haohaochexian.top/Article/details/gtvfsrfixr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.ybcxt.top/Article/details/gtkodcqotw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtxzxpojdy.html

[G16] 对象转数组 / 字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxyjmwidf.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.gotoacloud.top/Article/details/gtyuyszoyp.html

PHP:  get_object_vars($obj);
来源：http://dali.hnqzz.top/Article/details/gttooggavw.html

JS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtoahyiavm.html

TS:   Object.entries(obj)
来源：http://dali.nanxinkj.top/Article/details/gtcxxuiylp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guannengcc.top/Article/details/gtmdowtvuu.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxesjahy.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gthcuwzmcl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtkwzowtma.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtjpnbmtlk.html

H. 异常与错误处理
来源：http://dali.tian-w.cn/Article/details/gtyrpexjll.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtbcegtmxx.html

[H01] try / catch 基础
来源：http://dali.shanyushiyangtech.top/Article/details/gtewocwayk.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmcntpwpl.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuanzx.com/Article/details/gtcvmuvqez.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.guowangkeji.top/Article/details/gtaleaotpn.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.dianchejie.cn/Article/details/gtlczhcmgq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtuptsbcjf.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxbamgxtj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yj20258.top/Article/details/gtfnnyfpel.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.316326.xyz/Article/details/gtjkgpmnum.html

[H02] finally / ensure 收尾
来源：http://dali.jiagoushi.top/Article/details/gtkouwcxzb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xziqi.cn/Article/details/gtdgifwmdb.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtikqbuatu.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtxuutlbok.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnwnmdihb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenlongwang.top/Article/details/gtkgltlxve.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhoulong.xyz/Article/details/gtifeizyte.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.quarkkingdee.top/Article/details/gtjmmunndn.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.sxryk.cn/Article/details/gtuvckptfu.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gtphdloxqn.html

Py:   raise ValueError("错误信息")
来源：http://dali.9152youxi.cn/Article/details/gtbjsdvdan.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtxvvscgwn.html

JS:   throw new Error("错误信息");
来源：http://dali.kuanghao11.cn/Article/details/gtuytxfjwq.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gtmezjhhup.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtfvkefslx.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnweflth.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.xziqi.cn/Article/details/gttpiucelg.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtzfifoica.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtmjejiacn.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtrtrjnzxj.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.sysykeji.top/Article/details/gtgfhpapah.html

JS:   class MyError extends Error {}
来源：http://dali.svipenyu.cn/Article/details/gtelophqhz.html

TS:   class MyError extends Error {}
来源：http://dali.ppjwa.cn/Article/details/gtzfcqmcdk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtjkzfidle.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hywenlv.cn/Article/details/gtlejqptfb.html

Ruby: class MyError < StandardError; end
来源：http://dali.cheryme.top/Article/details/gtqarvbknk.html

C#:   class MyException : Exception {}
来源：http://dali.fzhhl.top/Article/details/gtprjzlosh.html

[H05] 捕获特定类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgjgltdn.html

Py:   except ValueError as e:
来源：http://dali.hysaishi.cn/Article/details/gtailgddsd.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.gzhubu.top/Article/details/gtfoxqpcdi.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zdqjudy.top/Article/details/gttpgrtjen.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthbgmswkb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.bjfxy.top/Article/details/gtphjpfbln.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.tian-w.cn/Article/details/gtnxkhkdiy.html

Ruby: rescue ArgumentError => e
来源：http://dali.ivvv.top/Article/details/gtbojxkroy.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.ppjwa.cn/Article/details/gteiphokik.html

[H06] 可选值 / 空值安全访问
来源：http://dali.316326.xyz/Article/details/gtnyqrekkp.html

Py:   value = d.get("k") or default
来源：http://dali.hywenlv.cn/Article/details/gtiavagvcp.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gtbnatuudr.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.shangyingyoupin.top/Article/details/gtqvlryraj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gtqridhdsi.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrnvlwuib.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.andypj.xyz/Article/details/gtgvmpfxtz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.quarkkingdee.top/Article/details/gtsgjeaxgq.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtwxlzuxjc.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gtuveowobo.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dashuyun.cn/Article/details/gtbnatjcsz.html

PHP:  assert($x > 0);
来源：http://dali.zycfv.cn/Article/details/gtqpiigbss.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gtfqcpgked.html

TS:   console.assert(x > 0);
来源：http://dali.fengsongda.top/Article/details/gtpjzvxjbd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.yvedp.cn/Article/details/gtujndiaih.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jqgfzy.top/Article/details/gtrxnrsqgo.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.nanxuanxn.top/Article/details/gtpjbcshyn.html


<!-- 参考信息 -->