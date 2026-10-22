代发 wailian999

[F05] 判断文件或目录是否存在
来源：http://dali.chenlongwang.top/Article/details/gtcxxhndxe.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtlzcxflhe.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtzyocuhve.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gtxzyidnkm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtgifolpvl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtmsuhwsxn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.andypj.xyz/Article/details/gthxyuvhtc.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtqjlqztzh.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gthmxcwuxg.html

[F06] 删除文件
来源：http://dali.shangyingyoupin.top/Article/details/gtowqrmwov.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtppgxyulz.html

PHP:  unlink("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtsrmuzmjp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtggxeycfq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtzkoezdma.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtlgrwjcqo.html

Go:   os.Remove("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtnqawshpx.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtjkovvgim.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtyawsaaqk.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtpxhdcrxp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xziqi.cn/Article/details/gtjadyjirp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtilgibtcm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gtiyaidrib.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtsxfwuedt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigfzy.top/Article/details/gtlhprvtqu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sufxvd.cn/Article/details/gtjnypurip.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fengsongda.top/Article/details/gtvahkhsdl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuanzhike.top/Article/details/gtandaoety.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnpbwrle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuanzx.com/Article/details/gtudsxnjia.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtqrxrpysq.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gtqgvhvdgo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtjkgzlwbk.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtjoijsyng.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hnqzz.top/Article/details/gtjitglcdw.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gtgrprxqrm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtvvjpwxtl.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gteyzalhrd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyfygdmkt.html

PHP:  filesize("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gtrazlfjbl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.9152youxi.cn/Article/details/gtcjtwyqwl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuanyybxc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gthokaqelf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.fengsongda.top/Article/details/gtevtmfape.html

Ruby: File.size("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxmxfxsqu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xziqi.cn/Article/details/gtzqvghaww.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gtjipmlgbn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtvbdbjxuy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtqrpodugg.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtyvzrjcdj.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtmpuzhzjf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuanzhike.top/Article/details/gtxovwckfh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtjqssygjv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtylmklela.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtmruddloz.html

[F11] 复制与移动文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrruubspl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtehqbihvx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yangfankeji.com/Article/details/gtzqpjvjga.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cashguo.top/Article/details/gtdqelrdbn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtkflyinyy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtuctyxely.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gttnrindmh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrxzfyrfb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yueranfly.top/Article/details/gtnxfspsft.html

[F12] CSV 读写
来源：http://dali.xuetiantiany.cn/Article/details/gtkhnkqerb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gaohongyu789.top/Article/details/gtvizdtiij.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gtxtjrzqzi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daria6918.cn/Article/details/gtnmxmoeya.html

TS:   // 同上
来源：http://dali.yj20258888.top/Article/details/gtvnqaaozc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.haohaochexian.top/Article/details/gtplvqbuce.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdfmlotk.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtgfdthjsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gtwlhkmwnk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtwaslquxr.html

G. 面向对象
来源：http://dali.shzxlz.cn/Article/details/gtekdgaygf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtnscpxpsb.html

[G01] 定义类
来源：http://dali.zhijiandao.cn/Article/details/gthvdwfgpx.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gtdwfckpav.html

PHP:  class User {}
来源：http://dali.dianchejie.cn/Article/details/gtcilutcth.html

JS:   class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbyizlhl.html

TS:   class User { name: string = ""; }
来源：http://dali.haohaochexian.top/Article/details/gtoqcsnzri.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtnwlxofoc.html

Go:   type User struct { Name string }
来源：http://dali.dashuyun.cn/Article/details/gtdbwfcfem.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gtxljoovev.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmjlnzvn.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtddetvahr.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtnsrrdfld.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cucudq.cn/Article/details/gtteaqiyvu.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.mhx1999.top/Article/details/gtzscifkix.html

TS:   constructor(public name: string) {}
来源：http://dali.hfpthk.cn/Article/details/gtqcwuihyf.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjzqpwcj.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gtkcsgbgec.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.nanxuanxn.top/Article/details/gtapmfajmg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.vqdsnc.cn/Article/details/gtzxinstax.html

[G03] 实例属性
来源：http://dali.meibo888.top/Article/details/gtsfnomhai.html

Py:   self.name = "x"
来源：http://dali.cucudq.cn/Article/details/gtswyhbmqg.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtypfdaduf.html

JS:   this.name = "x";
来源：http://dali.mhx1999.top/Article/details/gtadgigjes.html

TS:   name: string = "x";
来源：http://dali.mhx1999.top/Article/details/gtkznkqskb.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gtykljusmp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sufxvd.cn/Article/details/gtmohzyzwx.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtvpbcjekn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtkagllmtd.html

[G04] 定义方法
来源：http://dali.yangfankeji.com/Article/details/gtximruenj.html

Py:   def greet(self): return self.name
来源：http://dali.zhengqikj.top/Article/details/gtougwecal.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.guannengcc.top/Article/details/gtldtllfhl.html

JS:   greet() { return this.name; }
来源：http://dali.daxiang520.top/Article/details/gtbqplzqtq.html

TS:   greet(): string { return this.name; }
来源：http://dali.gzhubu.top/Article/details/gtkyplpfqd.html

Java: String greet() { return name; }
来源：http://dali.sysykeji.top/Article/details/gtupcwcplh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zycfv.cn/Article/details/gtkqwvklfg.html

Ruby: def greet; @name; end
来源：http://dali.aizwys.cn/Article/details/gtfvqlpoes.html

C#:   public string Greet() => Name;
来源：http://dali.gzhubu.top/Article/details/gtwwpghetx.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gtfmnwidbr.html

Py:   class Admin(User): pass
来源：http://dali.zhongyouzk.top/Article/details/gtcddcwlut.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjarrpqnc.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gtxxypxoiq.html

TS:   class Admin extends User {}
来源：http://dali.zhijiandao.cn/Article/details/gttivfeegs.html

Java: class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gtdgscxicu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.redwolf501.top/Article/details/gtlbrprcsm.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gtbrpkkdhm.html

C#:   class Admin : User {}
来源：http://dali.zhoulong.xyz/Article/details/gtatguzefm.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gtafdfxtze.html

Py:   def greet(self): return "admin"
来源：http://dali.svipenyu.cn/Article/details/gtryxpacrp.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxnoaofw.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtntuhmulb.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gtmmgpbyxq.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.guannengcc.top/Article/details/gtqpxfrzcn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.havefunace.top/Article/details/gtdnnusmdm.html

Ruby: def greet; "admin"; end
来源：http://dali.shangyingyoupin.top/Article/details/gtxexsfqmr.html

C#:   public override string Greet() => "admin";
来源：http://dali.andypj.xyz/Article/details/gtvqaoccbi.html

[G07] 调用父类方法
来源：http://dali.chenlongwang.top/Article/details/gtubokfjbc.html

Py:   super().greet()
来源：http://dali.0kj1m.cn/Article/details/gtbrhvxdff.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gtqagbxmls.html

JS:   super.greet();
来源：http://dali.yj202588.top/Article/details/gtbvayvjwm.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gtwxsqhlfq.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqdpxahpf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtsydtzjla.html

Ruby: super
来源：http://dali.yj20258888.top/Article/details/gtcqaaeelf.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gtrosjcujq.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gtzugslcrn.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gtkbhvpzmp.html

PHP:  public static function f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyfwmozw.html

JS:   static f() {}
来源：http://dali.xylfe.cn/Article/details/gtqrpkzawj.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gtipgkygks.html

Java: static void f() {}
来源：http://dali.xylfe.cn/Article/details/gtfevhldoa.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.nanxinkj.top/Article/details/gtdqrspkzt.html

Ruby: def self.f; end
来源：http://dali.quarkkingdee.top/Article/details/gtcgvyyswc.html

C#:   public static void F() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjanhywyw.html

[G09] 接口 / 抽象类
来源：http://dali.gzhubu.top/Article/details/gtsgiaryxy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sysykeji.top/Article/details/gtwhiijntc.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gtukpfoacp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gtohrrelsm.html

TS:   interface Shape { area(): number; }
来源：http://dali.cdnleiting.top/Article/details/gtaknojzzv.html

Java: interface Shape { double area(); }
来源：http://dali.xuanzx.com/Article/details/gtbkekpjru.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jiagoushi.top/Article/details/gtuuphtxnw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xinyue.icu/Article/details/gtbqxnlmea.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtvppteooo.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtbhonszpq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.snrcjt.cn/Article/details/gtiqxdypth.html

PHP:  public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gthamqewvm.html

JS:   #private 字段；其余公开
来源：http://dali.hammf.cn/Article/details/gtlqoxinwr.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gtgkwafhbz.html

Java: public / protected / private / 默认包级
来源：http://dali.jianghu66.top/Article/details/gtlkuggygg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenzaomai.com/Article/details/gtumrpaotm.html

Ruby: public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gtofekixvx.html

C#:   public / protected / private / internal
来源：http://dali.sweek.top/Article/details/gtrzyeowkx.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gtmqspwrzo.html

Py:   @property 与 @x.setter
来源：http://dali.kuanghao11.cn/Article/details/gtcauzuvbf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gtpvzevrby.html

JS:   get name() { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gtxpavlnqk.html

TS:   get name(): string { return this._name; }
来源：http://dali.xuanzx.com/Article/details/gthbavjkod.html

Java: public String getName() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gtvzicbytq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gtcugmkjbd.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gtvdcaipqi.html

C#:   public string Name { get; set; }
来源：http://dali.svipenyu.cn/Article/details/gtiydxogkd.html

[G12] 对象转字符串
来源：http://dali.wangdashe.top/Article/details/gtkfzsjbeu.html

Py:   def __str__(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtbufiexrp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtraekukuj.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexpqvjub.html

TS:   toString(): string { return this.name; }
来源：http://dali.daria6918.cn/Article/details/gtrlojixzv.html

Java: @Override public String toString() { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtgndtglah.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.c1oappe.top/Article/details/gtqqwiipud.html

Ruby: def to_s; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtgqifplmz.html

C#:   public override string ToString() => Name;
来源：http://dali.andypj.xyz/Article/details/gtxndrwspj.html

[G13] 判断对象类型
来源：http://dali.c1oappe.top/Article/details/gtkayvczac.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtzxtswaci.html

PHP:  $u instanceof User
来源：http://dali.chenlongwang.top/Article/details/gtdzfmzxru.html

JS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtrhlkqzrz.html

TS:   u instanceof User
来源：http://dali.zhoulong.xyz/Article/details/gtbgeujvse.html

Java: u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gtadkdwkpo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hfpthk.cn/Article/details/gthvpgksew.html

Ruby: u.is_a?(User)
来源：http://dali.redwolf501.top/Article/details/gtcbqukfsr.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtpqtmbiia.html

[G14] 数据类 / record
来源：http://dali.cashguo.top/Article/details/gteerbvjbu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.haohaochexian.top/Article/details/gtbzmojttw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.quarkkingdee.top/Article/details/gtqudzaubf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fengsongda.top/Article/details/gtxebhcsjo.html

TS:   type User = { name: string; age: number };
来源：http://dali.haohaochexian.top/Article/details/gthnmwdsbu.html

Java: record User(String name, int age) {}
来源：http://dali.daxiang520.top/Article/details/gthmcvpbrf.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gthmyvnjea.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtywlytylf.html

C#:   record User(string Name, int Age);
来源：http://dali.xuanzx.com/Article/details/gtodqtctcy.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gtioukhtrs.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tian-w.cn/Article/details/gtkxceytqs.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yangfankeji.com/Article/details/gtwtlytzln.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.dianchejie.cn/Article/details/gtpfhplfqh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.meibo888.top/Article/details/gtswjckzcp.html

Java: enum Color { RED, GREEN }
来源：http://dali.yuanzhike.top/Article/details/gtrvvzagtr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.xuanzx.com/Article/details/gtghzldnzu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jqgufenzy.top/Article/details/gtqfchlnmo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yangfankeji.com/Article/details/gthzyghwwh.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gtinzvrour.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.meibo888.top/Article/details/gtycduvxay.html

PHP:  get_object_vars($obj);
来源：http://dali.yonumen.top/Article/details/gtueepcycy.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtlzjqzhbk.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gtmkzshhyp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrmmxuec.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtgsafrcvr.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtinndclqt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gtzjaqwszf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtozglsilm.html

H. 异常与错误处理
来源：http://dali.cqqwz.cn/Article/details/gthsqdklhd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtebsvajfg.html

[H01] try / catch 基础
来源：http://dali.jqgufenzy.top/Article/details/gtjxiuebof.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jqgfzy.top/Article/details/gtjvaqikhp.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.birdmap.top/Article/details/gtnnfzfiiu.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yanxiufei.cn/Article/details/gtqzkcrods.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtmnxeitqa.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guowangkeji.top/Article/details/gtelctarfr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ydzc1.top/Article/details/gtulvpsngs.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.sxryk.cn/Article/details/gtnqmcfntz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gtpsfqacio.html

[H02] finally / ensure 收尾
来源：http://dali.gotoacloud.top/Article/details/gtnkmrlveb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.dianchejie.cn/Article/details/gtreuainpy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtaotcfroh.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtsiiyphvx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hysaishi.cn/Article/details/gtjekintnw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtxaqxjstw.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.meibo888.top/Article/details/gtjvnauyov.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.316326.xyz/Article/details/gthqelxrrc.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gtomtcigou.html

[H03] 主动抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtpyqtsxuy.html

Py:   raise ValueError("错误信息")
来源：http://dali.zhiwuduotai.top/Article/details/gtstavpzdy.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtykowspja.html

JS:   throw new Error("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gtnozvbcmf.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gtaeecmtoz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj20258.top/Article/details/gtfvzsttni.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.cdnleiting.top/Article/details/gtdhcvlskj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.9152youxi.cn/Article/details/gtorvyschp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cucudq.cn/Article/details/gtxxqjmhik.html

[H04] 自定义异常类型
来源：http://dali.smart0.xyz/Article/details/gtcvwdtola.html

Py:   class MyError(Exception): pass
来源：http://dali.yongpay.top/Article/details/gtrkcpmcvr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.bjfxy.top/Article/details/gtojzdvzea.html

JS:   class MyError extends Error {}
来源：http://dali.daria6918.cn/Article/details/gtmjrmnqqw.html

TS:   class MyError extends Error {}
来源：http://dali.gzhubu.top/Article/details/gtuaqlaycg.html

Java: class MyException extends RuntimeException {}
来源：http://dali.andypj.xyz/Article/details/gtdlmlrkxh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.kuanghao11.cn/Article/details/gtujlryuwd.html

Ruby: class MyError < StandardError; end
来源：http://dali.yangfankeji.com/Article/details/gtrinimcgz.html

C#:   class MyException : Exception {}
来源：http://dali.cucudq.cn/Article/details/gtdxyuznqr.html

[H05] 捕获特定类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbxbhjkb.html

Py:   except ValueError as e:
来源：http://dali.kuanghao11.cn/Article/details/gtrqnwpiui.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zhongyouzk.top/Article/details/gtkiiaczbl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yuxming.cn/Article/details/gtgqmrphla.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.zycfv.cn/Article/details/gtooyhxxww.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjlaaxedm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guowangkeji.top/Article/details/gtoeghewqz.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gtkbmduilz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbfjhxwj.html

[H06] 可选值 / 空值安全访问
来源：http://dali.birdmap.top/Article/details/gtpkbvudnu.html

Py:   value = d.get("k") or default
来源：http://dali.daria6918.cn/Article/details/gtpmjbxbpv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.ivvv.top/Article/details/gtghbygaup.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.yj202588.top/Article/details/gtvbthtzcb.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.hywenlv.cn/Article/details/gtdbkflfbe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shuidangran.top/Article/details/gtoymngjgf.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cqqwz.cn/Article/details/gtxarieegg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.nwbrower.top/Article/details/gtmzarvczq.html

C#:   obj?.A?.B ?? default
来源：http://dali.hfpthk.cn/Article/details/gtgisyfdqb.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gttaafhwsx.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cashguo.top/Article/details/gtftivrdpy.html

PHP:  assert($x > 0);
来源：http://dali.pycfn.com/Article/details/gtmbrsvxep.html

JS:   console.assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gtrtlhudet.html

TS:   console.assert(x > 0);
来源：http://dali.quarkkingdee.top/Article/details/gtgwgzxfoj.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jlsjyb.cn/Article/details/gtsvsmxteb.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hnqzz.top/Article/details/gtncnrqbpm.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yuanzhike.top/Article/details/gtawqzfhdu.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cashguo.top/Article/details/gtubtexmex.html

[H08] 获取错误信息与堆栈
来源：http://dali.zhengqikj.top/Article/details/gtzouzbwsx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.hnxiangtu.top/Article/details/gtchhyerof.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.0kj1m.cn/Article/details/gtxghovvzl.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gttenkvfkd.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.cucudq.cn/Article/details/gtlvbhlcnp.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.pengpengdd.cyou/Article/details/gtfgbfwpaj.html

Go:   err.Error()
来源：http://dali.chenzaomai.com/Article/details/gtxdaeegth.html

Ruby: e.message;  e.backtrace
来源：http://dali.jianghu66.top/Article/details/gtbidipgqh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.tianlin.xyz/Article/details/gtrzwfkwmg.html

[H09] 带错误码的异常
来源：http://dali.zhongyouzk.top/Article/details/gtkazzikwk.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.zhiwuduotai.top/Article/details/gttlhztjfg.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.0kj1m.cn/Article/details/gtoqqjopyd.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.zhoulong.xyz/Article/details/gtvjxabxoj.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gtvnwonbpt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytdgarxs.html


<!-- 参考信息 -->