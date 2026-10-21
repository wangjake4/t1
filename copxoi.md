代发 wailian999

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdlptnzv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258.top/Article/details/gtvylfdtfc.html

[F03] 写入文件（覆盖）
来源：http://dali.smart0.xyz/Article/details/gtrrrexccy.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbnakkow.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gtwmdlegjb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthznnakpi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gtmgfiqkqa.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtutkvxqpb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gtpakopgtr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtqhprdkre.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gtiuxwirvw.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gtothzrhnn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ivvv.top/Article/details/gtdwymiuic.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtxywpksjy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtwchvmnee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmqqrvzw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtgemsqrns.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenlongwang.top/Article/details/gtyfxvsjia.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtxjdpyulf.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gtoafjrdxp.html

[F05] 判断文件或目录是否存在
来源：http://dali.ehwqpu.com/Article/details/gtjyviiewp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtcliedzow.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gtcgzavowz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtpzttqalm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyjfcvpmq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtzbvfyrvk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtzpkxtlkb.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvawqofze.html

C#:   File.Exists("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtksdzztwa.html

[F06] 删除文件
来源：http://dali.dianchejie.cn/Article/details/gtecbnyxxy.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtmdxgskjx.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtzczugmht.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtakjvthpp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtwxwtrxas.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtvfcpdjgh.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtcthledtc.html

Ruby: File.delete("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gthsewifkq.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtggiejfzc.html

[F07] 创建目录（含多级）
来源：http://dali.cashguo.top/Article/details/gtwcyrdgyd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtwhgxuoxb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gtxtsgqfhn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gtjrqmeaqz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtvtkjxcsw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.redwolf501.top/Article/details/gtndxjjkyi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gaohongyu789.top/Article/details/gtumklipwu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtnpvmxbot.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ivvv.top/Article/details/gttemtwinm.html

[F08] 遍历目录
来源：http://dali.hfpthk.cn/Article/details/gthmnfuwfq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtctraqhcx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aizwys.cn/Article/details/gtymuneytr.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtcxezoiza.html

TS:   fs.readdirSync("dir")
来源：http://dali.mhx1999.top/Article/details/gttpahkiho.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gtltfkwiij.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xylfe.cn/Article/details/gtljnzxwor.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gtyinrlorn.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyruowwf.html

[F09] 获取文件大小
来源：http://dali.jqgfzy.top/Article/details/gtplzndzyt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtchnwygzm.html

PHP:  filesize("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtcctresgl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtubfrnjsj.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtrchwuhvu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtgfezzikr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouhsjjit.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtgnrisyqv.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvvetttv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhixingplan.top/Article/details/gtaiqpnbbo.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtmsgcgvxc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gthslpvsjo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtirxvoucu.html

TS:   path.extname("a.txt")
来源：http://dali.sweek.top/Article/details/gtxlbinmgx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shangyingyoupin.top/Article/details/gtehievypt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtxohuzqks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtdjtpzkcd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkcwyfdwp.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtvlezqirc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gtetepoyxv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtytzlytkf.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkbdsoiwz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gttjvsjkzn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gtcocngwuj.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhongyouzk.top/Article/details/gtigaqkaco.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhxpjfvs.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yvedp.cn/Article/details/gtxnvczoyk.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gtaskmtpre.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenzaomai.com/Article/details/gtmojwugra.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.andypj.xyz/Article/details/gtmaeopbvw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gtvbiajpll.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gtvtmmdrlx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtzkmmtyef.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.redwolf501.top/Article/details/gtiqdaknog.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.cucudq.cn/Article/details/gtltcslvel.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhengqikj.top/Article/details/gtnubrfick.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwkzacti.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtidqktxex.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtonelsioa.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gtxqkfthfo.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gtzxytccar.html

PHP:  class User {}
来源：http://dali.ivvv.top/Article/details/gtnmzgshts.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gtwjcohcdx.html

TS:   class User { name: string = ""; }
来源：http://dali.shuidangran.top/Article/details/gttytgsxxo.html

Java: class User {}
来源：http://dali.svipenyu.cn/Article/details/gtksnlkglh.html

Go:   type User struct { Name string }
来源：http://dali.hywenlv.cn/Article/details/gtpwroeeja.html

Ruby: class User; end
来源：http://dali.pycfn.com/Article/details/gtpwgbldgr.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuoatgwe.html

[G02] 构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxohchbg.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.redwolf501.top/Article/details/gtfcydipzi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtcgxdvglb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gthmtkpzjk.html

TS:   constructor(public name: string) {}
来源：http://dali.daxiang520.top/Article/details/gtwwaxmvhj.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtujeqeinl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sufxvd.cn/Article/details/gtozvdfmdv.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pycfn.com/Article/details/gtqzvtzgng.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gttoxjjnme.html

[G03] 实例属性
来源：http://dali.jqgufenzy.top/Article/details/gtscxlkcfs.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gtifbaltmn.html

PHP:  public string $name = "x";
来源：http://dali.smart0.xyz/Article/details/gtbqcceyor.html

JS:   this.name = "x";
来源：http://dali.sxryk.cn/Article/details/gtmdlbdfsl.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gtfgtytaxj.html

Java: private String name;
来源：http://dali.sweek.top/Article/details/gtetcfnccv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.wangdashe.top/Article/details/gtnvixaxqo.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gtahefmhtn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yueranfly.top/Article/details/gtdurnazby.html

[G04] 定义方法
来源：http://dali.chenjidiqi.icu/Article/details/gtyirofqnk.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtsxsbwjbd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yj20258888.top/Article/details/gtgrgckrfk.html

JS:   greet() { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtbtwsenof.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtgwnvtxkq.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxhqnxchd.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.wangdashe.top/Article/details/gtjvvkrylh.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtygfdphwt.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gtnjimnjht.html

[G05] 继承
来源：http://dali.zhoulong.xyz/Article/details/gtqapdtuov.html

Py:   class Admin(User): pass
来源：http://dali.hnqzz.top/Article/details/gtvusyaddn.html

PHP:  class Admin extends User {}
来源：http://dali.yuxming.cn/Article/details/gthpdafkaf.html

JS:   class Admin extends User {}
来源：http://dali.aizwys.cn/Article/details/gtpfcvssxi.html

TS:   class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtcdrvcovm.html

Java: class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gttgkgkuyd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj20258888.top/Article/details/gtjxlisteq.html

Ruby: class Admin < User; end
来源：http://dali.wangshuangyany.cn/Article/details/gtwfntkeot.html

C#:   class Admin : User {}
来源：http://dali.jqgufenzy.top/Article/details/gtdkdgembc.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gtmavtaihy.html

Py:   def greet(self): return "admin"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxtpmogwa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtgvgnluza.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gthxqgwbjh.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtlrwhkqyj.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gtkwvdpthy.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnxiangtu.top/Article/details/gtqvgnhumm.html

Ruby: def greet; "admin"; end
来源：http://dali.chenzaomai.com/Article/details/gtjbjtqygy.html

C#:   public override string Greet() => "admin";
来源：http://dali.dashuyun.cn/Article/details/gtvwvbrktv.html

[G07] 调用父类方法
来源：http://dali.svipenyu.cn/Article/details/gtruavhflb.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlfwuqpja.html

PHP:  parent::greet();
来源：http://dali.sweek.top/Article/details/gtnwyxpwnu.html

JS:   super.greet();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbjizcza.html

TS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gtnuihynoi.html

Java: super.greet();
来源：http://dali.dianchejie.cn/Article/details/gteozvxlcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gteankjydx.html

Ruby: super
来源：http://dali.chenzaomai.com/Article/details/gtakbyzhgb.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gtjsrdgugo.html

[G08] 静态方法与属性
来源：http://dali.vqdsnc.cn/Article/details/gtoodhpnoj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jqgufenzy.top/Article/details/gtaictezuz.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtviiuxfcw.html

JS:   static f() {}
来源：http://dali.316326.xyz/Article/details/gtrhdginnr.html

TS:   static f(): void {}
来源：http://dali.yvedp.cn/Article/details/gtmzwtjoua.html

Java: static void f() {}
来源：http://dali.fzhhl.top/Article/details/gthnxlrvai.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daxiang520.top/Article/details/gtwcstjxpe.html

Ruby: def self.f; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbiebirh.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gtbngvnpqt.html

[G09] 接口 / 抽象类
来源：http://dali.xinyue.icu/Article/details/gtsdhmdzww.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gtdpfvvmlb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmocespgh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.snrcjt.cn/Article/details/gtmmnrmueg.html

TS:   interface Shape { area(): number; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnjjxnos.html

Java: interface Shape { double area(); }
来源：http://dali.andypj.xyz/Article/details/gtldruidua.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gttehbugfj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.daxiang520.top/Article/details/gtqyuenbvl.html

C#:   interface IShape { double Area(); }
来源：http://dali.hnxiangtu.top/Article/details/gtklfrixcd.html

[G10] 访问控制
来源：http://dali.zhixingplan.top/Article/details/gtlctmntrw.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gtqxtngscp.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvvvpqdc.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gthvgwzwsh.html

TS:   public / protected / private
来源：http://dali.zhaomingkeji.xyz/Article/details/gtofnkwiyc.html

Java: public / protected / private / 默认包级
来源：http://dali.zhongyouzk.top/Article/details/gtcfwjvuxh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258.top/Article/details/gtflyrjqam.html

Ruby: public / protected / private
来源：http://dali.yj202588.top/Article/details/gtoooojpmq.html

C#:   public / protected / private / internal
来源：http://dali.ydzc1.top/Article/details/gtjkaddfnf.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gtuhdsidjz.html

Py:   @property 与 @x.setter
来源：http://dali.c1oappe.top/Article/details/gtyewhdeze.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.chenzaomai.com/Article/details/gtmcojgbgp.html

JS:   get name() { return this._name; }
来源：http://dali.pycfn.com/Article/details/gtcckthrbl.html

TS:   get name(): string { return this._name; }
来源：http://dali.fengsongda.top/Article/details/gtprtkvcee.html

Java: public String getName() { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtjmxrhyje.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckshhjln.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gtmdnedbov.html

C#:   public string Name { get; set; }
来源：http://dali.fzhhl.top/Article/details/gtripobxfc.html

[G12] 对象转字符串
来源：http://dali.sufxvd.cn/Article/details/gtviqywcsi.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtxbrdcqeu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccmqtijw.html

JS:   toString() { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtdxouxahi.html

TS:   toString(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gtgphapcfj.html

Java: @Override public String toString() { return name; }
来源：http://dali.hammf.cn/Article/details/gtuzndisma.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.kuanghao11.cn/Article/details/gtimkxvvyz.html

Ruby: def to_s; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gtvrtczgyq.html

C#:   public override string ToString() => Name;
来源：http://dali.jlsjyb.cn/Article/details/gtwfoekkhp.html

[G13] 判断对象类型
来源：http://dali.sweek.top/Article/details/gtlvvmyagv.html

Py:   isinstance(u, User)
来源：http://dali.gzhubu.top/Article/details/gtamtfrfop.html

PHP:  $u instanceof User
来源：http://dali.hnqzz.top/Article/details/gtyhlajunb.html

JS:   u instanceof User
来源：http://dali.birdmap.top/Article/details/gtkgonkuei.html

TS:   u instanceof User
来源：http://dali.kuanghao11.cn/Article/details/gtahjrzssx.html

Java: u instanceof User
来源：http://dali.mhx1999.top/Article/details/gtcoyqbqho.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.birdmap.top/Article/details/gtywviylsz.html

Ruby: u.is_a?(User)
来源：http://dali.c1oappe.top/Article/details/gtplwgzfhq.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtaxzjfbiu.html

[G14] 数据类 / record
来源：http://dali.shuidangran.top/Article/details/gtzzuwxdsh.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xuanzx.com/Article/details/gtngilxpkq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.fzhhl.top/Article/details/gtqljrwgqx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.0kj1m.cn/Article/details/gtfvflivne.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gtzryntbqq.html

Java: record User(String name, int age) {}
来源：http://dali.ppjwa.cn/Article/details/gtymswksgl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gtuywvblyi.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gtwecohkxa.html

C#:   record User(string Name, int Age);
来源：http://dali.dashuyun.cn/Article/details/gtesttmnne.html

[G15] 枚举
来源：http://dali.dianchejie.cn/Article/details/gtyqzudpgx.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.nanxuanxn.top/Article/details/gtmruopkjb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gtnvmdmudg.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.jinqigfzy.top/Article/details/gtrighdbiw.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtbonkfdvh.html

Java: enum Color { RED, GREEN }
来源：http://dali.sxryk.cn/Article/details/gtpbukofdn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jlsjyb.cn/Article/details/gthrxxbhho.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhiwuduotai.top/Article/details/gtsqvbeseb.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gtwnnpidwh.html

[G16] 对象转数组 / 字典
来源：http://dali.zhijiandao.cn/Article/details/gtldciqvel.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yonumen.top/Article/details/gtyuiqital.html

PHP:  get_object_vars($obj);
来源：http://dali.zycfv.cn/Article/details/gtoxhurwna.html

JS:   Object.entries(obj)
来源：http://dali.quarkkingdee.top/Article/details/gthmabzsew.html

TS:   Object.entries(obj)
来源：http://dali.smart0.xyz/Article/details/gtghhjfaki.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.bjfxy.top/Article/details/gtvcsqkwzo.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.c1oappe.top/Article/details/gtlhhxdbhd.html

Ruby: obj.instance_variables
来源：http://dali.tianlin.xyz/Article/details/gtbtssjzjt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.ivvv.top/Article/details/gtzlsnslwk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyozsljlu.html

H. 异常与错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxphawsxp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtyukllfgk.html

[H01] try / catch 基础
来源：http://dali.zhijiandao.cn/Article/details/gteidsntun.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gtvsdfidef.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrabesgbv.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.birdmap.top/Article/details/gtypnpitqb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gtygwicydn.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.yj20258.top/Article/details/gtpsvjdvus.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.0kj1m.cn/Article/details/gthtqpcszj.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gtbqecgooy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zdqjudy.top/Article/details/gtzcipuvvc.html

[H02] finally / ensure 收尾
来源：http://dali.zdqjudy.top/Article/details/gtxldptcgh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.chenjidiqi.icu/Article/details/gtebcmoweq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.ivvv.top/Article/details/gtcaqkjoqa.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sweek.top/Article/details/gtvpcknwao.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.birdmap.top/Article/details/gtbrdjwsdo.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsclfbxeb.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.jinqigfzy.top/Article/details/gtjzraroxo.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdnxuoiiv.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zycfv.cn/Article/details/gtzjcjawdh.html

[H03] 主动抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtfhoyrkjp.html

Py:   raise ValueError("错误信息")
来源：http://dali.nanxinkj.top/Article/details/gtnygypwvm.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gtzpprmibg.html

JS:   throw new Error("错误信息");
来源：http://dali.bjfxy.top/Article/details/gtlqwwqotf.html

TS:   throw new Error("错误信息");
来源：http://dali.hnqzz.top/Article/details/gthzqycgqr.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.redwolf501.top/Article/details/gtfcuapzkl.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.gotoacloud.top/Article/details/gtqszhpnek.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhoulong.xyz/Article/details/gtumaxempw.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gtvgvkhqap.html

[H04] 自定义异常类型
来源：http://dali.ivvv.top/Article/details/gtpdonxpxa.html

Py:   class MyError(Exception): pass
来源：http://dali.daria6918.cn/Article/details/gtkieztsfk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.vqdsnc.cn/Article/details/gtpudpwbvz.html

JS:   class MyError extends Error {}
来源：http://dali.hnqzz.top/Article/details/gtetfrvwdh.html

TS:   class MyError extends Error {}
来源：http://dali.birdmap.top/Article/details/gtbflclwae.html

Java: class MyException extends RuntimeException {}
来源：http://dali.daxiang520.top/Article/details/gtxasamxef.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.iojbl.cn/Article/details/gtbjcmejvn.html

Ruby: class MyError < StandardError; end
来源：http://dali.guowangkeji.top/Article/details/gtxbsacmpn.html

C#:   class MyException : Exception {}
来源：http://dali.xuanzx.com/Article/details/gtppznjxfb.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpzpnoig.html

Py:   except ValueError as e:
来源：http://dali.ydzc1.top/Article/details/gtbxxwxxco.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.cheryme.top/Article/details/gtpexacaap.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkrodqhnq.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdunrfpjh.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.redwolf501.top/Article/details/gtrjeqliyb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.meibo888.top/Article/details/gtjxksiphz.html

Ruby: rescue ArgumentError => e
来源：http://dali.yueranfly.top/Article/details/gthhkbwwdi.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.yuxming.cn/Article/details/gthphfmvkq.html

[H06] 可选值 / 空值安全访问
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcvmjypkp.html

Py:   value = d.get("k") or default
来源：http://dali.mhx1999.top/Article/details/gtcmyvssnl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtipyuhocj.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.0kj1m.cn/Article/details/gtqlzvswjr.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gtasaqdjlm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.vqdsnc.cn/Article/details/gtnhmvcokw.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.redwolf501.top/Article/details/gtblmtfrii.html

Ruby: d&.dig(:a, :b)
来源：http://dali.jlsjyb.cn/Article/details/gtekslbexh.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtcfgfuxxw.html

[H07] 断言
来源：http://dali.yj20258.top/Article/details/gthousmmha.html

Py:   assert x > 0, "必须为正"
来源：http://dali.jiagoushi.top/Article/details/gtwqadryqq.html

PHP:  assert($x > 0);
来源：http://dali.haohaochexian.top/Article/details/gtddjkqxwz.html

JS:   console.assert(x > 0);
来源：http://dali.snrcjt.cn/Article/details/gtntscktnq.html


<!-- 参考信息 -->