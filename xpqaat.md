代发 wailian999

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gt2sdicwiol.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2ugvbazek.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2uyeyzwws.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdiavjxz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gt2liyjkvbz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2zyejwcze.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2dlwdwsdk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gt2nlxrqwyh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gt2rvcxufxj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cheryme.top/Article/details/gt2tfiqqgcr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2wfjzikty.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2donursaw.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gt2xgzsviml.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gt2cayiujry.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2rpodczjs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkzvkdcu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2sbeqwfbq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gt2arnctfus.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gt2efygqckt.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2plfvwndz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhixingplan.top/Article/details/gt2pwjfqamr.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2ftppvzoe.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2mwsosqgz.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2qckwyltd.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gt2jidvdzst.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cdnleiting.top/Article/details/gt2atgfuzbj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2bqxkjbnq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gt2hywqpayr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2ytcwcciw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gt2ivgrhnzj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yvedp.cn/Article/details/gt2comrqnnd.html

Ruby: File.read("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2setdtiqx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2tabwlbxz.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2yfzjcsdf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gt2pmqjxmsh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2hwaotxyz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258.top/Article/details/gt2jczeqoxq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ukqktmii.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2hhgooypn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gt2zifjgiys.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.quarkkingdee.top/Article/details/gt2tduiazci.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hcscyazm.html

[F03] 写入文件（覆盖）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hppoqtfu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gt2crqjkjwv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gt2okiwzowm.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zfuracxk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gt2sgavfhnp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2eljqcvft.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dashuyun.cn/Article/details/gt2klqdyeks.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.vqdsnc.cn/Article/details/gt2mjtlxpvc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdobbxkp.html

[F04] 追加写入文件
来源：http://dali.havefunace.top/Article/details/gt2znjkmnng.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gt2hrjirlql.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.guowangkeji.top/Article/details/gt2hzxxtgxn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yangfankeji.com/Article/details/gt2uscbppcb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2gthwsgyn.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgztmavo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2qosspwgg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kasuhzwn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fzhhl.top/Article/details/gt2pogpsrty.html

[F05] 判断文件或目录是否存在
来源：http://dali.hfpthk.cn/Article/details/gt2ypuopvfd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gnsdwczi.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2kxmcczeb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2drytqpmg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2kukqfpar.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2huyblpmc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2hmvospgv.html

Ruby: File.exist?("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2iywlmxrm.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2awwymxac.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gt2uygaduzf.html

Py:   os.remove("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2owdqzzom.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2qigmedld.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uiatikos.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2brypgplu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2qkxmekne.html

Go:   os.Remove("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2rvruxkya.html

Ruby: File.delete("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2sgkenxpv.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2qgfsgchq.html

[F07] 创建目录（含多级）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhdevbrm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gzflamsi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2gixakfeb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2udaudnix.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gt2cyoeyxkv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2wxurxrhz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hnxiangtu.top/Article/details/gt2angqjfxb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2twpwcjgw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2vsynyvxe.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gt2teffcvlp.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sweek.top/Article/details/gt2yqsmdkff.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2lltulgao.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gt2ofvezikr.html

TS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2sjjqdnrg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ivvv.top/Article/details/gt2qnwxntsu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2ejhgizmk.html

Ruby: Dir.children("dir")
来源：http://dali.hammf.cn/Article/details/gt2knyhayjl.html

C#:   Directory.GetFiles("dir")
来源：http://dali.tanke756.top/Article/details/gt2rarxjhwd.html

[F09] 获取文件大小
来源：http://dali.kuanghao11.cn/Article/details/gt2nubfhzum.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2vqjwemro.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2csplggsw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.wangdashe.top/Article/details/gt2lcvauwuh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogjiqwty.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2hnkyjsaf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zycfv.cn/Article/details/gt2wdtxmelj.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xkycyzly.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2nomgktcd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.tianlin.xyz/Article/details/gt2mdwsvpnl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2idqtapnd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2odxtnppk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ogvunpao.html

TS:   path.extname("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2wjzzatzf.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjhfbcga.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2hudohmaq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2bybundbx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2hexregmf.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2zarumexj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2plsemval.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2odzlzzpb.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2goupswes.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wqbwncon.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2srcibtcb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2kyjirnre.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsbtvins.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gt2dpqtdsqa.html

[F12] CSV 读写
来源：http://dali.havefunace.top/Article/details/gt2wdjawstc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.bjfxy.top/Article/details/gt2xnbmpics.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ivvv.top/Article/details/gt2wucbbxrs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yj20258.top/Article/details/gt2glzdcihp.html

TS:   // 同上
来源：http://dali.daxiang520.top/Article/details/gt2kpxsxtkp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yuxming.cn/Article/details/gt2wtkgynmq.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gt2myxtsymb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hammf.cn/Article/details/gt2dsvzbtvs.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jqgufenzy.top/Article/details/gt2hxvlyqeg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2xbpyikua.html

G. 面向对象
来源：http://dali.ivvv.top/Article/details/gt2myergidn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vusnsbbp.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2slaowwko.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2ymqwxkbu.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2wsirznqp.html

JS:   class User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2dffjglas.html

TS:   class User { name: string = ""; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2omeraauj.html

Java: class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2xvplbped.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2otifdnmt.html

Ruby: class User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ipzdjmiz.html

C#:   class User {}
来源：http://dali.yj20258.top/Article/details/gt2lrlikmfj.html

[G02] 构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bahebbnb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gt2imcswgau.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hnqzz.top/Article/details/gt2mvrqjnxv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2qovbuahu.html

TS:   constructor(public name: string) {}
来源：http://dali.yangfankeji.com/Article/details/gt2cpqyznvn.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvvoroxz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2abaqspro.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yonumen.top/Article/details/gt2bzjgyavz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2zgxsbitc.html

[G03] 实例属性
来源：http://dali.cdnleiting.top/Article/details/gt2knbodddl.html

Py:   self.name = "x"
来源：http://dali.nwbrower.top/Article/details/gt2imcukske.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gt2foomdyfu.html

JS:   this.name = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wvylsppu.html

TS:   name: string = "x";
来源：http://dali.gogol.net.cn/Article/details/gt2edcdqhwy.html

Java: private String name;
来源：http://dali.jqgfzy.top/Article/details/gt2arlmlqku.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwwpefcr.html

Ruby: @name = "x"
来源：http://dali.chenjidiqi.icu/Article/details/gt2mnqbgdqf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afemwrio.html

[G04] 定义方法
来源：http://dali.zhijiandao.cn/Article/details/gt2sunepcmy.html

Py:   def greet(self): return self.name
来源：http://dali.xuanzx.com/Article/details/gt2ggkmpwuk.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xylfe.cn/Article/details/gt2frgpajmt.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2xwhlnpmc.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2ekvwypgz.html

Java: String greet() { return name; }
来源：http://dali.sxryk.cn/Article/details/gt2qlwikskr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.gzhubu.top/Article/details/gt2xeblyohw.html

Ruby: def greet; @name; end
来源：http://dali.birdmap.top/Article/details/gt2hxzgxsba.html

C#:   public string Greet() => Name;
来源：http://dali.cheryme.top/Article/details/gt2jagsqqkh.html

[G05] 继承
来源：http://dali.hnqzz.top/Article/details/gt2lyjrcrcj.html

Py:   class Admin(User): pass
来源：http://dali.yj202588.top/Article/details/gt2uqnkbdbe.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gt2eoegzctt.html

JS:   class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2hhyjraqw.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2hhgwzrbr.html

Java: class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2stjkmvtp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmmqifhk.html

Ruby: class Admin < User; end
来源：http://dali.jinqigufen.top/Article/details/gt2kzwcksrj.html

C#:   class Admin : User {}
来源：http://dali.9152youxi.cn/Article/details/gt2oaptycgy.html

[G06] 重写方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kdkokoii.html

Py:   def greet(self): return "admin"
来源：http://dali.sufxvd.cn/Article/details/gt2qhjdmtrm.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2hvvtelpp.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2hfojgjmr.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2stuipzew.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2wchtcdhl.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gt2wzusjlbr.html

Ruby: def greet; "admin"; end
来源：http://dali.yanxiufei.cn/Article/details/gt2gbpcshax.html

C#:   public override string Greet() => "admin";
来源：http://dali.yanxiufei.cn/Article/details/gt2mimylpyz.html

[G07] 调用父类方法
来源：http://dali.yuxming.cn/Article/details/gt2hnuncqhz.html

Py:   super().greet()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dzqmqkwv.html

PHP:  parent::greet();
来源：http://dali.wangdashe.top/Article/details/gt2dvtshuok.html

JS:   super.greet();
来源：http://dali.yueranfly.top/Article/details/gt2fjajyoao.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2snvvkaay.html

Java: super.greet();
来源：http://dali.daxiang520.top/Article/details/gt2fzqhpkds.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yanxiufei.cn/Article/details/gt2cjssoxam.html

Ruby: super
来源：http://dali.pycfn.com/Article/details/gt2unxfhxuy.html

C#:   base.Greet();
来源：http://dali.havefunace.top/Article/details/gt2qeuwwyas.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gt2ocaviklj.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dashuyun.cn/Article/details/gt2saaygfuo.html

PHP:  public static function f() {}
来源：http://dali.hnxiangtu.top/Article/details/gt2rtjjsuwl.html

JS:   static f() {}
来源：http://dali.hysaishi.cn/Article/details/gt2maougaxk.html

TS:   static f(): void {}
来源：http://dali.sysykeji.top/Article/details/gt2itdfpdfi.html

Java: static void f() {}
来源：http://dali.0kj1m.cn/Article/details/gt2llcjifrz.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.smart0.xyz/Article/details/gt2tapjumum.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gt2heywbczx.html

C#:   public static void F() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhhwwzgr.html

[G09] 接口 / 抽象类
来源：http://dali.yj202588.top/Article/details/gt2ukurwljt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.nwbrower.top/Article/details/gt2tnezxgzu.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.cheryme.top/Article/details/gt2duuoyiuw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.ehwqpu.com/Article/details/gt2dtafsejz.html

TS:   interface Shape { area(): number; }
来源：http://dali.shzxlz.cn/Article/details/gt2gocnywsu.html

Java: interface Shape { double area(); }
来源：http://dali.meibo888.top/Article/details/gt2jsitdxyw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shuidangran.top/Article/details/gt2wbtyyard.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzzmvete.html

C#:   interface IShape { double Area(); }
来源：http://dali.yangfankeji.com/Article/details/gt2nrfrfnbj.html

[G10] 访问控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2alspahim.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yonumen.top/Article/details/gt2cztyvhpe.html

PHP:  public / protected / private
来源：http://dali.gotoacloud.top/Article/details/gt2tksblnhs.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2aatrtdgo.html

TS:   public / protected / private
来源：http://dali.hammf.cn/Article/details/gt2ecjusbuw.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2qjezrald.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.pycfn.com/Article/details/gt2cyuurwct.html

Ruby: public / protected / private
来源：http://dali.gzhubu.top/Article/details/gt2dqsbdlgu.html

C#:   public / protected / private / internal
来源：http://dali.ivvv.top/Article/details/gt2fxuwlsbq.html

[G11] getter / setter
来源：http://dali.yongpay.top/Article/details/gt2jtzdwknu.html

Py:   @property 与 @x.setter
来源：http://dali.yvedp.cn/Article/details/gt2dsuucijs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nrpposly.html

JS:   get name() { return this._name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mwerqpkh.html

TS:   get name(): string { return this._name; }
来源：http://dali.smart0.xyz/Article/details/gt2ejkcnxcm.html

Java: public String getName() { return name; }
来源：http://dali.cashguo.top/Article/details/gt2vdscvend.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxlbiwym.html

Ruby: attr_accessor :name
来源：http://dali.dianchejie.cn/Article/details/gt2nwqmrcex.html

C#:   public string Name { get; set; }
来源：http://dali.hnqzz.top/Article/details/gt2ecoqrmoh.html

[G12] 对象转字符串
来源：http://dali.xinyue.icu/Article/details/gt2doaqnbem.html

Py:   def __str__(self): return self.name
来源：http://dali.ybcxt.top/Article/details/gt2tkejhsde.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.cqqwz.cn/Article/details/gt2hmuoooan.html

JS:   toString() { return this.name; }
来源：http://dali.ivvv.top/Article/details/gt2bqepowpt.html

TS:   toString(): string { return this.name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jvdqznsb.html

Java: @Override public String toString() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2fudtwmap.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.tian-w.cn/Article/details/gt2ayreeqok.html

Ruby: def to_s; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2twsscvdo.html

C#:   public override string ToString() => Name;
来源：http://dali.yonumen.top/Article/details/gt2iohrpeup.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2jkhgfkam.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gt2caydlhki.html

PHP:  $u instanceof User
来源：http://dali.zhixingplan.top/Article/details/gt2ueixpjan.html

JS:   u instanceof User
来源：http://dali.cqqwz.cn/Article/details/gt2ltdrtsgq.html

TS:   u instanceof User
来源：http://dali.ybcxt.top/Article/details/gt2hgrdkgrq.html

Java: u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2bpzjtvqq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tianlin.xyz/Article/details/gt2fvuphkcv.html

Ruby: u.is_a?(User)
来源：http://dali.ybcxt.top/Article/details/gt2bblwlrjm.html

C#:   u is User
来源：http://dali.svipenyu.cn/Article/details/gt2xcrtadrs.html

[G14] 数据类 / record
来源：http://dali.havefunace.top/Article/details/gt2vezrduey.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jqgufenzy.top/Article/details/gt2chewlbql.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jinqigfzy.top/Article/details/gt2drbazhgk.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.nanxinkj.top/Article/details/gt2wncqcssl.html

TS:   type User = { name: string; age: number };
来源：http://dali.andypj.xyz/Article/details/gt2becazjzf.html

Java: record User(String name, int age) {}
来源：http://dali.ybcxt.top/Article/details/gt2pogaixlu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wujtvhek.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.zhijiandao.cn/Article/details/gt2fjnixhox.html

C#:   record User(string Name, int Age);
来源：http://dali.zycfv.cn/Article/details/gt2fgxnzaee.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gt2fcstrybv.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivomuphh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.chenlongwang.top/Article/details/gt2zxbxpwqh.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.feifeiyinyue.top/Article/details/gt2wijzhivh.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vqvrqanr.html

Java: enum Color { RED, GREEN }
来源：http://dali.gotoacloud.top/Article/details/gt2bbfrhifp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.c1oappe.top/Article/details/gt2tjztxagk.html

Ruby: Color = %i[red green].freeze
来源：http://dali.shzxlz.cn/Article/details/gt2edryvobd.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.zhixingplan.top/Article/details/gt2esvxqhwu.html

[G16] 对象转数组 / 字典
来源：http://dali.bjfxy.top/Article/details/gt2reavdovz.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.tianlin.xyz/Article/details/gt2afccundl.html

PHP:  get_object_vars($obj);
来源：http://dali.hfpthk.cn/Article/details/gt2qjjovgam.html

JS:   Object.entries(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gt2leamxexz.html

TS:   Object.entries(obj)
来源：http://dali.yj20258888.top/Article/details/gt2fhrjoppk.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.ppjwa.cn/Article/details/gt2sqxeaapb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.gogol.net.cn/Article/details/gt2ypsisesl.html

Ruby: obj.instance_variables
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aifdfssj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pengpengdd.cyou/Article/details/gt2snapegdu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2uvrheebt.html

H. 异常与错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nmoxpgms.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2zkrbcyop.html

[H01] try / catch 基础
来源：http://dali.sxryk.cn/Article/details/gt2ekxkqpzn.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.zhoulong.xyz/Article/details/gt2xtkiodqw.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hysaishi.cn/Article/details/gt2uxcjqjay.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gt2qcoocllb.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vipzdzjy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gt2jofaozic.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cbadexeh.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.shuidangran.top/Article/details/gt2jdevrsjw.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.shzxlz.cn/Article/details/gt2zjjrzptd.html

[H02] finally / ensure 收尾
来源：http://dali.yvedp.cn/Article/details/gt2ljgsvbbe.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.cdnleiting.top/Article/details/gt2qmuetuuy.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.xuanzx.com/Article/details/gt2danopiok.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvspgkit.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2caiabeno.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.aizwys.cn/Article/details/gt2taueoscv.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.havefunace.top/Article/details/gt2agutjwye.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2cqgewqhs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2dqzyrivs.html


<!-- 参考信息 -->