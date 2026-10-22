代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shzxlz.cn/Article/details/gtfpbcjcjs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtampkgnlu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gtwaszirze.html

[F04] 追加写入文件
来源：http://dali.meibo888.top/Article/details/gtbsobmkqu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtzhfeognj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tianlin.xyz/Article/details/gthuolcsbk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tianlin.xyz/Article/details/gtyilrcsij.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtxmogueey.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pengpengdd.cyou/Article/details/gtfkdhtpwi.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtemuelgyn.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nanxinkj.top/Article/details/gthaavdlih.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cheryme.top/Article/details/gtbxviawqx.html

[F05] 判断文件或目录是否存在
来源：http://dali.pycfn.com/Article/details/gtlvqugsql.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtlheyquqk.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtnxqsgwpb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtemtcviwz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gthmfdfsxk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtjvqwfabi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gotoacloud.top/Article/details/gtfswabdkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtqfatydii.html

C#:   File.Exists("a.txt")
来源：http://dali.cheryme.top/Article/details/gtqkgpjnme.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gtypfqnbgo.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtiqfmwrkt.html

PHP:  unlink("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtffxlsbea.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtdcgtlhjk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvgrlwyim.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtjiwjcbyf.html

Go:   os.Remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtdnwdnzkl.html

Ruby: File.delete("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gttzpfpnfw.html

C#:   File.Delete("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtmpnaewpx.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gthhtjuoww.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthahhqsez.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gtuyfwnltl.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gtpgqvjntj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtvamuyjjt.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtonznnyep.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gtrczduwds.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.cashguo.top/Article/details/gtygbmynso.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigufen.top/Article/details/gtoyrsdzgo.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtzxlublfx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gtxetchudc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtjkvdapji.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokcedbmh.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gtkwxlixrc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gttecetgmx.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gteyvoglvt.html

Ruby: Dir.children("dir")
来源：http://dali.xuanzx.com/Article/details/gtfifawtqo.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtviarjynh.html

[F09] 获取文件大小
来源：http://dali.xuanzx.com/Article/details/gtivqiujna.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gthapnnyvh.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtaiekdafe.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gttvywuayx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtqwbczkdi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tianlin.xyz/Article/details/gtywvptakj.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhoulong.xyz/Article/details/gtjtowqnxc.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtrmfuyfjy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuxming.cn/Article/details/gtjhrobare.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gtafqxepfd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gtvhkxggmz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yj20258888.top/Article/details/gtpaumcetp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtktopngte.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyvamxaxu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sufxvd.cn/Article/details/gtuswfpenp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtwnrhmmsn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrilywjqv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtibhkowyo.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtbybwyxjj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.andypj.xyz/Article/details/gtsufdzixy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuanzhike.top/Article/details/gtubosmcjj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yueranfly.top/Article/details/gtwmsopauy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtrcpqfxol.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtrusauswk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.wangdashe.top/Article/details/gtlzomdzic.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtchpchwbk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.9152youxi.cn/Article/details/gtouecxscq.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtcsamanvh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gtqxpsukdz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gtawndbivo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtxyqhqtrj.html

TS:   // 同上
来源：http://dali.zhengqikj.top/Article/details/gtzscmzqpr.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jiagoushi.top/Article/details/gtsjegfnab.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daria6918.cn/Article/details/gtyrefxghe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.fzhhl.top/Article/details/gtcbvoasgh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gtslnwndgz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwhcxokiv.html

G. 面向对象
来源：http://dali.dashuyun.cn/Article/details/gtuqtefvrf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtlcgefbwb.html

[G01] 定义类
来源：http://dali.zhiwuduotai.top/Article/details/gtcbsjjbmo.html

Py:   class User: pass
来源：http://dali.chenlongwang.top/Article/details/gtzacjodyj.html

PHP:  class User {}
来源：http://dali.yuanzhike.top/Article/details/gtfskeefys.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtkazatrll.html

TS:   class User { name: string = ""; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtkqnejz.html

Java: class User {}
来源：http://dali.havefunace.top/Article/details/gtnpgynzlm.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtrmiynvod.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gteurdvsju.html

C#:   class User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinsespkh.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtfxxhpebv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.guannengcc.top/Article/details/gtgjoaoyvx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtrwnaqmbv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gtgzegcaou.html

TS:   constructor(public name: string) {}
来源：http://dali.jiagoushi.top/Article/details/gtscvhrkvv.html

Java: User(String name) { this.name = name; }
来源：http://dali.0kj1m.cn/Article/details/gtzodhplpw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhengqikj.top/Article/details/gtmrrroyrk.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.gotoacloud.top/Article/details/gtfgwmesaf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ppjwa.cn/Article/details/gtdgtaezha.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gtgtrpcblf.html

Py:   self.name = "x"
来源：http://dali.cheryme.top/Article/details/gtyyocgffe.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtgyhyluul.html

JS:   this.name = "x";
来源：http://dali.jinqigfzy.top/Article/details/gthqrmiohj.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gtrgombvqc.html

Java: private String name;
来源：http://dali.pengpengdd.cyou/Article/details/gtbyirkrxh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj20258888.top/Article/details/gtsysesenj.html

Ruby: @name = "x"
来源：http://dali.gzhubu.top/Article/details/gtgsuoijvk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aizwys.cn/Article/details/gtpltxtydb.html

[G04] 定义方法
来源：http://dali.feifeiyinyue.top/Article/details/gtxxrhnxsk.html

Py:   def greet(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gtqpmzhgfd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.tanke756.top/Article/details/gtbvlephyx.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtoaitmksw.html

TS:   greet(): string { return this.name; }
来源：http://dali.dashuyun.cn/Article/details/gtoqxgfxlo.html

Java: String greet() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtebeaatxf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yueranfly.top/Article/details/gtejupuzlt.html

Ruby: def greet; @name; end
来源：http://dali.dashuyun.cn/Article/details/gthbztjgre.html

C#:   public string Greet() => Name;
来源：http://dali.zhijiandao.cn/Article/details/gtgazmkulb.html

[G05] 继承
来源：http://dali.nanxuanxn.top/Article/details/gtnabcajhu.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gtxodsjadh.html

PHP:  class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtwjjqwkhg.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gtnjhupdrl.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gtmmkokijx.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbbkgssg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.daria6918.cn/Article/details/gtyvbrqxsj.html

Ruby: class Admin < User; end
来源：http://dali.xziqi.cn/Article/details/gtmfgioxfa.html

C#:   class Admin : User {}
来源：http://dali.ivvv.top/Article/details/gtsnmjwkfa.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gtyiqmpycz.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtizxwoadi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtpmqfuqpo.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gtbitzwbxm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gtcjckqzvh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gtflkltoyq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj202588.top/Article/details/gtbfckdlii.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtbkazecoa.html

C#:   public override string Greet() => "admin";
来源：http://dali.quarkkingdee.top/Article/details/gtalkjyyye.html

[G07] 调用父类方法
来源：http://dali.iojbl.cn/Article/details/gtehlmwyoj.html

Py:   super().greet()
来源：http://dali.9152youxi.cn/Article/details/gtlngvtffo.html

PHP:  parent::greet();
来源：http://dali.nanxinkj.top/Article/details/gtinuhnwij.html

JS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gtmohnwpis.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtjdhwfxoc.html

Java: super.greet();
来源：http://dali.xziqi.cn/Article/details/gtceqiyuft.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.nanxuanxn.top/Article/details/gticttfgts.html

Ruby: super
来源：http://dali.aibaodan.cn/Article/details/gtwarochxo.html

C#:   base.Greet();
来源：http://dali.shuidangran.top/Article/details/gtophtdums.html

[G08] 静态方法与属性
来源：http://dali.c1oappe.top/Article/details/gtrqwpeqdu.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.birdmap.top/Article/details/gtooefhexo.html

PHP:  public static function f() {}
来源：http://dali.tianlin.xyz/Article/details/gtyxpnevcx.html

JS:   static f() {}
来源：http://dali.gogol.net.cn/Article/details/gtbgzgrjwf.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gtrvtmygxj.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gthpmdvbvc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yuanzhike.top/Article/details/gtvkzhwuyc.html

Ruby: def self.f; end
来源：http://dali.vqdsnc.cn/Article/details/gtneqcmizp.html

C#:   public static void F() {}
来源：http://dali.yuxming.cn/Article/details/gtroiduvvy.html

[G09] 接口 / 抽象类
来源：http://dali.9152youxi.cn/Article/details/gtybjuvmof.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gtwddvqxcv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258.top/Article/details/gtmridqdai.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtpaxlbqee.html

TS:   interface Shape { area(): number; }
来源：http://dali.nwbrower.top/Article/details/gtbwvyramy.html

Java: interface Shape { double area(); }
来源：http://dali.hammf.cn/Article/details/gttgngkyli.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.bjfxy.top/Article/details/gtdvlquzmr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtqbpdvxnl.html

C#:   interface IShape { double Area(); }
来源：http://dali.tianlin.xyz/Article/details/gtyjfxapzc.html

[G10] 访问控制
来源：http://dali.ydzc1.top/Article/details/gtokouikqr.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gaohongyu789.top/Article/details/gtbfqjibva.html

PHP:  public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtllopxjqm.html

JS:   #private 字段；其余公开
来源：http://dali.yuxming.cn/Article/details/gtqlyakrkj.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gtjaytyzpw.html

Java: public / protected / private / 默认包级
来源：http://dali.0kj1m.cn/Article/details/gtxwazbpxx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sysykeji.top/Article/details/gtbtnbhjot.html

Ruby: public / protected / private
来源：http://dali.bjfxy.top/Article/details/gtbythfyun.html

C#:   public / protected / private / internal
来源：http://dali.hysaishi.cn/Article/details/gtikwuqpci.html

[G11] getter / setter
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstiuakoe.html

Py:   @property 与 @x.setter
来源：http://dali.daxiang520.top/Article/details/gtumkqfhsz.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzmxzhvaq.html

JS:   get name() { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gthxbhfbbe.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnxiangtu.top/Article/details/gtlornuwll.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtdbnrpcdj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.feifeiyinyue.top/Article/details/gtpokufvty.html

Ruby: attr_accessor :name
来源：http://dali.yueranfly.top/Article/details/gtydxfdwaz.html

C#:   public string Name { get; set; }
来源：http://dali.cqqwz.cn/Article/details/gtyprfdtxf.html

[G12] 对象转字符串
来源：http://dali.dashuyun.cn/Article/details/gtsuyhyuvb.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gtcnnkcdwy.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.9152youxi.cn/Article/details/gtiaqeikha.html

JS:   toString() { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gtfheuwiht.html

TS:   toString(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtencwxhyl.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtinsgkobc.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gtvihytuhi.html

Ruby: def to_s; @name; end
来源：http://dali.birdmap.top/Article/details/gtpsezymzb.html

C#:   public override string ToString() => Name;
来源：http://dali.chenlongwang.top/Article/details/gtwrkovext.html

[G13] 判断对象类型
来源：http://dali.yueranfly.top/Article/details/gtwlxvrgjd.html

Py:   isinstance(u, User)
来源：http://dali.svipenyu.cn/Article/details/gthnybmkjp.html

PHP:  $u instanceof User
来源：http://dali.yj202588.top/Article/details/gtcbxafumb.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gtmolhzebu.html

TS:   u instanceof User
来源：http://dali.c1oappe.top/Article/details/gtuswyjetn.html

Java: u instanceof User
来源：http://dali.havefunace.top/Article/details/gtrmeiglbf.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.xinyue.icu/Article/details/gtptbqpsff.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnekmwti.html

C#:   u is User
来源：http://dali.birdmap.top/Article/details/gtxtucadxq.html

[G14] 数据类 / record
来源：http://dali.xylfe.cn/Article/details/gttvujbuqc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.svipenyu.cn/Article/details/gtzgslbmhw.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zycfv.cn/Article/details/gttufdsrrf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hammf.cn/Article/details/gtokzfskek.html

TS:   type User = { name: string; age: number };
来源：http://dali.wangshuangyany.cn/Article/details/gtdhmvprev.html

Java: record User(String name, int age) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohnwwujc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zhongyouzk.top/Article/details/gthdsjsnkz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gthqgjnasd.html

C#:   record User(string Name, int Age);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrogqpgp.html

[G15] 枚举
来源：http://dali.redwolf501.top/Article/details/gtlmtwnlyh.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhiwuduotai.top/Article/details/gttclmknmy.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwgojkdli.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinghuilouyu.cn/Article/details/gtexgmgmvv.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtycerngjy.html

Java: enum Color { RED, GREEN }
来源：http://dali.guowangkeji.top/Article/details/gtennagpym.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zdqjudy.top/Article/details/gtwjiowsjh.html

Ruby: Color = %i[red green].freeze
来源：http://dali.bjfxy.top/Article/details/gtxbosjyvp.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtjdwhsfed.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gtkgvqxmxq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.vqdsnc.cn/Article/details/gtpjthfyyn.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gthdcbsuvw.html

JS:   Object.entries(obj)
来源：http://dali.ehwqpu.com/Article/details/gtrtsrejgz.html

TS:   Object.entries(obj)
来源：http://dali.jianghu66.top/Article/details/gtucbtlddg.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zycfv.cn/Article/details/gtungsizal.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.daxiang520.top/Article/details/gtxqdaizsm.html

Ruby: obj.instance_variables
来源：http://dali.shanyushiyangtech.top/Article/details/gteoenvict.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yueranfly.top/Article/details/gtqpvjjxpy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtuygdcctx.html

H. 异常与错误处理
来源：http://dali.gzhubu.top/Article/details/gtybyzhnkl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjnixpktw.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtijasuirm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.jiagoushi.top/Article/details/gtctytmump.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkdicvcuz.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gtjaulzcfy.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xylfe.cn/Article/details/gtfbkhuceo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.gotoacloud.top/Article/details/gtcjbjsodp.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj20258888.top/Article/details/gtnvhfrpox.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zdqjudy.top/Article/details/gtfkfqemiz.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jqgufenzy.top/Article/details/gtbncjrqhx.html

[H02] finally / ensure 收尾
来源：http://dali.sufxvd.cn/Article/details/gtcwyhtsky.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258.top/Article/details/gtchsamtjf.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtpcuvezxo.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.cucudq.cn/Article/details/gtdayqqftw.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gtbuvzvdsv.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.ydzc1.top/Article/details/gttkokqlbp.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhongyouzk.top/Article/details/gtpcapcoax.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.daria6918.cn/Article/details/gtqcxbsbfr.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.quarkkingdee.top/Article/details/gtbjorsmxa.html

[H03] 主动抛出异常
来源：http://dali.zycfv.cn/Article/details/gtjoyqnjpx.html

Py:   raise ValueError("错误信息")
来源：http://dali.cdnleiting.top/Article/details/gtrkccxqbn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.316326.xyz/Article/details/gtvdknfibz.html

JS:   throw new Error("错误信息");
来源：http://dali.guowangkeji.top/Article/details/gtjtejjqtp.html

TS:   throw new Error("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtmmnbuwwh.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yj202588.top/Article/details/gtquaplopt.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtomygzubv.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.ydzc1.top/Article/details/gtlagzvutx.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtrkvmkclx.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gtjsnliyvz.html

Py:   class MyError(Exception): pass
来源：http://dali.redwolf501.top/Article/details/gteffebamp.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yuxming.cn/Article/details/gtwyhilxmf.html

JS:   class MyError extends Error {}
来源：http://dali.gaohongyu789.top/Article/details/gthogbdkru.html

TS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtfmpseklm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.guannengcc.top/Article/details/gtufhticjj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gtjqfaztay.html

Ruby: class MyError < StandardError; end
来源：http://dali.sysykeji.top/Article/details/gtbxnfycsi.html

C#:   class MyException : Exception {}
来源：http://dali.chenzaomai.com/Article/details/gtkbvvkrkb.html

[H05] 捕获特定类型
来源：http://dali.zycfv.cn/Article/details/gttonreecy.html

Py:   except ValueError as e:
来源：http://dali.hywenlv.cn/Article/details/gtdwzedtyk.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.316326.xyz/Article/details/gtehvxepfe.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.yongpay.top/Article/details/gtnzpxkjqs.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.sxryk.cn/Article/details/gttmrnbsvn.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gaohongyu789.top/Article/details/gtvuezfmio.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.chenjidiqi.icu/Article/details/gtvliaqtdn.html

Ruby: rescue ArgumentError => e
来源：http://dali.zhongyouzk.top/Article/details/gttzmcwfbd.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zdqjudy.top/Article/details/gtztjpgqoc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbggchjkn.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gtyoapzarw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.316326.xyz/Article/details/gtlagiszmf.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.nwbrower.top/Article/details/gtxtdfzaaa.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.wangdashe.top/Article/details/gtstrsceba.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hnxiangtu.top/Article/details/gtinupcnoj.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gogol.net.cn/Article/details/gtftrxbxfo.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jinqigfzy.top/Article/details/gtjmcfddtv.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gtezkpralx.html

[H07] 断言
来源：http://dali.daxiang520.top/Article/details/gtulphgapv.html

Py:   assert x > 0, "必须为正"
来源：http://dali.iojbl.cn/Article/details/gtodfxsumh.html

PHP:  assert($x > 0);
来源：http://dali.jqgufenzy.top/Article/details/gtylucdnbm.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtujezgydg.html

TS:   console.assert(x > 0);
来源：http://dali.nwbrower.top/Article/details/gtoftysejr.html

Java: assert x > 0 : "必须为正";
来源：http://dali.shuidangran.top/Article/details/gtxqoglcyq.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.hywenlv.cn/Article/details/gtzfquydka.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.svipenyu.cn/Article/details/gtkkqtumbk.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hammf.cn/Article/details/gtzilczizu.html

[H08] 获取错误信息与堆栈
来源：http://dali.tanke756.top/Article/details/gtbthrarkk.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtybbjbpjg.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.meibo888.top/Article/details/gtcuzubled.html


<!-- 参考信息 -->