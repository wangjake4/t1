代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtpkqyhbku.html

[F06] 删除文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjpqgizpy.html

Py:   os.remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtsnkekndi.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtepvphtvc.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtbvhwfdzw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtouhqrahc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gthixsybsy.html

Go:   os.Remove("a.txt")
来源：http://dali.pycfn.com/Article/details/gteyfiprye.html

Ruby: File.delete("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtgkbbbqhl.html

C#:   File.Delete("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtotvwfanx.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtsxslqbyg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtujsyvgxo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gtsfqmybqs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gtomtpzpox.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtajthbcmw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gtsnffrndw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.9152youxi.cn/Article/details/gtudvkylhq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gtisnadslx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gzhubu.top/Article/details/gtmajepebx.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuvlsblp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtdlslwkws.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigufen.top/Article/details/gtghtcoffg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtvatoeqsb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gtitepjbup.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtzylbuuqf.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtsorempij.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtgsmmkdyl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tianlin.xyz/Article/details/gtwzbojkii.html

[F09] 获取文件大小
来源：http://dali.tanke756.top/Article/details/gtqwlglsuv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtcbjsiwxp.html

PHP:  filesize("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtkkcnvxwi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtgdlpynse.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtjahktbym.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtmiunftnv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhiwuduotai.top/Article/details/gtymvguktx.html

Ruby: File.size("a.txt")
来源：http://dali.yj202588.top/Article/details/gtifrwvutn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenjidiqi.icu/Article/details/gtzjfdbdlp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtbsqfyqea.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtuwsgtigh.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtfqdpjbdy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gteybrasbr.html

TS:   path.extname("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtpfaihnfv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtkvqdpkac.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtgewpiyra.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtzyscculo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtyftxfcqa.html

[F11] 复制与移动文件
来源：http://dali.sxryk.cn/Article/details/gtiueyaazc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtfwjtshui.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gthnjzmzmb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gtkzpqztdp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgqmyuyb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gtfqnhrshj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gtiotojysn.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gthxxbbegq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhmyycho.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtqjffdxfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gtnpnifkxd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gtvbxpmdgr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cqqwz.cn/Article/details/gtyoinrbbn.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtohzpmilg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtfekgrscz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yongpay.top/Article/details/gtoyjaolgl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonbmbvxu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.0kj1m.cn/Article/details/gtikfqpnih.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtglabxywv.html

G. 面向对象
来源：http://dali.meibo888.top/Article/details/gtnqsutkfn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwzwryfw.html

[G01] 定义类
来源：http://dali.nanxuanxn.top/Article/details/gtdfuxlnij.html

Py:   class User: pass
来源：http://dali.sysykeji.top/Article/details/gtffbteigs.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtlbrksifj.html

JS:   class User {}
来源：http://dali.316326.xyz/Article/details/gtsyxsqjse.html

TS:   class User { name: string = ""; }
来源：http://dali.zhengqikj.top/Article/details/gtormdcbms.html

Java: class User {}
来源：http://dali.9152youxi.cn/Article/details/gtnenrlrpu.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gtvstdivey.html

Ruby: class User; end
来源：http://dali.shangyingyoupin.top/Article/details/gtyzuvqpcj.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtqusgefeo.html

[G02] 构造函数
来源：http://dali.svipenyu.cn/Article/details/gtonvwwlxo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gtogwyzhnq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtwsfgepdd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gtbewrosik.html

TS:   constructor(public name: string) {}
来源：http://dali.hysaishi.cn/Article/details/gthpajiisd.html

Java: User(String name) { this.name = name; }
来源：http://dali.yonumen.top/Article/details/gtmlwdsufs.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hnxiangtu.top/Article/details/gthlmfjzoi.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.iojbl.cn/Article/details/gtssluvkaa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yonumen.top/Article/details/gtjwgnexik.html

[G03] 实例属性
来源：http://dali.yuanzhike.top/Article/details/gtfajebuxs.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtddyhdqlw.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gtyqeqlwrw.html

JS:   this.name = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyksdduom.html

TS:   name: string = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtcoottqgs.html

Java: private String name;
来源：http://dali.jinqigufen.top/Article/details/gttlwyveak.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gtkwqfmvug.html

Ruby: @name = "x"
来源：http://dali.redwolf501.top/Article/details/gtxczljawl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hysaishi.cn/Article/details/gtemsecojp.html

[G04] 定义方法
来源：http://dali.hysaishi.cn/Article/details/gtxlirrpht.html

Py:   def greet(self): return self.name
来源：http://dali.iojbl.cn/Article/details/gtmyysszhv.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnqzz.top/Article/details/gtirwbswje.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gtlenpiitf.html

TS:   greet(): string { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlzbnmyg.html

Java: String greet() { return name; }
来源：http://dali.gzhubu.top/Article/details/gtmqlqeeop.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xinyue.icu/Article/details/gtukygeeaj.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gtbmqssyhf.html

C#:   public string Greet() => Name;
来源：http://dali.feifeiyinyue.top/Article/details/gttkscbzan.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gtsbspldik.html

Py:   class Admin(User): pass
来源：http://dali.ppjwa.cn/Article/details/gtqtftpbhq.html

PHP:  class Admin extends User {}
来源：http://dali.birdmap.top/Article/details/gtklcwvxvj.html

JS:   class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gtjxigbiqf.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gtyyitvent.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtwrynrfir.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.feifeiyinyue.top/Article/details/gtuutxvxki.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtjhfsjnie.html

C#:   class Admin : User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtghiqnvwk.html

[G06] 重写方法
来源：http://dali.nanxuanxn.top/Article/details/gtzhbchlsf.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtbzubxujr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gtiyqvdxle.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gtnvyvsdqc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gttkvbfxcv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxgcdoil.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.meibo888.top/Article/details/gtommxrtgk.html

Ruby: def greet; "admin"; end
来源：http://dali.yueranfly.top/Article/details/gtzmmpzvud.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwkqvczi.html

[G07] 调用父类方法
来源：http://dali.kuanghao11.cn/Article/details/gtofsczwmu.html

Py:   super().greet()
来源：http://dali.cheryme.top/Article/details/gtpasalbje.html

PHP:  parent::greet();
来源：http://dali.cheryme.top/Article/details/gtvthtbvaa.html

JS:   super.greet();
来源：http://dali.9152youxi.cn/Article/details/gtgjgxjifi.html

TS:   super.greet();
来源：http://dali.sweek.top/Article/details/gtvkyzofck.html

Java: super.greet();
来源：http://dali.fzhhl.top/Article/details/gtqxmtlkqa.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.0kj1m.cn/Article/details/gtgwlbculi.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtqvibstle.html

C#:   base.Greet();
来源：http://dali.316326.xyz/Article/details/gtswliuauy.html

[G08] 静态方法与属性
来源：http://dali.chenlongwang.top/Article/details/gtqdrzycya.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtsdcyswmq.html

PHP:  public static function f() {}
来源：http://dali.redwolf501.top/Article/details/gtyjdtweqg.html

JS:   static f() {}
来源：http://dali.daria6918.cn/Article/details/gticjylhea.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtvrhdzqka.html

Java: static void f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwxdrlgqi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxuanxn.top/Article/details/gtfbmjlvrv.html

Ruby: def self.f; end
来源：http://dali.shuidangran.top/Article/details/gtrhnoohbu.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtuvnzuvhq.html

[G09] 接口 / 抽象类
来源：http://dali.svipenyu.cn/Article/details/gtybgpbvrj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ybcxt.top/Article/details/gtufpjbbbo.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.mhx1999.top/Article/details/gtrsvcuxlk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shangyingyoupin.top/Article/details/gtazuhnejx.html

TS:   interface Shape { area(): number; }
来源：http://dali.mhx1999.top/Article/details/gtintxeraj.html

Java: interface Shape { double area(); }
来源：http://dali.zycfv.cn/Article/details/gtvjvynzoz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.vqdsnc.cn/Article/details/gtxrbobhtj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.snrcjt.cn/Article/details/gtfqcrdbwr.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnqzz.top/Article/details/gtmjzxqhuc.html

[G10] 访问控制
来源：http://dali.hfpthk.cn/Article/details/gtmbcdvlwi.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gtnuthgbrd.html

PHP:  public / protected / private
来源：http://dali.ivvv.top/Article/details/gtltyxvqmd.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gtlpjakdis.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gtngmsopdz.html

Java: public / protected / private / 默认包级
来源：http://dali.hongshengwenyu.top/Article/details/gtpqzfxnlm.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jinqigufen.top/Article/details/gthisfdpjx.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtavcnbxqt.html

C#:   public / protected / private / internal
来源：http://dali.zycfv.cn/Article/details/gtkzwyaawc.html

[G11] getter / setter
来源：http://dali.guowangkeji.top/Article/details/gtqwtisoyy.html

Py:   @property 与 @x.setter
来源：http://dali.zycfv.cn/Article/details/gtfjloesqu.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cucudq.cn/Article/details/gtyllxfahf.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtvrshntsa.html

TS:   get name(): string { return this._name; }
来源：http://dali.xinyue.icu/Article/details/gtsqqfjiev.html

Java: public String getName() { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtrcoehcfq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.iojbl.cn/Article/details/gtnxtwootg.html

Ruby: attr_accessor :name
来源：http://dali.jlsjyb.cn/Article/details/gtjlgyxbuu.html

C#:   public string Name { get; set; }
来源：http://dali.yj202588.top/Article/details/gtaftsijya.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gtazyummjt.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnsjipmh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtafzcushg.html

JS:   toString() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gtbkpeovcy.html

TS:   toString(): string { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gtmohbsqpo.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtjoxqyotj.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sufxvd.cn/Article/details/gtfzwyrluv.html

Ruby: def to_s; @name; end
来源：http://dali.cashguo.top/Article/details/gtikepxckc.html

C#:   public override string ToString() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtsnezemkq.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtbduuoafc.html

Py:   isinstance(u, User)
来源：http://dali.zhixingplan.top/Article/details/gtjcacwyql.html

PHP:  $u instanceof User
来源：http://dali.sweek.top/Article/details/gtfadiktcc.html

JS:   u instanceof User
来源：http://dali.guannengcc.top/Article/details/gtebklnnxb.html

TS:   u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gtzvhspqjt.html

Java: u instanceof User
来源：http://dali.9152youxi.cn/Article/details/gticpomhbm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jlsjyb.cn/Article/details/gtbddgfqxs.html

Ruby: u.is_a?(User)
来源：http://dali.kuanghao11.cn/Article/details/gtegavfvis.html

C#:   u is User
来源：http://dali.iojbl.cn/Article/details/gtexnfobvw.html

[G14] 数据类 / record
来源：http://dali.ydzc1.top/Article/details/gtkxlhafda.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.cashguo.top/Article/details/gttjdvznio.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.nanxinkj.top/Article/details/gtiuveookt.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhengqikj.top/Article/details/gtdlpexbxr.html

TS:   type User = { name: string; age: number };
来源：http://dali.vqdsnc.cn/Article/details/gtecxcsxdl.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtblpzeacu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.smart0.xyz/Article/details/gtkbqcaiqq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zdqjudy.top/Article/details/gtchszflud.html

C#:   record User(string Name, int Age);
来源：http://dali.yonumen.top/Article/details/gtcptfvptf.html

[G15] 枚举
来源：http://dali.hfpthk.cn/Article/details/gtxspawcyt.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtjliabbif.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.tian-w.cn/Article/details/gtjoqaqrfd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.pengpengdd.cyou/Article/details/gthvtxpkuo.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gtnppspwps.html

Java: enum Color { RED, GREEN }
来源：http://dali.shangyingyoupin.top/Article/details/gtbmqlnoqw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nanxinkj.top/Article/details/gtmwsedzba.html

Ruby: Color = %i[red green].freeze
来源：http://dali.wangdashe.top/Article/details/gtmfjigegn.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.smart0.xyz/Article/details/gtggioumtg.html

[G16] 对象转数组 / 字典
来源：http://dali.jinqigufen.top/Article/details/gtcqplvvua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.c1oappe.top/Article/details/gtgzvorurf.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gtrigxlvpr.html

JS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gtouvtfsrx.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gtlfepjxlv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.sweek.top/Article/details/gtrodtufop.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.xuanzx.com/Article/details/gtmgzwrmqo.html

Ruby: obj.instance_variables
来源：http://dali.zhiwuduotai.top/Article/details/gtkxqbjbxi.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.gzhubu.top/Article/details/gtzjvpuhya.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtieakdqry.html

H. 异常与错误处理
来源：http://dali.meibo888.top/Article/details/gthhxhjnqg.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdxlflee.html

[H01] try / catch 基础
来源：http://dali.9152youxi.cn/Article/details/gtxukeugkq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.sysykeji.top/Article/details/gtyyfrbfir.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.bjfxy.top/Article/details/gtjkddjvsr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkgxebucl.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtlirqdesj.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtispuwdmx.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuxming.cn/Article/details/gttrqsnnms.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hysaishi.cn/Article/details/gtlqkcnzvc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.mhx1999.top/Article/details/gtlcmsaebq.html

[H02] finally / ensure 收尾
来源：http://dali.tian-w.cn/Article/details/gtlmzmaair.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cashguo.top/Article/details/gtmbndchmg.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gtgsgbmdos.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtwsyculgf.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj202588.top/Article/details/gtkxawrwbh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gtneyezgbg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtyhtnydvl.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.birdmap.top/Article/details/gtxorvudka.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.yongpay.top/Article/details/gtrwehxluh.html

[H03] 主动抛出异常
来源：http://dali.hysaishi.cn/Article/details/gtwtipclmg.html

Py:   raise ValueError("错误信息")
来源：http://dali.yueranfly.top/Article/details/gtuhaxcvxe.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtlontqexg.html

JS:   throw new Error("错误信息");
来源：http://dali.nwbrower.top/Article/details/gtlsjcheof.html

TS:   throw new Error("错误信息");
来源：http://dali.jlsjyb.cn/Article/details/gtidslycpz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujuexhcp.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shuidangran.top/Article/details/gtoopwxinw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.shuidangran.top/Article/details/gthveafhoe.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gtcdmghbuq.html

[H04] 自定义异常类型
来源：http://dali.sxryk.cn/Article/details/gtcgevzmia.html

Py:   class MyError(Exception): pass
来源：http://dali.guannengcc.top/Article/details/gtvretjxbx.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zhijiandao.cn/Article/details/gthrgjxuyf.html

JS:   class MyError extends Error {}
来源：http://dali.tianlin.xyz/Article/details/gtfrlklfcw.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtmdzgdzbw.html

Java: class MyException extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gtlqlxdsja.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.svipenyu.cn/Article/details/gtfdammqkh.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gteqgsqguv.html

C#:   class MyException : Exception {}
来源：http://dali.cqqwz.cn/Article/details/gtrymlyjml.html

[H05] 捕获特定类型
来源：http://dali.svipenyu.cn/Article/details/gtvnuezgyl.html

Py:   except ValueError as e:
来源：http://dali.cashguo.top/Article/details/gtrjozgukc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yongpay.top/Article/details/gtamrhltru.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtxvaogujo.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jianghu66.top/Article/details/gtueaslwvp.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbllzdfhn.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hfpthk.cn/Article/details/gtxjllyzdu.html

Ruby: rescue ArgumentError => e
来源：http://dali.aizwys.cn/Article/details/gtzzklzyxp.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cheryme.top/Article/details/gtdfizbhry.html

[H06] 可选值 / 空值安全访问
来源：http://dali.bjfxy.top/Article/details/gtygypwbnt.html

Py:   value = d.get("k") or default
来源：http://dali.chenzaomai.com/Article/details/gtmgmhlwhl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.daria6918.cn/Article/details/gtthetgzxf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtewezzcps.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gtaewtufep.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhijiandao.cn/Article/details/gtehsqpeuj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinqigfzy.top/Article/details/gtljgwgzki.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tian-w.cn/Article/details/gthnjixtxq.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gtcatrhypn.html

[H07] 断言
来源：http://dali.hnqzz.top/Article/details/gtrrdbmcqs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.shuidangran.top/Article/details/gtjxypqbfs.html

PHP:  assert($x > 0);
来源：http://dali.jianghu66.top/Article/details/gtafsxlebo.html

JS:   console.assert(x > 0);
来源：http://dali.yuxming.cn/Article/details/gtgystynia.html

TS:   console.assert(x > 0);
来源：http://dali.ppjwa.cn/Article/details/gtcevkjvza.html

Java: assert x > 0 : "必须为正";
来源：http://dali.aizwys.cn/Article/details/gtyydvaycf.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwpmxwmx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yvedp.cn/Article/details/gtmttplelb.html

C#:   Debug.Assert(x > 0);
来源：http://dali.sxryk.cn/Article/details/gtehrpkvdi.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhongyouzk.top/Article/details/gtotpgbfnj.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.wangdashe.top/Article/details/gtlmgkoidj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jinqigfzy.top/Article/details/gttzoaksiv.html

JS:   e.message;  e.stack
来源：http://dali.jlsjyb.cn/Article/details/gtkpvfeiqt.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.shangyingyoupin.top/Article/details/gtfshavhnd.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.guannengcc.top/Article/details/gtqlmijmcu.html

Go:   err.Error()
来源：http://dali.ehwqpu.com/Article/details/gtvloyimcc.html

Ruby: e.message;  e.backtrace
来源：http://dali.c1oappe.top/Article/details/gtanbiodbk.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258.top/Article/details/gtzqsrffau.html

[H09] 带错误码的异常
来源：http://dali.yongpay.top/Article/details/gtsebtzjwj.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.c1oappe.top/Article/details/gtlhzgyjpo.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.gaohongyu789.top/Article/details/gttsmowtlq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.jqgufenzy.top/Article/details/gtouksuuhq.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.cdnleiting.top/Article/details/gtkujraorg.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.sufxvd.cn/Article/details/gtojmrwcgv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.zhengqikj.top/Article/details/gtnnautbmc.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.zhixingplan.top/Article/details/gtlfuafttv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zhongyouzk.top/Article/details/gtzuydsqxh.html

[H10] 资源自动释放
来源：http://dali.0kj1m.cn/Article/details/gtgarhpklp.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.bjfxy.top/Article/details/gtxjdmlgnr.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.0kj1m.cn/Article/details/gtsvhlnoef.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbinrzbk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.ybcxt.top/Article/details/gttsowhfpv.html


<!-- 参考信息 -->