代发 wailian999

TS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2kwobcrit.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gt2alfdwsyk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gcvdspgi.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2mhroymjw.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2ekbxyymt.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2btejwvjz.html

Py:   os.remove("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2fphspelh.html

PHP:  unlink("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2nhskeqfn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2uspoqptm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2oibhqtjy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2wndxawbv.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2gktikmqn.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2jqndxqlb.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2pwwinppv.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2xfqvnwzu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2caldvgyd.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.iojbl.cn/Article/details/gt2djusiphy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zdqjudy.top/Article/details/gt2kfdnnieg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mnumczgc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.fzhhl.top/Article/details/gt2etopgnxp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yueranfly.top/Article/details/gt2deqsokpa.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2vssmxsgf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jiagoushi.top/Article/details/gt2lelnxeic.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gt2uqdktgtz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yanxiufei.cn/Article/details/gt2kqggklcn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qupbbrxm.html

JS:   fs.readdirSync("dir")
来源：http://dali.aizwys.cn/Article/details/gt2qnzbpngv.html

TS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gt2pzrvhpum.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jianghu66.top/Article/details/gt2zfsptvgu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2nobacgje.html

Ruby: Dir.children("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ivxnitcj.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2ovkvqrnj.html

[F09] 获取文件大小
来源：http://dali.ivvv.top/Article/details/gt2foxcybxw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2purexqkw.html

PHP:  filesize("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2gfplzlmx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2iquxrksy.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258.top/Article/details/gt2tiruerbh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2qsepcjco.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jiagoushi.top/Article/details/gt2glhmomfa.html

Ruby: File.size("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2xzdehnak.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gt2wdfowrzo.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gt2caxzjnby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2vbvchsjg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qareknvo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2djywosjb.html

TS:   path.extname("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2njiezeqj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgufenzy.top/Article/details/gt2cxeqwtbu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2zbxfkypm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jigkggxv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ffmvjqoc.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2xilastsm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ikgmgmgk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2hvrfhczf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2qztwclab.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gt2jlwgsuby.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gt2reqarkvv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.nanxuanxn.top/Article/details/gt2ufedkemw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2spatisav.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.wangdashe.top/Article/details/gt2fkezvoxp.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2ouomtusn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gt2ktjnfqed.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvybhjvs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2qtdjeujh.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2drmbzrgh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2piypmnyv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gt2dahevwgf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.tanke756.top/Article/details/gt2flcaonvs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioofhfmq.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2afrjnkbn.html

G. 面向对象
来源：http://dali.dianchejie.cn/Article/details/gt2qdykoovk.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzvzegzu.html

[G01] 定义类
来源：http://dali.wangshuangyany.cn/Article/details/gt2pnzpcwmt.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2btxbrjxo.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2ymprqcqd.html

JS:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2gobxdbzn.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2dfldfdaq.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gt2fxqxhhsp.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2pmjfgsds.html

Ruby: class User; end
来源：http://dali.ydzc1.top/Article/details/gt2bisgnsmn.html

C#:   class User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2skxjvsbm.html

[G02] 构造函数
来源：http://dali.zhixingplan.top/Article/details/gt2wopdbfre.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cucudq.cn/Article/details/gt2sxmxdqma.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ehwqpu.com/Article/details/gt2kawbfsnn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gt2vlwludxx.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2fjmpmwjx.html

Java: User(String name) { this.name = name; }
来源：http://dali.daxiang520.top/Article/details/gt2iixcvhqi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zycfv.cn/Article/details/gt2swehianj.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujpfeohj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2augftnwq.html

[G03] 实例属性
来源：http://dali.hfpthk.cn/Article/details/gt2gyburykz.html

Py:   self.name = "x"
来源：http://dali.ehwqpu.com/Article/details/gt2clvivpog.html

PHP:  public string $name = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2aemwacvx.html

JS:   this.name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2qdgzohiz.html

TS:   name: string = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2xwqpizst.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2pujfghuk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jiagoushi.top/Article/details/gt2fqdqhipn.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2vewwgqay.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.9152youxi.cn/Article/details/gt2ymvnwjra.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2gaeebccu.html

Py:   def greet(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gt2wougqowd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tctiissz.html

JS:   greet() { return this.name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wtrllkgw.html

TS:   greet(): string { return this.name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bddcspct.html

Java: String greet() { return name; }
来源：http://dali.yuxming.cn/Article/details/gt2xhtflarh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gt2yhnccxjf.html

Ruby: def greet; @name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adwdmqyg.html

C#:   public string Greet() => Name;
来源：http://dali.gotoacloud.top/Article/details/gt2zedwxfzh.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnmjdxcj.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gt2zqsryygk.html

PHP:  class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2zrcvrfxm.html

JS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gajeuymz.html

TS:   class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2mrqiuoxw.html

Java: class Admin extends User {}
来源：http://dali.ehwqpu.com/Article/details/gt2jhqyfndk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhengqikj.top/Article/details/gt2wsjvhyqy.html

Ruby: class Admin < User; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyyukxsp.html

C#:   class Admin : User {}
来源：http://dali.chenlongwang.top/Article/details/gt2bgcuaevr.html

[G06] 重写方法
来源：http://dali.316326.xyz/Article/details/gt2jeptxbrm.html

Py:   def greet(self): return "admin"
来源：http://dali.jiagoushi.top/Article/details/gt2gcuiybyg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vejlwioo.html

JS:   greet() { return "admin"; }
来源：http://dali.316326.xyz/Article/details/gt2dwfskizj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vnjttlpd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cgrrdvwd.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yonumen.top/Article/details/gt2lrlakcha.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2ijbyrstm.html

C#:   public override string Greet() => "admin";
来源：http://dali.guowangkeji.top/Article/details/gt2osbockbj.html

[G07] 调用父类方法
来源：http://dali.sysykeji.top/Article/details/gt2arjduryq.html

Py:   super().greet()
来源：http://dali.quarkkingdee.top/Article/details/gt2zclymgpm.html

PHP:  parent::greet();
来源：http://dali.yuxming.cn/Article/details/gt2ulwkxvrr.html

JS:   super.greet();
来源：http://dali.wangshuangyany.cn/Article/details/gt2plqdliib.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2jjeekwpl.html

Java: super.greet();
来源：http://dali.redwolf501.top/Article/details/gt2apsigubc.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gt2vztiowmv.html

Ruby: super
来源：http://dali.andypj.xyz/Article/details/gt2iucilvcl.html

C#:   base.Greet();
来源：http://dali.yueranfly.top/Article/details/gt2ulvgnbod.html

[G08] 静态方法与属性
来源：http://dali.cheryme.top/Article/details/gt2adodmzon.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2ciihkwps.html

PHP:  public static function f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tszlsmmj.html

JS:   static f() {}
来源：http://dali.yuxming.cn/Article/details/gt2nnapnprz.html

TS:   static f(): void {}
来源：http://dali.xziqi.cn/Article/details/gt2fxibkgof.html

Java: static void f() {}
来源：http://dali.chenlongwang.top/Article/details/gt2ulpcxcip.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangdashe.top/Article/details/gt2tbfvqgzc.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gt2xjawsoku.html

C#:   public static void F() {}
来源：http://dali.ydzc1.top/Article/details/gt2yzzrpmgp.html

[G09] 接口 / 抽象类
来源：http://dali.redwolf501.top/Article/details/gt2awdtykvb.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.sufxvd.cn/Article/details/gt2furpqhog.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shzxlz.cn/Article/details/gt2sdmgqkwg.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2hvzowszo.html

TS:   interface Shape { area(): number; }
来源：http://dali.yuxming.cn/Article/details/gt2lpilsxva.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gt2sjgoupgw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfodcwkm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gt2yooedkrj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shuidangran.top/Article/details/gt2vowmrwxq.html

[G10] 访问控制
来源：http://dali.zhongyouzk.top/Article/details/gt2bwlgqzkq.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2erlnwibi.html

PHP:  public / protected / private
来源：http://dali.aibaodan.cn/Article/details/gt2dzmglopa.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gt2wtsaalcb.html

TS:   public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2mdfsfuse.html

Java: public / protected / private / 默认包级
来源：http://dali.tianlin.xyz/Article/details/gt2prsexlbp.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.havefunace.top/Article/details/gt2xmywqfxq.html

Ruby: public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2jgopcjxe.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gt2zcpcxzfw.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2tshkdnae.html

Py:   @property 与 @x.setter
来源：http://dali.hnqzz.top/Article/details/gt2sjwywzqt.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2lwwfnlbd.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gt2wsyyblnn.html

TS:   get name(): string { return this._name; }
来源：http://dali.bjfxy.top/Article/details/gt2lgzenbyo.html

Java: public String getName() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2wmepppiy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.9152youxi.cn/Article/details/gt2lmqmilgr.html

Ruby: attr_accessor :name
来源：http://dali.jinqigufen.top/Article/details/gt2qwbemtyy.html

C#:   public string Name { get; set; }
来源：http://dali.cdnleiting.top/Article/details/gt2asqlhwxs.html

[G12] 对象转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2cwkjtmbg.html

Py:   def __str__(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2zitnxsmw.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2khtmzvic.html

JS:   toString() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpokarrp.html

TS:   toString(): string { return this.name; }
来源：http://dali.yonumen.top/Article/details/gt2kfnjyoou.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cszumyva.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.redwolf501.top/Article/details/gt2pzndrsso.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2ssltgiwx.html

C#:   public override string ToString() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2odlvrfla.html

[G13] 判断对象类型
来源：http://dali.jiagoushi.top/Article/details/gt2kzregepo.html

Py:   isinstance(u, User)
来源：http://dali.pycfn.com/Article/details/gt2txipivvm.html

PHP:  $u instanceof User
来源：http://dali.cucudq.cn/Article/details/gt2uoaguupz.html

JS:   u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uitcrlsl.html

TS:   u instanceof User
来源：http://dali.yuanzhike.top/Article/details/gt2eszhhluk.html

Java: u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2oswlkndn.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.gaohongyu789.top/Article/details/gt2wtsqbhtj.html

Ruby: u.is_a?(User)
来源：http://dali.hywenlv.cn/Article/details/gt2bdbwyqir.html

C#:   u is User
来源：http://dali.xuanzx.com/Article/details/gt2ncmrnkwv.html

[G14] 数据类 / record
来源：http://dali.gotoacloud.top/Article/details/gt2psnilrzj.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ehwqpu.com/Article/details/gt2pwxouexv.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.cucudq.cn/Article/details/gt2bducmbzo.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.fzhhl.top/Article/details/gt2tgnpqjvs.html

TS:   type User = { name: string; age: number };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oovusfgx.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vcvewsir.html

Go:   type User struct { Name string; Age int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvqecbot.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hysaishi.cn/Article/details/gt2oygpyeol.html

C#:   record User(string Name, int Age);
来源：http://dali.yj202588.top/Article/details/gt2ulgagllc.html

[G15] 枚举
来源：http://dali.bjfxy.top/Article/details/gt2aajkhebk.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2jbjjdfsk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gogol.net.cn/Article/details/gt2empasaeu.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.aizwys.cn/Article/details/gt2cpxqqkif.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2bvuxbcnm.html

Java: enum Color { RED, GREEN }
来源：http://dali.jqgufenzy.top/Article/details/gt2cvpjwbtd.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuanzhike.top/Article/details/gt2evlqzmlv.html

Ruby: Color = %i[red green].freeze
来源：http://dali.c1oappe.top/Article/details/gt2uemotdgo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2ouhlgoyf.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2tgfvyofc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2buoigmyq.html

PHP:  get_object_vars($obj);
来源：http://dali.meibo888.top/Article/details/gt2gzdjpazi.html

JS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2vsjzztac.html

TS:   Object.entries(obj)
来源：http://dali.andypj.xyz/Article/details/gt2djteecnn.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zdqjudy.top/Article/details/gt2ofricwkp.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yangfankeji.com/Article/details/gt2kheuplwa.html

Ruby: obj.instance_variables
来源：http://dali.quarkkingdee.top/Article/details/gt2flrbitrl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.andypj.xyz/Article/details/gt2xbvcxjra.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mjlfvuyj.html

H. 异常与错误处理
来源：http://dali.guannengcc.top/Article/details/gt2hvhivgrh.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2muyvgnbs.html

[H01] try / catch 基础
来源：http://dali.guannengcc.top/Article/details/gt2kgxogiud.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rhflsgtf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hfpthk.cn/Article/details/gt2cqhoonyx.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2mklzscjx.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xziqi.cn/Article/details/gt2ankqssoz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gt2fqzfcwdq.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gogol.net.cn/Article/details/gt2wsgrktww.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2hblynjrr.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ehwqpu.com/Article/details/gt2usqcoalu.html

[H02] finally / ensure 收尾
来源：http://dali.jyoumei.cn/Article/details/gt2iiplhwnl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gt2vspntvix.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.sufxvd.cn/Article/details/gt2uaryzdvz.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.xziqi.cn/Article/details/gt2vkbttood.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yj20258888.top/Article/details/gt2xzeixrdb.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.svipenyu.cn/Article/details/gt2mppfktym.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gt2szhvljul.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yonumen.top/Article/details/gt2ydoplcve.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2nzbjxzlo.html

[H03] 主动抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2mdnkounr.html

Py:   raise ValueError("错误信息")
来源：http://dali.sxryk.cn/Article/details/gt2bbwyupck.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.cqqwz.cn/Article/details/gt2nypfslgr.html

JS:   throw new Error("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gt2nwfvaage.html

TS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gt2yahukxpt.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2jrbzmvri.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guannengcc.top/Article/details/gt2bgjjmuar.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hongshengwenyu.top/Article/details/gt2tvejsqod.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gt2rpeduobs.html

[H04] 自定义异常类型
来源：http://dali.svipenyu.cn/Article/details/gt2rzrbrerf.html

Py:   class MyError(Exception): pass
来源：http://dali.dianchejie.cn/Article/details/gt2alvuedjh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gt2twvipxui.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gt2qlgexakn.html

TS:   class MyError extends Error {}
来源：http://dali.cashguo.top/Article/details/gt2pldershl.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2qyhkkbdz.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.fzhhl.top/Article/details/gt2xximuevd.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2emetkihl.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kxskjney.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcyijasy.html

Py:   except ValueError as e:
来源：http://dali.gotoacloud.top/Article/details/gt2wfpgjkfx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.vqdsnc.cn/Article/details/gt2alnfezap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.aibaodan.cn/Article/details/gt2maklfbfy.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xziqi.cn/Article/details/gt2hfoaxeqr.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jiagoushi.top/Article/details/gt2vbirentc.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.guannengcc.top/Article/details/gt2foaiofva.html

Ruby: rescue ArgumentError => e
来源：http://dali.xuetiantiany.cn/Article/details/gt2rljblclw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ayavdybh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.fzhhl.top/Article/details/gt2eabgvamd.html

Py:   value = d.get("k") or default
来源：http://dali.wangshuangyany.cn/Article/details/gt2yueybmnj.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.gotoacloud.top/Article/details/gt2ajknbcaz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2qoxttjsj.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2sqpkjdqu.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yuxming.cn/Article/details/gt2vizztsng.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cialnehz.html

Ruby: d&.dig(:a, :b)
来源：http://dali.hysaishi.cn/Article/details/gt2rzmhrgjw.html

C#:   obj?.A?.B ?? default
来源：http://dali.yongpay.top/Article/details/gt2bpeiugsq.html

[H07] 断言
来源：http://dali.haohaochexian.top/Article/details/gt2qimxpjrn.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cqqwz.cn/Article/details/gt2igxnfxhg.html

PHP:  assert($x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2snzsuxhu.html

JS:   console.assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gt2eckpgzuu.html

TS:   console.assert(x > 0);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ikvufjdu.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rqibpcgw.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.fzhhl.top/Article/details/gt2lvqmupsg.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pycfn.com/Article/details/gt2ehqaguek.html

C#:   Debug.Assert(x > 0);
来源：http://dali.iojbl.cn/Article/details/gt2duwevity.html

[H08] 获取错误信息与堆栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxqozbzw.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.ydzc1.top/Article/details/gt2yysnawkc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.xylfe.cn/Article/details/gt2okigtvga.html

JS:   e.message;  e.stack
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gtrldbem.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.chenzaomai.com/Article/details/gt2vlsobecz.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zycfv.cn/Article/details/gt2vcdrfdcl.html

Go:   err.Error()
来源：http://dali.cheryme.top/Article/details/gt2twrngmja.html

Ruby: e.message;  e.backtrace
来源：http://dali.yj20258.top/Article/details/gt2hzuhzrdp.html

C#:   e.Message;  e.StackTrace
来源：http://dali.hammf.cn/Article/details/gt2xxqlmwwr.html

[H09] 带错误码的异常
来源：http://dali.shzxlz.cn/Article/details/gt2ypejelrf.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.gogol.net.cn/Article/details/gt2exfmcvkv.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.andypj.xyz/Article/details/gt2uzkmqpqe.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcmxfzae.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.smart0.xyz/Article/details/gt2ntjexlxc.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.daxiang520.top/Article/details/gt2smzpmxju.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yuanzhike.top/Article/details/gt2buxtucsd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shuidangran.top/Article/details/gt2fpoogzrj.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.zdqjudy.top/Article/details/gt2eipjsihm.html

[H10] 资源自动释放
来源：http://dali.daria6918.cn/Article/details/gt2karnapqo.html


<!-- 参考信息 -->