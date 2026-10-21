代发 wailian999

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tanke756.top/Article/details/gthwfzhtto.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gtsohwpbsp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gtlqnltcid.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yueranfly.top/Article/details/gteoypxqsu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.kuanghao11.cn/Article/details/gtiqvhygpo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtnlkjxcmu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cqqwz.cn/Article/details/gtgyapdxtj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtttrpyvrd.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgufenzy.top/Article/details/gtxewnjygl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gtantvjoxh.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtlphnorxt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtengyiuwd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtxngsumcw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj202588.top/Article/details/gtzhppgbdl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nanxuanxn.top/Article/details/gtxtztsagj.html

Ruby: File.exist?("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtggmkesnc.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqxozdnc.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gtuxaffdjg.html

Py:   os.remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtbpnltoou.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtcvqqptgm.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gthwojgxxr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtgujrodkm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtrojyajxa.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtaoucujjo.html

Ruby: File.delete("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtposwjgzq.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtpwhxhtkj.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gtcgyrqxzq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtixdezuae.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zycfv.cn/Article/details/gtvwkcbtzm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtsaokzhhb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gtzxouwjoe.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gtnhdkhwhi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.quarkkingdee.top/Article/details/gtflrihegi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daria6918.cn/Article/details/gturobaruz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gtdhcifthl.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtbzinqgmy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tanke756.top/Article/details/gtxyvoylxt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zdqjudy.top/Article/details/gtcyrbrxxq.html

JS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtrewfnqoi.html

TS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gtmwwiomzi.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtstwzhhck.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nwbrower.top/Article/details/gtstupgxbu.html

Ruby: Dir.children("dir")
来源：http://dali.meibo888.top/Article/details/gtpcdniweb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.0kj1m.cn/Article/details/gtrfevdztg.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtrlwrwwka.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtboicbcol.html

PHP:  filesize("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gtofrdbipr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtblpqipno.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtiirriniu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gtpjkqkjbz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.redwolf501.top/Article/details/gtpdbivgcy.html

Ruby: File.size("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtbqvzcfrn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hfpthk.cn/Article/details/gthrmyllzj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtnfergcwt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtsxuqneod.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gthhxwvqae.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtcdgmyayt.html

TS:   path.extname("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstmnkuae.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cdnleiting.top/Article/details/gtbxgwhymo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtyjxgiupj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtuifoeiaz.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtveitfbyr.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtvkudpusx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gtewkywunv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.iojbl.cn/Article/details/gthqnwywre.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugrupnda.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmhhiyer.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhbqifbx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sxryk.cn/Article/details/gtpbtnltvd.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtejazjkpg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnqzz.top/Article/details/gtskfmdhax.html

[F12] CSV 读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfiixfapg.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gtsuiupumq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cashguo.top/Article/details/gtrmplmgbe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinqigfzy.top/Article/details/gtqwzsnqjg.html

TS:   // 同上
来源：http://dali.jlsjyb.cn/Article/details/gtqbyhlqbn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gthubqxewk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.havefunace.top/Article/details/gtagllyxqm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gzhubu.top/Article/details/gtlpoydztq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gtyrpebied.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxlzcggaa.html

G. 面向对象
来源：http://dali.zdqjudy.top/Article/details/gthbfbcvif.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtyqruslls.html

[G01] 定义类
来源：http://dali.smart0.xyz/Article/details/gtxulnlotq.html

Py:   class User: pass
来源：http://dali.zdqjudy.top/Article/details/gtasmfvzwj.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gtsisaxbzz.html

JS:   class User {}
来源：http://dali.jinqigufen.top/Article/details/gtqjqeqqss.html

TS:   class User { name: string = ""; }
来源：http://dali.nanxinkj.top/Article/details/gttxrcsiwg.html

Java: class User {}
来源：http://dali.sweek.top/Article/details/gteukywxms.html

Go:   type User struct { Name string }
来源：http://dali.ivvv.top/Article/details/gtiftrnbwx.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtdbhszjzi.html

C#:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtbzjddmem.html

[G02] 构造函数
来源：http://dali.c1oappe.top/Article/details/gttzambckd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gtxipzrina.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.mhx1999.top/Article/details/gtghwghiub.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hnqzz.top/Article/details/gttedwzryy.html

TS:   constructor(public name: string) {}
来源：http://dali.hywenlv.cn/Article/details/gtaltbwhwz.html

Java: User(String name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtuijlbppo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtevpaqqsy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zdqjudy.top/Article/details/gthrqadheb.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gthxtztzld.html

[G03] 实例属性
来源：http://dali.aibaodan.cn/Article/details/gtjarazaro.html

Py:   self.name = "x"
来源：http://dali.pycfn.com/Article/details/gtumcosssa.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtqtsclgnl.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gtgnlbfkad.html

TS:   name: string = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtuklxzffh.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gtxotedblg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gtddjqbwok.html

Ruby: @name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtggmtnbrb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenzaomai.com/Article/details/gtjjtgnnte.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gtplkgxhzu.html

Py:   def greet(self): return self.name
来源：http://dali.hongshengwenyu.top/Article/details/gtuqnglgfc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.0kj1m.cn/Article/details/gtmjlnazrg.html

JS:   greet() { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gtvcywsyiy.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtresebmpk.html

Java: String greet() { return name; }
来源：http://dali.guowangkeji.top/Article/details/gtrdgwfenr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gtafayujbi.html

Ruby: def greet; @name; end
来源：http://dali.zycfv.cn/Article/details/gtquiellpl.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtjfikdqke.html

[G05] 继承
来源：http://dali.jyoumei.cn/Article/details/gtnvggmcjw.html

Py:   class Admin(User): pass
来源：http://dali.quarkkingdee.top/Article/details/gtykxxqmhd.html

PHP:  class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gtnvwbbfhf.html

JS:   class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtbsrbgolb.html

TS:   class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gtctqqvkfa.html

Java: class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjdchajmb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yvedp.cn/Article/details/gtpqmfvydj.html

Ruby: class Admin < User; end
来源：http://dali.ybcxt.top/Article/details/gtxlhixpvq.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gtpkotlftg.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gttdvhxguk.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpkcllof.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xinyue.icu/Article/details/gtvnevlodw.html

JS:   greet() { return "admin"; }
来源：http://dali.tanke756.top/Article/details/gtxttxsuon.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gtwidqufwo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ydzc1.top/Article/details/gtigmxzdiu.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ydzc1.top/Article/details/gtbmylspph.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gtkazjwdos.html

C#:   public override string Greet() => "admin";
来源：http://dali.yuanzhike.top/Article/details/gtrogiihpi.html

[G07] 调用父类方法
来源：http://dali.yj202588.top/Article/details/gtchprnxgv.html

Py:   super().greet()
来源：http://dali.tanke756.top/Article/details/gtwvpdqffm.html

PHP:  parent::greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtxftgchie.html

JS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtwqfjrrxs.html

TS:   super.greet();
来源：http://dali.316326.xyz/Article/details/gtaqfdndzj.html

Java: super.greet();
来源：http://dali.yj20258888.top/Article/details/gttrkikzku.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sxryk.cn/Article/details/gtjqaghgny.html

Ruby: super
来源：http://dali.aizwys.cn/Article/details/gtvuyigjdb.html

C#:   base.Greet();
来源：http://dali.gogol.net.cn/Article/details/gtnfclvsbl.html

[G08] 静态方法与属性
来源：http://dali.ydzc1.top/Article/details/gtfitbodmh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gtkyunomax.html

PHP:  public static function f() {}
来源：http://dali.smart0.xyz/Article/details/gtyisgsvua.html

JS:   static f() {}
来源：http://dali.hnqzz.top/Article/details/gtsqifrcfv.html

TS:   static f(): void {}
来源：http://dali.cashguo.top/Article/details/gtaswanlpw.html

Java: static void f() {}
来源：http://dali.hysaishi.cn/Article/details/gtawoopakn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cashguo.top/Article/details/gtnpiktymv.html

Ruby: def self.f; end
来源：http://dali.yangfankeji.com/Article/details/gtsltxlahq.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkwdmuquv.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gticufwihh.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cqqwz.cn/Article/details/gtptrrnwpf.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hywenlv.cn/Article/details/gtepudonha.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yvedp.cn/Article/details/gtyqhizssw.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gtrbhcvqap.html

Java: interface Shape { double area(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxchxtqd.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.gogol.net.cn/Article/details/gtdqdstzsq.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gtzuriknhv.html

C#:   interface IShape { double Area(); }
来源：http://dali.birdmap.top/Article/details/gtnsyxlilo.html

[G10] 访问控制
来源：http://dali.gzhubu.top/Article/details/gtjwtugjcy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gotoacloud.top/Article/details/gtcfnycaws.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gtrhzgfhnf.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gtmzdtsett.html

TS:   public / protected / private
来源：http://dali.yvedp.cn/Article/details/gtmalfllgi.html

Java: public / protected / private / 默认包级
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzapnvlu.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.redwolf501.top/Article/details/gtjhvcbsvq.html

Ruby: public / protected / private
来源：http://dali.wangdashe.top/Article/details/gtczyisfsj.html

C#:   public / protected / private / internal
来源：http://dali.nanxuanxn.top/Article/details/gtenxdviti.html

[G11] getter / setter
来源：http://dali.hnqzz.top/Article/details/gtdwrorrtn.html

Py:   @property 与 @x.setter
来源：http://dali.nanxuanxn.top/Article/details/gtktskdjiy.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuvtcdjag.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gtbqqyvfda.html

TS:   get name(): string { return this._name; }
来源：http://dali.0kj1m.cn/Article/details/gtdqrhoyxa.html

Java: public String getName() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtwutbgjqu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yanxiufei.cn/Article/details/gtyaundodq.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtdqpoghqs.html

C#:   public string Name { get; set; }
来源：http://dali.dianchejie.cn/Article/details/gtlfihflko.html

[G12] 对象转字符串
来源：http://dali.hywenlv.cn/Article/details/gthoprdvpk.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gtxsnidewi.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.iojbl.cn/Article/details/gtdccqllur.html

JS:   toString() { return this.name; }
来源：http://dali.xziqi.cn/Article/details/gtibqrroxm.html

TS:   toString(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gtpnhicier.html

Java: @Override public String toString() { return name; }
来源：http://dali.fengsongda.top/Article/details/gtsgenvsen.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtbrvbckvi.html

Ruby: def to_s; @name; end
来源：http://dali.daria6918.cn/Article/details/gtiylorbbg.html

C#:   public override string ToString() => Name;
来源：http://dali.nanxuanxn.top/Article/details/gttmraqixp.html

[G13] 判断对象类型
来源：http://dali.ivvv.top/Article/details/gtghpgejsj.html

Py:   isinstance(u, User)
来源：http://dali.bjfxy.top/Article/details/gtubnoavlj.html

PHP:  $u instanceof User
来源：http://dali.xylfe.cn/Article/details/gtitiufddd.html

JS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gtahyzgfvq.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gturylfdzk.html

Java: u instanceof User
来源：http://dali.gzhubu.top/Article/details/gteaukvovh.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.feifeiyinyue.top/Article/details/gtdqfcbonu.html

Ruby: u.is_a?(User)
来源：http://dali.hysaishi.cn/Article/details/gtiglxdprf.html

C#:   u is User
来源：http://dali.cashguo.top/Article/details/gtkmknbuit.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gtloxwzqsu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.nwbrower.top/Article/details/gtwbiktfso.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.hammf.cn/Article/details/gtiyiorych.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daria6918.cn/Article/details/gtzjmgbaxw.html

TS:   type User = { name: string; age: number };
来源：http://dali.xziqi.cn/Article/details/gtchitmnjk.html

Java: record User(String name, int age) {}
来源：http://dali.hysaishi.cn/Article/details/gtnkpuwkbb.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gzhubu.top/Article/details/gtwtapodtf.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tian-w.cn/Article/details/gtuvkdjsmx.html

C#:   record User(string Name, int Age);
来源：http://dali.jianghu66.top/Article/details/gtyuhnamge.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gtnguwlhom.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.cashguo.top/Article/details/gtmekfyexi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.gaohongyu789.top/Article/details/gtwzbprqkg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.sufxvd.cn/Article/details/gtxauptwzf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtwdsxyrhi.html

Java: enum Color { RED, GREEN }
来源：http://dali.iojbl.cn/Article/details/gtlsgqmpwm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.iojbl.cn/Article/details/gtxzapazuc.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xuetiantiany.cn/Article/details/gtlrtcsviy.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.havefunace.top/Article/details/gtfxnypbuq.html

[G16] 对象转数组 / 字典
来源：http://dali.jyoumei.cn/Article/details/gtdztcaapr.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gtmqbejquq.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtnisgbpeh.html

JS:   Object.entries(obj)
来源：http://dali.dashuyun.cn/Article/details/gtyqsdhqcd.html

TS:   Object.entries(obj)
来源：http://dali.snrcjt.cn/Article/details/gtqbofjeqy.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ydzc1.top/Article/details/gtbrlacdze.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gtxijnpmqx.html

Ruby: obj.instance_variables
来源：http://dali.shangyingyoupin.top/Article/details/gtiapkkgsw.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.sufxvd.cn/Article/details/gtobbfcydd.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtamxlifpf.html

H. 异常与错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtjetfbiod.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gteowpehhh.html

[H01] try / catch 基础
来源：http://dali.yj20258.top/Article/details/gtkpxtxxdl.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.yangfankeji.com/Article/details/gtvbxxbneo.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cashguo.top/Article/details/gtwpgtedgm.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtecpmnvsd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtourqayof.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlcnqzwia.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.bjfxy.top/Article/details/gthtnbcvne.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhijiandao.cn/Article/details/gtlqdaigok.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.sweek.top/Article/details/gtqhjqqiou.html

[H02] finally / ensure 收尾
来源：http://dali.yuanzhike.top/Article/details/gtlpidirds.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.quarkkingdee.top/Article/details/gtjxjpasjk.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gthshdmobm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsbwuttef.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujfoembj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtuqdtvfed.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.c1oappe.top/Article/details/gthgtlvhed.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.vqdsnc.cn/Article/details/gtbmmronlx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoinqfqrj.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtwqvuveug.html

Py:   raise ValueError("错误信息")
来源：http://dali.yuxming.cn/Article/details/gtrndszhga.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.iojbl.cn/Article/details/gtrpxliyhy.html

JS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gtbjuulutu.html

TS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtaeliagmz.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gtqexaopgv.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.jinqigfzy.top/Article/details/gtfacpcucg.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.nanxuanxn.top/Article/details/gtgwdrhnaj.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.shzxlz.cn/Article/details/gtdltugcnq.html

[H04] 自定义异常类型
来源：http://dali.xylfe.cn/Article/details/gtxrsfdlbr.html

Py:   class MyError(Exception): pass
来源：http://dali.daxiang520.top/Article/details/gtzcfltjfb.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yongpay.top/Article/details/gtubttnplu.html

JS:   class MyError extends Error {}
来源：http://dali.vqdsnc.cn/Article/details/gtbfyaltro.html

TS:   class MyError extends Error {}
来源：http://dali.jinqigufen.top/Article/details/gtcilwqyvk.html

Java: class MyException extends RuntimeException {}
来源：http://dali.chenzaomai.com/Article/details/gthvveycyh.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.smart0.xyz/Article/details/gtvvradwit.html

Ruby: class MyError < StandardError; end
来源：http://dali.sufxvd.cn/Article/details/gttwmnwdvy.html

C#:   class MyException : Exception {}
来源：http://dali.jqgfzy.top/Article/details/gtjwewjgpt.html

[H05] 捕获特定类型
来源：http://dali.wangshuangyany.cn/Article/details/gtsqddrrxr.html

Py:   except ValueError as e:
来源：http://dali.guannengcc.top/Article/details/gtlzvaojjr.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.zycfv.cn/Article/details/gtecktsdej.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtqgbxhvgz.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.xinyue.icu/Article/details/gtreqqfwun.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.jyoumei.cn/Article/details/gtkwqamowh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yuxming.cn/Article/details/gtdmcxzuza.html

Ruby: rescue ArgumentError => e
来源：http://dali.havefunace.top/Article/details/gttvsxbhry.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.chenlongwang.top/Article/details/gtpjjqgjsm.html

[H06] 可选值 / 空值安全访问
来源：http://dali.yongpay.top/Article/details/gtoxpuodfw.html

Py:   value = d.get("k") or default
来源：http://dali.gzhubu.top/Article/details/gtqvziwlhg.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.wangshuangyany.cn/Article/details/gtlhgskhko.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.cucudq.cn/Article/details/gtnqcbwoub.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.daxiang520.top/Article/details/gtxrucfavt.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.hfpthk.cn/Article/details/gtpcalhhqp.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.jianghu66.top/Article/details/gtdalakkwm.html

Ruby: d&.dig(:a, :b)
来源：http://dali.shangyingyoupin.top/Article/details/gtrpmzgtty.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtinwkujua.html

[H07] 断言
来源：http://dali.jqgfzy.top/Article/details/gtfihufdml.html

Py:   assert x > 0, "必须为正"
来源：http://dali.havefunace.top/Article/details/gtwytfsyls.html

PHP:  assert($x > 0);
来源：http://dali.tian-w.cn/Article/details/gtdckxxdif.html

JS:   console.assert(x > 0);
来源：http://dali.jiagoushi.top/Article/details/gtzzlcjtee.html

TS:   console.assert(x > 0);
来源：http://dali.pycfn.com/Article/details/gtjcailmru.html

Java: assert x > 0 : "必须为正";
来源：http://dali.0kj1m.cn/Article/details/gtkbnovwwy.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ppjwa.cn/Article/details/gtmakviyfj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258.top/Article/details/gtggjubcjf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.yj20258888.top/Article/details/gtfwqdguzt.html

[H08] 获取错误信息与堆栈
来源：http://dali.316326.xyz/Article/details/gtpcpqcqzp.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.shzxlz.cn/Article/details/gttvlysuqc.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gtkjpfmplj.html

JS:   e.message;  e.stack
来源：http://dali.gogol.net.cn/Article/details/gtkuxefcof.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yongpay.top/Article/details/gtzutezdpu.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbieaxyv.html

Go:   err.Error()
来源：http://dali.daxiang520.top/Article/details/gtznvjxwgx.html


<!-- 参考信息 -->