代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenlongwang.top/Article/details/gt2kffktgrt.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gt2nvahlbcg.html

Py:   s.splitlines()
来源：http://dali.jqgufenzy.top/Article/details/gt2lksfbexj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gt2xdvynhnj.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ekrfubch.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2cohvhbnx.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2ammjryly.html

Go:   strings.Split(s, "\n")
来源：http://dali.0kj1m.cn/Article/details/gt2tggxexpz.html

Ruby: s.lines
来源：http://dali.c1oappe.top/Article/details/gt2batomtjr.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfxepdyx.html

[E20] 判断字符串是否为空
来源：http://dali.dianchejie.cn/Article/details/gt2egnvweac.html

Py:   if not s:
来源：http://dali.cqqwz.cn/Article/details/gt2emlslygn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gt2dlwuralm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tian-w.cn/Article/details/gt2camhnjaj.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2envndqbh.html

Java: if (s.isEmpty()) {}
来源：http://dali.shzxlz.cn/Article/details/gt2nmuedugp.html

Go:   if s == "" {}
来源：http://dali.daria6918.cn/Article/details/gt2pfnrlhna.html

Ruby: if s.empty?
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hjwantkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2hnpjcvbf.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gt2gepqysgt.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gt2xmkysxgo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gt2rzcflfcf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2ckfhgjla.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2bagnmtnj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gt2mahfqhvk.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2jegnmdir.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2zluwlmge.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2tqdpdlyq.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2pnevxagr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2xnwhroqc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2fstmkkbf.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2updmrfwx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gogol.net.cn/Article/details/gt2rcwzttjo.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2rryitrpp.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aibaodan.cn/Article/details/gt2zdhldvvp.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2lytrkves.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ppjwa.cn/Article/details/gt2aaravtrn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2jqwifava.html

F. 文件与目录
来源：http://dali.c1oappe.top/Article/details/gt2mwziqgso.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gorrvsai.html

[F01] 读取整个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovlgszsc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gt2xqtjvzwh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2cgehpasr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jyoumei.cn/Article/details/gt2ghnafykk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2uzglwacl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gt2zvrbrqnr.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ydzc1.top/Article/details/gt2hpiyiott.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2nqinkxzr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2wzhftkmt.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gt2oodsstzd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2glhpekzm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikcishbk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gt2pmeqsscd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2gecruiss.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yvedp.cn/Article/details/gt2wiimnwtc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqhcebrj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gt2wjjiqdtf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yonumen.top/Article/details/gt2ogbilajl.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gt2uyxxkwjw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gt2zgxsocil.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ydzc1.top/Article/details/gt2rezjrmdq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gt2zwebaqyv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gt2utexnszg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ybcxt.top/Article/details/gt2sbsvunae.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.vqdsnc.cn/Article/details/gt2qlcgsykd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.smart0.xyz/Article/details/gt2abasetbc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.haohaochexian.top/Article/details/gt2ullyfywx.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gt2tgnzjuap.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yonumen.top/Article/details/gt2wdxdador.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gt2tfrdormw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2agzkfdpt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2mpfabwds.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnqzz.top/Article/details/gt2gixxcqbb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnjelcuy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gt2mpdxwvug.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2ptiqycib.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2aulzifgw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fengsongda.top/Article/details/gt2smfgjoeg.html

PHP:  file_exists("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2ygwmbrhq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2nfxzeztu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2vmzqabpo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2vcogvlyb.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2ogcytqcn.html

Ruby: File.exist?("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2vqcyqdfn.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2vifymlnn.html

[F06] 删除文件
来源：http://dali.yuanzhike.top/Article/details/gt2ukpilgis.html

Py:   os.remove("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2imjawign.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2gcfdsbhn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2cauznius.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfybsqti.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2szygzzad.html

Go:   os.Remove("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2ltmaufkk.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmaskxwn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2wbyukrxu.html

[F07] 创建目录（含多级）
来源：http://dali.haohaochexian.top/Article/details/gt2xfvvzwrk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dianchejie.cn/Article/details/gt2kizymfvw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gt2euvpxmju.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gt2hzspgrno.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gt2sdygbyfm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gt2jogvjiug.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ucqnozyd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.c1oappe.top/Article/details/gt2mkdslxvb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sysykeji.top/Article/details/gt2ngsrrdwl.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2xwowzelz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yonumen.top/Article/details/gt2vuifuojo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.havefunace.top/Article/details/gt2sifoycww.html

JS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pwgxfqak.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2cgdklbkh.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gt2hrybrthz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj202588.top/Article/details/gt2oiihlyym.html

Ruby: Dir.children("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrkfyqdp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fengsongda.top/Article/details/gt2ejdjrrsw.html

[F09] 获取文件大小
来源：http://dali.daxiang520.top/Article/details/gt2uivnirnu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2vwzsgljx.html

PHP:  filesize("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2eiygsswc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.meibo888.top/Article/details/gt2nkqbhtxb.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2vhabnfhe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2mlnlzgjc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gt2bzamsjwy.html

Ruby: File.size("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2okvfgqvr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gt2bacyxwcs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.redwolf501.top/Article/details/gt2vyjskybd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2nzuxcggp.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gt2ynebqook.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2acctojch.html

TS:   path.extname("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2zpuuejeq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2xnjnuelk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2cknszdpg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2qdohyecp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zdaapixi.html

[F11] 复制与移动文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ysibxfao.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2jptorrhr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2gcszxgan.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ihuywmkt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2utlnyduq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2zpettcan.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2thrpydty.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gt2woosircr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jqgufenzy.top/Article/details/gt2ltnswtxm.html

[F12] CSV 读写
来源：http://dali.bjfxy.top/Article/details/gt2swkqfkrq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cheryme.top/Article/details/gt2cfhrdegk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.haohaochexian.top/Article/details/gt2wkeshktq.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2qhsogmgf.html

TS:   // 同上
来源：http://dali.aibaodan.cn/Article/details/gt2cngqqbth.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.sxryk.cn/Article/details/gt2nroxfolf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nwbrower.top/Article/details/gt2idlztqnb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2kgpsqxlk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2rzafqzym.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2kyrcgrcy.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2zxllnfzd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2osrlmvod.html

[G01] 定义类
来源：http://dali.tian-w.cn/Article/details/gt2tdpvfhur.html

Py:   class User: pass
来源：http://dali.cucudq.cn/Article/details/gt2exuvzwjz.html

PHP:  class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wwldrwqy.html

JS:   class User {}
来源：http://dali.andypj.xyz/Article/details/gt2hqfldigo.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gt2bxyxjpyg.html

Java: class User {}
来源：http://dali.mhx1999.top/Article/details/gt2zvqknwqs.html

Go:   type User struct { Name string }
来源：http://dali.shuidangran.top/Article/details/gt2jmzvmqwz.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gt2grtxdpof.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gt2sqcjgrxy.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2zrguwdfy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenjidiqi.icu/Article/details/gt2hffttuem.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcenbxep.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2kktdohtv.html

TS:   constructor(public name: string) {}
来源：http://dali.xuanzx.com/Article/details/gt2vhzgjoua.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2oaxrckxh.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qptxhqhn.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tklwoxke.html

C#:   public User(string name) { Name = name; }
来源：http://dali.bjfxy.top/Article/details/gt2ccclwiny.html

[G03] 实例属性
来源：http://dali.fengsongda.top/Article/details/gt2fqizcejx.html

Py:   self.name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2koailozg.html

PHP:  public string $name = "x";
来源：http://dali.sysykeji.top/Article/details/gt2sukxjglt.html

JS:   this.name = "x";
来源：http://dali.hywenlv.cn/Article/details/gt2evfoguft.html

TS:   name: string = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2muxunqfb.html

Java: private String name;
来源：http://dali.c1oappe.top/Article/details/gt2qeudkcih.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ybcxt.top/Article/details/gt2wifxmjoi.html

Ruby: @name = "x"
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmaauolq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2hncsqxoc.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2yntoqnhs.html

Py:   def greet(self): return self.name
来源：http://dali.tianlin.xyz/Article/details/gt2lqaiqhuh.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2zxcrwppt.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2aebmxusj.html

TS:   greet(): string { return this.name; }
来源：http://dali.yuxming.cn/Article/details/gt2exhebcci.html

Java: String greet() { return name; }
来源：http://dali.gogol.net.cn/Article/details/gt2gtyiinxz.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ivvv.top/Article/details/gt2xkctoytm.html

Ruby: def greet; @name; end
来源：http://dali.yvedp.cn/Article/details/gt2sbvnliru.html

C#:   public string Greet() => Name;
来源：http://dali.meibo888.top/Article/details/gt2tbzremoz.html

[G05] 继承
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltnxqwgh.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2assnpecx.html

PHP:  class Admin extends User {}
来源：http://dali.aibaodan.cn/Article/details/gt2nxfpskjn.html

JS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2taofgvhr.html

TS:   class Admin extends User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2zdjmzxsi.html

Java: class Admin extends User {}
来源：http://dali.redwolf501.top/Article/details/gt2blgitdwu.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yuxming.cn/Article/details/gt2xyyepyel.html

Ruby: class Admin < User; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2ibverlaq.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2jlvtkyei.html

[G06] 重写方法
来源：http://dali.hnqzz.top/Article/details/gt2kibojgaz.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258.top/Article/details/gt2vhdeetul.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.daria6918.cn/Article/details/gt2okiaelww.html

JS:   greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2xojvrwyj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jinqigufen.top/Article/details/gt2wjcgwjtw.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2wqmghlyn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhongyouzk.top/Article/details/gt2zxzxohwd.html

Ruby: def greet; "admin"; end
来源：http://dali.guowangkeji.top/Article/details/gt2esnjmhjr.html

C#:   public override string Greet() => "admin";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dexjsjnw.html

[G07] 调用父类方法
来源：http://dali.chenzaomai.com/Article/details/gt2cinvujrg.html

Py:   super().greet()
来源：http://dali.bjfxy.top/Article/details/gt2erjsywic.html

PHP:  parent::greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuqziczg.html

JS:   super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rfsumgwr.html

TS:   super.greet();
来源：http://dali.daria6918.cn/Article/details/gt2hhwwyrud.html

Java: super.greet();
来源：http://dali.chenzaomai.com/Article/details/gt2pkaepeme.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.hnxiangtu.top/Article/details/gt2zhrsqrjr.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gt2uwdojxot.html

C#:   base.Greet();
来源：http://dali.yonumen.top/Article/details/gt2mdrnaupj.html

[G08] 静态方法与属性
来源：http://dali.zhongyouzk.top/Article/details/gt2zquyotmk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.nanxinkj.top/Article/details/gt2xadnrjqc.html

PHP:  public static function f() {}
来源：http://dali.shuidangran.top/Article/details/gt2avdoxrke.html

JS:   static f() {}
来源：http://dali.gzhubu.top/Article/details/gt2yzubaslw.html

TS:   static f(): void {}
来源：http://dali.haohaochexian.top/Article/details/gt2prwkkzit.html

Java: static void f() {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2pgyiebor.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.chenzaomai.com/Article/details/gt2metaiopr.html

Ruby: def self.f; end
来源：http://dali.guowangkeji.top/Article/details/gt2reaoegpf.html

C#:   public static void F() {}
来源：http://dali.smart0.xyz/Article/details/gt2wtoskzyr.html

[G09] 接口 / 抽象类
来源：http://dali.sxryk.cn/Article/details/gt2byewurpa.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shuidangran.top/Article/details/gt2bmvyhctv.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yj20258888.top/Article/details/gt2glmmlqxz.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2vmvoasdy.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gt2dpirwyna.html

Java: interface Shape { double area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2rvdnrdrz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.shzxlz.cn/Article/details/gt2iwmdbrop.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jiagoushi.top/Article/details/gt2hzxazmys.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gt2ebqaplkr.html

[G10] 访问控制
来源：http://dali.daria6918.cn/Article/details/gt2lzltwfih.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buardlve.html

PHP:  public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2hiomeyex.html

JS:   #private 字段；其余公开
来源：http://dali.316326.xyz/Article/details/gt2agydbrsi.html

TS:   public / protected / private
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtkpsvuz.html

Java: public / protected / private / 默认包级
来源：http://dali.yueranfly.top/Article/details/gt2wydmezyx.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ydzc1.top/Article/details/gt2slmeetgh.html

Ruby: public / protected / private
来源：http://dali.aizwys.cn/Article/details/gt2jzfwobgp.html

C#:   public / protected / private / internal
来源：http://dali.xuetiantiany.cn/Article/details/gt2bvdhsdup.html

[G11] getter / setter
来源：http://dali.aibaodan.cn/Article/details/gt2chxqadni.html

Py:   @property 与 @x.setter
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqahfrxm.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hfpthk.cn/Article/details/gt2vemdaeqn.html

JS:   get name() { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gt2xrirayoh.html

TS:   get name(): string { return this._name; }
来源：http://dali.jyoumei.cn/Article/details/gt2hrxssnvh.html

Java: public String getName() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2hsiljmfm.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.cqqwz.cn/Article/details/gt2etcqmqzn.html

Ruby: attr_accessor :name
来源：http://dali.zycfv.cn/Article/details/gt2zzidzwtz.html

C#:   public string Name { get; set; }
来源：http://dali.cucudq.cn/Article/details/gt2libzynre.html

[G12] 对象转字符串
来源：http://dali.daria6918.cn/Article/details/gt2mpsofuzx.html

Py:   def __str__(self): return self.name
来源：http://dali.shzxlz.cn/Article/details/gt2rrbcktmp.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yj202588.top/Article/details/gt2ixspvybj.html

JS:   toString() { return this.name; }
来源：http://dali.birdmap.top/Article/details/gt2sttinbqs.html

TS:   toString(): string { return this.name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tjaeehia.html

Java: @Override public String toString() { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2yqfesiid.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.aibaodan.cn/Article/details/gt2gtodguri.html

Ruby: def to_s; @name; end
来源：http://dali.zhoulong.xyz/Article/details/gt2ipynshpw.html

C#:   public override string ToString() => Name;
来源：http://dali.jyoumei.cn/Article/details/gt2tbrhhsgo.html

[G13] 判断对象类型
来源：http://dali.9152youxi.cn/Article/details/gt2fifuyfgg.html

Py:   isinstance(u, User)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wbfcralg.html

PHP:  $u instanceof User
来源：http://dali.c1oappe.top/Article/details/gt2ufgimapy.html

JS:   u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2osoubeso.html

TS:   u instanceof User
来源：http://dali.haohaochexian.top/Article/details/gt2ptcrfybm.html

Java: u instanceof User
来源：http://dali.wangdashe.top/Article/details/gt2pkmdtzrw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.jqgufenzy.top/Article/details/gt2knesgigz.html

Ruby: u.is_a?(User)
来源：http://dali.shuidangran.top/Article/details/gt2hrnbsnoc.html

C#:   u is User
来源：http://dali.snrcjt.cn/Article/details/gt2vuhmmkao.html

[G14] 数据类 / record
来源：http://dali.hnxiangtu.top/Article/details/gt2uiaobwzc.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigufen.top/Article/details/gt2rmacleon.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.havefunace.top/Article/details/gt2cuuxwhma.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.cashguo.top/Article/details/gt2rfirhmkj.html

TS:   type User = { name: string; age: number };
来源：http://dali.ivvv.top/Article/details/gt2feanilwq.html

Java: record User(String name, int age) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jdfzapzw.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joihahwj.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenzaomai.com/Article/details/gt2yegcftlt.html

C#:   record User(string Name, int Age);
来源：http://dali.smart0.xyz/Article/details/gt2guspzouz.html

[G15] 枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmekupb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2yetorabi.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ybcxt.top/Article/details/gt2jphnrdgf.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.kuanghao11.cn/Article/details/gt2bfvyvbxt.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.guannengcc.top/Article/details/gt2pprdivgf.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnckdaqg.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2kqnnddco.html

Ruby: Color = %i[red green].freeze
来源：http://dali.aizwys.cn/Article/details/gt2vtsfqlmo.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.ybcxt.top/Article/details/gt2ientjotr.html

[G16] 对象转数组 / 字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2zluhmsne.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pycfn.com/Article/details/gt2dicvlowu.html

PHP:  get_object_vars($obj);
来源：http://dali.snrcjt.cn/Article/details/gt2teypnjzq.html

JS:   Object.entries(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2dexqvunx.html

TS:   Object.entries(obj)
来源：http://dali.gaohongyu789.top/Article/details/gt2lsrvkyav.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.jiagoushi.top/Article/details/gt2epcjqipb.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.sysykeji.top/Article/details/gt2qcckioda.html

Ruby: obj.instance_variables
来源：http://dali.hongshengwenyu.top/Article/details/gt2cinubsyq.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2txnbqyjg.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2poyjfteh.html

H. 异常与错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2chxjvaay.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xzvkswlo.html

[H01] try / catch 基础
来源：http://dali.zhongyouzk.top/Article/details/gt2oksozmtj.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ycbfscze.html


<!-- 参考信息 -->