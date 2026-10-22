代发 wailian999

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fzhhl.top/Article/details/gt2qxuybasj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2cebicrho.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2inqktaqp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2zbxwaqls.html

[F01] 读取整个文件
来源：http://dali.hnqzz.top/Article/details/gt2mwutogfg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgfzy.top/Article/details/gt2gqqcbwwi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2nuywhnqp.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohpzsuqt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gt2bqoesiea.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2zkshaqfd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gt2oyhevuks.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2bvbecdiz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2nmrhmcrs.html

[F02] 逐行读取文件
来源：http://dali.cashguo.top/Article/details/gt2gxcmvwpu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ehwqpu.com/Article/details/gt2wqsmxugf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgufenzy.top/Article/details/gt2bomgklli.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fatlgkxr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vgmfozpt.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jiagoushi.top/Article/details/gt2ikgnjiuv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2rlxofvom.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj202588.top/Article/details/gt2qxhvsoir.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2cieleqtd.html

[F03] 写入文件（覆盖）
来源：http://dali.fzhhl.top/Article/details/gt2hfykpetx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2atirnzhf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2nmkvjveb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2marielpc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gt2qmeruwvx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2sxcgizwl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gt2nrcraakp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.c1oappe.top/Article/details/gt2ecbjpchm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2ioupswzv.html

[F04] 追加写入文件
来源：http://dali.jqgfzy.top/Article/details/gt2wqnnkalk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gt2aeemhbwy.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.smart0.xyz/Article/details/gt2csgcnugd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lwzmjspp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2bpefcpnr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jiagoushi.top/Article/details/gt2cnacerzy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2aqotpgoj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xinyue.icu/Article/details/gt2bkxvtvmv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2hnnwlfeh.html

[F05] 判断文件或目录是否存在
来源：http://dali.hnqzz.top/Article/details/gt2gyuibtnt.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2lvacaynr.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2pduggoph.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ranyawpx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2fhvfgjip.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gt2oncupgqr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yj20258888.top/Article/details/gt2zdzbeenz.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2sjrtqord.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jaoymbmx.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gt2gmjfvtbx.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2blhuawyg.html

PHP:  unlink("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2rhsrcgbp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2prnycjii.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2doeemuba.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2rubsmxgv.html

Go:   os.Remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2khsnauwi.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zqihairy.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2kkkneqza.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gt2kzidihhw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfkacnxw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2ggfkxwue.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2vcszzkmu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gt2zigolayo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tian-w.cn/Article/details/gt2ioqgltwc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gt2djptikbw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.sweek.top/Article/details/gt2xwqyoigd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qvupondu.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2yvltihpz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.pycfn.com/Article/details/gt2gnhofojg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ewpmjisb.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2ugcyjoqi.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gt2sutewzmf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmuawfby.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2vdidxbnv.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gt2jvlnpmpy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2afxqqsrq.html

[F09] 获取文件大小
来源：http://dali.xylfe.cn/Article/details/gt2bipqvmiy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dokqrypy.html

PHP:  filesize("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2xgllpehr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2aaftolcn.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gt2omxhqcfa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.zhongyouzk.top/Article/details/gt2hrggyfae.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.c1oappe.top/Article/details/gt2ipdrwcuq.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2oshvcyez.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.daria6918.cn/Article/details/gt2rhfgndcf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nanxinkj.top/Article/details/gt2ffytoqdu.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mahxaqmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bljpmztd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2enauxbyw.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2cimmbiau.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gt2hchseyxm.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lchjplob.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2onbgzfvj.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2tezixlts.html

[F11] 复制与移动文件
来源：http://dali.shuidangran.top/Article/details/gt2cbnvmykv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.mhx1999.top/Article/details/gt2tkigdemk.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yuxming.cn/Article/details/gt2itffedpt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2iwvqkswg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2polhxeni.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2odqmueeb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iajqfhoz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sxryk.cn/Article/details/gt2hvftlyhc.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2isffqiic.html

[F12] CSV 读写
来源：http://dali.zhongyouzk.top/Article/details/gt2zbirdraj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.andypj.xyz/Article/details/gt2depiicxy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuanzx.com/Article/details/gt2pekapewy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dashuyun.cn/Article/details/gt2aoefvhul.html

TS:   // 同上
来源：http://dali.sweek.top/Article/details/gt2yyouvcwg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gt2aqeinsjh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gt2flbwboop.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shuidangran.top/Article/details/gt2mewrwtkp.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yuxming.cn/Article/details/gt2hztmztyl.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2uucvhzxc.html

G. 面向对象
来源：http://dali.hongshengwenyu.top/Article/details/gt2iivumxmu.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wayigktt.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2fagxxeae.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gt2cezlqkqj.html

PHP:  class User {}
来源：http://dali.snrcjt.cn/Article/details/gt2fzpfyjfn.html

JS:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2ttifahev.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpviaron.html

Java: class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uonpzeau.html

Go:   type User struct { Name string }
来源：http://dali.chenzaomai.com/Article/details/gt2phxcogub.html

Ruby: class User; end
来源：http://dali.zdqjudy.top/Article/details/gt2rtvmlsuu.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2pelvcfvz.html

[G02] 构造函数
来源：http://dali.ybcxt.top/Article/details/gt2mlpdnexe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fzhhl.top/Article/details/gt2faokcyis.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gt2ohtyqvjq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yweixiax.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2hsjumdaz.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2eyaqtfwz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.sxryk.cn/Article/details/gt2locnzdbt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cheryme.top/Article/details/gt2zpceimtv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtztctex.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gt2rydodrlk.html

Py:   self.name = "x"
来源：http://dali.jinqigufen.top/Article/details/gt2znitzqit.html

PHP:  public string $name = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2hyfyurez.html

JS:   this.name = "x";
来源：http://dali.jianghu66.top/Article/details/gt2jxrozcuy.html

TS:   name: string = "x";
来源：http://dali.yongpay.top/Article/details/gt2lqxwprcr.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gt2kdntffwf.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ppjwa.cn/Article/details/gt2izsbqndn.html

Ruby: @name = "x"
来源：http://dali.chenlongwang.top/Article/details/gt2tfpnosnf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2kcgjlvax.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gt2glhjqykr.html

Py:   def greet(self): return self.name
来源：http://dali.dianchejie.cn/Article/details/gt2plkixvno.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhixingplan.top/Article/details/gt2oetolwqq.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2fjodelpc.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfujxmre.html

Java: String greet() { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2zdwmzqwp.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gt2qtknssje.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2lsaunebn.html

C#:   public string Greet() => Name;
来源：http://dali.jqgufenzy.top/Article/details/gt2taxzlztz.html

[G05] 继承
来源：http://dali.jinqigufen.top/Article/details/gt2dgkkttnv.html

Py:   class Admin(User): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pfmbboud.html

PHP:  class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcujpwxw.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2jqmretst.html

TS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2ojgjkfna.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cjdszgdp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2nxztpaow.html

Ruby: class Admin < User; end
来源：http://dali.ehwqpu.com/Article/details/gt2xbwxwwiq.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gt2qxyfxdlp.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2lgfocouu.html

Py:   def greet(self): return "admin"
来源：http://dali.tianlin.xyz/Article/details/gt2mnwoufnr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2plqfafmq.html

JS:   greet() { return "admin"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2exxhiojl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gt2aodzkpxe.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2kkbklerw.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2dkxekten.html

Ruby: def greet; "admin"; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hclqqkww.html

C#:   public override string Greet() => "admin";
来源：http://dali.xylfe.cn/Article/details/gt2rtxgslii.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2osdowgxs.html

Py:   super().greet()
来源：http://dali.xuetiantiany.cn/Article/details/gt2hojbbtzi.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2ykqgjnkl.html

JS:   super.greet();
来源：http://dali.zycfv.cn/Article/details/gt2xwvfukvm.html

TS:   super.greet();
来源：http://dali.zhiwuduotai.top/Article/details/gt2sqepeqkj.html

Java: super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2dpdvpldo.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sweek.top/Article/details/gt2xihzhifn.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2xbtewcuy.html

C#:   base.Greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2dyawekxr.html

[G08] 静态方法与属性
来源：http://dali.fzhhl.top/Article/details/gt2bweituro.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yongpay.top/Article/details/gt2nsakyanc.html

PHP:  public static function f() {}
来源：http://dali.jqgfzy.top/Article/details/gt2mhjnkppt.html

JS:   static f() {}
来源：http://dali.ydzc1.top/Article/details/gt2crzqonra.html

TS:   static f(): void {}
来源：http://dali.iojbl.cn/Article/details/gt2yhcghfoh.html

Java: static void f() {}
来源：http://dali.xziqi.cn/Article/details/gt2cmqepgdd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhongyouzk.top/Article/details/gt2raszterq.html

Ruby: def self.f; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2htrxilki.html

C#:   public static void F() {}
来源：http://dali.yonumen.top/Article/details/gt2gsamtxcf.html

[G09] 接口 / 抽象类
来源：http://dali.mhx1999.top/Article/details/gt2zujheplv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2sxynapfr.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.wangdashe.top/Article/details/gt2fvmylcwd.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ivvv.top/Article/details/gt2trblsnqn.html

TS:   interface Shape { area(): number; }
来源：http://dali.jlsjyb.cn/Article/details/gt2yskzvlcq.html

Java: interface Shape { double area(); }
来源：http://dali.zdqjudy.top/Article/details/gt2jhhxpstg.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gt2azvvsvhi.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yangfankeji.com/Article/details/gt2myrsheox.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2dzgomiwp.html

[G10] 访问控制
来源：http://dali.jianghu66.top/Article/details/gt2uuevwnfk.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.cdnleiting.top/Article/details/gt2jtvkoyzj.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2aifpzyky.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2boqynfhn.html

TS:   public / protected / private
来源：http://dali.zdqjudy.top/Article/details/gt2uzoylibp.html

Java: public / protected / private / 默认包级
来源：http://dali.bjfxy.top/Article/details/gt2krujbddh.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xypqbjac.html

Ruby: public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2khxeqxty.html

C#:   public / protected / private / internal
来源：http://dali.zhixingplan.top/Article/details/gt2ogljjuwn.html

[G11] getter / setter
来源：http://dali.daria6918.cn/Article/details/gt2wsecydlp.html

Py:   @property 与 @x.setter
来源：http://dali.yj202588.top/Article/details/gt2wwpcyuxp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2twuxahzn.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjsdiewc.html

TS:   get name(): string { return this._name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2uruitaxm.html

Java: public String getName() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2egjewvib.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2qqjnpwqj.html

Ruby: attr_accessor :name
来源：http://dali.svipenyu.cn/Article/details/gt2betgqoda.html

C#:   public string Name { get; set; }
来源：http://dali.yuxming.cn/Article/details/gt2wlfylmwx.html

[G12] 对象转字符串
来源：http://dali.tanke756.top/Article/details/gt2kpjzvlna.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2exjpwcrz.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.sweek.top/Article/details/gt2drwbburk.html

JS:   toString() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gt2mnafvvlh.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2argvahrj.html

Java: @Override public String toString() { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2ilddvftz.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2cxsgqsjn.html

Ruby: def to_s; @name; end
来源：http://dali.zdqjudy.top/Article/details/gt2funrpksk.html

C#:   public override string ToString() => Name;
来源：http://dali.yueranfly.top/Article/details/gt2ctmygzbf.html

[G13] 判断对象类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwnfqhhk.html

Py:   isinstance(u, User)
来源：http://dali.chenzaomai.com/Article/details/gt2rbdilxap.html

PHP:  $u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2klvgmpwr.html

JS:   u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2exctkjeb.html

TS:   u instanceof User
来源：http://dali.zycfv.cn/Article/details/gt2zhwnvtpb.html

Java: u instanceof User
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfnqwuzv.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.dashuyun.cn/Article/details/gt2nntidjvi.html

Ruby: u.is_a?(User)
来源：http://dali.yuanzhike.top/Article/details/gt2fccrotlx.html

C#:   u is User
来源：http://dali.zhoulong.xyz/Article/details/gt2racuddwt.html

[G14] 数据类 / record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2saubgxva.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yj20258.top/Article/details/gt2gchmtwbn.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhoulong.xyz/Article/details/gt2ulyhkoll.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.daxiang520.top/Article/details/gt2vntfiozu.html

TS:   type User = { name: string; age: number };
来源：http://dali.jqgufenzy.top/Article/details/gt2vjlobrya.html

Java: record User(String name, int age) {}
来源：http://dali.jqgfzy.top/Article/details/gt2fpovadsn.html

Go:   type User struct { Name string; Age int }
来源：http://dali.cheryme.top/Article/details/gt2kkomkysu.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebkphric.html

C#:   record User(string Name, int Age);
来源：http://dali.kuanghao11.cn/Article/details/gt2xsglhgla.html

[G15] 枚举
来源：http://dali.cheryme.top/Article/details/gt2abmxzvda.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2bmfqsqzw.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.guowangkeji.top/Article/details/gt2boumnxep.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gt2snjbngkx.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgufenzy.top/Article/details/gt2mnpwxpso.html

Java: enum Color { RED, GREEN }
来源：http://dali.yj202588.top/Article/details/gt2bvlcpemn.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2teuyndqe.html

Ruby: Color = %i[red green].freeze
来源：http://dali.yanxiufei.cn/Article/details/gt2qcjvzhyi.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jiagoushi.top/Article/details/gt2urvwipun.html

[G16] 对象转数组 / 字典
来源：http://dali.316326.xyz/Article/details/gt2rgbwekpt.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.cucudq.cn/Article/details/gt2vranoclf.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2nuevvbmt.html

JS:   Object.entries(obj)
来源：http://dali.cheryme.top/Article/details/gt2yrsgapdo.html

TS:   Object.entries(obj)
来源：http://dali.zhongyouzk.top/Article/details/gt2wmstvgxz.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xbmokehd.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzeggkfp.html

Ruby: obj.instance_variables
来源：http://dali.gotoacloud.top/Article/details/gt2novmxhxe.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guannengcc.top/Article/details/gt2cklylxco.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2nwwjztwv.html

H. 异常与错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qpykfjqi.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2msqewriq.html

[H01] try / catch 基础
来源：http://dali.cheryme.top/Article/details/gt2wewbhcyo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzxinltf.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.havefunace.top/Article/details/gt2syrfdpny.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.svipenyu.cn/Article/details/gt2ybxkqqyc.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.9152youxi.cn/Article/details/gt2cjfosvmo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shuidangran.top/Article/details/gt2akimvrfy.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.nanxinkj.top/Article/details/gt2sewjokwu.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.ppjwa.cn/Article/details/gt2dgaasnif.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.chenlongwang.top/Article/details/gt2gymzddnh.html

[H02] finally / ensure 收尾
来源：http://dali.hywenlv.cn/Article/details/gt2cqtrvbjl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dmwtpjml.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gityolot.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sluazkgo.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2ltmecsns.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jipolqjg.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.tian-w.cn/Article/details/gt2zzsdcadj.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2nxvjwzcb.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2gscfemil.html

[H03] 主动抛出异常
来源：http://dali.fzhhl.top/Article/details/gt2hqmreegp.html

Py:   raise ValueError("错误信息")
来源：http://dali.yanxiufei.cn/Article/details/gt2icvscotk.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.guannengcc.top/Article/details/gt2npdhpcez.html

JS:   throw new Error("错误信息");
来源：http://dali.ivvv.top/Article/details/gt2lpbviydj.html

TS:   throw new Error("错误信息");
来源：http://dali.gotoacloud.top/Article/details/gt2gfubdthx.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.fengsongda.top/Article/details/gt2mfdyjpps.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvhkxslj.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.hfpthk.cn/Article/details/gt2ennhodve.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wzkhzwug.html

[H04] 自定义异常类型
来源：http://dali.meibo888.top/Article/details/gt2nqjkohuz.html

Py:   class MyError(Exception): pass
来源：http://dali.tianlin.xyz/Article/details/gt2bgvabfrh.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2oojnodwn.html

JS:   class MyError extends Error {}
来源：http://dali.nanxinkj.top/Article/details/gt2dlywzyhk.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gt2ivehczgo.html

Java: class MyException extends RuntimeException {}
来源：http://dali.pycfn.com/Article/details/gt2geaeiaht.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.birdmap.top/Article/details/gt2rkiwdajb.html

Ruby: class MyError < StandardError; end
来源：http://dali.tanke756.top/Article/details/gt2kvdemzvd.html

C#:   class MyException : Exception {}
来源：http://dali.zycfv.cn/Article/details/gt2tmcfbevj.html

[H05] 捕获特定类型
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejmnspor.html

Py:   except ValueError as e:
来源：http://dali.fengsongda.top/Article/details/gt2yvpcrzmw.html


<!-- 参考信息 -->