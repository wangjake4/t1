代发 wailian999

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.cheryme.top/Article/details/gt2envbltym.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hhdkwtad.html

TS:   if (s === "") {}
来源：http://dali.c1oappe.top/Article/details/gt2xhdnstpg.html

Java: if (s.isEmpty()) {}
来源：http://dali.cucudq.cn/Article/details/gt2woyudkfq.html

Go:   if s == "" {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eqpketpz.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gt2chjhhorf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigufen.top/Article/details/gt2vawwflol.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gt2vyprdrjf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2vwjqqvuv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.quarkkingdee.top/Article/details/gt2lmnxmchw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2vyucoray.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gt2koakiani.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2svrdtyxt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gt2xfgovbjj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2qxvwsirb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2ocnroybe.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gt2adhbftzo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gt2exkuznwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2yfutlghe.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ivvv.top/Article/details/gt2mlnqpzwz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhoulong.xyz/Article/details/gt2yvtrasql.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gt2idoagxmb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2tmenpsrd.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gt2xdotoqmx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqclshne.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2wwvbixak.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2jhpiagij.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2oanlfxgk.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gt2obgibblh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2amyobacn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2fjaanofy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gt2uiemkria.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2bzlsjajs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gt2uakpuxmi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gt2glcwbpro.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2misqzzhb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ygobfawg.html

[F02] 逐行读取文件
来源：http://dali.shuidangran.top/Article/details/gt2lzmzaavc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gt2qtlnnevp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mzepadeb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2lmgwqhvh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2kffkfkfo.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gt2faaezuwq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gt2xdewhjnx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tian-w.cn/Article/details/gt2ieurymdg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2ccjywhoc.html

[F03] 写入文件（覆盖）
来源：http://dali.ppjwa.cn/Article/details/gt2razndjso.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gt2dsvvtyjs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2okzyafwl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2injowbrz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2gcoazryp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hfpthk.cn/Article/details/gt2kiwzrcuu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2umjffhfc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2aaumamgx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cucudq.cn/Article/details/gt2lvshhrwe.html

[F04] 追加写入文件
来源：http://dali.jinqigufen.top/Article/details/gt2vwvrfxnz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2swsdltbn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yanxiufei.cn/Article/details/gt2swvvfjns.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjxifdez.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gt2vixzvxok.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gt2ntonxqnb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2sfczvcei.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gt2euokltfy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gt2ykntyacd.html

[F05] 判断文件或目录是否存在
来源：http://dali.yongpay.top/Article/details/gt2ugrgjtop.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xinyue.icu/Article/details/gt2vvbgilpz.html

PHP:  file_exists("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2rzkmydzb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2mjkkzubo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ttuenivq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2fvgvrfdt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenzaomai.com/Article/details/gt2kudhsfvx.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2wdufhhsu.html

C#:   File.Exists("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2sgmyyadd.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2poexqzxi.html

Py:   os.remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2nxmdupff.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2yjqwknrg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2riyuhjex.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2xgbteced.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2wumpbxko.html

Go:   os.Remove("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2kpcivoex.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2nrxjspye.html

C#:   File.Delete("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2zrhsekjb.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gt2cyxitwxg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aholgoic.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.snrcjt.cn/Article/details/gt2vrlsbyey.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2zarrwnfe.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gt2qeqpgoyg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinqigufen.top/Article/details/gt2psjkkqhw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gt2kcvadoiu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gt2gkyjbpou.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tanke756.top/Article/details/gt2frqyiral.html

[F08] 遍历目录
来源：http://dali.aizwys.cn/Article/details/gt2xwkxlzuy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mgmgvily.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yvedp.cn/Article/details/gt2ydswnbig.html

JS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gt2ydcanqwi.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2ijqesfpn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycwscnju.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2waycblew.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2sejjqgco.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yuxming.cn/Article/details/gt2fdotctoz.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2mwvromgl.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2qhkfpgka.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2ylnuqokv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gt2cdihiysk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2phnppcyl.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2icsslsnm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cashguo.top/Article/details/gt2irrmlbxd.html

Ruby: File.size("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2qgtwajyh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gt2wdsszamp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gt2trxsoydc.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ffdndowa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gt2cyueopdr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2bbyfffdy.html

TS:   path.extname("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2grsjyctl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gt2hajkospu.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2rbjvylgi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2kgocdwtk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2hcbwhrtf.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2vohhuofz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2vzqqnkin.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2xqxeondi.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2slzzsdxm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwmnwbup.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2snpmivan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gt2ynmswzjx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2qjzsuadi.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gaohongyu789.top/Article/details/gt2kzoajrmb.html

[F12] CSV 读写
来源：http://dali.vqdsnc.cn/Article/details/gt2xnaizcay.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhengqikj.top/Article/details/gt2xqsehuwq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.iojbl.cn/Article/details/gt2aihfrsfv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.daxiang520.top/Article/details/gt2swmhkzob.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gt2xgbhslus.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2jobjihpn.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.wangshuangyany.cn/Article/details/gt2dnarjshe.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2aqfxrdiv.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.9152youxi.cn/Article/details/gt2xxellqri.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2tbwuqknz.html

G. 面向对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sxfoncun.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2thpjawvd.html

[G01] 定义类
来源：http://dali.jqgfzy.top/Article/details/gt2xvbwxrio.html

Py:   class User: pass
来源：http://dali.dianchejie.cn/Article/details/gt2artukric.html

PHP:  class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2adicvosn.html

JS:   class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlwwzrbe.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2evkhardp.html

Java: class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2jtpwirka.html

Go:   type User struct { Name string }
来源：http://dali.jinqigfzy.top/Article/details/gt2mivxtbxt.html

Ruby: class User; end
来源：http://dali.jianghu66.top/Article/details/gt2tyoznrkz.html

C#:   class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2cjncaovf.html

[G02] 构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2fwxkavvs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2kszlccjw.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gtphosth.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2zsilxqxs.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbvjmwku.html

Java: User(String name) { this.name = name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nolsceqx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2kegnsciy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.dianchejie.cn/Article/details/gt2oalqlzqo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.fzhhl.top/Article/details/gt2pnvsekhj.html

[G03] 实例属性
来源：http://dali.gotoacloud.top/Article/details/gt2dlpmugcn.html

Py:   self.name = "x"
来源：http://dali.yongpay.top/Article/details/gt2aomswlfa.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gt2ewlhnqym.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gt2fvwsmjgj.html

TS:   name: string = "x";
来源：http://dali.ivvv.top/Article/details/gt2csqparht.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2lmftssut.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.cqqwz.cn/Article/details/gt2hfqovbeh.html

Ruby: @name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2vjgayclo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yonumen.top/Article/details/gt2gjdleyxb.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2jegnrcyw.html

Py:   def greet(self): return self.name
来源：http://dali.gaohongyu789.top/Article/details/gt2zijjwtgi.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shzxlz.cn/Article/details/gt2yofecial.html

JS:   greet() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2yvqkrweg.html

TS:   greet(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2hksmoprh.html

Java: String greet() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2fwtnuycj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2bhimcewv.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2shlocvsn.html

C#:   public string Greet() => Name;
来源：http://dali.yanxiufei.cn/Article/details/gt2hayuboqi.html

[G05] 继承
来源：http://dali.hywenlv.cn/Article/details/gt2thjibqwr.html

Py:   class Admin(User): pass
来源：http://dali.haohaochexian.top/Article/details/gt2pxfewlnb.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2tdyaggbz.html

JS:   class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gt2jagucqyo.html

TS:   class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2scpsihjc.html

Java: class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gt2xtdmaolk.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuanzhike.top/Article/details/gt2qlfjqcbk.html

Ruby: class Admin < User; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xanxgefr.html

C#:   class Admin : User {}
来源：http://dali.redwolf501.top/Article/details/gt2cgfizuca.html

[G06] 重写方法
来源：http://dali.jinqigufen.top/Article/details/gt2ueaykhyw.html

Py:   def greet(self): return "admin"
来源：http://dali.nanxuanxn.top/Article/details/gt2urfjhqup.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cashguo.top/Article/details/gt2acwfzqjj.html

JS:   greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2lbbwdvcl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2xajldukp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2tswbwkak.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.smart0.xyz/Article/details/gt2svsvpnrb.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2ngkeeykw.html

C#:   public override string Greet() => "admin";
来源：http://dali.hongshengwenyu.top/Article/details/gt2wepgxfam.html

[G07] 调用父类方法
来源：http://dali.nanxinkj.top/Article/details/gt2kzhjftgq.html

Py:   super().greet()
来源：http://dali.ivvv.top/Article/details/gt2sqrziyfo.html

PHP:  parent::greet();
来源：http://dali.cucudq.cn/Article/details/gt2wayxqdge.html

JS:   super.greet();
来源：http://dali.snrcjt.cn/Article/details/gt2jgrlcoam.html

TS:   super.greet();
来源：http://dali.jqgfzy.top/Article/details/gt2lwiqazyd.html

Java: super.greet();
来源：http://dali.yvedp.cn/Article/details/gt2awtbuxmx.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.tianlin.xyz/Article/details/gt2bjiohsih.html

Ruby: super
来源：http://dali.zycfv.cn/Article/details/gt2icwpvhrc.html

C#:   base.Greet();
来源：http://dali.snrcjt.cn/Article/details/gt2rmpxxkur.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gt2tcsjghlo.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xylfe.cn/Article/details/gt2yiwzmhdf.html

PHP:  public static function f() {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyyvlgde.html

JS:   static f() {}
来源：http://dali.nwbrower.top/Article/details/gt2lqanpwjl.html

TS:   static f(): void {}
来源：http://dali.guowangkeji.top/Article/details/gt2opivpdft.html

Java: static void f() {}
来源：http://dali.redwolf501.top/Article/details/gt2ggdygdlw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.ehwqpu.com/Article/details/gt2aioldoco.html

Ruby: def self.f; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2alvnbcib.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2yunmrccv.html

[G09] 接口 / 抽象类
来源：http://dali.iojbl.cn/Article/details/gt2mdwtsgqq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2dwcrnkmp.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hnqzz.top/Article/details/gt2cgcxdahb.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2xqyoffxj.html

TS:   interface Shape { area(): number; }
来源：http://dali.meibo888.top/Article/details/gt2iykajtsv.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2yyafcznt.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.guowangkeji.top/Article/details/gt2ccrpwebe.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.andypj.xyz/Article/details/gt2rkziqaah.html

C#:   interface IShape { double Area(); }
来源：http://dali.aibaodan.cn/Article/details/gt2ivcpmbfn.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lttzeetf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.pycfn.com/Article/details/gt2hrstszhe.html

PHP:  public / protected / private
来源：http://dali.hnqzz.top/Article/details/gt2xturczjp.html

JS:   #private 字段；其余公开
来源：http://dali.svipenyu.cn/Article/details/gt2alradbae.html

TS:   public / protected / private
来源：http://dali.smart0.xyz/Article/details/gt2zzoxkhiy.html

Java: public / protected / private / 默认包级
来源：http://dali.hammf.cn/Article/details/gt2kysrvrfv.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.jiagoushi.top/Article/details/gt2xyjfgqyd.html

Ruby: public / protected / private
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eqdsnhdl.html

C#:   public / protected / private / internal
来源：http://dali.gogol.net.cn/Article/details/gt2pjwtatxn.html

[G11] getter / setter
来源：http://dali.xylfe.cn/Article/details/gt2qvddyzna.html

Py:   @property 与 @x.setter
来源：http://dali.jianghu66.top/Article/details/gt2pqtbzotv.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2wkelgfbe.html

JS:   get name() { return this._name; }
来源：http://dali.shuidangran.top/Article/details/gt2lpaybwap.html

TS:   get name(): string { return this._name; }
来源：http://dali.sxryk.cn/Article/details/gt2xahdcmux.html

Java: public String getName() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2jbomtzhd.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinqigfzy.top/Article/details/gt2afaattik.html

Ruby: attr_accessor :name
来源：http://dali.chenlongwang.top/Article/details/gt2wfgxqzwc.html

C#:   public string Name { get; set; }
来源：http://dali.hysaishi.cn/Article/details/gt2ljwmqfui.html

[G12] 对象转字符串
来源：http://dali.gotoacloud.top/Article/details/gt2bmrxeuek.html

Py:   def __str__(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gt2dypnwruh.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.tian-w.cn/Article/details/gt2diiiblti.html

JS:   toString() { return this.name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2exxiggof.html

TS:   toString(): string { return this.name; }
来源：http://dali.fzhhl.top/Article/details/gt2lbnyrxif.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2ajanufph.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2yasshoyk.html

Ruby: def to_s; @name; end
来源：http://dali.nanxinkj.top/Article/details/gt2soslaqsj.html

C#:   public override string ToString() => Name;
来源：http://dali.wangdashe.top/Article/details/gt2zselkncb.html

[G13] 判断对象类型
来源：http://dali.shuidangran.top/Article/details/gt2rhnzcntd.html

Py:   isinstance(u, User)
来源：http://dali.sufxvd.cn/Article/details/gt2tuhypnmo.html

PHP:  $u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2aipnatje.html

JS:   u instanceof User
来源：http://dali.hfpthk.cn/Article/details/gt2fhjihgth.html

TS:   u instanceof User
来源：http://dali.chenzaomai.com/Article/details/gt2ajjbkddw.html

Java: u instanceof User
来源：http://dali.wangshuangyany.cn/Article/details/gt2amncirjc.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jinqigufen.top/Article/details/gt2ssbklhhh.html

Ruby: u.is_a?(User)
来源：http://dali.zycfv.cn/Article/details/gt2wpvcbxdp.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqiyzpvw.html

[G14] 数据类 / record
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtvzemuu.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvgndhrq.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.gotoacloud.top/Article/details/gt2sclezxzf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.hongshengwenyu.top/Article/details/gt2kunojxsv.html

TS:   type User = { name: string; age: number };
来源：http://dali.cheryme.top/Article/details/gt2vddyitmr.html

Java: record User(String name, int age) {}
来源：http://dali.c1oappe.top/Article/details/gt2ermnqnfm.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hysaishi.cn/Article/details/gt2ibxwmkwn.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.jiagoushi.top/Article/details/gt2yccwedxp.html

C#:   record User(string Name, int Age);
来源：http://dali.yj20258.top/Article/details/gt2aartjaib.html

[G15] 枚举
来源：http://dali.fzhhl.top/Article/details/gt2dmspzwyj.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.tianlin.xyz/Article/details/gt2hledqeim.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sxryk.cn/Article/details/gt2kkibisps.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.yueranfly.top/Article/details/gt2smsyzcbd.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2fkjwbpwz.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2sivaqjlm.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcaqwjww.html

Ruby: Color = %i[red green].freeze
来源：http://dali.quarkkingdee.top/Article/details/gt2aulxbadj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbrhifgd.html

[G16] 对象转数组 / 字典
来源：http://dali.tian-w.cn/Article/details/gt2lsqjpmki.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.snrcjt.cn/Article/details/gt2daiakgqr.html

PHP:  get_object_vars($obj);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bcgxytuq.html

JS:   Object.entries(obj)
来源：http://dali.fengsongda.top/Article/details/gt2fhswensc.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2cwebylas.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xuanzx.com/Article/details/gt2nuukuzpb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.yanxiufei.cn/Article/details/gt2kkbrjjte.html

Ruby: obj.instance_variables
来源：http://dali.sysykeji.top/Article/details/gt2kgaupqpo.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.pycfn.com/Article/details/gt2fbrbqvjy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2xrrlcibp.html

H. 异常与错误处理
来源：http://dali.zhoulong.xyz/Article/details/gt2lxjqynch.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2khbhidtj.html

[H01] try / catch 基础
来源：http://dali.sweek.top/Article/details/gt2ynpybpqy.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nhoxsmbs.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.cucudq.cn/Article/details/gt2cykcjcce.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.mhx1999.top/Article/details/gt2zkkikvve.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gt2lnwsorzk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.dianchejie.cn/Article/details/gt2blskbehi.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.pycfn.com/Article/details/gt2owemytsv.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.hywenlv.cn/Article/details/gt2girpobxo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ivvv.top/Article/details/gt2mbmsbufd.html

[H02] finally / ensure 收尾
来源：http://dali.ivvv.top/Article/details/gt2gxfwoxja.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.hnqzz.top/Article/details/gt2fzgktxgj.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.dianchejie.cn/Article/details/gt2pacamucw.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.sysykeji.top/Article/details/gt2gnavbxjm.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dqdcbcty.html


<!-- 参考信息 -->