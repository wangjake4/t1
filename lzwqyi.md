代发 wailian999

Go:   if s == "" {}
来源：http://dali.jianghu66.top/Article/details/gt2twfpbemw.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gt2mfwscukc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2vyrdqktk.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gt2hlrgjbkt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gt2slkugdqx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2zwdklfmn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2cqkqyzip.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqbpqbdu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2vzwwqmix.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gt2vvijlssq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gt2mqzmykzr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2rcerancy.html

[E22] 字节长度与字符长度
来源：http://dali.9152youxi.cn/Article/details/gt2ysqjotwo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2gvbndjye.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2bqcsdegk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2xgpjmlkq.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fxvernkb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fsgbjgna.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2jxzmnrsf.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gt2mbjngboj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangdashe.top/Article/details/gt2vkhsqmnk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2kjssnydv.html

F. 文件与目录
来源：http://dali.yuxming.cn/Article/details/gt2lfkwmvze.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kkhjpcif.html

[F01] 读取整个文件
来源：http://dali.yanxiufei.cn/Article/details/gt2bebggucw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hywenlv.cn/Article/details/gt2xysxrstv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2iekydryz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jqgfzy.top/Article/details/gt2vlxtoobz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2hivqdaha.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2zbdttwnp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhongyouzk.top/Article/details/gt2lxrjtxvd.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2lrxjqyka.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj202588.top/Article/details/gt2lrvdwtko.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gt2tdzachxr.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.fzhhl.top/Article/details/gt2zcbjedbs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.aizwys.cn/Article/details/gt2wocmtxeo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2markzcmn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2cmoilfbo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gt2ialksmdu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gt2ngewbqer.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jyoumei.cn/Article/details/gt2qfjigoen.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2rppmzsfn.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gt2fzuugdsp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.fengsongda.top/Article/details/gt2evpmvbqs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gt2vxktxxrm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gt2ljzhwsvn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2acuzoxbm.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nanxinkj.top/Article/details/gt2hykakfct.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2ydkochnx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2wexxfdxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2fnsesgci.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gt2rwevnrvl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.tian-w.cn/Article/details/gt2fiprcchl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2jbuflnjx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2okmxiedz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2xrbuxqsp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yanxiufei.cn/Article/details/gt2blwfwlrs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ggbfnfox.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xylfe.cn/Article/details/gt2snugivqv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ehwqpu.com/Article/details/gt2uzrnbihc.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2ynnwugxw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sysykeji.top/Article/details/gt2lxnwppjn.html

PHP:  file_exists("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2kfcvncvu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2sqdttlzz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2zeyhtsqv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gt2fesvtvoc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ppjwa.cn/Article/details/gt2wxniddxa.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2mmnpbqrp.html

C#:   File.Exists("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2zmcwgmoe.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gt2pkuguizy.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2mcjxgcnu.html

PHP:  unlink("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2bmsbivpj.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2ksqoeqms.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2xphiqamy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cucudq.cn/Article/details/gt2ukfbnxne.html

Go:   os.Remove("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2xvvtqtku.html

Ruby: File.delete("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vurbmbwt.html

C#:   File.Delete("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2hmtrnuof.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gt2bbptrxkv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xylfe.cn/Article/details/gt2fwwrtfln.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuanzhike.top/Article/details/gt2cffuyvcu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2ypkgmzif.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2okvfdvlr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nlziviwb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2yddrbgvl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gt2wfqllaiy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.pycfn.com/Article/details/gt2kkkghqkb.html

[F08] 遍历目录
来源：http://dali.yangfankeji.com/Article/details/gt2bmitnjuc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2nflcuuud.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daxiang520.top/Article/details/gt2vzzbvybn.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2nufiofvv.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gt2knfmfgyr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gt2ocgqefyn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.havefunace.top/Article/details/gt2erahpgsy.html

Ruby: Dir.children("dir")
来源：http://dali.jyoumei.cn/Article/details/gt2djnjdbww.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2dkjdpahu.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2qdilzgsy.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pyxaahba.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2cxymihlc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2oitpmkfk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2tyrdnefe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2jqwjifma.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gt2cjaxyzpt.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2woerjlzr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hywenlv.cn/Article/details/gt2toqajsdd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2gmllyjqd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2acxjmzyk.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2dbuofibn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2yrpyoqfg.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zbbjhyfm.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xziqi.cn/Article/details/gt2fljfbnvv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2kjxthzld.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2shuhidww.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2hddptxbl.html

[F11] 复制与移动文件
来源：http://dali.yanxiufei.cn/Article/details/gt2yvclnpuu.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2yefppdmz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxuanxn.top/Article/details/gt2yvzciqal.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2cufzaqdq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2rsydinvl.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenzaomai.com/Article/details/gt2htyicejc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2ltphadkx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2qxgwugkv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2ympfyzdl.html

[F12] CSV 读写
来源：http://dali.xylfe.cn/Article/details/gt2klbdvoig.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.guowangkeji.top/Article/details/gt2cnnnxkwi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.guowangkeji.top/Article/details/gt2nyzouljl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.cashguo.top/Article/details/gt2qwcccwup.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2zgpmucpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gt2wkvtacgp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.tanke756.top/Article/details/gt2kzrikkzq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.haohaochexian.top/Article/details/gt2vftvwieh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258888.top/Article/details/gt2xnwdcuho.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ymnvzmgb.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2zojiyjmq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2ibalvnfq.html

[G01] 定义类
来源：http://dali.zdqjudy.top/Article/details/gt2vzwhjrig.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2getwkzdb.html

PHP:  class User {}
来源：http://dali.yueranfly.top/Article/details/gt2mcuzmati.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2pzibbefk.html

TS:   class User { name: string = ""; }
来源：http://dali.aibaodan.cn/Article/details/gt2mhxhslna.html

Java: class User {}
来源：http://dali.shzxlz.cn/Article/details/gt2olhyihbb.html

Go:   type User struct { Name string }
来源：http://dali.svipenyu.cn/Article/details/gt2tsjnobpl.html

Ruby: class User; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2ehyggzsx.html

C#:   class User {}
来源：http://dali.ybcxt.top/Article/details/gt2hjzrriey.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2stplimrw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2kgisbtka.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shuidangran.top/Article/details/gt2vluuulvq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2idxcjrqm.html

TS:   constructor(public name: string) {}
来源：http://dali.chenlongwang.top/Article/details/gt2igfoyyxs.html

Java: User(String name) { this.name = name; }
来源：http://dali.andypj.xyz/Article/details/gt2stcypclt.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.pycfn.com/Article/details/gt2xhfrkikz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.snrcjt.cn/Article/details/gt2manmqrgw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2uftjnhkt.html

[G03] 实例属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2ixkfsepm.html

Py:   self.name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2yiaagphc.html

PHP:  public string $name = "x";
来源：http://dali.mhx1999.top/Article/details/gt2ucxqafud.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdtwuezs.html

TS:   name: string = "x";
来源：http://dali.sweek.top/Article/details/gt2qkkahtvn.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2hpuvhtjq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.smart0.xyz/Article/details/gt2hrvxcmgn.html

Ruby: @name = "x"
来源：http://dali.xylfe.cn/Article/details/gt2cyjlcybv.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2jmjeqdra.html

[G04] 定义方法
来源：http://dali.ivvv.top/Article/details/gt2ocysvecx.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2ibnbrrce.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.cheryme.top/Article/details/gt2bktjbxxe.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jnpvcfqu.html

TS:   greet(): string { return this.name; }
来源：http://dali.jiagoushi.top/Article/details/gt2cjtodzyn.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2mopyytpv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2haecahxf.html

Ruby: def greet; @name; end
来源：http://dali.kuanghao11.cn/Article/details/gt2kcbdtjcm.html

C#:   public string Greet() => Name;
来源：http://dali.yongpay.top/Article/details/gt2wfexryxz.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gt2biulrjqm.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2owolsutf.html

PHP:  class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gt2vaymrmpx.html

JS:   class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2cxqeapyk.html

TS:   class Admin extends User {}
来源：http://dali.9152youxi.cn/Article/details/gt2ertowzzg.html

Java: class Admin extends User {}
来源：http://dali.fengsongda.top/Article/details/gt2minzdarm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.316326.xyz/Article/details/gt2gplsdvtg.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2sojnlahf.html

C#:   class Admin : User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2daznvwjz.html

[G06] 重写方法
来源：http://dali.birdmap.top/Article/details/gt2daxkaqcc.html

Py:   def greet(self): return "admin"
来源：http://dali.zdqjudy.top/Article/details/gt2whqlgdkt.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ukvkmlff.html

JS:   greet() { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2byyvufeg.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ffmnylpc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2wfovdkwh.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jyoumei.cn/Article/details/gt2ynqolkow.html

Ruby: def greet; "admin"; end
来源：http://dali.ydzc1.top/Article/details/gt2vlobkrky.html

C#:   public override string Greet() => "admin";
来源：http://dali.redwolf501.top/Article/details/gt2prkjfrcb.html

[G07] 调用父类方法
来源：http://dali.vqdsnc.cn/Article/details/gt2wkcoupaw.html

Py:   super().greet()
来源：http://dali.yuanzhike.top/Article/details/gt2csujasye.html

PHP:  parent::greet();
来源：http://dali.jiagoushi.top/Article/details/gt2xrcbwtui.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwpgbucl.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2rwieydcj.html

Java: super.greet();
来源：http://dali.chenlongwang.top/Article/details/gt2xhcvafbg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gt2ysuhquqg.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2dzktxjdo.html

C#:   base.Greet();
来源：http://dali.zdqjudy.top/Article/details/gt2kpyegoch.html

[G08] 静态方法与属性
来源：http://dali.hfpthk.cn/Article/details/gt2veroisqo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2wucdpjst.html

PHP:  public static function f() {}
来源：http://dali.xuanzx.com/Article/details/gt2uewvrndl.html

JS:   static f() {}
来源：http://dali.gotoacloud.top/Article/details/gt2snuzeqjg.html

TS:   static f(): void {}
来源：http://dali.daria6918.cn/Article/details/gt2vdyldvng.html

Java: static void f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2fmnfszvi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jiagoushi.top/Article/details/gt2lzbhbmpv.html

Ruby: def self.f; end
来源：http://dali.zdqjudy.top/Article/details/gt2acpfvxph.html

C#:   public static void F() {}
来源：http://dali.xziqi.cn/Article/details/gt2yhaqidyf.html

[G09] 接口 / 抽象类
来源：http://dali.zhengqikj.top/Article/details/gt2dujwxesv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2rmfqicpx.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gt2xzcjbafb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gt2kjjjaabc.html

TS:   interface Shape { area(): number; }
来源：http://dali.gaohongyu789.top/Article/details/gt2iaejochn.html

Java: interface Shape { double area(); }
来源：http://dali.yvedp.cn/Article/details/gt2jjrngxyq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.316326.xyz/Article/details/gt2lcsiozjg.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shzxlz.cn/Article/details/gt2hmkkxzgg.html

C#:   interface IShape { double Area(); }
来源：http://dali.ppjwa.cn/Article/details/gt2kpwlmioq.html

[G10] 访问控制
来源：http://dali.birdmap.top/Article/details/gt2yqmakngb.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.jqgfzy.top/Article/details/gt2spaijzeq.html

PHP:  public / protected / private
来源：http://dali.cheryme.top/Article/details/gt2pquhkbkj.html

JS:   #private 字段；其余公开
来源：http://dali.yongpay.top/Article/details/gt2xdqavozw.html

TS:   public / protected / private
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsdsokv.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2ohtvecxr.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.hnqzz.top/Article/details/gt2lfybjqbn.html

Ruby: public / protected / private
来源：http://dali.c1oappe.top/Article/details/gt2vielqfgy.html

C#:   public / protected / private / internal
来源：http://dali.yj202588.top/Article/details/gt2dettzyyr.html

[G11] getter / setter
来源：http://dali.hnxiangtu.top/Article/details/gt2gqtxqlmu.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gt2sqovcqkc.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2cekvwjwg.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2wiupdqbo.html

TS:   get name(): string { return this._name; }
来源：http://dali.wangdashe.top/Article/details/gt2sbmurrnp.html

Java: public String getName() { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sethrvwr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2ckmvirly.html

Ruby: attr_accessor :name
来源：http://dali.snrcjt.cn/Article/details/gt2tossbtvj.html

C#:   public string Name { get; set; }
来源：http://dali.haohaochexian.top/Article/details/gt2imuhugfo.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2msgiruma.html

Py:   def __str__(self): return self.name
来源：http://dali.jinqigfzy.top/Article/details/gt2zevohhnm.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.ivvv.top/Article/details/gt2cxvfirlm.html

JS:   toString() { return this.name; }
来源：http://dali.yongpay.top/Article/details/gt2xislbdrc.html

TS:   toString(): string { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2vaejacir.html

Java: @Override public String toString() { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2molhizlq.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.shuidangran.top/Article/details/gt2kfqetatt.html

Ruby: def to_s; @name; end
来源：http://dali.andypj.xyz/Article/details/gt2kgdpcnrs.html

C#:   public override string ToString() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2sqmotxjy.html

[G13] 判断对象类型
来源：http://dali.jinqigufen.top/Article/details/gt2uamcuccl.html

Py:   isinstance(u, User)
来源：http://dali.zdqjudy.top/Article/details/gt2cpjixhyp.html

PHP:  $u instanceof User
来源：http://dali.tanke756.top/Article/details/gt2ytjcscjb.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2yrzfiqrf.html

TS:   u instanceof User
来源：http://dali.xylfe.cn/Article/details/gt2uxeyzjzu.html

Java: u instanceof User
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mandbiob.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.snrcjt.cn/Article/details/gt2fzzjyshf.html

Ruby: u.is_a?(User)
来源：http://dali.wangshuangyany.cn/Article/details/gt2friisgsg.html

C#:   u is User
来源：http://dali.havefunace.top/Article/details/gt2vkhaqvvp.html

[G14] 数据类 / record
来源：http://dali.9152youxi.cn/Article/details/gt2lunfnbzn.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.kuanghao11.cn/Article/details/gt2qcftimqc.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhengqikj.top/Article/details/gt2zvtfrdro.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tianlin.xyz/Article/details/gt2vidnvuly.html

TS:   type User = { name: string; age: number };
来源：http://dali.sxryk.cn/Article/details/gt2bxqhqqfh.html

Java: record User(String name, int age) {}
来源：http://dali.snrcjt.cn/Article/details/gt2yoouaiyc.html

Go:   type User struct { Name string; Age int }
来源：http://dali.tian-w.cn/Article/details/gt2kgyinjfn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.vqdsnc.cn/Article/details/gt2hxzrsrif.html

C#:   record User(string Name, int Age);
来源：http://dali.guowangkeji.top/Article/details/gt2nhyjfdck.html

[G15] 枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhvhgegw.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jyoumei.cn/Article/details/gt2tptyybuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2lsiemytb.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.cdnleiting.top/Article/details/gt2tukzbbwr.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cucudq.cn/Article/details/gt2oqhbbtpn.html

Java: enum Color { RED, GREEN }
来源：http://dali.cucudq.cn/Article/details/gt2swrlmlcp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.zhixingplan.top/Article/details/gt2grlkahms.html

Ruby: Color = %i[red green].freeze
来源：http://dali.hfpthk.cn/Article/details/gt2imyeilas.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tanke756.top/Article/details/gt2jvbrfqgo.html

[G16] 对象转数组 / 字典
来源：http://dali.pengpengdd.cyou/Article/details/gt2rqiqkkww.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.mhx1999.top/Article/details/gt2trjsjvrb.html

PHP:  get_object_vars($obj);
来源：http://dali.sufxvd.cn/Article/details/gt2pqxxaxwi.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2vpinnoxq.html

TS:   Object.entries(obj)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qlkxjitt.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.redwolf501.top/Article/details/gt2heioqojn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2viwsbizm.html

Ruby: obj.instance_variables
来源：http://dali.ybcxt.top/Article/details/gt2kchlozwr.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yuanzhike.top/Article/details/gt2aiozyfgg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2aohgxjen.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2kviqlsnq.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2nitsrlvo.html

[H01] try / catch 基础
来源：http://dali.sufxvd.cn/Article/details/gt2zjyfpyhw.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.xziqi.cn/Article/details/gt2oqbolxjn.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.fengsongda.top/Article/details/gt2yxkbxwxi.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.gogol.net.cn/Article/details/gt2vxlemxsv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gt2ckwfrukq.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.aibaodan.cn/Article/details/gt2hqhgxakn.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.ybcxt.top/Article/details/gt2wxusyyjv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.iojbl.cn/Article/details/gt2yignuwqh.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.jianghu66.top/Article/details/gt2habgmapy.html

[H02] finally / ensure 收尾
来源：http://dali.smart0.xyz/Article/details/gt2njjskjpi.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.xuetiantiany.cn/Article/details/gt2boqmuejz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2acshsdha.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2tldbzjat.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gotoacloud.top/Article/details/gt2mauqsawi.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.jinqigufen.top/Article/details/gt2xrjczscm.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzbnque.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2xamdxxea.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2sumpeoug.html


<!-- 参考信息 -->