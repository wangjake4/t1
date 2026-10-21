代发 wailian999

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtarwbjqie.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtzdaglzqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtqnbptjbj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhengqikj.top/Article/details/gtduezxjtn.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtgibibjtr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gttliegzir.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtmvujnwht.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtkdzjtqgj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtbtphgekd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtsvodckqj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtzqajfztl.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtmxdfxtpn.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gthovhgqgh.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtdorcxwki.html

Py:   os.remove("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtyaxfucdy.html

PHP:  unlink("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtrpikogno.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtljkyziwk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrpxonqmj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtyoijuyvq.html

Go:   os.Remove("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtkgezbzje.html

Ruby: File.delete("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbrusgyqc.html

C#:   File.Delete("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gthdeswfdr.html

[F07] 创建目录（含多级）
来源：http://dali.svipenyu.cn/Article/details/gtqqmfcciq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtyvfwsqwl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.fengsongda.top/Article/details/gtjfqohjyt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtipoarsmt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gtwlcnatjs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cdnleiting.top/Article/details/gtwsftjqcr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gogol.net.cn/Article/details/gtjwkpirhm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shuidangran.top/Article/details/gtgzcmxusm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtlzfftqmp.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gtbssfszvn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtivjxjnzk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yangfankeji.com/Article/details/gtarkhrmvh.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gtoedaftlp.html

TS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gthojzseij.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrgigval.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gtekkhxlcl.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gttwrfypmi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sufxvd.cn/Article/details/gtqmayncpf.html

[F09] 获取文件大小
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbajghaib.html

Py:   os.path.getsize("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmylnfted.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtnpwibcwo.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gtkgmnhwuk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gtjmlpgmtf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gtwirccyho.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jianghu66.top/Article/details/gtewlaizry.html

Ruby: File.size("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtyvxaaggx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gteilpbyjl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gtadkngrcs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtxngtkbdr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtdwqfnasg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatpkjzmo.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuqztzihr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gtuuuazvmu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtvmzpadhs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtbehlural.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gtsrfdqhvg.html

[F11] 复制与移动文件
来源：http://dali.sysykeji.top/Article/details/gtdrfztnqu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtdyzizzxh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.svipenyu.cn/Article/details/gtwsidiudb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtywssaohd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtdfzcvcih.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yvedp.cn/Article/details/gtrcsxouyd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cqqwz.cn/Article/details/gthlbmxrwc.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gtrxgmgfvu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xziqi.cn/Article/details/gtobtnsgni.html

[F12] CSV 读写
来源：http://dali.ppjwa.cn/Article/details/gttzntlfbw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtawbesjcj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangshuangyany.cn/Article/details/gtvkmecryx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhixingplan.top/Article/details/gtbtkdmtvh.html

TS:   // 同上
来源：http://dali.9152youxi.cn/Article/details/gtntltkrkk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.tian-w.cn/Article/details/gtsmcxdkvt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ybcxt.top/Article/details/gtfezbgtun.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.aizwys.cn/Article/details/gtuxhdhznf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gtsechakxo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqgtbiyya.html

G. 面向对象
来源：http://dali.svipenyu.cn/Article/details/gtvklzplhf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtswldrqxr.html

[G01] 定义类
来源：http://dali.316326.xyz/Article/details/gthfimwjjt.html

Py:   class User: pass
来源：http://dali.nanxuanxn.top/Article/details/gtcndqexmf.html

PHP:  class User {}
来源：http://dali.xylfe.cn/Article/details/gtckjakrnf.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gttyoumlmp.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxuanxn.top/Article/details/gtxgkziwht.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtsxyukndl.html

Go:   type User struct { Name string }
来源：http://dali.jinqigufen.top/Article/details/gtglaoxjqy.html

Ruby: class User; end
来源：http://dali.yanxiufei.cn/Article/details/gtlgozwqcv.html

C#:   class User {}
来源：http://dali.hywenlv.cn/Article/details/gteaasalei.html

[G02] 构造函数
来源：http://dali.hnqzz.top/Article/details/gtrspwpljx.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tianlin.xyz/Article/details/gtzoytivnb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cheryme.top/Article/details/gtyevatvmq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtoegytuzy.html

TS:   constructor(public name: string) {}
来源：http://dali.nwbrower.top/Article/details/gtslvrtxnn.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtesferfzt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangdashe.top/Article/details/gtirrtmxcd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.wangshuangyany.cn/Article/details/gtkwwbzlua.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdjgdyvmy.html

[G03] 实例属性
来源：http://dali.sysykeji.top/Article/details/gtwwlilxdy.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gtuivcfviz.html

PHP:  public string $name = "x";
来源：http://dali.jqgfzy.top/Article/details/gtojojavyn.html

JS:   this.name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gtflfbgudf.html

TS:   name: string = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgevxnljg.html

Java: private String name;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvkhlopi.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgfzy.top/Article/details/gtrpzwmzhz.html

Ruby: @name = "x"
来源：http://dali.fzhhl.top/Article/details/gtmtqfiqhl.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtwjfiuimb.html

[G04] 定义方法
来源：http://dali.sysykeji.top/Article/details/gtxwefwwsm.html

Py:   def greet(self): return self.name
来源：http://dali.zdqjudy.top/Article/details/gtdnawzird.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeayumjh.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gtfmrtbwmh.html

TS:   greet(): string { return this.name; }
来源：http://dali.tian-w.cn/Article/details/gtazlfunvp.html

Java: String greet() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtuvqqieoo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gtnudjrdym.html

Ruby: def greet; @name; end
来源：http://dali.tanke756.top/Article/details/gtomaijvdr.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtbbbhfdkx.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtusivwzqr.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gthialwajc.html

PHP:  class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtctpshfnv.html

JS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtegjjoijc.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinasfcgx.html

Java: class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtsnpcqufl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcmuuxca.html

Ruby: class Admin < User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtzuoeyjey.html

C#:   class Admin : User {}
来源：http://dali.zhengqikj.top/Article/details/gtaeowettq.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gtobekvamq.html

Py:   def greet(self): return "admin"
来源：http://dali.yongpay.top/Article/details/gtntmxzaan.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtunsblkxi.html

JS:   greet() { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtpyewimtu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbscjgkws.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtkdfmfvap.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258.top/Article/details/gtdwkbgvqw.html

Ruby: def greet; "admin"; end
来源：http://dali.yuanzhike.top/Article/details/gtktdavfxr.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258888.top/Article/details/gtyyrgbebx.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtnbdkjhds.html

Py:   super().greet()
来源：http://dali.smart0.xyz/Article/details/gtqcezmssq.html

PHP:  parent::greet();
来源：http://dali.havefunace.top/Article/details/gtomznehii.html

JS:   super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlcqgptr.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtpnekuiee.html

Java: super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtpupyglrw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jiagoushi.top/Article/details/gtdryolieh.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gtviulzokh.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gtsavizlxd.html

[G08] 静态方法与属性
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfoeubsr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gtwyskarwr.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gthusfkknb.html

JS:   static f() {}
来源：http://dali.cashguo.top/Article/details/gtptgwkphm.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gtywccfhid.html

Java: static void f() {}
来源：http://dali.cqqwz.cn/Article/details/gtzqvogmhj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gtlqvouqru.html

Ruby: def self.f; end
来源：http://dali.nanxuanxn.top/Article/details/gtqpcxglgf.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gtzzdoafwf.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtjhlcwemv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.jinqigufen.top/Article/details/gtpeuwxtbt.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtvopzordp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gtzpjbznhe.html

TS:   interface Shape { area(): number; }
来源：http://dali.chenlongwang.top/Article/details/gtstsaoagh.html

Java: interface Shape { double area(); }
来源：http://dali.tanke756.top/Article/details/gtggshdbvk.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.quarkkingdee.top/Article/details/gttuexzyly.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daria6918.cn/Article/details/gtbllfuhby.html

C#:   interface IShape { double Area(); }
来源：http://dali.svipenyu.cn/Article/details/gtwohqgiwm.html

[G10] 访问控制
来源：http://dali.feifeiyinyue.top/Article/details/gtdiaxuvtr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gtydgiompa.html

PHP:  public / protected / private
来源：http://dali.redwolf501.top/Article/details/gthxalvqsg.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtqfmifxxa.html

TS:   public / protected / private
来源：http://dali.316326.xyz/Article/details/gtbdtufizq.html

Java: public / protected / private / 默认包级
来源：http://dali.jqgufenzy.top/Article/details/gtyctbtyka.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gtykzigser.html

Ruby: public / protected / private
来源：http://dali.zhixingplan.top/Article/details/gtvtscbcdp.html

C#:   public / protected / private / internal
来源：http://dali.tianlin.xyz/Article/details/gtxyuvmmjo.html

[G11] getter / setter
来源：http://dali.sxryk.cn/Article/details/gtftwowvny.html

Py:   @property 与 @x.setter
来源：http://dali.nwbrower.top/Article/details/gtqygqqkci.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtikdjigsb.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtzjcclksm.html

TS:   get name(): string { return this._name; }
来源：http://dali.hammf.cn/Article/details/gtbwrhtdoa.html

Java: public String getName() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtxnwzyiwc.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gtjuigodpf.html

Ruby: attr_accessor :name
来源：http://dali.vqdsnc.cn/Article/details/gtcibyhlry.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuxxlersu.html

[G12] 对象转字符串
来源：http://dali.cucudq.cn/Article/details/gtiolfycgt.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtjeozxjrx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yvedp.cn/Article/details/gtpgaaztxc.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gtgxiwcabx.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtscvrphdx.html

Java: @Override public String toString() { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfpxezsbt.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gthlkpxjwd.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gtixcwxutc.html

C#:   public override string ToString() => Name;
来源：http://dali.birdmap.top/Article/details/gtivpeyxio.html

[G13] 判断对象类型
来源：http://dali.hnxiangtu.top/Article/details/gtgueymsgu.html

Py:   isinstance(u, User)
来源：http://dali.yuxming.cn/Article/details/gtabrbbeyj.html

PHP:  $u instanceof User
来源：http://dali.ydzc1.top/Article/details/gtctyxdxhx.html

JS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtztqzpphk.html

TS:   u instanceof User
来源：http://dali.smart0.xyz/Article/details/gtnnqeqgmg.html

Java: u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gtebtutzvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.yongpay.top/Article/details/gtckcslpvt.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gtlsrldalt.html

C#:   u is User
来源：http://dali.quarkkingdee.top/Article/details/gtojgzkztw.html

[G14] 数据类 / record
来源：http://dali.daxiang520.top/Article/details/gtgoehqpkz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yongpay.top/Article/details/gtknwzkzov.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.guowangkeji.top/Article/details/gtqdoortle.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.sxryk.cn/Article/details/gtvlddqrya.html

TS:   type User = { name: string; age: number };
来源：http://dali.ppjwa.cn/Article/details/gtqqcfvhvx.html

Java: record User(String name, int age) {}
来源：http://dali.xinyue.icu/Article/details/gtsdoqopku.html

Go:   type User struct { Name string; Age int }
来源：http://dali.nanxuanxn.top/Article/details/gtazdrimpb.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nanxinkj.top/Article/details/gtgxhbwcwa.html

C#:   record User(string Name, int Age);
来源：http://dali.zdqjudy.top/Article/details/gtubiugnbo.html

[G15] 枚举
来源：http://dali.guowangkeji.top/Article/details/gtgkglvjem.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gthqjtacho.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yonumen.top/Article/details/gtowudfwyj.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cashguo.top/Article/details/gtptgbjoaz.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtorboznmq.html

Java: enum Color { RED, GREEN }
来源：http://dali.redwolf501.top/Article/details/gthjwwziyo.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuetiantiany.cn/Article/details/gtpxiguikc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gtvgjjbeui.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpkzoeum.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gtbjwjpfua.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.nanxinkj.top/Article/details/gtahkylrui.html

PHP:  get_object_vars($obj);
来源：http://dali.jqgfzy.top/Article/details/gthcclhqcv.html

JS:   Object.entries(obj)
来源：http://dali.chenzaomai.com/Article/details/gtaycwadba.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gtqfxkhusx.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhoulong.xyz/Article/details/gtqjptfhks.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hysaishi.cn/Article/details/gtykuwvbyb.html

Ruby: obj.instance_variables
来源：http://dali.pengpengdd.cyou/Article/details/gtylavjepg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuxming.cn/Article/details/gtzgggioun.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtipaqnloc.html

H. 异常与错误处理
来源：http://dali.mhx1999.top/Article/details/gtjqcacgca.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvqlhmxcc.html

[H01] try / catch 基础
来源：http://dali.shangyingyoupin.top/Article/details/gtjftivgtq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gtzuhzofqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.smart0.xyz/Article/details/gtdfqskyok.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinqigfzy.top/Article/details/gtdpbnkybw.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gtzmeeiiij.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dashuyun.cn/Article/details/gtqwyusuia.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.zhongyouzk.top/Article/details/gtgtrcgrtd.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlaynvhe.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.yanxiufei.cn/Article/details/gtwljclmqz.html

[H02] finally / ensure 收尾
来源：http://dali.chenzaomai.com/Article/details/gtsdzqvlmc.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.c1oappe.top/Article/details/gtfetsufvd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.tian-w.cn/Article/details/gtoyorhdyf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gtfbnltfdd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jqgfzy.top/Article/details/gtfwmxblxb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnopvfbm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hfpthk.cn/Article/details/gtfwxyuhpm.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.nanxinkj.top/Article/details/gtehxyxsdh.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtalwtmbku.html

[H03] 主动抛出异常
来源：http://dali.yangfankeji.com/Article/details/gteqmujvrk.html

Py:   raise ValueError("错误信息")
来源：http://dali.yj202588.top/Article/details/gtdoxurhrs.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtxsnvmxbx.html

JS:   throw new Error("错误信息");
来源：http://dali.tanke756.top/Article/details/gtbuebdboa.html

TS:   throw new Error("错误信息");
来源：http://dali.havefunace.top/Article/details/gtgvyrziwt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.haohaochexian.top/Article/details/gtlilptalk.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gtpcgnmvsx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.jqgufenzy.top/Article/details/gtmvmjeemh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yueranfly.top/Article/details/gtjmvualwg.html

[H04] 自定义异常类型
来源：http://dali.daxiang520.top/Article/details/gtblktufmh.html

Py:   class MyError(Exception): pass
来源：http://dali.yj20258.top/Article/details/gtqyfmuygk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwmjcxdkz.html

JS:   class MyError extends Error {}
来源：http://dali.iojbl.cn/Article/details/gtbtrxgmyf.html

TS:   class MyError extends Error {}
来源：http://dali.guowangkeji.top/Article/details/gtfyklymxq.html

Java: class MyException extends RuntimeException {}
来源：http://dali.mhx1999.top/Article/details/gtzzznfmqr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.chenjidiqi.icu/Article/details/gtyrwzemai.html

Ruby: class MyError < StandardError; end
来源：http://dali.zhongyouzk.top/Article/details/gtgdmuteou.html

C#:   class MyException : Exception {}
来源：http://dali.shzxlz.cn/Article/details/gtkpccmpui.html

[H05] 捕获特定类型
来源：http://dali.yj202588.top/Article/details/gtouxirusg.html

Py:   except ValueError as e:
来源：http://dali.mhx1999.top/Article/details/gtfwdjpqux.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yuxming.cn/Article/details/gtnfzruzog.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.hammf.cn/Article/details/gtfylcpbqc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtggpwjvul.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.ivvv.top/Article/details/gtkdxwyuna.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.pengpengdd.cyou/Article/details/gtgzhhuksx.html

Ruby: rescue ArgumentError => e
来源：http://dali.9152youxi.cn/Article/details/gtqbbytour.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtwesuonll.html

[H06] 可选值 / 空值安全访问
来源：http://dali.iojbl.cn/Article/details/gtpeofnuwh.html

Py:   value = d.get("k") or default
来源：http://dali.nanxuanxn.top/Article/details/gtvkqzbkrt.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtwcjfubqs.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.xuetiantiany.cn/Article/details/gtkmribfvt.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sweek.top/Article/details/gthlnxgjdg.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhongyouzk.top/Article/details/gtriutcahz.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.mhx1999.top/Article/details/gtrovhjixf.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsxlcuhrh.html

C#:   obj?.A?.B ?? default
来源：http://dali.xuanzx.com/Article/details/gtmspxbmpz.html

[H07] 断言
来源：http://dali.snrcjt.cn/Article/details/gtgrjdfmnf.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hysaishi.cn/Article/details/gtohlwxeuq.html

PHP:  assert($x > 0);
来源：http://dali.chenlongwang.top/Article/details/gtiqactayt.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigfzy.top/Article/details/gtugsnjpgm.html

TS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtxoidocmv.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtvbqimsby.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.smart0.xyz/Article/details/gtwfjwhmyx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.havefunace.top/Article/details/gtaqqjmtzc.html

C#:   Debug.Assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gteuvvvdsv.html

[H08] 获取错误信息与堆栈
来源：http://dali.redwolf501.top/Article/details/gtdvszfoft.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jlsjyb.cn/Article/details/gtkecglloe.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xinyue.icu/Article/details/gttqerrzcp.html

JS:   e.message;  e.stack
来源：http://dali.xylfe.cn/Article/details/gtklyylcrs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jlsjyb.cn/Article/details/gtgazhuzpj.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hnqzz.top/Article/details/gtxvbqapfp.html

Go:   err.Error()
来源：http://dali.yanxiufei.cn/Article/details/gttoheawgy.html

Ruby: e.message;  e.backtrace
来源：http://dali.haohaochexian.top/Article/details/gtuitpywkz.html

C#:   e.Message;  e.StackTrace
来源：http://dali.mhx1999.top/Article/details/gtoypgovyo.html

[H09] 带错误码的异常
来源：http://dali.aizwys.cn/Article/details/gtqiewurfk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.cdnleiting.top/Article/details/gtweukselc.html


<!-- 参考信息 -->