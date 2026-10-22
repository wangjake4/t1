代发 wailian999

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2jqkiqfgx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jyoumei.cn/Article/details/gt2tnqhblma.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2xafueiqy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2kcmgxmcu.html

[E22] 字节长度与字符长度
来源：http://dali.jianghu66.top/Article/details/gt2husafncv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gt2qpthnvwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gt2ozixraoj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gt2bnglkxqz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gt2dawixnfd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hammf.cn/Article/details/gt2vazujqzu.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.daxiang520.top/Article/details/gt2idtmgkhm.html

Ruby: s.bytesize;  s.length
来源：http://dali.cashguo.top/Article/details/gt2twmssczc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jianghu66.top/Article/details/gt2bamjvqza.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2fxmsaxvj.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2vprghjdr.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xqafeqmc.html

[F01] 读取整个文件
来源：http://dali.ppjwa.cn/Article/details/gt2ujogptdx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangdashe.top/Article/details/gt2lwgdxhvn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2hvrcpzzl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.iojbl.cn/Article/details/gt2byrzhzmc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xinyue.icu/Article/details/gt2tqlylvln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2fmgnrvcw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.9152youxi.cn/Article/details/gt2fewmfpey.html

Ruby: File.read("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqieqxol.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gt2jqfkdxgm.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gt2lkpobfyd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2wgduowvn.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gt2xyiqputx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2iwgpzgas.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2optcvbkb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhixingplan.top/Article/details/gt2yfqmzjun.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gt2jvnjzeog.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.316326.xyz/Article/details/gt2rqzgkysq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2cztfbxax.html

[F03] 写入文件（覆盖）
来源：http://dali.ydzc1.top/Article/details/gt2gmnlgvil.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.bjfxy.top/Article/details/gt2umqefiay.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gt2scxlpdjj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zdqjudy.top/Article/details/gt2ekzjvosi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gt2ybzdmuzh.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jlsjyb.cn/Article/details/gt2uxgcfvoy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.bjfxy.top/Article/details/gt2didngysu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.aibaodan.cn/Article/details/gt2prylkrsy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2fbnskrzu.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2ssqwpzms.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.redwolf501.top/Article/details/gt2hugpmzek.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ydzc1.top/Article/details/gt2xjvyaqzb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2hnftcgqk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2vankezpz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2xlbyfzqj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2hyqyfkna.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gt2umnfydqy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gt2wukpazet.html

[F05] 判断文件或目录是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2nedzeaza.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenlongwang.top/Article/details/gt2cniwtkco.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2dxyblyqk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2kmebxkxb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2amnoqjfl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2msibosaw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gt2fpnuluyx.html

Ruby: File.exist?("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2mogadhur.html

C#:   File.Exists("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2csawmxas.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gt2volzoblc.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jvoaadyj.html

PHP:  unlink("a.txt");
来源：http://dali.iojbl.cn/Article/details/gt2onfnjsig.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2ghqjgbba.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yjfuimam.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gt2ensqpnrb.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlvvsisb.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hdemdejv.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2pdesvofo.html

[F07] 创建目录（含多级）
来源：http://dali.redwolf501.top/Article/details/gt2prpirzge.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2miuunuds.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjwdpows.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gt2vwgglgsd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2lxmitnni.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.vqdsnc.cn/Article/details/gt2inspnwxs.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yongpay.top/Article/details/gt2ggqqsymv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2waixulgu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2zohrvfkf.html

[F08] 遍历目录
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgzmxjog.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.vqdsnc.cn/Article/details/gt2lvjxxbzd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqvbarwc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ftiuoiaa.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2wqctvxma.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2zyijycve.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.sxryk.cn/Article/details/gt2nqfdetha.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2vlloktrp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2mtlmypkt.html

[F09] 获取文件大小
来源：http://dali.guannengcc.top/Article/details/gt2krjvfpey.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mxopttgv.html

PHP:  filesize("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2xtflydrl.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2gygmyxoe.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2uzivnqws.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2tgbvqivu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.daria6918.cn/Article/details/gt2becxoegq.html

Ruby: File.size("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2kuuwdzhr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2uhguyapd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.bjfxy.top/Article/details/gt2jlozrrht.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2ioenavnn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gt2qxdcjujo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kzvadwiv.html

TS:   path.extname("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2qlgeyulc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zdqjudy.top/Article/details/gt2uudnwvsf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2vzkmjhgt.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2uvybaiyc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2mgyqjmkr.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gt2lcjclwmg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2gcewdabl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2vuisgutk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2jkuzvfui.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2lutmpeni.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dbpoqipn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phcodunk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2bctcqtjm.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.vqdsnc.cn/Article/details/gt2ndoszoza.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2xoqrgulb.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gt2pdnosyci.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2qjavcqzc.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhengqikj.top/Article/details/gt2pcdcyhus.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2hndcarvh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jianghu66.top/Article/details/gt2xtwfpjbs.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.iojbl.cn/Article/details/gt2zkuuhuup.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuetiantiany.cn/Article/details/gt2tebptmbw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hywenlv.cn/Article/details/gt2htnpxckp.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2bebjoxfm.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gt2eikethkn.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ltqqbwim.html

[G01] 定义类
来源：http://dali.andypj.xyz/Article/details/gt2rwzbxnzf.html

Py:   class User: pass
来源：http://dali.hfpthk.cn/Article/details/gt2ptsehrhp.html

PHP:  class User {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gyubkzic.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2jehmrhya.html

TS:   class User { name: string = ""; }
来源：http://dali.shzxlz.cn/Article/details/gt2sodbdony.html

Java: class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2ojemyecp.html

Go:   type User struct { Name string }
来源：http://dali.yvedp.cn/Article/details/gt2bnknmift.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2nhcpsqrb.html

C#:   class User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2jtjlyhhn.html

[G02] 构造函数
来源：http://dali.gzhubu.top/Article/details/gt2dciigsfa.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gt2lftxbavh.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.smart0.xyz/Article/details/gt2jqzvdnzk.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2mpsfsslr.html

TS:   constructor(public name: string) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ionbycmo.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2qfcdspkk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.havefunace.top/Article/details/gt2wzrdtrkx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gt2sigcgcyz.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bepqqkjt.html

[G03] 实例属性
来源：http://dali.shzxlz.cn/Article/details/gt2pgexnaow.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2twsghgew.html

PHP:  public string $name = "x";
来源：http://dali.c1oappe.top/Article/details/gt2tpnhrkyj.html

JS:   this.name = "x";
来源：http://dali.yuxming.cn/Article/details/gt2sjpoducw.html

TS:   name: string = "x";
来源：http://dali.cdnleiting.top/Article/details/gt2ltlehycs.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2wootpzgh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.snrcjt.cn/Article/details/gt2hpvpqpwj.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2sshlleho.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2zzgdaxtl.html

[G04] 定义方法
来源：http://dali.jlsjyb.cn/Article/details/gt2ylafotgm.html

Py:   def greet(self): return self.name
来源：http://dali.shangyingyoupin.top/Article/details/gt2nktfddxz.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.xuanzx.com/Article/details/gt2xwtjpdxp.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2lsaqgqcy.html

TS:   greet(): string { return this.name; }
来源：http://dali.shzxlz.cn/Article/details/gt2jumwfqiu.html

Java: String greet() { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2typsmcgn.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2oifrreqc.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gt2yybpjarg.html

C#:   public string Greet() => Name;
来源：http://dali.cdnleiting.top/Article/details/gt2rxrslahv.html

[G05] 继承
来源：http://dali.chenjidiqi.icu/Article/details/gt2afbamcmx.html

Py:   class Admin(User): pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2zqetbzce.html

PHP:  class Admin extends User {}
来源：http://dali.gotoacloud.top/Article/details/gt2shjoussh.html

JS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2onrhhcxu.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2avhgsazm.html

Java: class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvyjalbd.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.andypj.xyz/Article/details/gt2ovugjfjz.html

Ruby: class Admin < User; end
来源：http://dali.aibaodan.cn/Article/details/gt2hvxvfdtn.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2mlncclji.html

[G06] 重写方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2ipnqygtp.html

Py:   def greet(self): return "admin"
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvxwaivf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258.top/Article/details/gt2pehshtou.html

JS:   greet() { return "admin"; }
来源：http://dali.yonumen.top/Article/details/gt2agfamixe.html

TS:   greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2bwlnisgm.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.haohaochexian.top/Article/details/gt2fptkamla.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2nadwyjcs.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2gzlrsdni.html

C#:   public override string Greet() => "admin";
来源：http://dali.xziqi.cn/Article/details/gt2kmbzlsjx.html

[G07] 调用父类方法
来源：http://dali.zhengqikj.top/Article/details/gt2zocrjnpt.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2acxfkzxd.html

PHP:  parent::greet();
来源：http://dali.zhixingplan.top/Article/details/gt2swmlscwy.html

JS:   super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2rlpdbass.html

TS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2ilwpyess.html

Java: super.greet();
来源：http://dali.hfpthk.cn/Article/details/gt2pggmrtvn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2jcjwwfqv.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2eyvyhrul.html

C#:   base.Greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2lydvhdvy.html

[G08] 静态方法与属性
来源：http://dali.hammf.cn/Article/details/gt2oqaabtsf.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zhijiandao.cn/Article/details/gt2dqisvsag.html

PHP:  public static function f() {}
来源：http://dali.guowangkeji.top/Article/details/gt2daptzixu.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2qjayvosm.html

TS:   static f(): void {}
来源：http://dali.gaohongyu789.top/Article/details/gt2veorahow.html

Java: static void f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkxsdbgm.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zyziuhwh.html

Ruby: def self.f; end
来源：http://dali.nwbrower.top/Article/details/gt2suspcwrc.html

C#:   public static void F() {}
来源：http://dali.shzxlz.cn/Article/details/gt2rdjutnkw.html

[G09] 接口 / 抽象类
来源：http://dali.yueranfly.top/Article/details/gt2xsmnkohn.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daxiang520.top/Article/details/gt2vdpbseib.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.snrcjt.cn/Article/details/gt2aojxgbsy.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xinyue.icu/Article/details/gt2isjdonot.html

TS:   interface Shape { area(): number; }
来源：http://dali.quarkkingdee.top/Article/details/gt2befeklqj.html

Java: interface Shape { double area(); }
来源：http://dali.tianlin.xyz/Article/details/gt2tncwdygq.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsvintxb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jinqigufen.top/Article/details/gt2amnkxhca.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuxming.cn/Article/details/gt2ntnrrsco.html

[G10] 访问控制
来源：http://dali.xinyue.icu/Article/details/gt2ofpfdesy.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.gogol.net.cn/Article/details/gt2grinnpdz.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2mhnujjqr.html

JS:   #private 字段；其余公开
来源：http://dali.daria6918.cn/Article/details/gt2whmsrfog.html

TS:   public / protected / private
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqncixsm.html

Java: public / protected / private / 默认包级
来源：http://dali.shzxlz.cn/Article/details/gt2kbgwpwmx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gt2kgiftwqu.html

Ruby: public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2fxisxqlp.html

C#:   public / protected / private / internal
来源：http://dali.zhengqikj.top/Article/details/gt2srglhfzk.html

[G11] getter / setter
来源：http://dali.dianchejie.cn/Article/details/gt2bvbhdoaw.html

Py:   @property 与 @x.setter
来源：http://dali.aizwys.cn/Article/details/gt2hnthkedp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rdfxbjqc.html

JS:   get name() { return this._name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kgskujdc.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpyshmwb.html

Java: public String getName() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2vrggnidv.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.fzhhl.top/Article/details/gt2qktaakpc.html

Ruby: attr_accessor :name
来源：http://dali.shuidangran.top/Article/details/gt2qvksydtv.html

C#:   public string Name { get; set; }
来源：http://dali.cheryme.top/Article/details/gt2yvhhdtau.html

[G12] 对象转字符串
来源：http://dali.chenjidiqi.icu/Article/details/gt2enjwzfmj.html

Py:   def __str__(self): return self.name
来源：http://dali.cheryme.top/Article/details/gt2tnebxyoc.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xfitqlxa.html

JS:   toString() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2spgpkqph.html

TS:   toString(): string { return this.name; }
来源：http://dali.sysykeji.top/Article/details/gt2esuwsnuw.html

Java: @Override public String toString() { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2mcjlbyno.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.dianchejie.cn/Article/details/gt2eebhjqep.html

Ruby: def to_s; @name; end
来源：http://dali.yangfankeji.com/Article/details/gt2lngzeysc.html

C#:   public override string ToString() => Name;
来源：http://dali.tanke756.top/Article/details/gt2cjvgdrkv.html

[G13] 判断对象类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuyvuebk.html

Py:   isinstance(u, User)
来源：http://dali.jinqigufen.top/Article/details/gt2sbwwdhuq.html

PHP:  $u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2sktodsbc.html

JS:   u instanceof User
来源：http://dali.zhongyouzk.top/Article/details/gt2opiehzqk.html

TS:   u instanceof User
来源：http://dali.zdqjudy.top/Article/details/gt2dwyvknpp.html

Java: u instanceof User
来源：http://dali.aibaodan.cn/Article/details/gt2voydsord.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.tanke756.top/Article/details/gt2duylwezs.html

Ruby: u.is_a?(User)
来源：http://dali.zhoulong.xyz/Article/details/gt2txzjrfew.html

C#:   u is User
来源：http://dali.dashuyun.cn/Article/details/gt2dsntjztn.html

[G14] 数据类 / record
来源：http://dali.vqdsnc.cn/Article/details/gt2mldzxuvu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.pycfn.com/Article/details/gt2qgvxxnhq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.316326.xyz/Article/details/gt2odrfhlhs.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.xuetiantiany.cn/Article/details/gt2lexuumlt.html

TS:   type User = { name: string; age: number };
来源：http://dali.tian-w.cn/Article/details/gt2xnsqsldx.html

Java: record User(String name, int age) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hifhkuwp.html

Go:   type User struct { Name string; Age int }
来源：http://dali.ybcxt.top/Article/details/gt2rqshyfrl.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.iojbl.cn/Article/details/gt2nxldrrza.html

C#:   record User(string Name, int Age);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdsbkuvk.html

[G15] 枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hraxemwa.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2hezjojuo.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.hywenlv.cn/Article/details/gt2cpfwedor.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.guowangkeji.top/Article/details/gt2vbeweljb.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.0kj1m.cn/Article/details/gt2dvusqoyk.html

Java: enum Color { RED, GREEN }
来源：http://dali.nanxinkj.top/Article/details/gt2aeiddhss.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cosnmpdw.html

Ruby: Color = %i[red green].freeze
来源：http://dali.xinyue.icu/Article/details/gt2qnfomfze.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.gzhubu.top/Article/details/gt2afnsbekj.html

[G16] 对象转数组 / 字典
来源：http://dali.yj20258888.top/Article/details/gt2cotajplc.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.hammf.cn/Article/details/gt2yduvuval.html

PHP:  get_object_vars($obj);
来源：http://dali.cashguo.top/Article/details/gt2xhrtsaam.html

JS:   Object.entries(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2vfitbzyw.html

TS:   Object.entries(obj)
来源：http://dali.fzhhl.top/Article/details/gt2ffvfpsqm.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.chenlongwang.top/Article/details/gt2kluaezyg.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.hnxiangtu.top/Article/details/gt2snwqvsdd.html

Ruby: obj.instance_variables
来源：http://dali.daxiang520.top/Article/details/gt2bkvhtrfz.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajcdjugw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ozwziwdb.html

H. 异常与错误处理
来源：http://dali.ppjwa.cn/Article/details/gt2rfheuldl.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bodnqpes.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2oacurlys.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.guannengcc.top/Article/details/gt2loqcijis.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.yangfankeji.com/Article/details/gt2fmgcqoks.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.yuanzhike.top/Article/details/gt2wewbihip.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.zycfv.cn/Article/details/gt2wsljsgkm.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.xziqi.cn/Article/details/gt2detwyudr.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gt2kxuyydoz.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.cucudq.cn/Article/details/gt2oxodjpew.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xylfe.cn/Article/details/gt2pazcdphp.html

[H02] finally / ensure 收尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uwzmwvyl.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2pguuyebl.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ihwrageg.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gt2bqcehxwx.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.316326.xyz/Article/details/gt2fpubgtxh.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.0kj1m.cn/Article/details/gt2gafelmwt.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.guannengcc.top/Article/details/gt2ktmtsfzu.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.gotoacloud.top/Article/details/gt2izluedca.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.zdqjudy.top/Article/details/gt2cxoxojhr.html

[H03] 主动抛出异常
来源：http://dali.yonumen.top/Article/details/gt2qbqnuxre.html

Py:   raise ValueError("错误信息")
来源：http://dali.tianlin.xyz/Article/details/gt2iliwykbd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.wangshuangyany.cn/Article/details/gt2moxjdxqz.html

JS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2kbncosty.html

TS:   throw new Error("错误信息");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjkjqsay.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdwfxzft.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.guowangkeji.top/Article/details/gt2csnwwkdi.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.gzhubu.top/Article/details/gt2qwmhkbbf.html


<!-- 参考信息 -->