代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtaisjrolr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtyxrnecdp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gtyvhmebqy.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtvvbybcsg.html

C#:   File.Exists("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkenwhps.html

[F06] 删除文件
来源：http://dali.gaohongyu789.top/Article/details/gtrouumtmr.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtisxodwmg.html

PHP:  unlink("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtizqpsgfi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrurfytcl.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtwitdtirg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gtofxrwvdt.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtoaeusmbf.html

Ruby: File.delete("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjlihgbjd.html

C#:   File.Delete("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtozpjfzjg.html

[F07] 创建目录（含多级）
来源：http://dali.zhongyouzk.top/Article/details/gtspxftsiq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtsqgbkhnv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj20258.top/Article/details/gtwhigddhh.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtuejbjkik.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtcddhopqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gtjzfzfghb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtnisalglt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhixingplan.top/Article/details/gtayyxtcbj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hnqzz.top/Article/details/gtotttresf.html

[F08] 遍历目录
来源：http://dali.sufxvd.cn/Article/details/gtodejdzer.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtohtsfgqm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtneuudstr.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtncfupbkc.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gthaodipdh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gtiyynpmfw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gthplfpmzu.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gtgfvebtcx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtvwylebbp.html

[F09] 获取文件大小
来源：http://dali.birdmap.top/Article/details/gtshiihtgw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtxhgjgqcc.html

PHP:  filesize("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtsejecrsf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtagpqwzyh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gtlceholni.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtkzpxsigm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.dianchejie.cn/Article/details/gtgvwqriqm.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtyyjeqljx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ehwqpu.com/Article/details/gttfrczfpb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtvxivajxm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtyxnidfpx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.c1oappe.top/Article/details/gtwpwxhllb.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtnmwuuqnw.html

TS:   path.extname("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtoyqwyuay.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gtovrxquok.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtgcohjerl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtsgrpmhtq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtehxfptxt.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gtdaeqwtmc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gtgsnnjupn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtqvotnzxc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtjlbyjchr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtciuvliau.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gttdvkawno.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jlsjyb.cn/Article/details/gtuvowpvhn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtzhpdkmou.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gtlsxqfies.html

[F12] CSV 读写
来源：http://dali.cqqwz.cn/Article/details/gtkpmexapl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.dashuyun.cn/Article/details/gtusaojsme.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.bjfxy.top/Article/details/gthzawfmcp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtgboqblgf.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtqayiwvca.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtvwzgkkhi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.chenjidiqi.icu/Article/details/gtqinwotij.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gthbbdazyy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.tian-w.cn/Article/details/gtzyxrqoio.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtxlmfhiaa.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gtocmokuwd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbhedgxvx.html

[G01] 定义类
来源：http://dali.jinqigfzy.top/Article/details/gtqobsylad.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtlrmgqvsw.html

PHP:  class User {}
来源：http://dali.yanxiufei.cn/Article/details/gtiylufwnx.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtybfdjyne.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gtodublalc.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gttnmcwpyn.html

Go:   type User struct { Name string }
来源：http://dali.zhiwuduotai.top/Article/details/gtqsybayce.html

Ruby: class User; end
来源：http://dali.dashuyun.cn/Article/details/gttoxrzgrk.html

C#:   class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtytaiqwls.html

[G02] 构造函数
来源：http://dali.haohaochexian.top/Article/details/gtbcoywnii.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cdnleiting.top/Article/details/gtqntnsvhg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.gzhubu.top/Article/details/gttdbqpnwd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gtsnruiqtb.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gtazxpbdnc.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtjbrhwviy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daxiang520.top/Article/details/gtsriylgas.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnxiangtu.top/Article/details/gtqybthxho.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtggslhagi.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtnmmtdobk.html

Py:   self.name = "x"
来源：http://dali.gzhubu.top/Article/details/gtcgdwkgrj.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gtxwzldzbv.html

JS:   this.name = "x";
来源：http://dali.chenlongwang.top/Article/details/gttupoxiql.html

TS:   name: string = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtrmmzhwau.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtfquvhxpk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.havefunace.top/Article/details/gtzehbqccd.html

Ruby: @name = "x"
来源：http://dali.c1oappe.top/Article/details/gtqcasvnal.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhijiandao.cn/Article/details/gtwkyvpsvd.html

[G04] 定义方法
来源：http://dali.sweek.top/Article/details/gtlsxwilhd.html

Py:   def greet(self): return self.name
来源：http://dali.nwbrower.top/Article/details/gtwahiofaz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hysaishi.cn/Article/details/gtlzivymmy.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtvyzulqks.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangdashe.top/Article/details/gtpkwmopxl.html

Java: String greet() { return name; }
来源：http://dali.iojbl.cn/Article/details/gttowujrrf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtbtghvjoo.html

Ruby: def greet; @name; end
来源：http://dali.shangyingyoupin.top/Article/details/gtqozgolke.html

C#:   public string Greet() => Name;
来源：http://dali.bjfxy.top/Article/details/gtadxuowbi.html

[G05] 继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtszgnclho.html

Py:   class Admin(User): pass
来源：http://dali.daxiang520.top/Article/details/gtcfvyjlui.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzxbfotvs.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtmfodtbjc.html

TS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gttyrmgzol.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtlslbcalu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gthonmtefa.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtsarzjeea.html

C#:   class Admin : User {}
来源：http://dali.c1oappe.top/Article/details/gtjkfhjqmk.html

[G06] 重写方法
来源：http://dali.9152youxi.cn/Article/details/gteppotwcj.html

Py:   def greet(self): return "admin"
来源：http://dali.316326.xyz/Article/details/gtfbycsgwf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtuibyaiwe.html

JS:   greet() { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtissxeerl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtlxifnagx.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dashuyun.cn/Article/details/gtddgdasaa.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zdqjudy.top/Article/details/gticrzzvnc.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gtugoilbkq.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gthebvelzz.html

[G07] 调用父类方法
来源：http://dali.zhijiandao.cn/Article/details/gthzjzwyjn.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gtjllfysyk.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gtpfbdddwm.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gtrrmwirvk.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtqauxoyaw.html

Java: super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gtenfrpnxs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gtigigxedo.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuhvwykd.html

C#:   base.Greet();
来源：http://dali.iojbl.cn/Article/details/gtzuqejsby.html

[G08] 静态方法与属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmugvgax.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmopnied.html

PHP:  public static function f() {}
来源：http://dali.0kj1m.cn/Article/details/gttlzfzvoh.html

JS:   static f() {}
来源：http://dali.jinqigfzy.top/Article/details/gtxdleoxxy.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gtsuitmwwg.html

Java: static void f() {}
来源：http://dali.nwbrower.top/Article/details/gtvsuycazn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.fengsongda.top/Article/details/gtekbodhyp.html

Ruby: def self.f; end
来源：http://dali.sxryk.cn/Article/details/gtmblbmfqq.html

C#:   public static void F() {}
来源：http://dali.svipenyu.cn/Article/details/gtxorybeaf.html

[G09] 接口 / 抽象类
来源：http://dali.xylfe.cn/Article/details/gtdplzetrr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigfzy.top/Article/details/gtazyxxiwi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cashguo.top/Article/details/gtspzrdyij.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtrrdsjcoz.html

TS:   interface Shape { area(): number; }
来源：http://dali.cheryme.top/Article/details/gtnvrgouox.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gtokpgngmu.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmaaqfds.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.dashuyun.cn/Article/details/gtojgwphnt.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtbuuvazav.html

[G10] 访问控制
来源：http://dali.tian-w.cn/Article/details/gtzeqostik.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtfsviicgj.html

PHP:  public / protected / private
来源：http://dali.quarkkingdee.top/Article/details/gtzfnohxdt.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtetawlpvs.html

TS:   public / protected / private
来源：http://dali.yj202588.top/Article/details/gtydcloklq.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gtfwrpqpra.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.aizwys.cn/Article/details/gtmrvbpskc.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gtbtpcnipg.html

C#:   public / protected / private / internal
来源：http://dali.shuidangran.top/Article/details/gtkxzkgamr.html

[G11] getter / setter
来源：http://dali.hongshengwenyu.top/Article/details/gtycuikjya.html

Py:   @property 与 @x.setter
来源：http://dali.redwolf501.top/Article/details/gtbzoxsgjw.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangdashe.top/Article/details/gthakwpwjr.html

JS:   get name() { return this._name; }
来源：http://dali.yj20258888.top/Article/details/gtxdufexas.html

TS:   get name(): string { return this._name; }
来源：http://dali.jlsjyb.cn/Article/details/gtzcqizcst.html

Java: public String getName() { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtepxndryv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pengpengdd.cyou/Article/details/gtzsttnhna.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtpfsllrpb.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtmhaxfefw.html

[G12] 对象转字符串
来源：http://dali.yvedp.cn/Article/details/gtkhccunst.html

Py:   def __str__(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gteqyptcnk.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtpmkkudbj.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtdnozeljb.html

TS:   toString(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gtjotbgvqq.html

Java: @Override public String toString() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtqynuxnar.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.andypj.xyz/Article/details/gtmmylpaxj.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtbkyyysis.html

C#:   public override string ToString() => Name;
来源：http://dali.yj20258.top/Article/details/gtuyxjoyis.html

[G13] 判断对象类型
来源：http://dali.hnqzz.top/Article/details/gtuqtwzqas.html

Py:   isinstance(u, User)
来源：http://dali.chenjidiqi.icu/Article/details/gthrfmedvf.html

PHP:  $u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gthvpkicrd.html

JS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtghoqkckc.html

TS:   u instanceof User
来源：http://dali.shzxlz.cn/Article/details/gtrpttkbgx.html

Java: u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtdjviwxoz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.pycfn.com/Article/details/gtdhqtrcvc.html

Ruby: u.is_a?(User)
来源：http://dali.pycfn.com/Article/details/gtltvovvcp.html

C#:   u is User
来源：http://dali.yj20258888.top/Article/details/gtgvreuotm.html

[G14] 数据类 / record
来源：http://dali.c1oappe.top/Article/details/gtsuwavfqp.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuetiantiany.cn/Article/details/gtftessqvy.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtbkhyogjm.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.meibo888.top/Article/details/gtmpuozwow.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuxming.cn/Article/details/gtnyswjaoh.html

Java: record User(String name, int age) {}
来源：http://dali.gogol.net.cn/Article/details/gtbsodgsvr.html

Go:   type User struct { Name string; Age int }
来源：http://dali.meibo888.top/Article/details/gttoundqzj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.cdnleiting.top/Article/details/gtinbucjhx.html

C#:   record User(string Name, int Age);
来源：http://dali.hywenlv.cn/Article/details/gtvuplvktj.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtdobxjibk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtskxgjfhd.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.havefunace.top/Article/details/gtaunlvxgz.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dashuyun.cn/Article/details/gtbtoyplvn.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.pycfn.com/Article/details/gtezgyvbjl.html

Java: enum Color { RED, GREEN }
来源：http://dali.cqqwz.cn/Article/details/gtwqnpbhsr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.fzhhl.top/Article/details/gtvpmhbojb.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jiagoushi.top/Article/details/gtccgyskby.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yongpay.top/Article/details/gtbhkpwygf.html

[G16] 对象转数组 / 字典
来源：http://dali.snrcjt.cn/Article/details/gtgufpkniq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtofhbbzxi.html

PHP:  get_object_vars($obj);
来源：http://dali.fengsongda.top/Article/details/gtcmxvoxcu.html

JS:   Object.entries(obj)
来源：http://dali.mhx1999.top/Article/details/gtzzpolwfh.html

TS:   Object.entries(obj)
来源：http://dali.zdqjudy.top/Article/details/gtyfmbfknn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gtophywazp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.birdmap.top/Article/details/gtqfyszfap.html

Ruby: obj.instance_variables
来源：http://dali.yvedp.cn/Article/details/gtuteotzao.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.havefunace.top/Article/details/gtmnigxhmn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtzrappasy.html

H. 异常与错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtzwpqfzdc.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtltygpyzo.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtxzxtzijl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hywenlv.cn/Article/details/gtcrdkqzde.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.aibaodan.cn/Article/details/gtiphjzoio.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtzqgezwgk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtletadmtp.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.fengsongda.top/Article/details/gtaevoapzh.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.aizwys.cn/Article/details/gtzpwwkqls.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtoryejcko.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhiwuduotai.top/Article/details/gtzckggftf.html

[H02] finally / ensure 收尾
来源：http://dali.pengpengdd.cyou/Article/details/gtdblcjzqm.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.guowangkeji.top/Article/details/gtmyfwqybk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtopmbtepa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.smart0.xyz/Article/details/gtauccnxel.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.pycfn.com/Article/details/gtruaecebu.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.guowangkeji.top/Article/details/gtrtqfnuwg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.dianchejie.cn/Article/details/gtbseoktvy.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jiagoushi.top/Article/details/gtslvsiiae.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhoulong.xyz/Article/details/gtthydvtym.html

[H03] 主动抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gttfqvjcuq.html

Py:   raise ValueError("错误信息")
来源：http://dali.sufxvd.cn/Article/details/gthvdltzfr.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtjfjdseev.html

JS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxdmylmn.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtcahxkrwp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gtgaytlauj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigufen.top/Article/details/gtgxsmsmwh.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sweek.top/Article/details/gtoofwgbtn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtsmyqancr.html

[H04] 自定义异常类型
来源：http://dali.daria6918.cn/Article/details/gtlbzctetm.html

Py:   class MyError(Exception): pass
来源：http://dali.wangshuangyany.cn/Article/details/gtsrtsmkmo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxjstyzm.html

JS:   class MyError extends Error {}
来源：http://dali.ydzc1.top/Article/details/gtjynxjifu.html

TS:   class MyError extends Error {}
来源：http://dali.sxryk.cn/Article/details/gtkwqwlanw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.yueranfly.top/Article/details/gtavixegfk.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gtnoznnotd.html

Ruby: class MyError < StandardError; end
来源：http://dali.chenjidiqi.icu/Article/details/gtjnsigofl.html

C#:   class MyException : Exception {}
来源：http://dali.tianlin.xyz/Article/details/gttzwiesjd.html

[H05] 捕获特定类型
来源：http://dali.yuanzhike.top/Article/details/gthjrbcwqn.html

Py:   except ValueError as e:
来源：http://dali.yangfankeji.com/Article/details/gtpnpfyrin.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.ydzc1.top/Article/details/gtqxlygfzm.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.meibo888.top/Article/details/gtmpuoybws.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmjuwlnsz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zdqjudy.top/Article/details/gtwmxwlmmk.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.sxryk.cn/Article/details/gtolbgcddd.html

Ruby: rescue ArgumentError => e
来源：http://dali.0kj1m.cn/Article/details/gtavfpfbgv.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gaohongyu789.top/Article/details/gtgqkchimm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.gogol.net.cn/Article/details/gttgbmfewp.html

Py:   value = d.get("k") or default
来源：http://dali.gotoacloud.top/Article/details/gtqpisbneb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.aizwys.cn/Article/details/gtrurmuwtj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.pycfn.com/Article/details/gtunwxnajx.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.xylfe.cn/Article/details/gtzmzlutiu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnqzz.top/Article/details/gthbslhadi.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jyoumei.cn/Article/details/gtjsmavstc.html

Ruby: d&.dig(:a, :b)
来源：http://dali.snrcjt.cn/Article/details/gtzwmlnpqn.html

C#:   obj?.A?.B ?? default
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqljvoyf.html

[H07] 断言
来源：http://dali.yangfankeji.com/Article/details/gttiiipocg.html

Py:   assert x > 0, "必须为正"
来源：http://dali.xinyue.icu/Article/details/gtspmouqjb.html

PHP:  assert($x > 0);
来源：http://dali.shzxlz.cn/Article/details/gtthhnrijm.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtlhkrsgcz.html

TS:   console.assert(x > 0);
来源：http://dali.andypj.xyz/Article/details/gtkyoawdcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.sufxvd.cn/Article/details/gtsdafxkgf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.jiagoushi.top/Article/details/gtshtyxcxk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.jinqigfzy.top/Article/details/gtkqqfcfxp.html

C#:   Debug.Assert(x > 0);
来源：http://dali.bjfxy.top/Article/details/gtjepxioxd.html

[H08] 获取错误信息与堆栈
来源：http://dali.yuxming.cn/Article/details/gtegzsdxmn.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.zhiwuduotai.top/Article/details/gtyocddyto.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhiwuduotai.top/Article/details/gtkrvrimke.html

JS:   e.message;  e.stack
来源：http://dali.yanxiufei.cn/Article/details/gtcpyerzko.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.gaohongyu789.top/Article/details/gtwbfzojds.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.quarkkingdee.top/Article/details/gtyshbezzo.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gtrvigvoji.html

Ruby: e.message;  e.backtrace
来源：http://dali.guannengcc.top/Article/details/gtxqeukhum.html

C#:   e.Message;  e.StackTrace
来源：http://dali.feifeiyinyue.top/Article/details/gtzwlourpb.html

[H09] 带错误码的异常
来源：http://dali.zhoulong.xyz/Article/details/gtvgxjzghi.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.aibaodan.cn/Article/details/gtuyhqonyp.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.hnxiangtu.top/Article/details/gtbehxsdid.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.yanxiufei.cn/Article/details/gtjprgvcqu.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.iojbl.cn/Article/details/gtaxrbeukf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ybcxt.top/Article/details/gthobyzvri.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yanxiufei.cn/Article/details/gtamyuwzzv.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.andypj.xyz/Article/details/gtjafuqhes.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gtdwyjadkq.html

[H10] 资源自动释放
来源：http://dali.zycfv.cn/Article/details/gtbczrofoi.html


<!-- 参考信息 -->