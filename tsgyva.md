代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtymbufqio.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtnvmpnwoj.html

PHP:  file_exists("a.txt");
来源：http://dali.316326.xyz/Article/details/gtcaatducb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gttggfpwnd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttakbogvu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtqterjhvn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtewwyowlj.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttqkoejer.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjfcdkuun.html

[F06] 删除文件
来源：http://dali.aizwys.cn/Article/details/gtphseiztu.html

Py:   os.remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtjxjporrm.html

PHP:  unlink("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtverjmqnp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtgjtsarja.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtggdoivfn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddubrzfz.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtofcrlwaf.html

Ruby: File.delete("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtjmhtgtik.html

C#:   File.Delete("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtupoihyuj.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gtjpeydsvo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gtcgcihpjg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sxryk.cn/Article/details/gthitorcxp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tanke756.top/Article/details/gtkxxqkrfp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.redwolf501.top/Article/details/gtfgbbtyga.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtdeefedmk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtusiarovo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nanxinkj.top/Article/details/gttanfclfu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtxkvdavig.html

[F08] 遍历目录
来源：http://dali.shuidangran.top/Article/details/gtphmksgnc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yuxming.cn/Article/details/gtclvgivww.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtfohzylpg.html

JS:   fs.readdirSync("dir")
来源：http://dali.0kj1m.cn/Article/details/gtcjkqgicw.html

TS:   fs.readdirSync("dir")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsdxomsi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gtvyyhxzkz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtehufzsjv.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gtbqycbrmq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.svipenyu.cn/Article/details/gtjcszbcgr.html

[F09] 获取文件大小
来源：http://dali.havefunace.top/Article/details/gtiqxqxkfs.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsorptvge.html

PHP:  filesize("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtkzygxbhm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtamvdiswo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinqigufen.top/Article/details/gtvveqxnek.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtcdhivnea.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtvpkdqmww.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtomilmwmu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gtrlqpajuy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtffyucqcw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtqsydxubt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ybcxt.top/Article/details/gtwgbrccnv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlbdwisfj.html

TS:   path.extname("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtppqcnafa.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jinqigfzy.top/Article/details/gtzxxtphhi.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtfldfqgki.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtqoqubaga.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtpwlfmpfa.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtmgzicspz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnuruqts.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gthfnblzmf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gtzjvwcqhn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gtttlaimbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtsbdpypvq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gtcbbxolmo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtihvzzeqw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gtoiygfexd.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gtozjatudr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtqkmbhlwj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.kuanghao11.cn/Article/details/gthoymydjt.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xziqi.cn/Article/details/gtwavtynpl.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtzunmxflq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.bjfxy.top/Article/details/gtnyahhlof.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtdryjfleb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtiuoyiivz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sxryk.cn/Article/details/gtknwuddba.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtyjbpcfbi.html

G. 面向对象
来源：http://dali.chenzaomai.com/Article/details/gtlxyhxdyb.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtcvfpoofj.html

[G01] 定义类
来源：http://dali.meibo888.top/Article/details/gtasspknnt.html

Py:   class User: pass
来源：http://dali.zhoulong.xyz/Article/details/gtzsmhlsbh.html

PHP:  class User {}
来源：http://dali.gogol.net.cn/Article/details/gtduccjuss.html

JS:   class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtzkaziooi.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gtmsbnjwat.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtlcvulgvo.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtksqbbpei.html

Ruby: class User; end
来源：http://dali.xinyue.icu/Article/details/gtgmattrfi.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtftsgfmwl.html

[G02] 构造函数
来源：http://dali.shzxlz.cn/Article/details/gthcwdtpoe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtgkjtbzju.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtivwueplh.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jiagoushi.top/Article/details/gtehoufrac.html

TS:   constructor(public name: string) {}
来源：http://dali.ydzc1.top/Article/details/gtapseyodg.html

Java: User(String name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtqosstcco.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.andypj.xyz/Article/details/gtarpycnac.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gteecejnzi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtsnayljih.html

[G03] 实例属性
来源：http://dali.dashuyun.cn/Article/details/gtufbqqbgb.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtglcabiyf.html

PHP:  public string $name = "x";
来源：http://dali.cheryme.top/Article/details/gtgoyufpvp.html

JS:   this.name = "x";
来源：http://dali.redwolf501.top/Article/details/gtqzdoaaxf.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtkmrfbmzh.html

Java: private String name;
来源：http://dali.jianghu66.top/Article/details/gtnavpakhb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlvoobjc.html

Ruby: @name = "x"
来源：http://dali.sufxvd.cn/Article/details/gtbtzfyroj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtyedkvjpp.html

[G04] 定义方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxqynpyp.html

Py:   def greet(self): return self.name
来源：http://dali.aizwys.cn/Article/details/gtuxnncvii.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.dashuyun.cn/Article/details/gtlobrblfv.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gtirxyryhv.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtecwostgf.html

Java: String greet() { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtuxhzudsj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jqgufenzy.top/Article/details/gtqvqoziih.html

Ruby: def greet; @name; end
来源：http://dali.meibo888.top/Article/details/gtdsjqsfvi.html

C#:   public string Greet() => Name;
来源：http://dali.hnqzz.top/Article/details/gtsfseahjs.html

[G05] 继承
来源：http://dali.ydzc1.top/Article/details/gtsbjehqug.html

Py:   class Admin(User): pass
来源：http://dali.guannengcc.top/Article/details/gtnejkqucy.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtsjdlqomp.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoohqbtih.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtferlvikw.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtugqznymf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.chenjidiqi.icu/Article/details/gtsfcptaps.html

Ruby: class Admin < User; end
来源：http://dali.yonumen.top/Article/details/gtdvnfleyo.html

C#:   class Admin : User {}
来源：http://dali.cucudq.cn/Article/details/gtajwozrtr.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gtoyswhsnd.html

Py:   def greet(self): return "admin"
来源：http://dali.cucudq.cn/Article/details/gtrutjnmim.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gtfouvbamr.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtmdcpdzfh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yanxiufei.cn/Article/details/gtsnrjtxmy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yangfankeji.com/Article/details/gtqjiqfkzn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gtlmquzjtf.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtcleotjbf.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gtwefycavy.html

[G07] 调用父类方法
来源：http://dali.yanxiufei.cn/Article/details/gtxevkclos.html

Py:   super().greet()
来源：http://dali.zhixingplan.top/Article/details/gtjriszhbp.html

PHP:  parent::greet();
来源：http://dali.wangshuangyany.cn/Article/details/gtyrsmohea.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gtbvfurrgm.html

TS:   super.greet();
来源：http://dali.shzxlz.cn/Article/details/gtfxecfwtl.html

Java: super.greet();
来源：http://dali.yuxming.cn/Article/details/gtkezyqbed.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtfaoeffew.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gtiamckvix.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqipyzwp.html

[G08] 静态方法与属性
来源：http://dali.birdmap.top/Article/details/gtkjjeoomi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aibaodan.cn/Article/details/gtlxxnsrjr.html

PHP:  public static function f() {}
来源：http://dali.sufxvd.cn/Article/details/gtfhwtmnlb.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtmpzbizqw.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtwblpqoyv.html

Java: static void f() {}
来源：http://dali.cashguo.top/Article/details/gtrvxvwwzb.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hammf.cn/Article/details/gtclqtkoae.html

Ruby: def self.f; end
来源：http://dali.hammf.cn/Article/details/gtupxfgrgc.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtclvprgaf.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtxrmpdesm.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gtlefggqnu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xziqi.cn/Article/details/gtacenjvyd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtlhlyxcup.html

TS:   interface Shape { area(): number; }
来源：http://dali.gzhubu.top/Article/details/gtjnqvqdng.html

Java: interface Shape { double area(); }
来源：http://dali.fengsongda.top/Article/details/gtuncpfjfx.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gtaizkwvym.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtdcrxkkiu.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gtcahzjyho.html

[G10] 访问控制
来源：http://dali.yvedp.cn/Article/details/gtayanbrvb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tian-w.cn/Article/details/gtvnbmmruh.html

PHP:  public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtpmrllclp.html

JS:   #private 字段；其余公开
来源：http://dali.xylfe.cn/Article/details/gtcbxutpnh.html

TS:   public / protected / private
来源：http://dali.wangshuangyany.cn/Article/details/gtrmyuxqyn.html

Java: public / protected / private / 默认包级
来源：http://dali.yanxiufei.cn/Article/details/gtnyskdnrx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtbfqywmry.html

Ruby: public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipdvbrxf.html

C#:   public / protected / private / internal
来源：http://dali.9152youxi.cn/Article/details/gtvdgizbnu.html

[G11] getter / setter
来源：http://dali.hfpthk.cn/Article/details/gtdgkywgzs.html

Py:   @property 与 @x.setter
来源：http://dali.chenzaomai.com/Article/details/gtrjrqifng.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.andypj.xyz/Article/details/gthmvwgniq.html

JS:   get name() { return this._name; }
来源：http://dali.cqqwz.cn/Article/details/gtegfsmcnq.html

TS:   get name(): string { return this._name; }
来源：http://dali.jinqigfzy.top/Article/details/gtppmapdfs.html

Java: public String getName() { return name; }
来源：http://dali.yongpay.top/Article/details/gtxmspyxjd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtmonzwmgd.html

Ruby: attr_accessor :name
来源：http://dali.chenzaomai.com/Article/details/gtqoxjmjjt.html

C#:   public string Name { get; set; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjgzvjraa.html

[G12] 对象转字符串
来源：http://dali.yuanzhike.top/Article/details/gtzybtuyvn.html

Py:   def __str__(self): return self.name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzukggaf.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gtmdolgqay.html

JS:   toString() { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gticpeuwnu.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gthllvooka.html

Java: @Override public String toString() { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gttqibejhn.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.nanxuanxn.top/Article/details/gtxghacsfx.html

Ruby: def to_s; @name; end
来源：http://dali.snrcjt.cn/Article/details/gtrggogitf.html

C#:   public override string ToString() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gttlnkvxpu.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtqatsjhjs.html

Py:   isinstance(u, User)
来源：http://dali.hfpthk.cn/Article/details/gtxmadakhw.html

PHP:  $u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gtsiwqvoaa.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxehnrqv.html

TS:   u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtvdxikvxt.html

Java: u instanceof User
来源：http://dali.sysykeji.top/Article/details/gtqmgysbtn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.sysykeji.top/Article/details/gtchatfltd.html

Ruby: u.is_a?(User)
来源：http://dali.9152youxi.cn/Article/details/gtookkhoau.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gtfvqbdovw.html

[G14] 数据类 / record
来源：http://dali.meibo888.top/Article/details/gtlnubouth.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gtsipqaibp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.kuanghao11.cn/Article/details/gtaqozjqqk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gtlhcdhxmn.html

TS:   type User = { name: string; age: number };
来源：http://dali.gaohongyu789.top/Article/details/gtfjxdifew.html

Java: record User(String name, int age) {}
来源：http://dali.yanxiufei.cn/Article/details/gthbbdjnky.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cqqwz.cn/Article/details/gtwftlugaq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gtxqhfdxrd.html

C#:   record User(string Name, int Age);
来源：http://dali.yanxiufei.cn/Article/details/gtmzoiuiuv.html

[G15] 枚举
来源：http://dali.cucudq.cn/Article/details/gtznhgyhqg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtdovhmglu.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ehwqpu.com/Article/details/gteyhljces.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yuanzhike.top/Article/details/gtfuczfikg.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.iojbl.cn/Article/details/gtrjwbzrte.html

Java: enum Color { RED, GREEN }
来源：http://dali.c1oappe.top/Article/details/gtbgxhojtz.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cashguo.top/Article/details/gtatlqmznx.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gthrjfnviw.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtbopvuhxc.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258.top/Article/details/gtcipxcoio.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gttmhyzruv.html

PHP:  get_object_vars($obj);
来源：http://dali.yongpay.top/Article/details/gtcyzofzkx.html

JS:   Object.entries(obj)
来源：http://dali.hongshengwenyu.top/Article/details/gtxabpefzp.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtlutcmgcc.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenzaomai.com/Article/details/gtqbqtlagz.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.iojbl.cn/Article/details/gtjvpvwhod.html

Ruby: obj.instance_variables
来源：http://dali.wangdashe.top/Article/details/gtdgmsmqah.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtzscuceud.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtxvhzctbp.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtxjnsslxc.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdgzrlmnq.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gtjgtcsgyn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sweek.top/Article/details/gtonzltsxq.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtlqllkkgh.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gthusifnvi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gtugwvwuwv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gaohongyu789.top/Article/details/gtwszgfuqw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.chenjidiqi.icu/Article/details/gtvyvwecfy.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.havefunace.top/Article/details/gtsyuaszsf.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sxryk.cn/Article/details/gtbnxuexlh.html

[H02] finally / ensure 收尾
来源：http://dali.ehwqpu.com/Article/details/gtbzscjwjo.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfutozkbr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hywenlv.cn/Article/details/gtsxildthy.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnxiangtu.top/Article/details/gtcrmptefs.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjvgdpgz.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtrwdbffmx.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.vqdsnc.cn/Article/details/gtanqnmeoc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yangfankeji.com/Article/details/gtpinbbzhz.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtxfbtkszr.html

[H03] 主动抛出异常
来源：http://dali.aizwys.cn/Article/details/gtxmqcikcf.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxuanxn.top/Article/details/gtnxkxtvut.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtdxkdmltd.html

JS:   throw new Error("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtcsxlnyxl.html

TS:   throw new Error("错误信息");
来源：http://dali.chenjidiqi.icu/Article/details/gtlxdgqkoj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejtkuimd.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.quarkkingdee.top/Article/details/gtlvyskncz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.fzhhl.top/Article/details/gtpsblnhjj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtewrifkyj.html

[H04] 自定义异常类型
来源：http://dali.yj20258.top/Article/details/gtuzmzfgmv.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gtcspsfabf.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtrrufkpjk.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtphdlrlpl.html

TS:   class MyError extends Error {}
来源：http://dali.yvedp.cn/Article/details/gtyipvtocm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gtiavavdfp.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gtajhgkpsc.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenzaomai.com/Article/details/gtlgwdavec.html

C#:   class MyException : Exception {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzlgyzuaw.html

[H05] 捕获特定类型
来源：http://dali.cashguo.top/Article/details/gthewoqkir.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtnhgumlpg.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.kuanghao11.cn/Article/details/gtfmhqrcjc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtjtkpnopf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tanke756.top/Article/details/gtqtgtpwoe.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.meibo888.top/Article/details/gtgsfvuuvf.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.birdmap.top/Article/details/gtuvbntxtb.html

Ruby: rescue ArgumentError => e
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbygvxcvp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shuidangran.top/Article/details/gtnoforovn.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gtcknnjdva.html

Py:   value = d.get("k") or default
来源：http://dali.haohaochexian.top/Article/details/gtypxyfies.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yj202588.top/Article/details/gtraxndwqe.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yangfankeji.com/Article/details/gtvdeemmmu.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.9152youxi.cn/Article/details/gtwyvsfpnd.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtlitcjxky.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.kuanghao11.cn/Article/details/gtcrytqcmt.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gtwvsnjttr.html

C#:   obj?.A?.B ?? default
来源：http://dali.yanxiufei.cn/Article/details/gtnodivcwm.html

[H07] 断言
来源：http://dali.wangdashe.top/Article/details/gtlbzigqnn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shangyingyoupin.top/Article/details/gtgsqueqfe.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtfjjlbafg.html

JS:   console.assert(x > 0);
来源：http://dali.yvedp.cn/Article/details/gtaqvcetkb.html

TS:   console.assert(x > 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtblafrwvd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cashguo.top/Article/details/gtpyzvvefc.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gotoacloud.top/Article/details/gthxspbcck.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.cdnleiting.top/Article/details/gtgwdhcqgs.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gttznwuxzz.html

[H08] 获取错误信息与堆栈
来源：http://dali.ydzc1.top/Article/details/gtkllcvttc.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.chenlongwang.top/Article/details/gtfguunvqx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtolgbyabv.html

JS:   e.message;  e.stack
来源：http://dali.ivvv.top/Article/details/gtzkndqkav.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.pycfn.com/Article/details/gtjwhlfgqs.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gtrgzpisgp.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gttgmvbuon.html

Ruby: e.message;  e.backtrace
来源：http://dali.smart0.xyz/Article/details/gtkiyhqlhh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gtwarxqhah.html

[H09] 带错误码的异常
来源：http://dali.hnxiangtu.top/Article/details/gtojvebspa.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.kuanghao11.cn/Article/details/gtelqxftju.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gtlrxmmjbd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.birdmap.top/Article/details/gtdpcwpskm.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtfymbrmhl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.xylfe.cn/Article/details/gtinnyqeji.html


<!-- 参考信息 -->