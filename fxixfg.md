代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtrbpgvrzy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.0kj1m.cn/Article/details/gtuuiqxklx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gtisctsjuo.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gtvtqtgywv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtsomoitwn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gtrwbqenfu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gthkmnvvmh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtapvrrwoy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gtachglyvo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtnmphocig.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gtedlxhhrx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zycfv.cn/Article/details/gteibuvfpd.html

[F05] 判断文件或目录是否存在
来源：http://dali.hywenlv.cn/Article/details/gtbkpelxjx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yonumen.top/Article/details/gtgaowefsw.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtevinxjsi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtiewuyzcp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtpzpksowy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gtusrzdyzo.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.wangdashe.top/Article/details/gttpdnwewh.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcwnxnphj.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtqdjedmvp.html

[F06] 删除文件
来源：http://dali.guannengcc.top/Article/details/gtxiwfpbiv.html

Py:   os.remove("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gttnnppels.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtgrxltgof.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgpycmuei.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtuaalrbhr.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtoissvpwg.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtinqqgbkp.html

Ruby: File.delete("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtjwigtona.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttsskunqy.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gtamnzijmg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtzmofbjdi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gtpikymnlu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guannengcc.top/Article/details/gtyvnswcrf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtieufpjnq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtxxyhtccl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtqutjozrz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtqignacry.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ppjwa.cn/Article/details/gttqpmpzqd.html

[F08] 遍历目录
来源：http://dali.yj20258.top/Article/details/gtrxxigudh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jinqigfzy.top/Article/details/gtwnojskmn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtbhoylusp.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gtryjessrf.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtxawldgqi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtpzznncrg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnxiangtu.top/Article/details/gtnowdnaej.html

Ruby: Dir.children("dir")
来源：http://dali.ppjwa.cn/Article/details/gtfmoxwqod.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gthvnjvvru.html

[F09] 获取文件大小
来源：http://dali.chenlongwang.top/Article/details/gtbxikzynj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtzfljgpwt.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtuvlnkaqf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.fzhhl.top/Article/details/gtjgydvxfq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxjcgkuwn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gtwzfpqxlm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtykxmnixj.html

Ruby: File.size("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtyiypwuhf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gttjlrejkm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtvbsffssm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtewlvsblj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtyycdyctx.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtagxpqlzy.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtmfzcrdlu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtgzhgbkin.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtsugowxvs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gthvwktsnq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtqwztyvuw.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gtjisvqvms.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtmaqzbqof.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.cqqwz.cn/Article/details/gtupcxkefy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtgxkzbzdn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shzxlz.cn/Article/details/gtlsdwzfcm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtkxnyzufr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ivvv.top/Article/details/gtjrvxanvj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtovtlfceo.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jlsjyb.cn/Article/details/gtvrhwrwvm.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtbxpzmvqg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtmlrsqtmv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtvcqejhbw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258888.top/Article/details/gtwvwuucln.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtvvpblbcw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shuidangran.top/Article/details/gtjrtjsqcu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtvovsglpp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.daria6918.cn/Article/details/gtmhmzikxk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtiaxxvwke.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthncpgmsp.html

G. 面向对象
来源：http://dali.ydzc1.top/Article/details/gtcilxnwsx.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtbmozdwjs.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtqofsqeps.html

Py:   class User: pass
来源：http://dali.ehwqpu.com/Article/details/gtockizind.html

PHP:  class User {}
来源：http://dali.wangdashe.top/Article/details/gtovhxvwgn.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtldbaobuv.html

TS:   class User { name: string = ""; }
来源：http://dali.xuanzx.com/Article/details/gtwwojdsnk.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gtmuipgqbt.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gttbbkmqxa.html

Ruby: class User; end
来源：http://dali.hnqzz.top/Article/details/gtqtxqpozm.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtgmaonsbf.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtbzdfllzc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.wangdashe.top/Article/details/gtbxtlzyxz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jqgufenzy.top/Article/details/gthlrtjkax.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gtzcnrqwjg.html

TS:   constructor(public name: string) {}
来源：http://dali.yvedp.cn/Article/details/gthuvelwhb.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gtiebxukkr.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenlongwang.top/Article/details/gtfpbminfw.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.9152youxi.cn/Article/details/gtwoprnasv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fengsongda.top/Article/details/gtxdwwinmx.html

[G03] 实例属性
来源：http://dali.aizwys.cn/Article/details/gtjftrmhhq.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtzbutioof.html

PHP:  public string $name = "x";
来源：http://dali.yj20258.top/Article/details/gtkaepmjes.html

JS:   this.name = "x";
来源：http://dali.fengsongda.top/Article/details/gtmeaxlaov.html

TS:   name: string = "x";
来源：http://dali.zhongyouzk.top/Article/details/gtfurmwpkx.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gtiqwmqeup.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.haohaochexian.top/Article/details/gtvkiwphbu.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gtppfcnnzb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jianghu66.top/Article/details/gtjbdutkbd.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gtupzqdtrm.html

Py:   def greet(self): return self.name
来源：http://dali.meibo888.top/Article/details/gtabzbovqs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daxiang520.top/Article/details/gtgehbsfyj.html

JS:   greet() { return this.name; }
来源：http://dali.yvedp.cn/Article/details/gtcxbqmomd.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooryyknq.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtaghosgye.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.fengsongda.top/Article/details/gtfuisksai.html

Ruby: def greet; @name; end
来源：http://dali.nanxinkj.top/Article/details/gtjoencpzd.html

C#:   public string Greet() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtiyappemf.html

[G05] 继承
来源：http://dali.nwbrower.top/Article/details/gthxnptdok.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gtldskyxcx.html

PHP:  class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtiuwrlgmw.html

JS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtxdcpwdqp.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtftbxlusi.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtrskusbjf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xinyue.icu/Article/details/gtwducmduc.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtvmbrivna.html

C#:   class Admin : User {}
来源：http://dali.jqgfzy.top/Article/details/gtarxjmfwk.html

[G06] 重写方法
来源：http://dali.jyoumei.cn/Article/details/gtxftnsdwx.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gthiukznlk.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtkwjxwrac.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxofjogzk.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtsyzxvcqr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gtargtxlzq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.wangshuangyany.cn/Article/details/gtedymecaf.html

Ruby: def greet; "admin"; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxphxexxe.html

C#:   public override string Greet() => "admin";
来源：http://dali.shanyushiyangtech.top/Article/details/gtbelhmgjy.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtiylrrblh.html

Py:   super().greet()
来源：http://dali.tian-w.cn/Article/details/gtietsblks.html

PHP:  parent::greet();
来源：http://dali.redwolf501.top/Article/details/gtyfznnrzr.html

JS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtsqdedgbd.html

TS:   super.greet();
来源：http://dali.jinqigufen.top/Article/details/gtwvewpmqv.html

Java: super.greet();
来源：http://dali.tanke756.top/Article/details/gtaawyojuz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtspjjyhlq.html

Ruby: super
来源：http://dali.jinghuilouyu.cn/Article/details/gttyzgatix.html

C#:   base.Greet();
来源：http://dali.daxiang520.top/Article/details/gtinfsedns.html

[G08] 静态方法与属性
来源：http://dali.pengpengdd.cyou/Article/details/gtevvrxtgu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhiwuduotai.top/Article/details/gtocfycehm.html

PHP:  public static function f() {}
来源：http://dali.birdmap.top/Article/details/gtjeprjcaf.html

JS:   static f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtlcyukgij.html

TS:   static f(): void {}
来源：http://dali.zhengqikj.top/Article/details/gtzmwnofwd.html

Java: static void f() {}
来源：http://dali.zhijiandao.cn/Article/details/gtviczgnco.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.havefunace.top/Article/details/gthqyhzztg.html

Ruby: def self.f; end
来源：http://dali.aibaodan.cn/Article/details/gtoznuszlo.html

C#:   public static void F() {}
来源：http://dali.jqgufenzy.top/Article/details/gtojakpaci.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gthzynljxl.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.0kj1m.cn/Article/details/gtlgtymlld.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.ydzc1.top/Article/details/gtnxfwagoy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gtabvykdsd.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gtkjskuqjd.html

Java: interface Shape { double area(); }
来源：http://dali.yueranfly.top/Article/details/gtnpltgwvv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.ivvv.top/Article/details/gtrxyewfii.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.quarkkingdee.top/Article/details/gtnyubgycg.html

C#:   interface IShape { double Area(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhouqiwk.html

[G10] 访问控制
来源：http://dali.hnqzz.top/Article/details/gtvvdkazes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gtpvhvuczb.html

PHP:  public / protected / private
来源：http://dali.yongpay.top/Article/details/gtltkhjddr.html

JS:   #private 字段；其余公开
来源：http://dali.jlsjyb.cn/Article/details/gtpvfvmodw.html

TS:   public / protected / private
来源：http://dali.yanxiufei.cn/Article/details/gtcbfidfpo.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gtrucmrxiu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gtstwgxiyi.html

Ruby: public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gtkxgowdpz.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtygmeyony.html

[G11] getter / setter
来源：http://dali.cashguo.top/Article/details/gtidjnrhlm.html

Py:   @property 与 @x.setter
来源：http://dali.meibo888.top/Article/details/gtapkbkpea.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtcowplyro.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtzrlhrdpq.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gtbtpguyrm.html

Java: public String getName() { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtrgbfitcb.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gttnfwcqrz.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtzgwhlrwb.html

C#:   public string Name { get; set; }
来源：http://dali.quarkkingdee.top/Article/details/gtoxyixpuw.html

[G12] 对象转字符串
来源：http://dali.hfpthk.cn/Article/details/gtxrwasacd.html

Py:   def __str__(self): return self.name
来源：http://dali.xziqi.cn/Article/details/gtwvuxmlor.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gtoijahoyj.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmxryknbl.html

TS:   toString(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gtwmedyysl.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtisrwkfcg.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtyrklobpt.html

Ruby: def to_s; @name; end
来源：http://dali.hywenlv.cn/Article/details/gtzpwcrnjp.html

C#:   public override string ToString() => Name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrjhosxp.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtvwktizsq.html

Py:   isinstance(u, User)
来源：http://dali.iojbl.cn/Article/details/gtdiuwjenc.html

PHP:  $u instanceof User
来源：http://dali.yj20258.top/Article/details/gtgomefsdk.html

JS:   u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdervbvir.html

TS:   u instanceof User
来源：http://dali.jlsjyb.cn/Article/details/gtpxgtlzzp.html

Java: u instanceof User
来源：http://dali.0kj1m.cn/Article/details/gtqddjamns.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.fzhhl.top/Article/details/gtpkkyitrh.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtdfmypoxd.html

C#:   u is User
来源：http://dali.sysykeji.top/Article/details/gteppwspkx.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtfaemcwgo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gtehkosppk.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhixingplan.top/Article/details/gtixqbtikc.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jqgufenzy.top/Article/details/gtzqnfuxxq.html

TS:   type User = { name: string; age: number };
来源：http://dali.daria6918.cn/Article/details/gtzvfxgyig.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gtxftxcqbj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuhaomaf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.yuanzhike.top/Article/details/gtmzjzfxks.html

C#:   record User(string Name, int Age);
来源：http://dali.wangdashe.top/Article/details/gtdybcqiqf.html

[G15] 枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjympgsq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxofwmfb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtwjfyvflo.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gtcshcrxav.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jyoumei.cn/Article/details/gtcszzspie.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gtgbmfcsgn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtjiczrmji.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxinkj.top/Article/details/gtftoknnuf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtozeedxvt.html

[G16] 对象转数组 / 字典
来源：http://dali.c1oappe.top/Article/details/gtyzelfnhq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.redwolf501.top/Article/details/gtblndohbs.html

PHP:  get_object_vars($obj);
来源：http://dali.chenlongwang.top/Article/details/gtqjdlnawt.html

JS:   Object.entries(obj)
来源：http://dali.aibaodan.cn/Article/details/gtihhdjjxm.html

TS:   Object.entries(obj)
来源：http://dali.hammf.cn/Article/details/gtirpleran.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yongpay.top/Article/details/gtyqmkhtex.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jyoumei.cn/Article/details/gtnpqaouih.html

Ruby: obj.instance_variables
来源：http://dali.nanxinkj.top/Article/details/gtikegeivz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtempbzoan.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwfcwogyj.html

H. 异常与错误处理
来源：http://dali.svipenyu.cn/Article/details/gtzgtdkrsl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtpylnquoj.html

[H01] try / catch 基础
来源：http://dali.pengpengdd.cyou/Article/details/gtkoykmggc.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.mhx1999.top/Article/details/gtbfncayrr.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtbjnbjtuw.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gthgzeniqv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvjhoixdi.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.bjfxy.top/Article/details/gtgulqizbe.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtasfoqzvn.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jyoumei.cn/Article/details/gtvxkvuvcd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.aizwys.cn/Article/details/gtnlcxdkeq.html

[H02] finally / ensure 收尾
来源：http://dali.gaohongyu789.top/Article/details/gtdtveeuyp.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fengsongda.top/Article/details/gtprolrako.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoconhdrq.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.gzhubu.top/Article/details/gtalslgyai.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuxming.cn/Article/details/gtsogbagpa.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gttlouqnvs.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.sweek.top/Article/details/gtzmalrtkb.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.cashguo.top/Article/details/gtjfopixlz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtogwmducx.html

[H03] 主动抛出异常
来源：http://dali.iojbl.cn/Article/details/gtqoobrmxq.html

Py:   raise ValueError("错误信息")
来源：http://dali.haohaochexian.top/Article/details/gtffmqrbwa.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.daxiang520.top/Article/details/gttutshelx.html

JS:   throw new Error("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtppkdkpcb.html

TS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtbmtcfjkq.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtkwaqlxsy.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jqgufenzy.top/Article/details/gtufdioyig.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cucudq.cn/Article/details/gtpwvpktkw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.tanke756.top/Article/details/gtjzkmirnj.html

[H04] 自定义异常类型
来源：http://dali.jlsjyb.cn/Article/details/gtwpdxjzgq.html

Py:   class MyError(Exception): pass
来源：http://dali.yonumen.top/Article/details/gtjyferslh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhoulong.xyz/Article/details/gtqtvmetos.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gtbgidtwsj.html

TS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gturdrhxwt.html

Java: class MyException extends RuntimeException {}
来源：http://dali.dashuyun.cn/Article/details/gtpcepbfpj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cashguo.top/Article/details/gtonzjwbpr.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gtedjxgtay.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtxvrimohh.html

[H05] 捕获特定类型
来源：http://dali.jqgufenzy.top/Article/details/gtlkjxqovh.html

Py:   except ValueError as e:
来源：http://dali.andypj.xyz/Article/details/gtlicbskpm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.tanke756.top/Article/details/gtbzizofkh.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtjzjnioag.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yj20258888.top/Article/details/gtlafldfhe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.dianchejie.cn/Article/details/gtjhnizxgy.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenzaomai.com/Article/details/gtppxuwwse.html

Ruby: rescue ArgumentError => e
来源：http://dali.cdnleiting.top/Article/details/gtgqrzjoqb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.hywenlv.cn/Article/details/gthavzuthd.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenzaomai.com/Article/details/gtqmeaeuco.html

Py:   value = d.get("k") or default
来源：http://dali.ydzc1.top/Article/details/gtafbghzua.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxqxjgum.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ppjwa.cn/Article/details/gtrbbgtjqe.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jinqigufen.top/Article/details/gthaabwbck.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtjvmngkui.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtdmlpaxhh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.feifeiyinyue.top/Article/details/gtvgbxdkyl.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gtxqhcrkma.html

[H07] 断言
来源：http://dali.jiagoushi.top/Article/details/gtmebfmbqt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.ppjwa.cn/Article/details/gtbejqlbvc.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtwygzrpyo.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gtubumdbah.html

TS:   console.assert(x > 0);
来源：http://dali.ybcxt.top/Article/details/gtqqpuggpj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gttfsqzppt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.yj20258.top/Article/details/gtcieyvdkl.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cheryme.top/Article/details/gtzzxowtld.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cucudq.cn/Article/details/gtohmdyytq.html

[H08] 获取错误信息与堆栈
来源：http://dali.ivvv.top/Article/details/gtoyuuomla.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yonumen.top/Article/details/gtltnohoxt.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xuetiantiany.cn/Article/details/gtjxmqsfjp.html


<!-- 参考信息 -->