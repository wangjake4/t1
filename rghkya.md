代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtpwnhaycq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbdcnpkid.html

TS:   if (s === "") {}
来源：http://dali.nwbrower.top/Article/details/gtpmjqjunh.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gtacxebvqb.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtswbjsipw.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtbwrnntlv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtbsmgxzjw.html

[E21] 超长截断加省略号
来源：http://dali.fengsongda.top/Article/details/gtwqdeaqae.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gtpkcklsjs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtcdcvrzlw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gtfmliovku.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtvhbvykyt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtxfpjcsys.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.bjfxy.top/Article/details/gtypynjjwp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtcpsbrvrm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtumxwzlyx.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gthzqtoohs.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gtcmoswxen.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtxnozpuyx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtgsrdtoni.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gtbjotkgyx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cdnleiting.top/Article/details/gtiozfrzyt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtbyraoobh.html

Ruby: s.bytesize;  s.length
来源：http://dali.andypj.xyz/Article/details/gtreczudfv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj202588.top/Article/details/gtzvclbpwd.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtlyphopld.html

F. 文件与目录
来源：http://dali.sufxvd.cn/Article/details/gtbropsgzn.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtrtwzsehw.html

[F01] 读取整个文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrypdvmbg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gtfowduihx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtnqypibpo.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtkjdhosii.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gtpwxraepg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtygrwcsun.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gzhubu.top/Article/details/gtbrqnfnof.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdkcbxuu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtqktvvfcu.html

[F02] 逐行读取文件
来源：http://dali.cdnleiting.top/Article/details/gtfveohhjf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.smart0.xyz/Article/details/gtqlymlmib.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.hfpthk.cn/Article/details/gtzrfjfksi.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtymmmqfid.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgfzy.top/Article/details/gtfjmxwzzl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuetiantiany.cn/Article/details/gtgvjvdjuv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.aizwys.cn/Article/details/gtinoaeuzg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtpdvfamqv.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtigxvgzzr.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gtcdmfnrsv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjovrjfq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jqgfzy.top/Article/details/gtdnehbjle.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gtuemfhojj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gtyrmymfop.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtxbmnrtfd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenlongwang.top/Article/details/gtlrxxqlkt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtwsccstlw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtbbivseig.html

[F04] 追加写入文件
来源：http://dali.feifeiyinyue.top/Article/details/gtdcifcmuy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.c1oappe.top/Article/details/gtcpvbvuer.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gtslviremf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtkjgowyqe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtcmsjixxh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gtveihsnwu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqrdeibj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gtkjdhelgo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gtfifhgnzx.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gttkggfyci.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gogol.net.cn/Article/details/gtclyjovzj.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtcqbrptmt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtehggxyii.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtzpgkodcy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gtqjwosdzs.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtghvxdtpp.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmsdvckio.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtsmhfowzv.html

[F06] 删除文件
来源：http://dali.sweek.top/Article/details/gtqpnbfmro.html

Py:   os.remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdwrglabv.html

PHP:  unlink("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtvntoejss.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtxtyywglp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtaomorsjx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtlgsljrif.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtcxhmsmnd.html

Ruby: File.delete("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtvfqtgvxx.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtputerqed.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtywbawlwz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtzwssqfpw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtkkvvcljr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtbxswvpis.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtikvhqjgr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.daxiang520.top/Article/details/gtmgtlfnfs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinghuilouyu.cn/Article/details/gthduwcrvu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gtuvcqjaev.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.andypj.xyz/Article/details/gtufwmvryg.html

[F08] 遍历目录
来源：http://dali.hammf.cn/Article/details/gtuwzrhhbn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.kuanghao11.cn/Article/details/gtqprriorn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gtedsvlvij.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtbgimowhs.html

TS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gtqgyznosr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtkmdmznqt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yuanzhike.top/Article/details/gtmngcteji.html

Ruby: Dir.children("dir")
来源：http://dali.yj202588.top/Article/details/gtpenrttln.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gtacijiipm.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gtjyqfuhtc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvhmkdzgg.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtlvivdlhq.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sweek.top/Article/details/gtrnnrhabf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gtpmgfftwx.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtmwlosfrd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinqigfzy.top/Article/details/gtfwitdchf.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtrmkdgdsq.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtyghmsiup.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjeewkyr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwqgrbiwn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tian-w.cn/Article/details/gtoprfetqn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtbiheihuz.html

TS:   path.extname("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtiehhaonz.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdswsmgda.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtdtxchqrv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtlkndhtza.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthofiyuwv.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtdykgcldk.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkizlncuh.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtxkcqystm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtlyrxeqgf.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jqgfzy.top/Article/details/gtutlgcswn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.havefunace.top/Article/details/gtuebbwaxh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinghuilouyu.cn/Article/details/gtvajkdbsh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gtfzkrxcrp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj202588.top/Article/details/gtetvxlbxk.html

[F12] CSV 读写
来源：http://dali.pengpengdd.cyou/Article/details/gtxxdjvmnh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdrmbydx.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.0kj1m.cn/Article/details/gtdsywavci.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.redwolf501.top/Article/details/gtugfllsqx.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gtscgldmaq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gtuhmmnfbo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcohsakhw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtyguaghdj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.guannengcc.top/Article/details/gtosxugriv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaavvubcx.html

G. 面向对象
来源：http://dali.aizwys.cn/Article/details/gteowzpfjd.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtoraskaxh.html

[G01] 定义类
来源：http://dali.yuxming.cn/Article/details/gtjmldihlu.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtjrqcjhym.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gtbaboecbf.html

JS:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtipczrrqi.html

TS:   class User { name: string = ""; }
来源：http://dali.zdqjudy.top/Article/details/gtzgsrugtt.html

Java: class User {}
来源：http://dali.vqdsnc.cn/Article/details/gtesudcvuq.html

Go:   type User struct { Name string }
来源：http://dali.tian-w.cn/Article/details/gtfxioqkyp.html

Ruby: class User; end
来源：http://dali.haohaochexian.top/Article/details/gtdxryftfd.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtraisykos.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gtqjnbbixm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.c1oappe.top/Article/details/gtfsnwmlbz.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.birdmap.top/Article/details/gtlcrrzzns.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdspwdln.html

TS:   constructor(public name: string) {}
来源：http://dali.guannengcc.top/Article/details/gtoohbgvxh.html

Java: User(String name) { this.name = name; }
来源：http://dali.dianchejie.cn/Article/details/gtzyljiijp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.bjfxy.top/Article/details/gtqhpsyhsc.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jianghu66.top/Article/details/gtmvnpswyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.quarkkingdee.top/Article/details/gtwrhgqkft.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gtrkkiulio.html

Py:   self.name = "x"
来源：http://dali.nanxinkj.top/Article/details/gtcjvbhwcw.html

PHP:  public string $name = "x";
来源：http://dali.wangdashe.top/Article/details/gtexhndxoo.html

JS:   this.name = "x";
来源：http://dali.meibo888.top/Article/details/gtumozwazi.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkynqtgj.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtscrocrkm.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jqgufenzy.top/Article/details/gtohvpnwkl.html

Ruby: @name = "x"
来源：http://dali.yongpay.top/Article/details/gtvlqlkwtd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gtfzxyjdcx.html

[G04] 定义方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjsnjcld.html

Py:   def greet(self): return self.name
来源：http://dali.vqdsnc.cn/Article/details/gtbcurifrf.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxuanxn.top/Article/details/gthamrqmnh.html

JS:   greet() { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gtbaanyxuo.html

TS:   greet(): string { return this.name; }
来源：http://dali.gotoacloud.top/Article/details/gtlyhblyhy.html

Java: String greet() { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtxyvzfqzg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hysaishi.cn/Article/details/gtriszwvxq.html

Ruby: def greet; @name; end
来源：http://dali.guannengcc.top/Article/details/gtokcwkmiu.html

C#:   public string Greet() => Name;
来源：http://dali.zdqjudy.top/Article/details/gtjdqlsdhc.html

[G05] 继承
来源：http://dali.guannengcc.top/Article/details/gtawlfrvsj.html

Py:   class Admin(User): pass
来源：http://dali.yongpay.top/Article/details/gtrsoadpgu.html

PHP:  class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gtojzrkdsm.html

JS:   class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gttpctlxkv.html

TS:   class Admin extends User {}
来源：http://dali.jqgufenzy.top/Article/details/gthvfplwje.html

Java: class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtvpxhabnz.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nanxuanxn.top/Article/details/gtsizozrhm.html

Ruby: class Admin < User; end
来源：http://dali.cheryme.top/Article/details/gtllqjgezo.html

C#:   class Admin : User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtbqkfqzgk.html

[G06] 重写方法
来源：http://dali.wangdashe.top/Article/details/gtklbyulwl.html

Py:   def greet(self): return "admin"
来源：http://dali.0kj1m.cn/Article/details/gtjeziigll.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciqvkyiv.html

JS:   greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtzzrcdbvp.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cucudq.cn/Article/details/gtbnmszosm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.iojbl.cn/Article/details/gthoewcvlt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.sxryk.cn/Article/details/gtomgibbpk.html

Ruby: def greet; "admin"; end
来源：http://dali.pycfn.com/Article/details/gtezgbxdig.html

C#:   public override string Greet() => "admin";
来源：http://dali.yonumen.top/Article/details/gtwekyaasb.html

[G07] 调用父类方法
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwmksoif.html

Py:   super().greet()
来源：http://dali.xuanzx.com/Article/details/gtougjvtib.html

PHP:  parent::greet();
来源：http://dali.chenjidiqi.icu/Article/details/gtglzdjkhq.html

JS:   super.greet();
来源：http://dali.0kj1m.cn/Article/details/gtgvqeesvt.html

TS:   super.greet();
来源：http://dali.tianlin.xyz/Article/details/gtmqtgtrtk.html

Java: super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtihhytpox.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shzxlz.cn/Article/details/gtznotksnr.html

Ruby: super
来源：http://dali.ybcxt.top/Article/details/gtplxnzsgx.html

C#:   base.Greet();
来源：http://dali.yj20258.top/Article/details/gthedlwbgf.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gtabtbnpvl.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gtxetnllaf.html

PHP:  public static function f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyuhqnsol.html

JS:   static f() {}
来源：http://dali.hnxiangtu.top/Article/details/gtvhuidtta.html

TS:   static f(): void {}
来源：http://dali.dashuyun.cn/Article/details/gtlroyzrzx.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtzzfiyvwi.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.mhx1999.top/Article/details/gtgagqumho.html

Ruby: def self.f; end
来源：http://dali.zycfv.cn/Article/details/gtapwkkzzp.html

C#:   public static void F() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuxngvwc.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gtyivfvxla.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yj202588.top/Article/details/gtzdbyhxnk.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigufen.top/Article/details/gttondvuod.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.tanke756.top/Article/details/gtmjwytpvv.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gtiokcqtcw.html

Java: interface Shape { double area(); }
来源：http://dali.yongpay.top/Article/details/gtejpbeebn.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.jianghu66.top/Article/details/gtnilcpgjr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtsllyxedy.html

C#:   interface IShape { double Area(); }
来源：http://dali.hfpthk.cn/Article/details/gtmkixwoow.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gtfawsbvgd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yj202588.top/Article/details/gtjjtynbmn.html

PHP:  public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxpyvzhf.html

JS:   #private 字段；其余公开
来源：http://dali.andypj.xyz/Article/details/gtbrkbhnih.html

TS:   public / protected / private
来源：http://dali.shzxlz.cn/Article/details/gtrpcvpxsc.html

Java: public / protected / private / 默认包级
来源：http://dali.shuidangran.top/Article/details/gtylwjtjeg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.gogol.net.cn/Article/details/gtbfmutjkn.html

Ruby: public / protected / private
来源：http://dali.yuanzhike.top/Article/details/gtygjnqhep.html

C#:   public / protected / private / internal
来源：http://dali.tanke756.top/Article/details/gtauwbminr.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrefqbfdn.html

Py:   @property 与 @x.setter
来源：http://dali.gogol.net.cn/Article/details/gtzskirdli.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.cdnleiting.top/Article/details/gtlwerdsvr.html

JS:   get name() { return this._name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmlhbvbkb.html

TS:   get name(): string { return this._name; }
来源：http://dali.hfpthk.cn/Article/details/gttdwnmmui.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gtsyfmmogl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigufen.top/Article/details/gtaablxsup.html

Ruby: attr_accessor :name
来源：http://dali.jinqigfzy.top/Article/details/gtgzsyitdq.html

C#:   public string Name { get; set; }
来源：http://dali.aizwys.cn/Article/details/gtxgbrulhm.html

[G12] 对象转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtrtresoxm.html

Py:   def __str__(self): return self.name
来源：http://dali.chenzaomai.com/Article/details/gtdvzaewef.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtncqlmtcm.html

JS:   toString() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvnopwvay.html

TS:   toString(): string { return this.name; }
来源：http://dali.shuidangran.top/Article/details/gtjikvitvc.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gtjulfmbya.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.jlsjyb.cn/Article/details/gtczzsfjxh.html

Ruby: def to_s; @name; end
来源：http://dali.chenzaomai.com/Article/details/gtdtcplydm.html

C#:   public override string ToString() => Name;
来源：http://dali.jianghu66.top/Article/details/gtlvnqxgky.html

[G13] 判断对象类型
来源：http://dali.dashuyun.cn/Article/details/gtzjphiwfx.html

Py:   isinstance(u, User)
来源：http://dali.sweek.top/Article/details/gteoxpvphm.html

PHP:  $u instanceof User
来源：http://dali.316326.xyz/Article/details/gtvnpwlnsd.html

JS:   u instanceof User
来源：http://dali.hywenlv.cn/Article/details/gtcsnyrsrw.html

TS:   u instanceof User
来源：http://dali.havefunace.top/Article/details/gtvmpmkdia.html

Java: u instanceof User
来源：http://dali.yongpay.top/Article/details/gtsgwwarkz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.hysaishi.cn/Article/details/gtcudcpbgr.html

Ruby: u.is_a?(User)
来源：http://dali.cqqwz.cn/Article/details/gtyxgrozdt.html

C#:   u is User
来源：http://dali.jqgufenzy.top/Article/details/gtmhbefqmu.html

[G14] 数据类 / record
来源：http://dali.zhiwuduotai.top/Article/details/gtayugvbyw.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.hywenlv.cn/Article/details/gtxpsvblxb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gtmgbpyprw.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.quarkkingdee.top/Article/details/gtqgujmgzu.html

TS:   type User = { name: string; age: number };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpkxmcue.html

Java: record User(String name, int age) {}
来源：http://dali.redwolf501.top/Article/details/gtumllejtl.html

Go:   type User struct { Name string; Age int }
来源：http://dali.daria6918.cn/Article/details/gtkhjosmal.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.nwbrower.top/Article/details/gtlzxxztuz.html

C#:   record User(string Name, int Age);
来源：http://dali.yangfankeji.com/Article/details/gtmmfibdjz.html

[G15] 枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtgajeyjfi.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.jinqigfzy.top/Article/details/gtycikospl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtivlzmrrn.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.gogol.net.cn/Article/details/gtrjjbjwbe.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.wangdashe.top/Article/details/gtnbhkivxu.html

Java: enum Color { RED, GREEN }
来源：http://dali.hongshengwenyu.top/Article/details/gtovraurnq.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.cheryme.top/Article/details/gtwygjsibn.html

Ruby: Color = %i[red green].freeze
来源：http://dali.mhx1999.top/Article/details/gtssscbhjt.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtjpsxjmlt.html

[G16] 对象转数组 / 字典
来源：http://dali.yueranfly.top/Article/details/gtanqqnote.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtqaemnern.html

PHP:  get_object_vars($obj);
来源：http://dali.zhijiandao.cn/Article/details/gtemsxjczd.html

JS:   Object.entries(obj)
来源：http://dali.iojbl.cn/Article/details/gtlgqzpsoi.html

TS:   Object.entries(obj)
来源：http://dali.vqdsnc.cn/Article/details/gteuoqwjqo.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.daxiang520.top/Article/details/gtkxpjgmvr.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zycfv.cn/Article/details/gttgnkmjzy.html

Ruby: obj.instance_variables
来源：http://dali.cheryme.top/Article/details/gthxjvwinh.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.tian-w.cn/Article/details/gtxgrxyowc.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gthkmvtuiy.html

H. 异常与错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtuktappxy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtgfupehvl.html

[H01] try / catch 基础
来源：http://dali.yonumen.top/Article/details/gtvvrkxmrm.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.wangdashe.top/Article/details/gtduckkobh.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.daxiang520.top/Article/details/gtehkyjggr.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.fengsongda.top/Article/details/gtdplcnixd.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gtdhonaihg.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.zhijiandao.cn/Article/details/gtlbczbozg.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gaohongyu789.top/Article/details/gtvreggven.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hfpthk.cn/Article/details/gtnhcxeydd.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.havefunace.top/Article/details/gtcfhqafdc.html

[H02] finally / ensure 收尾
来源：http://dali.jqgfzy.top/Article/details/gtydquevqh.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhiwuduotai.top/Article/details/gtvtglczfx.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gtipgacsju.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.fengsongda.top/Article/details/gtunkbsjcz.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.meibo888.top/Article/details/gtqpxceehi.html


<!-- 参考信息 -->