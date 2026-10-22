代发 wailian999

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkpmzbxh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtlgeiwsbb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aibaodan.cn/Article/details/gtojjstwdd.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtflunrgtj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhoulong.xyz/Article/details/gtkhrhqrlg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwmmvwwv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhengqikj.top/Article/details/gtatvimlzs.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gtwoyqjgse.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylvorerf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gtoypjplmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtrclatpjr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gtnpnswbvj.html

[F05] 判断文件或目录是否存在
来源：http://dali.andypj.xyz/Article/details/gtjwkvmbjn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtvtiwcmfx.html

PHP:  file_exists("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtttozjakb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtuunuumhf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsmrlwmkk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtggjdzhbm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtjaxpmfpx.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtyilgeopo.html

C#:   File.Exists("a.txt")
来源：http://dali.yongpay.top/Article/details/gtayrqhtoy.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gtgodybhzf.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtyxrgpwbc.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtlluhklee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtxchdahqr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gthhfdddkv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.fengsongda.top/Article/details/gtnbqdvpln.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtaatecrpr.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtjnbthuhs.html

C#:   File.Delete("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtgeuiknhe.html

[F07] 创建目录（含多级）
来源：http://dali.xylfe.cn/Article/details/gtqxtfhnep.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtogswnqoq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.haohaochexian.top/Article/details/gtjfocphvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtcpgpbggt.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yongpay.top/Article/details/gtqrmvkuwg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258888.top/Article/details/gtrbaqttyj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gtjjzzfcsd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.fzhhl.top/Article/details/gtqcetydnw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gaohongyu789.top/Article/details/gtntytkksz.html

[F08] 遍历目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijybvgys.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jiagoushi.top/Article/details/gtmxanujty.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sxryk.cn/Article/details/gtfmlailbs.html

JS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtejogdgub.html

TS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gttscbjkyo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtkzrgeozt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtxuaiyuji.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtipjlbajb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyvgbdtp.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtteboaenq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtfdvzvrlt.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtogpsngks.html

JS:   fs.statSync("a.txt").size
来源：http://dali.316326.xyz/Article/details/gtgxjxcpmv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.quarkkingdee.top/Article/details/gtdqeqipus.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtrceroubv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfrhmnbf.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtalerkvcu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtbowqjhot.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gtaalbbzwr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtileeremk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.ivvv.top/Article/details/gtupnvdjnh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtcbykkygq.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtkdcqlphq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhongyouzk.top/Article/details/gtbxyboxfz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtxukmoayk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtoslctzvf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtramnjqsf.html

[F11] 复制与移动文件
来源：http://dali.guannengcc.top/Article/details/gttstujcbd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gtakhfxyqr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gtzxcluenx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtpsfuatoi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtiaevuogb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.guannengcc.top/Article/details/gtwjeojbqf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gtsqvwzkcs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtepiwrcei.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gttpuhkyay.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtuvaidoby.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yj202588.top/Article/details/gtbylxqlaa.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cheryme.top/Article/details/gtupnpusqk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.tianlin.xyz/Article/details/gtwjsfwjua.html

TS:   // 同上
来源：http://dali.cashguo.top/Article/details/gtfuccznpl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yvedp.cn/Article/details/gtkzdvjoqg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ydzc1.top/Article/details/gtwgudhusl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gotoacloud.top/Article/details/gtjafprdtv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.wangshuangyany.cn/Article/details/gtzedfbtmu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtekmgvhmi.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gteplfxmfr.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gteykfhvtc.html

[G01] 定义类
来源：http://dali.shzxlz.cn/Article/details/gthkqdgcav.html

Py:   class User: pass
来源：http://dali.cheryme.top/Article/details/gtxwitnolo.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gtdjuseacg.html

JS:   class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gtckjcwhuj.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvymudfim.html

Java: class User {}
来源：http://dali.wangdashe.top/Article/details/gtavxckfev.html

Go:   type User struct { Name string }
来源：http://dali.guowangkeji.top/Article/details/gtnbrbbcat.html

Ruby: class User; end
来源：http://dali.nanxuanxn.top/Article/details/gtsuplkuqv.html

C#:   class User {}
来源：http://dali.316326.xyz/Article/details/gtesjnzvny.html

[G02] 构造函数
来源：http://dali.andypj.xyz/Article/details/gtstiggloo.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtwneukrfs.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.aibaodan.cn/Article/details/gtfatvriel.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtbarkctnf.html

TS:   constructor(public name: string) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuoewjlr.html

Java: User(String name) { this.name = name; }
来源：http://dali.aizwys.cn/Article/details/gtfivzzgkg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xinyue.icu/Article/details/gtyqsrjnxz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.daria6918.cn/Article/details/gtfbqzrcda.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhoulong.xyz/Article/details/gtkyzkdhex.html

[G03] 实例属性
来源：http://dali.quarkkingdee.top/Article/details/gtmyqdhdci.html

Py:   self.name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynspxtph.html

PHP:  public string $name = "x";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyihzlzm.html

JS:   this.name = "x";
来源：http://dali.sufxvd.cn/Article/details/gtvtyoopdm.html

TS:   name: string = "x";
来源：http://dali.bjfxy.top/Article/details/gtwboqxvga.html

Java: private String name;
来源：http://dali.jqgufenzy.top/Article/details/gtyyprcqqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.iojbl.cn/Article/details/gtkdobzqit.html

Ruby: @name = "x"
来源：http://dali.cqqwz.cn/Article/details/gtlsfioiun.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.gotoacloud.top/Article/details/gtxnlgdqsl.html

[G04] 定义方法
来源：http://dali.yueranfly.top/Article/details/gtrxauarss.html

Py:   def greet(self): return self.name
来源：http://dali.sufxvd.cn/Article/details/gtfuayeyrl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gaohongyu789.top/Article/details/gtypgvgybr.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gtpnvgqtdk.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjptvepj.html

Java: String greet() { return name; }
来源：http://dali.bjfxy.top/Article/details/gtvlmgpqpx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtxrfbzspv.html

Ruby: def greet; @name; end
来源：http://dali.c1oappe.top/Article/details/gthsamgkmn.html

C#:   public string Greet() => Name;
来源：http://dali.nwbrower.top/Article/details/gtrqmbnagg.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtshpeisye.html

Py:   class Admin(User): pass
来源：http://dali.yuanzhike.top/Article/details/gtuysdmgxv.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gtwxmtnhph.html

JS:   class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtepgaguvt.html

TS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzrlwwmc.html

Java: class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gttoygeihw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gtyfcbmlbo.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtjmldbsev.html

C#:   class Admin : User {}
来源：http://dali.shuidangran.top/Article/details/gtkslslduj.html

[G06] 重写方法
来源：http://dali.daxiang520.top/Article/details/gtafpmkmvj.html

Py:   def greet(self): return "admin"
来源：http://dali.tanke756.top/Article/details/gtgxxmrtma.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtkynmhhrw.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gturnhyzoi.html

TS:   greet(): string { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gtvlowlqqp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cdnleiting.top/Article/details/gtprojemhm.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gtfiuvzxjc.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtyuhbnrbk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gttrpkeixk.html

[G07] 调用父类方法
来源：http://dali.ydzc1.top/Article/details/gtdjwfbvth.html

Py:   super().greet()
来源：http://dali.zhengqikj.top/Article/details/gtnsvnmkzg.html

PHP:  parent::greet();
来源：http://dali.yueranfly.top/Article/details/gtlhbvxytz.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gtwreiayus.html

TS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtpyupjhsf.html

Java: super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtjfwwpagf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gthqdwijmj.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gtwokgdoug.html

C#:   base.Greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspilqjbi.html

[G08] 静态方法与属性
来源：http://dali.smart0.xyz/Article/details/gtaxdowefa.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinqigfzy.top/Article/details/gtprmbkjui.html

PHP:  public static function f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtcvrzdstt.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtlxkfyfev.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtastzjcnk.html

Java: static void f() {}
来源：http://dali.shuidangran.top/Article/details/gtzlpveior.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gtmitkatlr.html

Ruby: def self.f; end
来源：http://dali.iojbl.cn/Article/details/gtlmaqnrgo.html

C#:   public static void F() {}
来源：http://dali.redwolf501.top/Article/details/gtoqbkhymm.html

[G09] 接口 / 抽象类
来源：http://dali.guannengcc.top/Article/details/gtjwzhubsv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj20258888.top/Article/details/gtexkfntkn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.gaohongyu789.top/Article/details/gtdkfymgke.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jianghu66.top/Article/details/gtpzndmbeq.html

TS:   interface Shape { area(): number; }
来源：http://dali.iojbl.cn/Article/details/gtwbozpsxh.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gtoxmhmpqq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtwhcfrskr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sufxvd.cn/Article/details/gtnkbcsfvx.html

C#:   interface IShape { double Area(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtauwflwpt.html

[G10] 访问控制
来源：http://dali.chenlongwang.top/Article/details/gtwsrvnxns.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.bjfxy.top/Article/details/gtvfkcsmyh.html

PHP:  public / protected / private
来源：http://dali.chenlongwang.top/Article/details/gtxnnewsuv.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gtnwkyrsmk.html

TS:   public / protected / private
来源：http://dali.pengpengdd.cyou/Article/details/gtvllyjwgu.html

Java: public / protected / private / 默认包级
来源：http://dali.xylfe.cn/Article/details/gttfknjhss.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.cheryme.top/Article/details/gtjqfowwhc.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gtzojhrnaf.html

C#:   public / protected / private / internal
来源：http://dali.kuanghao11.cn/Article/details/gtdnspksul.html

[G11] getter / setter
来源：http://dali.yj20258.top/Article/details/gtwbxznzls.html

Py:   @property 与 @x.setter
来源：http://dali.zhijiandao.cn/Article/details/gtqoaontok.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhijiandao.cn/Article/details/gtckbudswu.html

JS:   get name() { return this._name; }
来源：http://dali.ydzc1.top/Article/details/gtnpbtqphl.html

TS:   get name(): string { return this._name; }
来源：http://dali.mhx1999.top/Article/details/gtvnktqppt.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gtuopsojas.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gtxhzjkuni.html

Ruby: attr_accessor :name
来源：http://dali.tian-w.cn/Article/details/gtsnumbtyk.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gtbdklzttk.html

[G12] 对象转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfupomjp.html

Py:   def __str__(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gtwnngiczn.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yangfankeji.com/Article/details/gtkbuscrel.html

JS:   toString() { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gtqzsfoudf.html

TS:   toString(): string { return this.name; }
来源：http://dali.nanxinkj.top/Article/details/gtyqnbafqv.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtmdbqiyku.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.daria6918.cn/Article/details/gtkllguyov.html

Ruby: def to_s; @name; end
来源：http://dali.daxiang520.top/Article/details/gtwhdlcetf.html

C#:   public override string ToString() => Name;
来源：http://dali.ppjwa.cn/Article/details/gtoqsxiujt.html

[G13] 判断对象类型
来源：http://dali.zhongyouzk.top/Article/details/gthucreors.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gtofgvhxuv.html

PHP:  $u instanceof User
来源：http://dali.snrcjt.cn/Article/details/gtvaupkuqz.html

JS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gtesfcyrar.html

TS:   u instanceof User
来源：http://dali.jqgfzy.top/Article/details/gtzzhougdb.html

Java: u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtzpsphddm.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.ivvv.top/Article/details/gtanjwwafr.html

Ruby: u.is_a?(User)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrdqewgg.html

C#:   u is User
来源：http://dali.smart0.xyz/Article/details/gtblatcyfn.html

[G14] 数据类 / record
来源：http://dali.hfpthk.cn/Article/details/gtmmdeeshm.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yuxming.cn/Article/details/gthgbuxpgq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.c1oappe.top/Article/details/gtmgclwykx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cucudq.cn/Article/details/gtluaxbhgd.html

TS:   type User = { name: string; age: number };
来源：http://dali.ybcxt.top/Article/details/gttsxrhadv.html

Java: record User(String name, int age) {}
来源：http://dali.hnqzz.top/Article/details/gtnqrvakqt.html

Go:   type User struct { Name string; Age int }
来源：http://dali.zdqjudy.top/Article/details/gtocitkflw.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ydzc1.top/Article/details/gtisdjlwbt.html

C#:   record User(string Name, int Age);
来源：http://dali.dianchejie.cn/Article/details/gttpjnmzwc.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtycwravui.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.hysaishi.cn/Article/details/gtoesptzfm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtlnlqgzft.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.birdmap.top/Article/details/gtduoiwpys.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtufeoec.html

Java: enum Color { RED, GREEN }
来源：http://dali.chenlongwang.top/Article/details/gtinzotipe.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.mhx1999.top/Article/details/gtfrxrydyn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.jyoumei.cn/Article/details/gtynjdfrna.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fzhhl.top/Article/details/gthconmgtu.html

[G16] 对象转数组 / 字典
来源：http://dali.yuxming.cn/Article/details/gtprkyphwj.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gtfyyglunw.html

PHP:  get_object_vars($obj);
来源：http://dali.xuanzx.com/Article/details/gtrmpitfcg.html

JS:   Object.entries(obj)
来源：http://dali.shuidangran.top/Article/details/gtbzlsmouw.html

TS:   Object.entries(obj)
来源：http://dali.aizwys.cn/Article/details/gtznysrpxv.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.svipenyu.cn/Article/details/gtlzrviljo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gtninfwisq.html

Ruby: obj.instance_variables
来源：http://dali.zhengqikj.top/Article/details/gtkbpyluld.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.haohaochexian.top/Article/details/gtarmetovm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtstvktstd.html

H. 异常与错误处理
来源：http://dali.redwolf501.top/Article/details/gtlioovlsy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtudtaebze.html

[H01] try / catch 基础
来源：http://dali.svipenyu.cn/Article/details/gtmgnxrcmb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hnqzz.top/Article/details/gtfvpjnmjw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ppjwa.cn/Article/details/gtwpyshugo.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gtoxhkyznj.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtrgejqlgz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yuanzhike.top/Article/details/gtidqkjbjb.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.yj202588.top/Article/details/gtgybiidru.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gtrtkzsgrd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gaohongyu789.top/Article/details/gtgmeulvkk.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gtbrhzulse.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.ybcxt.top/Article/details/gtgcxsdubs.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gtsbywvqcw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gtdevosfhl.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gtsfrnshjx.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.gogol.net.cn/Article/details/gtvhrlvapz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hnxiangtu.top/Article/details/gtypmlbjqw.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zhongyouzk.top/Article/details/gtbjsbndyi.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gtrsqjzpxg.html

[H03] 主动抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhwtwuax.html

Py:   raise ValueError("错误信息")
来源：http://dali.cqqwz.cn/Article/details/gtuibtmpdu.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.jyoumei.cn/Article/details/gthkpgttkr.html

JS:   throw new Error("错误信息");
来源：http://dali.birdmap.top/Article/details/gtrxaafgfy.html

TS:   throw new Error("错误信息");
来源：http://dali.yuanzhike.top/Article/details/gtnzqzcspu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.aizwys.cn/Article/details/gtpcajhsnu.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gaohongyu789.top/Article/details/gtjvwewuuf.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.yj202588.top/Article/details/gtkvrcvjdh.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.sxryk.cn/Article/details/gthfebxofu.html

[H04] 自定义异常类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifxhkfnj.html

Py:   class MyError(Exception): pass
来源：http://dali.gogol.net.cn/Article/details/gteyqroowu.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.jianghu66.top/Article/details/gtrkhicsxb.html

JS:   class MyError extends Error {}
来源：http://dali.sysykeji.top/Article/details/gthoavnvci.html

TS:   class MyError extends Error {}
来源：http://dali.fengsongda.top/Article/details/gtkenbarow.html

Java: class MyException extends RuntimeException {}
来源：http://dali.redwolf501.top/Article/details/gtdpwimsvd.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.pycfn.com/Article/details/gteyaxyykg.html

Ruby: class MyError < StandardError; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwluuboeb.html

C#:   class MyException : Exception {}
来源：http://dali.gotoacloud.top/Article/details/gtjzxxvvas.html

[H05] 捕获特定类型
来源：http://dali.0kj1m.cn/Article/details/gthsspaghw.html

Py:   except ValueError as e:
来源：http://dali.tanke756.top/Article/details/gttbqrqsgm.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.birdmap.top/Article/details/gtkyzfgudb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.smart0.xyz/Article/details/gtfubucutc.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.kuanghao11.cn/Article/details/gtbhgscias.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gtqijxhhne.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj202588.top/Article/details/gtwazcnhse.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyavdnysz.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xinyue.icu/Article/details/gtfpthrqfs.html

[H06] 可选值 / 空值安全访问
来源：http://dali.jinghuilouyu.cn/Article/details/gtydowtxyq.html

Py:   value = d.get("k") or default
来源：http://dali.xinyue.icu/Article/details/gtjhqnycdb.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.tanke756.top/Article/details/gtftklepgb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.hysaishi.cn/Article/details/gtcpvwrslq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.gaohongyu789.top/Article/details/gtnlsusxkq.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.feifeiyinyue.top/Article/details/gtxainjsfs.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.ehwqpu.com/Article/details/gtecyyzocw.html

Ruby: d&.dig(:a, :b)
来源：http://dali.yuxming.cn/Article/details/gtzgcrzddp.html

C#:   obj?.A?.B ?? default
来源：http://dali.dashuyun.cn/Article/details/gteqmssfez.html

[H07] 断言
来源：http://dali.nanxinkj.top/Article/details/gtkhlasggq.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zhengqikj.top/Article/details/gtsddreaxp.html

PHP:  assert($x > 0);
来源：http://dali.birdmap.top/Article/details/gtdwjbdjtx.html

JS:   console.assert(x > 0);
来源：http://dali.cheryme.top/Article/details/gtyrfwtxio.html

TS:   console.assert(x > 0);
来源：http://dali.yuanzhike.top/Article/details/gtjaqqqtnk.html

Java: assert x > 0 : "必须为正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuvemrme.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ybcxt.top/Article/details/gtwulixugb.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.pengpengdd.cyou/Article/details/gtdoahcoug.html

C#:   Debug.Assert(x > 0);
来源：http://dali.smart0.xyz/Article/details/gthmzyhwim.html

[H08] 获取错误信息与堆栈
来源：http://dali.jinghuilouyu.cn/Article/details/gtlheayyyx.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.pengpengdd.cyou/Article/details/gtavhmtdot.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskljmkyb.html


<!-- 参考信息 -->