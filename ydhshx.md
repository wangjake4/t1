代发 wailian999

C#:   File.Exists("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2krnjiocw.html

[F06] 删除文件
来源：http://dali.cqqwz.cn/Article/details/gt2znlzofru.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2nmotzewf.html

PHP:  unlink("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2vosualcj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2kmpuxulw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2lmvnjuzg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2oypnuhvx.html

Go:   os.Remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2lpnvlybj.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2pdfrdvds.html

C#:   File.Delete("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2gawfycyn.html

[F07] 创建目录（含多级）
来源：http://dali.sysykeji.top/Article/details/gt2gyxhdppk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2erzkwfiq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zdqjudy.top/Article/details/gt2oqvinjaq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2npizamvj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhiwuduotai.top/Article/details/gt2lytrtkas.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gt2fcntxnsg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zxoemqvs.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2akhoumss.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gogol.net.cn/Article/details/gt2ojmlsbzg.html

[F08] 遍历目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2yttoutzs.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2qyuplnvi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ofwgajkd.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teonorbk.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2rujsbmat.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2sedurylj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqirqyut.html

Ruby: Dir.children("dir")
来源：http://dali.tanke756.top/Article/details/gt2cchyeily.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2ippaoewg.html

[F09] 获取文件大小
来源：http://dali.hfpthk.cn/Article/details/gt2kzvsgcwq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2pfcacjxd.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2rfahavuf.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mrkkkjgr.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmcfjpmb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2mgnongqs.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2mvgagers.html

Ruby: File.size("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2pndvvhzk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.bjfxy.top/Article/details/gt2wwrxgacc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwvajlel.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2hjcqwsbt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2mjzouraq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkssnvbs.html

TS:   path.extname("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ktpuudsh.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yj202588.top/Article/details/gt2ruivcrjf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2zvhesein.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2cfapbbtw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2dmiwlavf.html

[F11] 复制与移动文件
来源：http://dali.jlsjyb.cn/Article/details/gt2smeueacg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2pgakoehq.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2rijofigi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rfcjpprc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2ekaopdyv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2grldfttm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gt2ptstmgfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ueccijky.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2uukcwpku.html

[F12] CSV 读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bqfgfslw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2uvlcpntr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jyoumei.cn/Article/details/gt2ofhuozqq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tian-w.cn/Article/details/gt2zmqhexch.html

TS:   // 同上
来源：http://dali.jyoumei.cn/Article/details/gt2rqhcntpe.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2pusqaepj.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxinkj.top/Article/details/gt2myngvgjy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2ivtahucl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gt2glpxhfan.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2sjubdykm.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gt2msexstey.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2efckfewj.html

[G01] 定义类
来源：http://dali.ivvv.top/Article/details/gt2dvmkdzfo.html

Py:   class User: pass
来源：http://dali.gogol.net.cn/Article/details/gt2qmgdynlj.html

PHP:  class User {}
来源：http://dali.yj20258888.top/Article/details/gt2ldtqamti.html

JS:   class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2tuxphrul.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gt2ofxgzpen.html

Java: class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2aiiinhak.html

Go:   type User struct { Name string }
来源：http://dali.guannengcc.top/Article/details/gt2wawcmbfu.html

Ruby: class User; end
来源：http://dali.ppjwa.cn/Article/details/gt2evmorxsn.html

C#:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2wqqmbznv.html

[G02] 构造函数
来源：http://dali.daria6918.cn/Article/details/gt2czdcsdfk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gt2ehwzjiof.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qypcaxgo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2enulsjiw.html

TS:   constructor(public name: string) {}
来源：http://dali.tian-w.cn/Article/details/gt2tbzugtqj.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2reminxtk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2pnszmgpz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aizwys.cn/Article/details/gt2azcqzfqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kknytnmq.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2ofabdfjz.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2ehwxkjvc.html

PHP:  public string $name = "x";
来源：http://dali.svipenyu.cn/Article/details/gt2fbvqgviw.html

JS:   this.name = "x";
来源：http://dali.316326.xyz/Article/details/gt2dwlsbdhq.html

TS:   name: string = "x";
来源：http://dali.yj202588.top/Article/details/gt2hcbbwxpi.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2fdejuzzc.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.tanke756.top/Article/details/gt2wnvsuobp.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2wqtkvpux.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wvyqoxje.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2mtspbtgt.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2jphxxxuq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zdqjudy.top/Article/details/gt2bhedujgx.html

JS:   greet() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2dmfdmtcq.html

TS:   greet(): string { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gt2hbdmsxlx.html

Java: String greet() { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2kbdnlqxx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gt2bhblxpba.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2nlixffgn.html

C#:   public string Greet() => Name;
来源：http://dali.yonumen.top/Article/details/gt2rlmztkdm.html

[G05] 继承
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffakogbz.html

Py:   class Admin(User): pass
来源：http://dali.fzhhl.top/Article/details/gt2kgmsquwy.html

PHP:  class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2rvsyyuxx.html

JS:   class Admin extends User {}
来源：http://dali.chenlongwang.top/Article/details/gt2pkbcidmc.html

TS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2jlytfziz.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2phbjtxcm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinqigfzy.top/Article/details/gt2umrwjvrt.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqoqmsbp.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gt2iwavoors.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2mrdrgmcp.html

Py:   def greet(self): return "admin"
来源：http://dali.redwolf501.top/Article/details/gt2nbhgzrxt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gzhubu.top/Article/details/gt2fwgxepke.html

JS:   greet() { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ikrpzyej.html

TS:   greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2umxmdoik.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2rkqvaygm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sysykeji.top/Article/details/gt2ubrptqvs.html

Ruby: def greet; "admin"; end
来源：http://dali.shzxlz.cn/Article/details/gt2rwrydalc.html

C#:   public override string Greet() => "admin";
来源：http://dali.shangyingyoupin.top/Article/details/gt2esghdbbw.html

[G07] 调用父类方法
来源：http://dali.hywenlv.cn/Article/details/gt2kzwnfjyd.html

Py:   super().greet()
来源：http://dali.xylfe.cn/Article/details/gt2vdhprkez.html

PHP:  parent::greet();
来源：http://dali.xuetiantiany.cn/Article/details/gt2ojazhpbl.html

JS:   super.greet();
来源：http://dali.aizwys.cn/Article/details/gt2giovhpdj.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2sekhhraf.html

Java: super.greet();
来源：http://dali.yangfankeji.com/Article/details/gt2ttrsebel.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daxiang520.top/Article/details/gt2xsybyian.html

Ruby: super
来源：http://dali.quarkkingdee.top/Article/details/gt2lozlylqp.html

C#:   base.Greet();
来源：http://dali.9152youxi.cn/Article/details/gt2kglmgfbz.html

[G08] 静态方法与属性
来源：http://dali.zhijiandao.cn/Article/details/gt2avwbaqqd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hnqzz.top/Article/details/gt2lrresbmw.html

PHP:  public static function f() {}
来源：http://dali.hfpthk.cn/Article/details/gt2fcdjqrcq.html

JS:   static f() {}
来源：http://dali.nanxinkj.top/Article/details/gt2xiiwvsjv.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2exnmpmge.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2mxgobwrv.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.wangshuangyany.cn/Article/details/gt2mvhrkhzj.html

Ruby: def self.f; end
来源：http://dali.xylfe.cn/Article/details/gt2pnfzyddk.html

C#:   public static void F() {}
来源：http://dali.c1oappe.top/Article/details/gt2byognhao.html

[G09] 接口 / 抽象类
来源：http://dali.dianchejie.cn/Article/details/gt2tfvgoteq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2swabnzyx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj202588.top/Article/details/gt2qomxiekj.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.wangdashe.top/Article/details/gt2qqpzpuee.html

TS:   interface Shape { area(): number; }
来源：http://dali.dashuyun.cn/Article/details/gt2xauclppo.html

Java: interface Shape { double area(); }
来源：http://dali.zhengqikj.top/Article/details/gt2ukiaykcm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2dlcxvlhk.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gt2ffxwuvbs.html

C#:   interface IShape { double Area(); }
来源：http://dali.yueranfly.top/Article/details/gt2fplcnxbt.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fjiwzpbr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.zhixingplan.top/Article/details/gt2djdenker.html

PHP:  public / protected / private
来源：http://dali.feifeiyinyue.top/Article/details/gt2tkfrgyqr.html

JS:   #private 字段；其余公开
来源：http://dali.yonumen.top/Article/details/gt2fmxustuc.html

TS:   public / protected / private
来源：http://dali.hnxiangtu.top/Article/details/gt2fhafovtw.html

Java: public / protected / private / 默认包级
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hxpnzwkt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj202588.top/Article/details/gt2fxonnrko.html

Ruby: public / protected / private
来源：http://dali.yangfankeji.com/Article/details/gt2scefgzvw.html

C#:   public / protected / private / internal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sygnazqo.html

[G11] getter / setter
来源：http://dali.dashuyun.cn/Article/details/gt2mivvjdae.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2tccxstrc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2aqzciuvu.html

JS:   get name() { return this._name; }
来源：http://dali.cdnleiting.top/Article/details/gt2xzobugmi.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2lbmhvvns.html

Java: public String getName() { return name; }
来源：http://dali.chenzaomai.com/Article/details/gt2budkydmz.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2vizvsvqg.html

Ruby: attr_accessor :name
来源：http://dali.jiagoushi.top/Article/details/gt2mummfjph.html

C#:   public string Name { get; set; }
来源：http://dali.zycfv.cn/Article/details/gt2uavxfcsb.html

[G12] 对象转字符串
来源：http://dali.yongpay.top/Article/details/gt2fsxixatu.html

Py:   def __str__(self): return self.name
来源：http://dali.yonumen.top/Article/details/gt2vqqcbxce.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.hammf.cn/Article/details/gt2egavraay.html

JS:   toString() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2irwfthxq.html

TS:   toString(): string { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nuikhnkt.html

Java: @Override public String toString() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2wwvqalps.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gt2exfvkdqi.html

Ruby: def to_s; @name; end
来源：http://dali.yongpay.top/Article/details/gt2neintcyu.html

C#:   public override string ToString() => Name;
来源：http://dali.tian-w.cn/Article/details/gt2tzluiiry.html

[G13] 判断对象类型
来源：http://dali.gzhubu.top/Article/details/gt2ntlaztis.html

Py:   isinstance(u, User)
来源：http://dali.smart0.xyz/Article/details/gt2wkynzasl.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2xracfowc.html

JS:   u instanceof User
来源：http://dali.gzhubu.top/Article/details/gt2ucqqbube.html

TS:   u instanceof User
来源：http://dali.zhengqikj.top/Article/details/gt2byepgyql.html

Java: u instanceof User
来源：http://dali.bjfxy.top/Article/details/gt2peelheqr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2vzaxmuln.html

Ruby: u.is_a?(User)
来源：http://dali.yangfankeji.com/Article/details/gt2zzhmjuxu.html

C#:   u is User
来源：http://dali.yvedp.cn/Article/details/gt2ourxxjeh.html

[G14] 数据类 / record
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojsapitf.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtgcwnsp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.yj20258.top/Article/details/gt2alipvkff.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yanxiufei.cn/Article/details/gt2sjrcqhku.html

TS:   type User = { name: string; age: number };
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjlmfshk.html

Java: record User(String name, int age) {}
来源：http://dali.yj202588.top/Article/details/gt2lxsdtyzt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dhexgazf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gt2jqdzwxrm.html

C#:   record User(string Name, int Age);
来源：http://dali.pengpengdd.cyou/Article/details/gt2teyluuyw.html

[G15] 枚举
来源：http://dali.mhx1999.top/Article/details/gt2xnmtysgz.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2fdikckwl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hplkwjxd.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.hnqzz.top/Article/details/gt2xtuagkbh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hnxiangtu.top/Article/details/gt2ydhuvdfo.html

Java: enum Color { RED, GREEN }
来源：http://dali.sysykeji.top/Article/details/gt2kdwgrnxw.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhengqikj.top/Article/details/gt2tjpvmqbl.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yuxming.cn/Article/details/gt2uztonnet.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yonumen.top/Article/details/gt2ezxarjwx.html

[G16] 对象转数组 / 字典
来源：http://dali.quarkkingdee.top/Article/details/gt2trggpnuh.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ppjwa.cn/Article/details/gt2pyrvstjc.html

PHP:  get_object_vars($obj);
来源：http://dali.cheryme.top/Article/details/gt2igsrifyy.html

JS:   Object.entries(obj)
来源：http://dali.cashguo.top/Article/details/gt2vvmtrftc.html

TS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2xbvojanu.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.guowangkeji.top/Article/details/gt2wsmmgppb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2stlmkwud.html

Ruby: obj.instance_variables
来源：http://dali.iojbl.cn/Article/details/gt2bvishcbw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gt2zsccajfn.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bwxjudwd.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gt2ylgybfpb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2jduygunk.html

[H01] try / catch 基础
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehbqllkb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ppjwa.cn/Article/details/gt2cxgchibs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2hbsbhhzl.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.wangdashe.top/Article/details/gt2vdnfkgot.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2treijouk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aizwys.cn/Article/details/gt2xrnyhdxb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.316326.xyz/Article/details/gt2yihlbxxe.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gt2uxcxmual.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2humqvyei.html

[H02] finally / ensure 收尾
来源：http://dali.yj202588.top/Article/details/gt2frhgcbrq.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.9152youxi.cn/Article/details/gt2avotlzec.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2zctbdwce.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgwsxwpd.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2tcpmkyud.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wzcunbgz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.wangdashe.top/Article/details/gt2rfcazffx.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2mnqdbfbw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.dashuyun.cn/Article/details/gt2xlstysvj.html

[H03] 主动抛出异常
来源：http://dali.meibo888.top/Article/details/gt2hmezangn.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuanzhike.top/Article/details/gt2qqlhxqnt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.meibo888.top/Article/details/gt2qbuwkovc.html

JS:   throw new Error("错误信息");
来源：http://dali.xylfe.cn/Article/details/gt2zecnbibt.html

TS:   throw new Error("错误信息");
来源：http://dali.aibaodan.cn/Article/details/gt2efnybyqi.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2ryjgllmv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.ybcxt.top/Article/details/gt2pkqdjekk.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhixingplan.top/Article/details/gt2vdmxmtly.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sysykeji.top/Article/details/gt2pbqrawoo.html

[H04] 自定义异常类型
来源：http://dali.zhengqikj.top/Article/details/gt2ggpgbool.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2jkpgiptp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.ehwqpu.com/Article/details/gt2bvedknnv.html

JS:   class MyError extends Error {}
来源：http://dali.quarkkingdee.top/Article/details/gt2erplgkzl.html

TS:   class MyError extends Error {}
来源：http://dali.bjfxy.top/Article/details/gt2jruotjer.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2cvkfvsrn.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.jyoumei.cn/Article/details/gt2pgnuldyz.html

Ruby: class MyError < StandardError; end
来源：http://dali.yonumen.top/Article/details/gt2jirauula.html

C#:   class MyException : Exception {}
来源：http://dali.redwolf501.top/Article/details/gt2dgsutjxy.html

[H05] 捕获特定类型
来源：http://dali.ivvv.top/Article/details/gt2qutrnech.html

Py:   except ValueError as e:
来源：http://dali.gzhubu.top/Article/details/gt2sgdmczrc.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hlpdthcl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.tianlin.xyz/Article/details/gt2hbwmoxbe.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2egvszeai.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yj202588.top/Article/details/gt2huxyhris.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.hywenlv.cn/Article/details/gt2gtvqnxwu.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinqigufen.top/Article/details/gt2icgyeeim.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.iojbl.cn/Article/details/gt2ppfkvbex.html

[H06] 可选值 / 空值安全访问
来源：http://dali.quarkkingdee.top/Article/details/gt2jfmhnets.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2excejeni.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tianlin.xyz/Article/details/gt2rzsnzadi.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guowangkeji.top/Article/details/gt2wfeptuit.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.pengpengdd.cyou/Article/details/gt2nruudiva.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.bjfxy.top/Article/details/gt2jvhquuml.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.316326.xyz/Article/details/gt2dtpayrrx.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jianghu66.top/Article/details/gt2wrlsmmvr.html

C#:   obj?.A?.B ?? default
来源：http://dali.hnqzz.top/Article/details/gt2qhprmtad.html

[H07] 断言
来源：http://dali.xinyue.icu/Article/details/gt2gdlxpxup.html

Py:   assert x > 0, "必须为正"
来源：http://dali.hongshengwenyu.top/Article/details/gt2styeglui.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gt2ckfohmwi.html

JS:   console.assert(x > 0);
来源：http://dali.shuidangran.top/Article/details/gt2uygtdghn.html

TS:   console.assert(x > 0);
来源：http://dali.haohaochexian.top/Article/details/gt2albbvvxs.html

Java: assert x > 0 : "必须为正";
来源：http://dali.cdnleiting.top/Article/details/gt2qvrjhsoz.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.cheryme.top/Article/details/gt2bsevjcrx.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yueranfly.top/Article/details/gt2snmdwvex.html

C#:   Debug.Assert(x > 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2igzeqpft.html

[H08] 获取错误信息与堆栈
来源：http://dali.kuanghao11.cn/Article/details/gt2nfwberro.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.birdmap.top/Article/details/gt2uvokrqkr.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ybcxt.top/Article/details/gt2ysixgmot.html

JS:   e.message;  e.stack
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ojtsyfhs.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.hnqzz.top/Article/details/gt2lgtdukwk.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.shangyingyoupin.top/Article/details/gt2akcokldw.html

Go:   err.Error()
来源：http://dali.shuidangran.top/Article/details/gt2kdohvbgf.html

Ruby: e.message;  e.backtrace
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onozawaq.html

C#:   e.Message;  e.StackTrace
来源：http://dali.jinqigufen.top/Article/details/gt2qcdzcdty.html

[H09] 带错误码的异常
来源：http://dali.havefunace.top/Article/details/gt2altgrlqv.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shzxlz.cn/Article/details/gt2yxikasgi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.shuidangran.top/Article/details/gt2hxxufifo.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.9152youxi.cn/Article/details/gt2gtklsvwt.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.havefunace.top/Article/details/gt2cbafrwvt.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.jyoumei.cn/Article/details/gt2twedfzuc.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.sweek.top/Article/details/gt2agedwvtd.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.yonumen.top/Article/details/gt2lpfpzekt.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gzhubu.top/Article/details/gt2qcdlfnry.html

[H10] 资源自动释放
来源：http://dali.andypj.xyz/Article/details/gt2zjzhavvn.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.zhongyouzk.top/Article/details/gt2wdtywanc.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xuetiantiany.cn/Article/details/gt2wtkcxork.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yuxming.cn/Article/details/gt2hkkgdqmx.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.yanxiufei.cn/Article/details/gt2qqyktxll.html


<!-- 参考信息 -->