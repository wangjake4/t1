代发 wailian999

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2wgrypseu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gaohongyu789.top/Article/details/gt2fxiyjrgp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2kyfykmgs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2iqlmgiyz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.andypj.xyz/Article/details/gt2dqndndyq.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2niwwaegt.html

Py:   s.splitlines()
来源：http://dali.nwbrower.top/Article/details/gt2cmifbrvk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gt2pxgkxbtg.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gt2qrkizqhj.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2skdaowmr.html

Java: s.lines().toList()
来源：http://dali.yonumen.top/Article/details/gt2xuzkkpex.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2fcirmnnp.html

Ruby: s.lines
来源：http://dali.nanxinkj.top/Article/details/gt2moxdrhgw.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gt2pxnpnrjd.html

[E20] 判断字符串是否为空
来源：http://dali.hnxiangtu.top/Article/details/gt2doasfltw.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2wxmitkpn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2vvomelld.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.guowangkeji.top/Article/details/gt2yyikgejm.html

TS:   if (s === "") {}
来源：http://dali.redwolf501.top/Article/details/gt2vpcwpczh.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gt2zushfqax.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2puryphxd.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gt2impzajjr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gt2xmuhxhiw.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2nukykrck.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cqqwz.cn/Article/details/gt2hypdmdbf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2vbvsabxi.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2vihugjco.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2yeljkhll.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2gfcruzbt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.316326.xyz/Article/details/gt2evhuvufg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2kgopqsbi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2hajjrcoo.html

[E22] 字节长度与字符长度
来源：http://dali.hnxiangtu.top/Article/details/gt2nrbonuri.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gt2xozphhnu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gt2jfttghvj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gt2mtqjtlvc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gt2fkvueluv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ybcxt.top/Article/details/gt2cvjrpkue.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2qeqlgbgx.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2ryifznyn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.316326.xyz/Article/details/gt2uvjsdovi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2mfbrhshg.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gt2wcgwsala.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2kwidcvbt.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2qiopjplr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sxryk.cn/Article/details/gt2tnkrwmwn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2nxjrxpaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.316326.xyz/Article/details/gt2mmwgvazi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpcpnyds.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gt2pzbasvad.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2awoxcqmq.html

Ruby: File.read("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2iubyyspy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2dfhvqczb.html

[F02] 逐行读取文件
来源：http://dali.jinqigufen.top/Article/details/gt2izmmtols.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gt2zzunxgrg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gt2oqihfmjl.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mvophaqk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2eopeqznj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gogol.net.cn/Article/details/gt2usxwnzzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jlsjyb.cn/Article/details/gt2sfsojbku.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gt2barhnhih.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhijiandao.cn/Article/details/gt2srqujtsg.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gt2tqsbwqvf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yangfankeji.com/Article/details/gt2ejusgiso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2wcgsoplh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gt2rsrgmyvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.smart0.xyz/Article/details/gt2gqovdlgo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xziqi.cn/Article/details/gt2ripwmrjx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gt2gzxbdyyc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gt2niiukjhx.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gt2oolylkag.html

[F04] 追加写入文件
来源：http://dali.yuxming.cn/Article/details/gt2ftquuarf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2qwmuerjw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gt2sbanvguf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258888.top/Article/details/gt2uxrxuaqe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knjfjsuj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gt2vxxvqyqj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qpwrtkla.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gt2pkvqkdnm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yangfankeji.com/Article/details/gt2qfrkvsms.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xvgddpfa.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gt2ywwzjadw.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2ynlvstrr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2gaabrzav.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2otlguaqm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gt2brqgvkwr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2yxbjkgzu.html

Ruby: File.exist?("a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2wrgxctum.html

C#:   File.Exists("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2zemfmotv.html

[F06] 删除文件
来源：http://dali.316326.xyz/Article/details/gt2afwtdpyh.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2fuxtfayw.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2zcyywyho.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2skqwcras.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2cdxhowqs.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2nizeelsz.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ydpoofyk.html

Ruby: File.delete("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2magjmfkq.html

C#:   File.Delete("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gt2wromlsma.html

[F07] 创建目录（含多级）
来源：http://dali.zhixingplan.top/Article/details/gt2tpwsxfan.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2bmqskisw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nmnhleba.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2jxaidmcs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2nfwtywox.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.svipenyu.cn/Article/details/gt2fzzvtisw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhijiandao.cn/Article/details/gt2uadyyjra.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gt2suvpukok.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gt2wigptlak.html

[F08] 遍历目录
来源：http://dali.svipenyu.cn/Article/details/gt2xvggkvyi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shzxlz.cn/Article/details/gt2yxlbvnuu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iucldjfn.html

JS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gt2tnaqmplw.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2vzwcvoez.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.tian-w.cn/Article/details/gt2ktjkkxjt.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2zrzlyxpy.html

Ruby: Dir.children("dir")
来源：http://dali.quarkkingdee.top/Article/details/gt2cekwhxgp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gt2sageqexb.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gt2iiurtsgn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2ktibzuvy.html

PHP:  filesize("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2nnknswfg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2oyipyxkh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2woswjrnr.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2uxjejizr.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gt2oiqrgxfz.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2zqhqozqy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.vqdsnc.cn/Article/details/gt2vxelpgbi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yueranfly.top/Article/details/gt2uxlvrzjp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2cdgllgwc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2argrambn.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2gnzzgkkg.html

TS:   path.extname("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2rgghcbqp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangshuangyany.cn/Article/details/gt2uczsxtlz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2krsdolej.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2oxgxdnra.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2sjpguklj.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gt2hgurpbul.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpvxbirg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ikrodzyd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2jwdyaijt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ijfwwjhb.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jqgfzy.top/Article/details/gt2xucdnygv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cdnleiting.top/Article/details/gt2wuxpjdoj.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2utycftqz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.haohaochexian.top/Article/details/gt2diwzraoa.html

[F12] CSV 读写
来源：http://dali.mhx1999.top/Article/details/gt2grqykboo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gjmocihq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.gogol.net.cn/Article/details/gt2bgiqyhcv.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.meibo888.top/Article/details/gt2dictzhhe.html

TS:   // 同上
来源：http://dali.yuanzhike.top/Article/details/gt2fgnqlqah.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sweek.top/Article/details/gt2axtncxri.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gt2hqzwpgak.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.xuanzx.com/Article/details/gt2fyuozpff.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.aibaodan.cn/Article/details/gt2yyjldmqc.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vlgcctce.html

G. 面向对象
来源：http://dali.zhixingplan.top/Article/details/gt2fcfjiptz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2wwruoktb.html

[G01] 定义类
来源：http://dali.guowangkeji.top/Article/details/gt2uvfngvop.html

Py:   class User: pass
来源：http://dali.hnqzz.top/Article/details/gt2wduhndih.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gt2ndaeooeu.html

JS:   class User {}
来源：http://dali.tianlin.xyz/Article/details/gt2puyfchld.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2vipbmwdk.html

Java: class User {}
来源：http://dali.smart0.xyz/Article/details/gt2yluykrro.html

Go:   type User struct { Name string }
来源：http://dali.redwolf501.top/Article/details/gt2kllxtkiz.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2uzgncxns.html

C#:   class User {}
来源：http://dali.mhx1999.top/Article/details/gt2lhripybv.html

[G02] 构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lkyreocv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2hmkbqkyg.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2xadiuvfw.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jianghu66.top/Article/details/gt2jrznrjcx.html

TS:   constructor(public name: string) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2zrniuwwr.html

Java: User(String name) { this.name = name; }
来源：http://dali.havefunace.top/Article/details/gt2dytmrimx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xylfe.cn/Article/details/gt2crkfdbmo.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2stvhvapg.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daria6918.cn/Article/details/gt2wzjwheql.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2osfrpbpn.html

Py:   self.name = "x"
来源：http://dali.gogol.net.cn/Article/details/gt2apufized.html

PHP:  public string $name = "x";
来源：http://dali.yuanzhike.top/Article/details/gt2eopjfdlt.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gt2ugapyhct.html

TS:   name: string = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gt2ektcwwke.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eatztxpa.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jyoumei.cn/Article/details/gt2ykcgdlst.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2nfydxrka.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2uepowtwo.html

[G04] 定义方法
来源：http://dali.hywenlv.cn/Article/details/gt2zhbwshlj.html

Py:   def greet(self): return self.name
来源：http://dali.zhijiandao.cn/Article/details/gt2zsffrkku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.meibo888.top/Article/details/gt2kloklibl.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2ogbajdsc.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2tmybbtma.html

Java: String greet() { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ellbbhgr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hywenlv.cn/Article/details/gt2fckrvxoj.html

Ruby: def greet; @name; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgwoqhy.html

C#:   public string Greet() => Name;
来源：http://dali.hnxiangtu.top/Article/details/gt2msacjukp.html

[G05] 继承
来源：http://dali.jqgufenzy.top/Article/details/gt2twugogzh.html

Py:   class Admin(User): pass
来源：http://dali.zhengqikj.top/Article/details/gt2llqfnvuz.html

PHP:  class Admin extends User {}
来源：http://dali.jinqigufen.top/Article/details/gt2qzlogvzq.html

JS:   class Admin extends User {}
来源：http://dali.ydzc1.top/Article/details/gt2sgvqujiv.html

TS:   class Admin extends User {}
来源：http://dali.yuanzhike.top/Article/details/gt2dhxnguyf.html

Java: class Admin extends User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2qdrulwjg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jgfugtuq.html

Ruby: class Admin < User; end
来源：http://dali.pycfn.com/Article/details/gt2nqnisuqy.html

C#:   class Admin : User {}
来源：http://dali.dianchejie.cn/Article/details/gt2murugyws.html

[G06] 重写方法
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbqqkvb.html

Py:   def greet(self): return "admin"
来源：http://dali.chenlongwang.top/Article/details/gt2ustvmjgr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gt2pbajkbaj.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gt2rntlzako.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2apszgpsa.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2kpphjjcj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.andypj.xyz/Article/details/gt2nzohyshb.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2jmxxsnew.html

C#:   public override string Greet() => "admin";
来源：http://dali.ydzc1.top/Article/details/gt2kvvxujfx.html

[G07] 调用父类方法
来源：http://dali.shuidangran.top/Article/details/gt2nbawvjrc.html

Py:   super().greet()
来源：http://dali.cdnleiting.top/Article/details/gt2dshivpxr.html

PHP:  parent::greet();
来源：http://dali.gzhubu.top/Article/details/gt2nlenvzvy.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2otwcefbu.html

TS:   super.greet();
来源：http://dali.zhijiandao.cn/Article/details/gt2powdvgxw.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2kjkgdspj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.gaohongyu789.top/Article/details/gt2dtbzainv.html

Ruby: super
来源：http://dali.yueranfly.top/Article/details/gt2lzvgovtv.html

C#:   base.Greet();
来源：http://dali.jinqigufen.top/Article/details/gt2rrqyaiwk.html

[G08] 静态方法与属性
来源：http://dali.tianlin.xyz/Article/details/gt2bvmifbea.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2chgfhbdo.html

PHP:  public static function f() {}
来源：http://dali.pycfn.com/Article/details/gt2kkwazpzl.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2qonixlsa.html

TS:   static f(): void {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wvlaibwb.html

Java: static void f() {}
来源：http://dali.xinyue.icu/Article/details/gt2swpgdpui.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2xeaafvop.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2ohaqkkzi.html

C#:   public static void F() {}
来源：http://dali.tanke756.top/Article/details/gt2rrkoqdua.html

[G09] 接口 / 抽象类
来源：http://dali.wangdashe.top/Article/details/gt2ztfbchpo.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.xinyue.icu/Article/details/gt2ewnpynee.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.chenlongwang.top/Article/details/gt2sdyssucs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.sweek.top/Article/details/gt2ahswfppw.html

TS:   interface Shape { area(): number; }
来源：http://dali.daria6918.cn/Article/details/gt2aymevjei.html

Java: interface Shape { double area(); }
来源：http://dali.hysaishi.cn/Article/details/gt2rpzkfkyr.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.aizwys.cn/Article/details/gt2ripvcnew.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jqgufenzy.top/Article/details/gt2dwrbempa.html

C#:   interface IShape { double Area(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2aiyjpwvf.html

[G10] 访问控制
来源：http://dali.yj202588.top/Article/details/gt2iadlasli.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sxjjfkof.html

PHP:  public / protected / private
来源：http://dali.daxiang520.top/Article/details/gt2dmstzsvf.html

JS:   #private 字段；其余公开
来源：http://dali.yuanzhike.top/Article/details/gt2oknfnynv.html

TS:   public / protected / private
来源：http://dali.fengsongda.top/Article/details/gt2tdkmhzhr.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2nxqmpknt.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxkcqyaj.html

Ruby: public / protected / private
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skdvcjkm.html

C#:   public / protected / private / internal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wmreekgo.html

[G11] getter / setter
来源：http://dali.tianlin.xyz/Article/details/gt2mxqkwmmk.html

Py:   @property 与 @x.setter
来源：http://dali.nanxinkj.top/Article/details/gt2mujalwfb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gt2ufkwngix.html

JS:   get name() { return this._name; }
来源：http://dali.zycfv.cn/Article/details/gt2wgyfcgfd.html

TS:   get name(): string { return this._name; }
来源：http://dali.shzxlz.cn/Article/details/gt2otvbwqod.html

Java: public String getName() { return name; }
来源：http://dali.zycfv.cn/Article/details/gt2fyndjitr.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yuanzhike.top/Article/details/gt2fhwszlir.html

Ruby: attr_accessor :name
来源：http://dali.fengsongda.top/Article/details/gt2uortoctk.html

C#:   public string Name { get; set; }
来源：http://dali.chenzaomai.com/Article/details/gt2wxfwukzy.html

[G12] 对象转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwolugsq.html

Py:   def __str__(self): return self.name
来源：http://dali.andypj.xyz/Article/details/gt2yfuvwzrd.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uyfgptck.html

JS:   toString() { return this.name; }
来源：http://dali.tanke756.top/Article/details/gt2rmgyvwcv.html

TS:   toString(): string { return this.name; }
来源：http://dali.gogol.net.cn/Article/details/gt2tjrtlysv.html

Java: @Override public String toString() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2auiyhjul.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.gogol.net.cn/Article/details/gt2ztptzdqp.html

Ruby: def to_s; @name; end
来源：http://dali.hfpthk.cn/Article/details/gt2mnkfngow.html

C#:   public override string ToString() => Name;
来源：http://dali.ybcxt.top/Article/details/gt2brskjrnv.html

[G13] 判断对象类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imnovpme.html

Py:   isinstance(u, User)
来源：http://dali.xuanzx.com/Article/details/gt2pgtrjtve.html

PHP:  $u instanceof User
来源：http://dali.xuanzx.com/Article/details/gt2doipphms.html

JS:   u instanceof User
来源：http://dali.tian-w.cn/Article/details/gt2bqwqoask.html

TS:   u instanceof User
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hykwltlc.html

Java: u instanceof User
来源：http://dali.pengpengdd.cyou/Article/details/gt2enzvbouz.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.316326.xyz/Article/details/gt2mfztpcun.html

Ruby: u.is_a?(User)
来源：http://dali.sweek.top/Article/details/gt2dtdklmsz.html

C#:   u is User
来源：http://dali.yuxming.cn/Article/details/gt2wpjhtvfi.html

[G14] 数据类 / record
来源：http://dali.feifeiyinyue.top/Article/details/gt2jticgmzv.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.ppjwa.cn/Article/details/gt2dytnqmof.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jqgfzy.top/Article/details/gt2xiycjkky.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgmkxdny.html

TS:   type User = { name: string; age: number };
来源：http://dali.jianghu66.top/Article/details/gt2wozqgeib.html

Java: record User(String name, int age) {}
来源：http://dali.wangdashe.top/Article/details/gt2jxrwoxrq.html

Go:   type User struct { Name string; Age int }
来源：http://dali.hnqzz.top/Article/details/gt2sypmpgbz.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.haohaochexian.top/Article/details/gt2qjlwxaqv.html

C#:   record User(string Name, int Age);
来源：http://dali.tian-w.cn/Article/details/gt2bjawgpsv.html

[G15] 枚举
来源：http://dali.cashguo.top/Article/details/gt2fmpxmbbq.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gt2wojbplkm.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.xuanzx.com/Article/details/gt2dsjbpxpm.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.redwolf501.top/Article/details/gt2rfahfznf.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.cashguo.top/Article/details/gt2umhgihib.html

Java: enum Color { RED, GREEN }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ojypfkli.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yj20258888.top/Article/details/gt2qjkjgzax.html

Ruby: Color = %i[red green].freeze
来源：http://dali.fzhhl.top/Article/details/gt2kauzaleu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yueranfly.top/Article/details/gt2vmmcfcjz.html

[G16] 对象转数组 / 字典
来源：http://dali.chenlongwang.top/Article/details/gt2htkyejjs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.yj20258.top/Article/details/gt2pdpjfgkc.html

PHP:  get_object_vars($obj);
来源：http://dali.redwolf501.top/Article/details/gt2ybgjglhz.html

JS:   Object.entries(obj)
来源：http://dali.tanke756.top/Article/details/gt2pmydkisg.html

TS:   Object.entries(obj)
来源：http://dali.haohaochexian.top/Article/details/gt2alasrght.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yonumen.top/Article/details/gt2jkplxuls.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.jqgfzy.top/Article/details/gt2nqouuxlx.html

Ruby: obj.instance_variables
来源：http://dali.bjfxy.top/Article/details/gt2edpscqcb.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258.top/Article/details/gt2ysykqren.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2mjbkevpv.html


<!-- 参考信息 -->