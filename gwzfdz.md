代发 wailian999

[E22] 字节长度与字符长度
来源：http://dali.tanke756.top/Article/details/gtouxvyioi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gtcjvrenga.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtqqllxoex.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtcommsalz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gtkfdnijdn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gtqyuovgaa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gtgjvxfmnc.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gttopaxnit.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtlrqpelab.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gthwdbmzvx.html

F. 文件与目录
来源：http://dali.aibaodan.cn/Article/details/gtghixorfe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtqlfqjhzg.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gtzeznebup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtlppodgre.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gtoqonwtqx.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gttgpkvqje.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtjpvhheum.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daria6918.cn/Article/details/gtmegdcsew.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gthkjtugie.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtgpkayawe.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtwbtyjmnw.html

[F02] 逐行读取文件
来源：http://dali.chenjidiqi.icu/Article/details/gtywmqevnw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gtvsavclqp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hywenlv.cn/Article/details/gtrychlfcb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gtsohojyqw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskovdile.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtiqubswrk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gtulncspqu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xylfe.cn/Article/details/gtrmdsitoo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtxjuqqsus.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtfijupetc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtmhngtzlt.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtrbxnuccb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gtxamsnala.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtabwdurdo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.gzhubu.top/Article/details/gtrzjrzmaz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtmrcaqnsc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gtzewgvcfg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gttyjdfson.html

[F04] 追加写入文件
来源：http://dali.zhiwuduotai.top/Article/details/gtphypveyy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.vqdsnc.cn/Article/details/gtceakcdvb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.redwolf501.top/Article/details/gtqppvupox.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gthimgukqt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtzwmkvbra.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.smart0.xyz/Article/details/gtjaqnsdeo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.andypj.xyz/Article/details/gtemzpyoqm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gtsmoupncl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gtxcabsuev.html

[F05] 判断文件或目录是否存在
来源：http://dali.smart0.xyz/Article/details/gtozgxzwko.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hongshengwenyu.top/Article/details/gtmlnohoas.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtliwqqxni.html

JS:   fs.existsSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtgnysdiry.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtytfdikcz.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtwkkivjtc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.316326.xyz/Article/details/gtchozmpqq.html

Ruby: File.exist?("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtvoclgpng.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtauwikrhx.html

[F06] 删除文件
来源：http://dali.chenzaomai.com/Article/details/gtryqoqlqr.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtdgmtzrxz.html

PHP:  unlink("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtbchlskiu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtxmqqvcqw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtgnancqnt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtjqgwcqnz.html

Go:   os.Remove("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtogudgtvl.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtmptfimxf.html

C#:   File.Delete("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtwhtfbrtl.html

[F07] 创建目录（含多级）
来源：http://dali.snrcjt.cn/Article/details/gtkabdkkyw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtjxjynrnc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhixingplan.top/Article/details/gtlueadduo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxinkj.top/Article/details/gtgpukghko.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gtemosqkkd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtdlixcxwk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yangfankeji.com/Article/details/gtmouduycw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gtelyyetly.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangtech.top/Article/details/gtvazinldg.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gtqkrsplij.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtiydhimwp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.iojbl.cn/Article/details/gtayrnjkuc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gtihrirssx.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gtsavgcsno.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtctzzoeoc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtyjktxjyj.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtxjdmujgi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtmdfznlis.html

[F09] 获取文件大小
来源：http://dali.hywenlv.cn/Article/details/gtgdznjrkn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtggurcpzb.html

PHP:  filesize("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gtgwlazpcc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gtbdhcjssh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gtckendwzy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jiagoushi.top/Article/details/gtxlxtqsdn.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hongshengwenyu.top/Article/details/gtmmbqfumm.html

Ruby: File.size("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtvpesgzfn.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tian-w.cn/Article/details/gtvuonodsf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ehwqpu.com/Article/details/gtdupwmfqx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtrwmbgkou.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.andypj.xyz/Article/details/gtzkiqwdvd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtqogxxgmm.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbhrasllk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtawndesqr.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtyktyzaru.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtqebldzmo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmekfruli.html

[F11] 复制与移动文件
来源：http://dali.xinyue.icu/Article/details/gtoywtgeno.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtogidlvns.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.chenlongwang.top/Article/details/gtgbtahggw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gtkkqnkjux.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtmzbhhbfw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nanxuanxn.top/Article/details/gtsjgkdvyq.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.bjfxy.top/Article/details/gtmnesdnvb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtttxpzrxq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gtaqblklcj.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gtugjmoozj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwauhqhwh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jlsjyb.cn/Article/details/gtfybbtvex.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.feifeiyinyue.top/Article/details/gtkomghgqk.html

TS:   // 同上
来源：http://dali.c1oappe.top/Article/details/gtkggyaghk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtyskllaqy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tian-w.cn/Article/details/gtxihuxdma.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.pengpengdd.cyou/Article/details/gtuyhpmfiy.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gtvfmjkefo.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtwsqiyykb.html

G. 面向对象
来源：http://dali.sweek.top/Article/details/gtumollsbp.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtggcarvyf.html

[G01] 定义类
来源：http://dali.ybcxt.top/Article/details/gtgevygvfq.html

Py:   class User: pass
来源：http://dali.cqqwz.cn/Article/details/gtfenxojrh.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtufaensec.html

JS:   class User {}
来源：http://dali.sxryk.cn/Article/details/gtdinciwrb.html

TS:   class User { name: string = ""; }
来源：http://dali.tian-w.cn/Article/details/gtqpgwruxx.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gtwrktlara.html

Go:   type User struct { Name string }
来源：http://dali.nwbrower.top/Article/details/gtjcoqvobv.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtkoxnzxgh.html

C#:   class User {}
来源：http://dali.yongpay.top/Article/details/gtmtugodyk.html

[G02] 构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtbicywsxz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gttlvcstub.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gtsenewoit.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.aibaodan.cn/Article/details/gtrdthlzkm.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gtkocblkau.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gtuwxxajif.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtwbnfcvbo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtykgcppkl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.shzxlz.cn/Article/details/gtcmhsoyxe.html

[G03] 实例属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gteplbgwpw.html

Py:   self.name = "x"
来源：http://dali.smart0.xyz/Article/details/gtibmhobqs.html

PHP:  public string $name = "x";
来源：http://dali.wangshuangyany.cn/Article/details/gtyfqjjoed.html

JS:   this.name = "x";
来源：http://dali.9152youxi.cn/Article/details/gtuaebuhum.html

TS:   name: string = "x";
来源：http://dali.tanke756.top/Article/details/gtpvlglkbk.html

Java: private String name;
来源：http://dali.jlsjyb.cn/Article/details/gtcznwdqos.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sweek.top/Article/details/gtqrrbikip.html

Ruby: @name = "x"
来源：http://dali.andypj.xyz/Article/details/gtlojepfzw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.kuanghao11.cn/Article/details/gtrjbazxhz.html

[G04] 定义方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtivkkmkrm.html

Py:   def greet(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtmzemurus.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pengpengdd.cyou/Article/details/gthscmbeej.html

JS:   greet() { return this.name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtafjkwosq.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gtfiuvovek.html

Java: String greet() { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtztfxjobj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gtxczchzph.html

Ruby: def greet; @name; end
来源：http://dali.yangfankeji.com/Article/details/gtvphkwavf.html

C#:   public string Greet() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtchzvwwio.html

[G05] 继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqbfopxx.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gtnizdhixs.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gtpzavsobm.html

JS:   class Admin extends User {}
来源：http://dali.shuidangran.top/Article/details/gtmwqazpqw.html

TS:   class Admin extends User {}
来源：http://dali.nanxinkj.top/Article/details/gtuhqyppyz.html

Java: class Admin extends User {}
来源：http://dali.gaohongyu789.top/Article/details/gtesggjvzb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gtrzftunod.html

Ruby: class Admin < User; end
来源：http://dali.tian-w.cn/Article/details/gtsiglqyxr.html

C#:   class Admin : User {}
来源：http://dali.yj20258888.top/Article/details/gtzslpugze.html

[G06] 重写方法
来源：http://dali.nanxinkj.top/Article/details/gtmrazilps.html

Py:   def greet(self): return "admin"
来源：http://dali.yueranfly.top/Article/details/gtwftugcxt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gtwmxwpsao.html

JS:   greet() { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gthjurojcc.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gtmldveagk.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gtqpirtivp.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xylfe.cn/Article/details/gtrmexpath.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtkiqxphmn.html

C#:   public override string Greet() => "admin";
来源：http://dali.meibo888.top/Article/details/gtfrmpizkr.html

[G07] 调用父类方法
来源：http://dali.jianghu66.top/Article/details/gthysbgqbb.html

Py:   super().greet()
来源：http://dali.zhijiandao.cn/Article/details/gtgzkbmrzy.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gtgwfojdfo.html

JS:   super.greet();
来源：http://dali.jianghu66.top/Article/details/gtjtmekliy.html

TS:   super.greet();
来源：http://dali.jinqigfzy.top/Article/details/gtftyzdwrr.html

Java: super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gtpkezhshy.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyptphgag.html

Ruby: super
来源：http://dali.wangdashe.top/Article/details/gtczghcklo.html

C#:   base.Greet();
来源：http://dali.jianghu66.top/Article/details/gtowixnpia.html

[G08] 静态方法与属性
来源：http://dali.ivvv.top/Article/details/gtdeuwhbwt.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yuanzhike.top/Article/details/gtxeawcwsx.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvnctjhh.html

JS:   static f() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslwoigbm.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gtdosoamks.html

Java: static void f() {}
来源：http://dali.jqgfzy.top/Article/details/gtkkebneey.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.316326.xyz/Article/details/gtqhthfxgl.html

Ruby: def self.f; end
来源：http://dali.hnxiangtu.top/Article/details/gtvhnewskm.html

C#:   public static void F() {}
来源：http://dali.gotoacloud.top/Article/details/gtxwmlqgfc.html

[G09] 接口 / 抽象类
来源：http://dali.gogol.net.cn/Article/details/gtcimqorjp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.cheryme.top/Article/details/gtvdrpudrh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sufxvd.cn/Article/details/gtqipouelu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cdnleiting.top/Article/details/gtfuidybph.html

TS:   interface Shape { area(): number; }
来源：http://dali.redwolf501.top/Article/details/gtvdsuvspd.html

Java: interface Shape { double area(); }
来源：http://dali.zhixingplan.top/Article/details/gtmkaqhiya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuanzhike.top/Article/details/gtbuqbitxp.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.sweek.top/Article/details/gtxxnbhnoy.html

C#:   interface IShape { double Area(); }
来源：http://dali.gzhubu.top/Article/details/gtapnmdrnp.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gthxgfdtxk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gtqttomtoi.html

PHP:  public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gtflydlxrc.html

JS:   #private 字段；其余公开
来源：http://dali.jinqigfzy.top/Article/details/gtaxphtzro.html

TS:   public / protected / private
来源：http://dali.cucudq.cn/Article/details/gtpzxemjan.html

Java: public / protected / private / 默认包级
来源：http://dali.mhx1999.top/Article/details/gthndqncnr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ppjwa.cn/Article/details/gtpytxgwjl.html

Ruby: public / protected / private
来源：http://dali.hongshengwenyu.top/Article/details/gtigimejea.html

C#:   public / protected / private / internal
来源：http://dali.dashuyun.cn/Article/details/gtvhldmgoe.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gtdhkcsrjk.html

Py:   @property 与 @x.setter
来源：http://dali.tianlin.xyz/Article/details/gtrqjhdsgl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gtyezkbojb.html

JS:   get name() { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgduoqlfg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhoulong.xyz/Article/details/gtbblitfxv.html

Java: public String getName() { return name; }
来源：http://dali.pycfn.com/Article/details/gtrzjrsfsg.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gtnqnnffzk.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gthylklweg.html

C#:   public string Name { get; set; }
来源：http://dali.yueranfly.top/Article/details/gttaqimheu.html

[G12] 对象转字符串
来源：http://dali.yj20258.top/Article/details/gtxenjrnbd.html

Py:   def __str__(self): return self.name
来源：http://dali.bjfxy.top/Article/details/gttljoxiyd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtskhevxqg.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gtrnyhhaha.html

TS:   toString(): string { return this.name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzsimuww.html

Java: @Override public String toString() { return name; }
来源：http://dali.redwolf501.top/Article/details/gtcnaxmsrw.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gtdaewbucj.html

Ruby: def to_s; @name; end
来源：http://dali.feifeiyinyue.top/Article/details/gtgxarvnhd.html

C#:   public override string ToString() => Name;
来源：http://dali.pengpengdd.cyou/Article/details/gtnulibooz.html

[G13] 判断对象类型
来源：http://dali.feifeiyinyue.top/Article/details/gtuctrtgvv.html

Py:   isinstance(u, User)
来源：http://dali.yongpay.top/Article/details/gteoeavznq.html

PHP:  $u instanceof User
来源：http://dali.daxiang520.top/Article/details/gtbdzklcwt.html

JS:   u instanceof User
来源：http://dali.yj20258888.top/Article/details/gtitgktile.html

TS:   u instanceof User
来源：http://dali.feifeiyinyue.top/Article/details/gtpgitsghq.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gthhpmgiyr.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.smart0.xyz/Article/details/gtbzgrhhxl.html

Ruby: u.is_a?(User)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgrqnlmg.html

C#:   u is User
来源：http://dali.aizwys.cn/Article/details/gtkuxkmthn.html

[G14] 数据类 / record
来源：http://dali.gzhubu.top/Article/details/gtistsrfff.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.gaohongyu789.top/Article/details/gtraryaxep.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.andypj.xyz/Article/details/gtqdrfvvwb.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cdnleiting.top/Article/details/gtulihqiya.html

TS:   type User = { name: string; age: number };
来源：http://dali.birdmap.top/Article/details/gtzloutcgd.html

Java: record User(String name, int age) {}
来源：http://dali.cqqwz.cn/Article/details/gtiwxxtpoj.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jlsjyb.cn/Article/details/gtfzetgdln.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.tanke756.top/Article/details/gtkoweqwgt.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gtllgzwrlm.html

[G15] 枚举
来源：http://dali.hysaishi.cn/Article/details/gthvhbdscw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gotoacloud.top/Article/details/gtpkbneqgb.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmclptyge.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.daria6918.cn/Article/details/gtqhnfymrp.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cheryme.top/Article/details/gtarmchyxe.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbeuqnbj.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinqigufen.top/Article/details/gtcxqzgqqu.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yangfankeji.com/Article/details/gtwqjbaakv.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gtjhncfaxt.html

[G16] 对象转数组 / 字典
来源：http://dali.dianchejie.cn/Article/details/gtbseabltp.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.jyoumei.cn/Article/details/gttsazcjqs.html

PHP:  get_object_vars($obj);
来源：http://dali.cdnleiting.top/Article/details/gtqkpspjrc.html

JS:   Object.entries(obj)
来源：http://dali.tianlin.xyz/Article/details/gtgbbenyfz.html

TS:   Object.entries(obj)
来源：http://dali.yonumen.top/Article/details/gtgyjmifxo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.quarkkingdee.top/Article/details/gtzxuajqxa.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hongshengwenyu.top/Article/details/gtxwdgzafq.html

Ruby: obj.instance_variables
来源：http://dali.andypj.xyz/Article/details/gtvwryrssg.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.smart0.xyz/Article/details/gtdctadtjk.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtnvjwfqxm.html

H. 异常与错误处理
来源：http://dali.havefunace.top/Article/details/gtbutfiuko.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtphtdedfi.html

[H01] try / catch 基础
来源：http://dali.hongshengwenyu.top/Article/details/gtendbsjbg.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.bjfxy.top/Article/details/gtvcioadgh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jinqigufen.top/Article/details/gtlypxoyke.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtecrkidcv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zhengqikj.top/Article/details/gtmuisrdxs.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.jyoumei.cn/Article/details/gthtqhtqew.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.fengsongda.top/Article/details/gtfitpolqq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.zhengqikj.top/Article/details/gtlmwkxmay.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtpjqfqjlb.html

[H02] finally / ensure 收尾
来源：http://dali.bjfxy.top/Article/details/gtvyjtplkx.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.smart0.xyz/Article/details/gtpfarlezd.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.c1oappe.top/Article/details/gthwafolvm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ppjwa.cn/Article/details/gtwrxtgpja.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.yuanzhike.top/Article/details/gtluuyehjj.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.yonumen.top/Article/details/gtzslpvgjz.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zdqjudy.top/Article/details/gtraxrwkfk.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.zdqjudy.top/Article/details/gtnioicwbw.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbyvxlmt.html

[H03] 主动抛出异常
来源：http://dali.cdnleiting.top/Article/details/gtqjqqames.html

Py:   raise ValueError("错误信息")
来源：http://dali.xuanzx.com/Article/details/gtmmfvvsci.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtknqnqfho.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gtqnkmtdnv.html

TS:   throw new Error("错误信息");
来源：http://dali.quarkkingdee.top/Article/details/gtdunezqid.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.birdmap.top/Article/details/gtijcfnvuo.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.tianlin.xyz/Article/details/gttlmulags.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.zhijiandao.cn/Article/details/gtbdrdlyri.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.jianghu66.top/Article/details/gtcocaltzu.html

[H04] 自定义异常类型
来源：http://dali.0kj1m.cn/Article/details/gtssnpllyk.html

Py:   class MyError(Exception): pass
来源：http://dali.cashguo.top/Article/details/gtgkgfyile.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.havefunace.top/Article/details/gtxwyrorxy.html


<!-- 参考信息 -->