代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gtjjvghoxb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtxzdyqflx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gttvxueadq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gtvexfccxs.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtztspxrvv.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbnxjzdkg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtuneztwvg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xuanzx.com/Article/details/gtzteyqjzt.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtprenbnho.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhengqikj.top/Article/details/gtmvbkxglt.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtpufxoabh.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtoiutjtpf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtpepeyoci.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtpgjttoug.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtcbrowhek.html

Ruby: File.exist?("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjvpylvcy.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtksfxxxyn.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gtovimswim.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtvhecjzdw.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtbviiedcy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtzutserbg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtecghhaxu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtdqyvmndc.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gttzphzhup.html

Ruby: File.delete("a.txt")
来源：http://dali.yj20258.top/Article/details/gtzcdgjvyk.html

C#:   File.Delete("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtrixcvsjw.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gtsjutdzdz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtsoeqmhom.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gtxtaddmgv.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtadjuuyuf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtlimtuhjf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yueranfly.top/Article/details/gtlmsizpbr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ehwqpu.com/Article/details/gtmzftgrtc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ehwqpu.com/Article/details/gtcektrrcm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgfzy.top/Article/details/gtmawjgfqy.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gtsancbiik.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gaohongyu789.top/Article/details/gtbuehnrxz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gtkjuvqyrd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtpskvflch.html

TS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtsdlwxgok.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtcotpjpdr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sysykeji.top/Article/details/gtvxhwhqzc.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gteiimtvqi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hammf.cn/Article/details/gtjvcyuhxu.html

[F09] 获取文件大小
来源：http://dali.zhixingplan.top/Article/details/gthvpkckpn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtyeyyigvk.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gtguibvbdg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.haohaochexian.top/Article/details/gtsiwljwdg.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtiioowedw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtqzgxpwyr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xinyue.icu/Article/details/gtnjsiotvf.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gthmxlmxpc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xuetiantiany.cn/Article/details/gtoyniawoj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.316326.xyz/Article/details/gtufirgtac.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtrkwodwon.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.iojbl.cn/Article/details/gtjdfaqmtr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtjbgudalg.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtqlcvkvhs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tanke756.top/Article/details/gthjriphpr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtdveumhek.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xylfe.cn/Article/details/gtuzxjiriz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtiwnmjoxo.html

[F11] 复制与移动文件
来源：http://dali.gaohongyu789.top/Article/details/gtnssdphts.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtfzynyolw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.shzxlz.cn/Article/details/gtjuvjospz.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gthhxwahtb.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gtrqmcsoqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gteejikoyu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhiwuduotai.top/Article/details/gtcpbjkgge.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtxyhfbaqy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.nanxuanxn.top/Article/details/gtkyzyzpzx.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gtrtjjlgbg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hywenlv.cn/Article/details/gtxvzseunr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.pycfn.com/Article/details/gtsxfmjcoo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gtfeipowpk.html

TS:   // 同上
来源：http://dali.gotoacloud.top/Article/details/gtriasdmxz.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtmetdipxk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gtsptupyau.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuanzhike.top/Article/details/gtqgveqbxi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxuanxn.top/Article/details/gtjkgjegua.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtolymvnaa.html

G. 面向对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoolcpmsf.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaadzwjar.html

[G01] 定义类
来源：http://dali.ydzc1.top/Article/details/gtyrwugycq.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdledudj.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtnyakmaea.html

JS:   class User {}
来源：http://dali.hnqzz.top/Article/details/gtrektbhsx.html

TS:   class User { name: string = ""; }
来源：http://dali.mhx1999.top/Article/details/gtmjsfdlsn.html

Java: class User {}
来源：http://dali.hammf.cn/Article/details/gtuhkxfghp.html

Go:   type User struct { Name string }
来源：http://dali.wangdashe.top/Article/details/gtmwyuegor.html

Ruby: class User; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdptykbis.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuwvrfqkt.html

[G02] 构造函数
来源：http://dali.kuanghao11.cn/Article/details/gtoufecokq.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiunjyrj.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xinyue.icu/Article/details/gtholryiyw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.9152youxi.cn/Article/details/gttpqgtzqi.html

TS:   constructor(public name: string) {}
来源：http://dali.yuxming.cn/Article/details/gtimdboqht.html

Java: User(String name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gtzyxwimss.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jiagoushi.top/Article/details/gtmnjyjsur.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtmwwgsdal.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jianghu66.top/Article/details/gtoinjwvon.html

[G03] 实例属性
来源：http://dali.guannengcc.top/Article/details/gthlwtjkmr.html

Py:   self.name = "x"
来源：http://dali.chenlongwang.top/Article/details/gtwlorhqgu.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtucmyhonv.html

JS:   this.name = "x";
来源：http://dali.c1oappe.top/Article/details/gtlbcysimt.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gtsveglrxt.html

Java: private String name;
来源：http://dali.hysaishi.cn/Article/details/gtopxxyhwk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shzxlz.cn/Article/details/gtodqxicim.html

Ruby: @name = "x"
来源：http://dali.havefunace.top/Article/details/gthhblnere.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtcsmamrfz.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtulcqaorw.html

Py:   def greet(self): return self.name
来源：http://dali.jqgufenzy.top/Article/details/gtjeemndkd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gtazfwxaup.html

JS:   greet() { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gtyezondtf.html

TS:   greet(): string { return this.name; }
来源：http://dali.cheryme.top/Article/details/gtyxroshig.html

Java: String greet() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtusbksgem.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gtgmbjanmz.html

Ruby: def greet; @name; end
来源：http://dali.havefunace.top/Article/details/gtgwhwnpbc.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gtbsmtjjps.html

[G05] 继承
来源：http://dali.yj20258.top/Article/details/gtdiqaswql.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gtxbyvgwkj.html

PHP:  class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtjxnisowz.html

JS:   class Admin extends User {}
来源：http://dali.chenzaomai.com/Article/details/gtasucjsrj.html

TS:   class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gtjuthtoqk.html

Java: class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gtlmnhkteu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gtotoijzmb.html

Ruby: class Admin < User; end
来源：http://dali.hfpthk.cn/Article/details/gtkxsvwdvb.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gtrkyaepul.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gtrtnobtgg.html

Py:   def greet(self): return "admin"
来源：http://dali.yuxming.cn/Article/details/gtppsnwpyq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gtuutlxwjr.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gtfnsvxvft.html

TS:   greet(): string { return "admin"; }
来源：http://dali.snrcjt.cn/Article/details/gtequlbhty.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gtlymftkky.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gtdbtfmtdm.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtndlmzinu.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxinkj.top/Article/details/gtzmmcswwc.html

[G07] 调用父类方法
来源：http://dali.ppjwa.cn/Article/details/gtzjzyxbik.html

Py:   super().greet()
来源：http://dali.iojbl.cn/Article/details/gtkjuyefmv.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gthxzntuhu.html

JS:   super.greet();
来源：http://dali.kuanghao11.cn/Article/details/gtbpvswgho.html

TS:   super.greet();
来源：http://dali.yangfankeji.com/Article/details/gttlcmimoz.html

Java: super.greet();
来源：http://dali.cheryme.top/Article/details/gtngyzbaby.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtxvbsqosu.html

Ruby: super
来源：http://dali.316326.xyz/Article/details/gturlnwwku.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gtrlgmlssz.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gtvqeywwsu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gtmoclmnac.html

PHP:  public static function f() {}
来源：http://dali.chenzaomai.com/Article/details/gtkkexrgdx.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtlvryfbij.html

TS:   static f(): void {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtstdgedyy.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtmgbrlaas.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtjotffvhp.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvdqecek.html

C#:   public static void F() {}
来源：http://dali.fengsongda.top/Article/details/gtzlcpikvy.html

[G09] 接口 / 抽象类
来源：http://dali.zhoulong.xyz/Article/details/gtiiyfkawx.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtdrgtnlmi.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gogol.net.cn/Article/details/gtikqmwdcu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.fzhhl.top/Article/details/gtqvjyilzi.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtkkmnhlhq.html

Java: interface Shape { double area(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmftfhbi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhongyouzk.top/Article/details/gtuukugcgc.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gotoacloud.top/Article/details/gtpcuwneku.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gtteylcklo.html

[G10] 访问控制
来源：http://dali.zdqjudy.top/Article/details/gttesebftx.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shangyingyoupin.top/Article/details/gtbrfcavct.html

PHP:  public / protected / private
来源：http://dali.iojbl.cn/Article/details/gtjfrcuwwr.html

JS:   #private 字段；其余公开
来源：http://dali.xinyue.icu/Article/details/gtglhdhnku.html

TS:   public / protected / private
来源：http://dali.sysykeji.top/Article/details/gtjnxloeks.html

Java: public / protected / private / 默认包级
来源：http://dali.shangyingyoupin.top/Article/details/gtsxizlevt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xziqi.cn/Article/details/gtrhnypcmu.html

Ruby: public / protected / private
来源：http://dali.jinqigfzy.top/Article/details/gtahyjezdh.html

C#:   public / protected / private / internal
来源：http://dali.zdqjudy.top/Article/details/gttmyxomft.html

[G11] getter / setter
来源：http://dali.daxiang520.top/Article/details/gtkgyzcuqu.html

Py:   @property 与 @x.setter
来源：http://dali.tian-w.cn/Article/details/gtbhvtmjks.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gtasbiqynz.html

JS:   get name() { return this._name; }
来源：http://dali.snrcjt.cn/Article/details/gtflgusfxv.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gtapntniub.html

Java: public String getName() { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtgsmdzqtn.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtfqbjphmh.html

Ruby: attr_accessor :name
来源：http://dali.yangfankeji.com/Article/details/gtwngvjukp.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtfbnpnkzu.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtuawkdtzv.html

Py:   def __str__(self): return self.name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuwmmtxz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gtlckerebl.html

JS:   toString() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gtugjesfov.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnxiangtu.top/Article/details/gtazpoxwqw.html

Java: @Override public String toString() { return name; }
来源：http://dali.jianghu66.top/Article/details/gtwdjpajpa.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xylfe.cn/Article/details/gtbmsevjwm.html

Ruby: def to_s; @name; end
来源：http://dali.cheryme.top/Article/details/gtxxlpddhx.html

C#:   public override string ToString() => Name;
来源：http://dali.hfpthk.cn/Article/details/gtgdhyzbon.html

[G13] 判断对象类型
来源：http://dali.zhijiandao.cn/Article/details/gtnwyxwgsp.html

Py:   isinstance(u, User)
来源：http://dali.feifeiyinyue.top/Article/details/gtksvsffvs.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gtzkwkgsnc.html

JS:   u instanceof User
来源：http://dali.yj202588.top/Article/details/gtuwttdgje.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtdtmivmhz.html

Java: u instanceof User
来源：http://dali.fengsongda.top/Article/details/gtdmmoyuww.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.zhiwuduotai.top/Article/details/gtuqwzlkvk.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtkzhpugci.html

C#:   u is User
来源：http://dali.zhiwuduotai.top/Article/details/gtcgkyshns.html

[G14] 数据类 / record
来源：http://dali.zycfv.cn/Article/details/gtpcwqgfux.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.tanke756.top/Article/details/gtbqinuxsw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tanke756.top/Article/details/gterqwwjci.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jianghu66.top/Article/details/gtllqqgyzo.html

TS:   type User = { name: string; age: number };
来源：http://dali.nwbrower.top/Article/details/gtzvxfzpdf.html

Java: record User(String name, int age) {}
来源：http://dali.316326.xyz/Article/details/gtrgcyurwi.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuanzx.com/Article/details/gtplsskvuq.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hfpthk.cn/Article/details/gtjzxklhha.html

C#:   record User(string Name, int Age);
来源：http://dali.xuetiantiany.cn/Article/details/gtltffbbcv.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gtcmkandzj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jlsjyb.cn/Article/details/gtlbzrvtkc.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.bjfxy.top/Article/details/gtjumkhirm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhyicsai.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtqfbbkjzb.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangdashe.top/Article/details/gtugzottlh.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.daxiang520.top/Article/details/gtrafnwwxo.html

Ruby: Color = %i[red green].freeze
来源：http://dali.meibo888.top/Article/details/gtykiahnjf.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtjacoqhyk.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkwzbjuo.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.shuidangran.top/Article/details/gtjodvqxer.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gtlsryvgpy.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtjbbxiqtb.html

TS:   Object.entries(obj)
来源：http://dali.sysykeji.top/Article/details/gtqmosgupt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.mhx1999.top/Article/details/gtaulrtiur.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhixingplan.top/Article/details/gtafwxfgql.html

Ruby: obj.instance_variables
来源：http://dali.xuetiantiany.cn/Article/details/gtncwqmysd.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gttuozmefb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvilzhczi.html

H. 异常与错误处理
来源：http://dali.jiagoushi.top/Article/details/gtkhsxpqwu.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtbojiyvjj.html

[H01] try / catch 基础
来源：http://dali.guowangkeji.top/Article/details/gtscwukgkz.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hysaishi.cn/Article/details/gtqcyqagzy.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shangyingyoupin.top/Article/details/gtqdksnyfx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppmlggnj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ehwqpu.com/Article/details/gtfmgvkmiv.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yanxiufei.cn/Article/details/gtbbmusfph.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtrjbezxjf.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhongyouzk.top/Article/details/gteotqsdri.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.birdmap.top/Article/details/gtifoexhsd.html

[H02] finally / ensure 收尾
来源：http://dali.sweek.top/Article/details/gtrhuyhcef.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hammf.cn/Article/details/gtrwunczef.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtftcgeoxf.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gturuxyfvq.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhengqikj.top/Article/details/gtdecrgipp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtnrcddura.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.gaohongyu789.top/Article/details/gtcaorzpwu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.snrcjt.cn/Article/details/gtuorfqyss.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gtxgmiynde.html

[H03] 主动抛出异常
来源：http://dali.ybcxt.top/Article/details/gttwbualnw.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhengqikj.top/Article/details/gtefhjcxkh.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jiagoushi.top/Article/details/gtvyzaaalb.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtgnaoefyd.html

TS:   throw new Error("错误信息");
来源：http://dali.yonumen.top/Article/details/gtwcmpfjmp.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.ppjwa.cn/Article/details/gtkxyzkftf.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.yj202588.top/Article/details/gthvpfypcb.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hnqzz.top/Article/details/gtsmyszjam.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gtyhpqxnqu.html

[H04] 自定义异常类型
来源：http://dali.316326.xyz/Article/details/gtcwovnert.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gtzgvuwddo.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtdshqmhqo.html

JS:   class MyError extends Error {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzjlxeeh.html

TS:   class MyError extends Error {}
来源：http://dali.zdqjudy.top/Article/details/gtcewjtcdd.html

Java: class MyException extends RuntimeException {}
来源：http://dali.aizwys.cn/Article/details/gtyzxmtbev.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.gaohongyu789.top/Article/details/gtebqkpgov.html

Ruby: class MyError < StandardError; end
来源：http://dali.jqgufenzy.top/Article/details/gtrkqgqasp.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtmcbzqqxb.html

[H05] 捕获特定类型
来源：http://dali.hnqzz.top/Article/details/gtjpcdococ.html

Py:   except ValueError as e:
来源：http://dali.tianlin.xyz/Article/details/gtmeewpsve.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.aibaodan.cn/Article/details/gtghgqumjl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.fzhhl.top/Article/details/gttxgioppm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zhongyouzk.top/Article/details/gtjzhpfdon.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tianlin.xyz/Article/details/gtfpaobyqg.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.ydzc1.top/Article/details/gttinnotmi.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gthlklohfx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.dashuyun.cn/Article/details/gtpzkzjtks.html

[H06] 可选值 / 空值安全访问
来源：http://dali.havefunace.top/Article/details/gtcvisazkw.html

Py:   value = d.get("k") or default
来源：http://dali.bjfxy.top/Article/details/gtrgucdmsr.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.chenzaomai.com/Article/details/gtjmcqljor.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtgftggokd.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtwnxabmsv.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.cheryme.top/Article/details/gtnfgmedbf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.iojbl.cn/Article/details/gtbdcsbdkw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hnqzz.top/Article/details/gtcrjuoyno.html

C#:   obj?.A?.B ?? default
来源：http://dali.cqqwz.cn/Article/details/gtcbgpiedz.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gtbssgktxs.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gtczeowfhm.html

PHP:  assert($x > 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtknkhmiwn.html

JS:   console.assert(x > 0);
来源：http://dali.zhongyouzk.top/Article/details/gtjtakswef.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtwpvtctcr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.9152youxi.cn/Article/details/gtghvytrzj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.guowangkeji.top/Article/details/gtasxiyadq.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.gogol.net.cn/Article/details/gtlkqyesuv.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtijomdxwi.html

[H08] 获取错误信息与堆栈
来源：http://dali.chenzaomai.com/Article/details/gtjtlrckex.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrjxiowu.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gtihainvvv.html

JS:   e.message;  e.stack
来源：http://dali.jinqigufen.top/Article/details/gturwzndft.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.iojbl.cn/Article/details/gtenvhvunv.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.daxiang520.top/Article/details/gtnqebijjv.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncxaupxn.html


<!-- 参考信息 -->