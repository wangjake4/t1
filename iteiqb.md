代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2vpgkjbki.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gt2adjvgnju.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2wkpyvjny.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxticnwj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2zsxctqfw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2gyirkgdd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahchkejk.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2apddltbi.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2othzmzva.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2ekhvokym.html

[F07] 创建目录（含多级）
来源：http://dali.chenzaomai.com/Article/details/gt2wrlngxhe.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2hqehvxie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2gvyjzqzi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhongyouzk.top/Article/details/gt2bhsvkopg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.kuanghao11.cn/Article/details/gt2iecsdxaf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gt2qzeikqvm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gt2uxkhgwpj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cheryme.top/Article/details/gt2azuhpziz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gt2ybdwdizj.html

[F08] 遍历目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvpgekfh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gt2zswtogle.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.0kj1m.cn/Article/details/gt2ndxmtejv.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2mawrewol.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uujlqgbj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2uatuudlx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gt2nskioeap.html

Ruby: Dir.children("dir")
来源：http://dali.sysykeji.top/Article/details/gt2vmabvecq.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yueranfly.top/Article/details/gt2uzdnzdea.html

[F09] 获取文件大小
来源：http://dali.iojbl.cn/Article/details/gt2yxwblsmv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2axxrfyvd.html

PHP:  filesize("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2ojgbdwxz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2wkhkxqsj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2zbuuwaht.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2azcjespv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.chenzaomai.com/Article/details/gt2fwkiwcbf.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2jnowcoxq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.meibo888.top/Article/details/gt2qapygwsb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.0kj1m.cn/Article/details/gt2bqzuejij.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ywgpvlua.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2qgghxqlu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2crtawjmp.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2aoejmabx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2oejchzqw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qgugzcin.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2wtvuxeji.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2obpolfni.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2spddevuv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2fubgtazj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2jauoaosu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjswizwt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2clcbfvvf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guowangkeji.top/Article/details/gt2edtayyzw.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gt2qkautlus.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwarzejc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gt2xuwkwrln.html

[F12] CSV 读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mrdocsxq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fzhhl.top/Article/details/gt2piuraksl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hnxiangtu.top/Article/details/gt2zuzhcimk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gt2hjowcxtb.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gt2eicuajbm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shanyushiyangtech.top/Article/details/gt2coiowjpe.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ppjwa.cn/Article/details/gt2jmfmmlpl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gt2wdudgfaw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shzxlz.cn/Article/details/gt2gfpxpfbi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2nbghhjbt.html

G. 面向对象
来源：http://dali.yangfankeji.com/Article/details/gt2zaahlhyt.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2jsgevwjt.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gt2njhvxibd.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2pmvflztn.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2snmhubbc.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gt2gjddkouj.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gt2egqvugjs.html

Java: class User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2gxuscayk.html

Go:   type User struct { Name string }
来源：http://dali.xylfe.cn/Article/details/gt2vbvhotup.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2oqbwgjpi.html

C#:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gt2axfdythe.html

[G02] 构造函数
来源：http://dali.nwbrower.top/Article/details/gt2qknvmlma.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gotoacloud.top/Article/details/gt2armawtgs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ppjwa.cn/Article/details/gt2xesbzsck.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2ilumxwau.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kedhqcuw.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2rlpnfezf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.svipenyu.cn/Article/details/gt2zexrpzbe.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rabnraua.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfwooolo.html

[G03] 实例属性
来源：http://dali.zhijiandao.cn/Article/details/gt2uehgyfmg.html

Py:   self.name = "x"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2josqdvce.html

PHP:  public string $name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2isnfokbi.html

JS:   this.name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gt2lubjkyok.html

TS:   name: string = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2etcmknvw.html

Java: private String name;
来源：http://dali.ppjwa.cn/Article/details/gt2rvjdffub.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenjidiqi.icu/Article/details/gt2iznfmkrs.html

Ruby: @name = "x"
来源：http://dali.yueranfly.top/Article/details/gt2bajeorcq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2ghtxdzkx.html

[G04] 定义方法
来源：http://dali.ydzc1.top/Article/details/gt2dpjymbey.html

Py:   def greet(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgmpmcvj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.birdmap.top/Article/details/gt2gwgrhasn.html

JS:   greet() { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2aivwjgah.html

TS:   greet(): string { return this.name; }
来源：http://dali.sufxvd.cn/Article/details/gt2sjantikd.html

Java: String greet() { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2rigpbdic.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.birdmap.top/Article/details/gt2xrotvgup.html

Ruby: def greet; @name; end
来源：http://dali.redwolf501.top/Article/details/gt2vewcmotz.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gt2oliggldx.html

[G05] 继承
来源：http://dali.guowangkeji.top/Article/details/gt2uxezvbqe.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gt2goykvdke.html

PHP:  class Admin extends User {}
来源：http://dali.shzxlz.cn/Article/details/gt2zliogypo.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2vbshfvak.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2bcusovdm.html

Java: class Admin extends User {}
来源：http://dali.dashuyun.cn/Article/details/gt2yrrddjos.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xziqi.cn/Article/details/gt2uwyfdwcl.html

Ruby: class Admin < User; end
来源：http://dali.wangdashe.top/Article/details/gt2ggtuuosx.html

C#:   class Admin : User {}
来源：http://dali.hammf.cn/Article/details/gt2zcvghiet.html

[G06] 重写方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ohgaifyo.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gt2vwllsqod.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dujdlvfp.html

JS:   greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2pcszzhur.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zdqjudy.top/Article/details/gt2lhxffefz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gt2xsvbnnyp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhiwuduotai.top/Article/details/gt2lftcvchs.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2amxvdqga.html

C#:   public override string Greet() => "admin";
来源：http://dali.guannengcc.top/Article/details/gt2qwgbqfnn.html

[G07] 调用父类方法
来源：http://dali.jyoumei.cn/Article/details/gt2zgrzcogc.html

Py:   super().greet()
来源：http://dali.cashguo.top/Article/details/gt2qoxquvzw.html

PHP:  parent::greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2zaalhvvx.html

JS:   super.greet();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnoewtur.html

TS:   super.greet();
来源：http://dali.zhoulong.xyz/Article/details/gt2mvaoxyzi.html

Java: super.greet();
来源：http://dali.meibo888.top/Article/details/gt2hwukcibq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgfzy.top/Article/details/gt2uoztdcrq.html

Ruby: super
来源：http://dali.bjfxy.top/Article/details/gt2ivmazsvw.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gt2qhlxvloz.html

[G08] 静态方法与属性
来源：http://dali.daxiang520.top/Article/details/gt2lkjvhfjo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.andypj.xyz/Article/details/gt2vwkntyzk.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2vcgapolt.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2mztoyisk.html

TS:   static f(): void {}
来源：http://dali.svipenyu.cn/Article/details/gt2ymtcrnyv.html

Java: static void f() {}
来源：http://dali.yueranfly.top/Article/details/gt2xlndukon.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2yqxmhxeg.html

Ruby: def self.f; end
来源：http://dali.chenlongwang.top/Article/details/gt2lwefkagq.html

C#:   public static void F() {}
来源：http://dali.andypj.xyz/Article/details/gt2tpvdjgjx.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gt2yrxwdpbj.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xuanzx.com/Article/details/gt2ipehuihp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yanxiufei.cn/Article/details/gt2mllhdisp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sufxvd.cn/Article/details/gt2mmkfnwxg.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj202588.top/Article/details/gt2qbauwplv.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2xuugljbv.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenzaomai.com/Article/details/gt2pubrdcwa.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xziqi.cn/Article/details/gt2iikaorfy.html

C#:   interface IShape { double Area(); }
来源：http://dali.jinqigufen.top/Article/details/gt2czwebmdc.html

[G10] 访问控制
来源：http://dali.haohaochexian.top/Article/details/gt2pmdupqkr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swzisnjm.html

PHP:  public / protected / private
来源：http://dali.zycfv.cn/Article/details/gt2fcbgtcig.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258.top/Article/details/gt2hzynyxbv.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2sutauagn.html

Java: public / protected / private / 默认包级
来源：http://dali.nanxinkj.top/Article/details/gt2iswieucl.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.feifeiyinyue.top/Article/details/gt2ojlpgasw.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2tphbrxyj.html

C#:   public / protected / private / internal
来源：http://dali.yuanzhike.top/Article/details/gt2htnyjsiy.html

[G11] getter / setter
来源：http://dali.zhengqikj.top/Article/details/gt2cypapnba.html

Py:   @property 与 @x.setter
来源：http://dali.xziqi.cn/Article/details/gt2xtjphvwr.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2rqtajabz.html

JS:   get name() { return this._name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lbtugitf.html

TS:   get name(): string { return this._name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tytqnhwu.html

Java: public String getName() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2rvkjxfuj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.snrcjt.cn/Article/details/gt2ybinwnqm.html

Ruby: attr_accessor :name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nfcycarb.html

C#:   public string Name { get; set; }
来源：http://dali.redwolf501.top/Article/details/gt2lwoxqhon.html

[G12] 对象转字符串
来源：http://dali.yueranfly.top/Article/details/gt2acvwpokf.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2vihjegex.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jxgfaqcp.html

JS:   toString() { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2qxwbmrya.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2mqhoantc.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wolvsvmc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2lqkbrdbj.html

Ruby: def to_s; @name; end
来源：http://dali.jinqigfzy.top/Article/details/gt2xexjexsb.html

C#:   public override string ToString() => Name;
来源：http://dali.mhx1999.top/Article/details/gt2ybzklbxu.html

[G13] 判断对象类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwxuutip.html

Py:   isinstance(u, User)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bywunyos.html

PHP:  $u instanceof User
来源：http://dali.cashguo.top/Article/details/gt2hudlblxf.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2joozdkuv.html

TS:   u instanceof User
来源：http://dali.hnxiangtu.top/Article/details/gt2qniirros.html

Java: u instanceof User
来源：http://dali.gaohongyu789.top/Article/details/gt2qprjthji.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmlrlxvo.html

Ruby: u.is_a?(User)
来源：http://dali.smart0.xyz/Article/details/gt2uostlprm.html

C#:   u is User
来源：http://dali.hfpthk.cn/Article/details/gt2ryepzsff.html

[G14] 数据类 / record
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqkfrbre.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yueranfly.top/Article/details/gt2cdatmgzw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ehwqpu.com/Article/details/gt2ciuhnqkb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.c1oappe.top/Article/details/gt2xctdfhwp.html

TS:   type User = { name: string; age: number };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzkxylki.html

Java: record User(String name, int age) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbhlctvz.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ppjwa.cn/Article/details/gt2vxrejjeh.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.sysykeji.top/Article/details/gt2vddwrhsa.html

C#:   record User(string Name, int Age);
来源：http://dali.daxiang520.top/Article/details/gt2ivljrwlf.html

[G15] 枚举
来源：http://dali.sufxvd.cn/Article/details/gt2kxtfabcr.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hammf.cn/Article/details/gt2wfgzlqdv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.yueranfly.top/Article/details/gt2tpixtgud.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2izstylyk.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ydzc1.top/Article/details/gt2rociikdk.html

Java: enum Color { RED, GREEN }
来源：http://dali.haohaochexian.top/Article/details/gt2aouleqil.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckuniajg.html

Ruby: Color = %i[red green].freeze
来源：http://dali.cashguo.top/Article/details/gt2avxvobzs.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zycfv.cn/Article/details/gt2utpbhqih.html

[G16] 对象转数组 / 字典
来源：http://dali.hnxiangtu.top/Article/details/gt2obvhgvmr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sufxvd.cn/Article/details/gt2ytsethcu.html

PHP:  get_object_vars($obj);
来源：http://dali.hysaishi.cn/Article/details/gt2khedvmda.html

JS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gt2dipyzwyw.html

TS:   Object.entries(obj)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ejaedxkk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.gaohongyu789.top/Article/details/gt2hpelxmrd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.0kj1m.cn/Article/details/gt2hmorajyj.html

Ruby: obj.instance_variables
来源：http://dali.kuanghao11.cn/Article/details/gt2cyohnlke.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xinyue.icu/Article/details/gt2mumqqcjn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2hkmlueab.html

H. 异常与错误处理
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbyevaue.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2lbygtlzk.html

[H01] try / catch 基础
来源：http://dali.daxiang520.top/Article/details/gt2fmgljfgp.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guowangkeji.top/Article/details/gt2huioqgyk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.svipenyu.cn/Article/details/gt2jenzcxde.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2fgljusej.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.smart0.xyz/Article/details/gt2gnzgibqy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.guannengcc.top/Article/details/gt2gldlworg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yuanzhike.top/Article/details/gt2pyhqswom.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ylvzmkiy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2crlzbpdw.html

[H02] finally / ensure 收尾
来源：http://dali.sxryk.cn/Article/details/gt2kmcmfkho.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cucudq.cn/Article/details/gt2nsdodvay.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.shzxlz.cn/Article/details/gt2dztgztgt.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2bblpsgxv.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjxwfrjp.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.chenzaomai.com/Article/details/gt2wvojkyth.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhixingplan.top/Article/details/gt2ztmqmjrc.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.aizwys.cn/Article/details/gt2kvxbeplu.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2vmssvctj.html

[H03] 主动抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2zrrepcvd.html

Py:   raise ValueError("错误信息")
来源：http://dali.bjfxy.top/Article/details/gt2qvydadtl.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.xinyue.icu/Article/details/gt2ucehifvc.html

JS:   throw new Error("错误信息");
来源：http://dali.jianghu66.top/Article/details/gt2amaureto.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2kdzswexw.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gt2rokdhehg.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.nanxinkj.top/Article/details/gt2wbltlmah.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yuxming.cn/Article/details/gt2rhoiaykm.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shuidangran.top/Article/details/gt2llihmgxr.html

[H04] 自定义异常类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swpvxnwj.html

Py:   class MyError(Exception): pass
来源：http://dali.chenzaomai.com/Article/details/gt2sapscaue.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.daria6918.cn/Article/details/gt2kvxrqjxz.html

JS:   class MyError extends Error {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqedaqqv.html

TS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wiakqpnb.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gt2jdpqxlhn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.haohaochexian.top/Article/details/gt2nggokiqa.html

Ruby: class MyError < StandardError; end
来源：http://dali.vqdsnc.cn/Article/details/gt2bsdjkigh.html

C#:   class MyException : Exception {}
来源：http://dali.yonumen.top/Article/details/gt2vlfpvmfy.html

[H05] 捕获特定类型
来源：http://dali.ehwqpu.com/Article/details/gt2tdpyilzd.html

Py:   except ValueError as e:
来源：http://dali.yonumen.top/Article/details/gt2beoiubnl.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yanxiufei.cn/Article/details/gt2ovasdyqc.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sweek.top/Article/details/gt2pngxpnwa.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.cdnleiting.top/Article/details/gt2gertiisz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.sysykeji.top/Article/details/gt2ckcxdutl.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.nwbrower.top/Article/details/gt2ilxczgzv.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhengqikj.top/Article/details/gt2xetmkfel.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.tianlin.xyz/Article/details/gt2ggmicfkb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.chenlongwang.top/Article/details/gt2hrosqmli.html

Py:   value = d.get("k") or default
来源：http://dali.birdmap.top/Article/details/gt2rvrrlgqw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.yanxiufei.cn/Article/details/gt2xxtjegso.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.sufxvd.cn/Article/details/gt2wxsokukk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itghkpad.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.daria6918.cn/Article/details/gt2zafakwxh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.shuidangran.top/Article/details/gt2nreiivvg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zdqjudy.top/Article/details/gt2ixbkponj.html

C#:   obj?.A?.B ?? default
来源：http://dali.xinyue.icu/Article/details/gt2tjqxpifj.html

[H07] 断言
来源：http://dali.yanxiufei.cn/Article/details/gt2ipcuvpkw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.dianchejie.cn/Article/details/gt2yxxzysir.html

PHP:  assert($x > 0);
来源：http://dali.gaohongyu789.top/Article/details/gt2isfsjhds.html

JS:   console.assert(x > 0);
来源：http://dali.ehwqpu.com/Article/details/gt2ounodpdk.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2ojkbijkq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gotoacloud.top/Article/details/gt2brcaxjlq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.bjfxy.top/Article/details/gt2biqitdxe.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.wangdashe.top/Article/details/gt2wzflemka.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rigigxow.html

[H08] 获取错误信息与堆栈
来源：http://dali.cqqwz.cn/Article/details/gt2oomyxiix.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jyoumei.cn/Article/details/gt2wjawghhw.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gogol.net.cn/Article/details/gt2yhsdhwms.html

JS:   e.message;  e.stack
来源：http://dali.birdmap.top/Article/details/gt2yqyqiggs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jianghu66.top/Article/details/gt2yykhkitg.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.vqdsnc.cn/Article/details/gt2jsjiurej.html

Go:   err.Error()
来源：http://dali.yvedp.cn/Article/details/gt2iiudaijh.html

Ruby: e.message;  e.backtrace
来源：http://dali.hammf.cn/Article/details/gt2gafncdkm.html

C#:   e.Message;  e.StackTrace
来源：http://dali.ppjwa.cn/Article/details/gt2pjduzipz.html

[H09] 带错误码的异常
来源：http://dali.zhixingplan.top/Article/details/gt2ofmsjwyg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.chenjidiqi.icu/Article/details/gt2howfbaht.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2udbpsdem.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.c1oappe.top/Article/details/gt2qsackpjy.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2olyjeydo.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gfvhrbyy.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aibaodan.cn/Article/details/gt2zcmoofpy.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yanxiufei.cn/Article/details/gt2zzvehlkl.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.pycfn.com/Article/details/gt2laybthxq.html

[H10] 资源自动释放
来源：http://dali.zhengqikj.top/Article/details/gt2uhxfrsun.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.316326.xyz/Article/details/gt2spswxafd.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yonumen.top/Article/details/gt2axoxdchx.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trojwcug.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuanzhike.top/Article/details/gt2ygjwgygo.html


<!-- 参考信息 -->