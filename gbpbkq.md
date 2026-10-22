代发 wailian999

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2xscwtaxp.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gt2yhizeyao.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2iqoxznpj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.cheryme.top/Article/details/gt2fsgsyxhr.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gt2fwwvbvvm.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gt2obwedbvw.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fohgzqhp.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gt2clwdjpvt.html

Ruby: s.lines
来源：http://dali.yuanzhike.top/Article/details/gt2fmeckdya.html

C#:   s.Split('\n')
来源：http://dali.chenlongwang.top/Article/details/gt2iszbpqkx.html

[E20] 判断字符串是否为空
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbcfjvif.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2wikvnqvi.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gaohongyu789.top/Article/details/gt2ertzqccf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2hgxbqkbi.html

TS:   if (s === "") {}
来源：http://dali.chenzaomai.com/Article/details/gt2txdekwjm.html

Java: if (s.isEmpty()) {}
来源：http://dali.guowangkeji.top/Article/details/gt2kscqqdpn.html

Go:   if s == "" {}
来源：http://dali.yj20258888.top/Article/details/gt2vkjzxqxv.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gt2jgmcoklh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gt2dfxbwglh.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gt2abutvlzy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hammf.cn/Article/details/gt2mvgcufus.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2vuyxxztn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2ddyokmdw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nznsckae.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2tkkqeugn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gt2xlmhmvkk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2tywfgybb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2mhhzrooc.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gt2dvxhuiag.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2tufrodoe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gt2eqxwsaqs.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2kvzgewor.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gt2mcvqxxao.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2iedybdzy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.0kj1m.cn/Article/details/gt2aqjihvpe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tfvlmofv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gt2skgmgclg.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2wzschidx.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gt2vvgwuqlb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2avzafgje.html

[F01] 读取整个文件
来源：http://dali.wangdashe.top/Article/details/gt2wznpqndw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.wangshuangyany.cn/Article/details/gt2bomqygrn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2fxhpvhzm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jmeovjjc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gt2xmjulzya.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2trspliwb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.316326.xyz/Article/details/gt2gbgdekmn.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2biwfxbjm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2acwmivtq.html

[F02] 逐行读取文件
来源：http://dali.pycfn.com/Article/details/gt2hmxhxpsb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gt2aigemszo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rzjsewxv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gt2epgmzxbl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2iremzfst.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2vowzhrph.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yj20258.top/Article/details/gt2gijypalz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gt2apdqpxrl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ehwqpu.com/Article/details/gt2hjqfvcrj.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gt2oautybie.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuxming.cn/Article/details/gt2dliprxnh.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gt2ykbajdnc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2catkckew.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenzaomai.com/Article/details/gt2ihaoposo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2hecorkpg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.wangshuangyany.cn/Article/details/gt2axqbtttf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gt2srgdbzsy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2odtenuga.html

[F04] 追加写入文件
来源：http://dali.andypj.xyz/Article/details/gt2kmsqjtjb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cucudq.cn/Article/details/gt2nydnepmx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpglyojj.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gt2ilcmrquy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2rykayozk.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2sumgtlgh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gt2atxntapf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gt2oedaobqs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jianghu66.top/Article/details/gt2kljezquk.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2hfvdxbye.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gt2pfjxyilj.html

PHP:  file_exists("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ghvpalvc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egroeenp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2xcsokeva.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2lzczdjdv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2pmozokuu.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2stuncomu.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2tqmnzdvd.html

[F06] 删除文件
来源：http://dali.haohaochexian.top/Article/details/gt2lofxzzgm.html

Py:   os.remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2koticeqj.html

PHP:  unlink("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odjyjfwu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2fxkujjou.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2eenuuucq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2djjtjlrz.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2wczfuicc.html

Ruby: File.delete("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tbryyhws.html

C#:   File.Delete("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2vrxvkiem.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gt2sachpktp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2vldzynun.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gt2wnrpeivc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2zkcmidrf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gotoacloud.top/Article/details/gt2onjhuczx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhongyouzk.top/Article/details/gt2yschwias.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gt2pxrbaomv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2idlqcxkw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cucudq.cn/Article/details/gt2nfyxjevf.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2cfiyyhnq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gotoacloud.top/Article/details/gt2mbowpcjo.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gt2jqkgjkul.html

JS:   fs.readdirSync("dir")
来源：http://dali.shuidangran.top/Article/details/gt2rrwinreo.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2hozchycv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gt2bmfcfkpi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yongpay.top/Article/details/gt2xomxbgmw.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gt2bdibetfm.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xowkyyzj.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyjhckpe.html

Py:   os.path.getsize("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2muhzltxb.html

PHP:  filesize("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2ewrvjpqh.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daxiang520.top/Article/details/gt2tcugqwxz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2mrxwmqrp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hywenlv.cn/Article/details/gt2drxgmpai.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sweek.top/Article/details/gt2dgeqpqro.html

Ruby: File.size("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2sirhjxen.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.sxryk.cn/Article/details/gt2qpeaetcv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gt2paexfqse.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2dcauvyia.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gt2szmwmqqy.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2jqczmlcr.html

TS:   path.extname("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2mwefmseq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gt2hcopzfsd.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2loscjzby.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2mzzjbwsc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2lfrlyrpc.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2ntbwhqyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2rfcfkgxb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2hkypwwfd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2ltpaxgpp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2nojrtjxi.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gzhubu.top/Article/details/gt2qgrspbss.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2jqfzsixi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2vwxhvdkq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2hhgbbrwz.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gt2hnpbdbdt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icgfgtnn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2xuxlmdys.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yuxming.cn/Article/details/gt2tphhgmjx.html

TS:   // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2xiksrorn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.dianchejie.cn/Article/details/gt2cjaiwscv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pprzerjn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dianchejie.cn/Article/details/gt2zkjteizr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sweek.top/Article/details/gt2vqmjrybm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2avfptqum.html

G. 面向对象
来源：http://dali.fengsongda.top/Article/details/gt2gyiidmtr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ffhekakp.html

[G01] 定义类
来源：http://dali.daxiang520.top/Article/details/gt2farrpgtm.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcevxcch.html

PHP:  class User {}
来源：http://dali.xinyue.icu/Article/details/gt2mnbpxleh.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2lpxkcygp.html

TS:   class User { name: string = ""; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgueort.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjfkedce.html

Go:   type User struct { Name string }
来源：http://dali.meibo888.top/Article/details/gt2xkmbgiwb.html

Ruby: class User; end
来源：http://dali.mhx1999.top/Article/details/gt2ebkpycht.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gt2glgauxmn.html

[G02] 构造函数
来源：http://dali.hfpthk.cn/Article/details/gt2ffigfych.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2sbahhuok.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2fpiqjcas.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gt2yxpbqvkz.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2qwsibapa.html

Java: User(String name) { this.name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2ptccpppp.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jyoumei.cn/Article/details/gt2qfdishok.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktxdmbfc.html

C#:   public User(string name) { Name = name; }
来源：http://dali.nanxinkj.top/Article/details/gt2qtyndobv.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2nndnavak.html

Py:   self.name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2nndnbtmd.html

PHP:  public string $name = "x";
来源：http://dali.daria6918.cn/Article/details/gt2tcqbknmk.html

JS:   this.name = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2qpjkqdny.html

TS:   name: string = "x";
来源：http://dali.aizwys.cn/Article/details/gt2wsihytxs.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2dkegaekh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.sxryk.cn/Article/details/gt2mphqadir.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2arzbenlq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.chenlongwang.top/Article/details/gt2shpwcpju.html

[G04] 定义方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wsccqblf.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2jcnwiloa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2sckrvwfd.html

JS:   greet() { return this.name; }
来源：http://dali.chenzaomai.com/Article/details/gt2uquujyqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.snrcjt.cn/Article/details/gt2jjrlfypn.html

Java: String greet() { return name; }
来源：http://dali.jqgfzy.top/Article/details/gt2mxkpdclg.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sysykeji.top/Article/details/gt2woxsqevw.html

Ruby: def greet; @name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnpljioi.html

C#:   public string Greet() => Name;
来源：http://dali.ivvv.top/Article/details/gt2wscrrqgl.html

[G05] 继承
来源：http://dali.yonumen.top/Article/details/gt2dtfmxali.html

Py:   class Admin(User): pass
来源：http://dali.jyoumei.cn/Article/details/gt2deqrxwvj.html

PHP:  class Admin extends User {}
来源：http://dali.havefunace.top/Article/details/gt2khphwuwe.html

JS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bivmeipr.html

TS:   class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gt2gqkrpbam.html

Java: class Admin extends User {}
来源：http://dali.gzhubu.top/Article/details/gt2uiwxhnsf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzbqjpzj.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gt2lulqlnct.html

C#:   class Admin : User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ajabcroh.html

[G06] 重写方法
来源：http://dali.cheryme.top/Article/details/gt2qfgoiyri.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gt2ebgxojvr.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.shzxlz.cn/Article/details/gt2pvvdmagf.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xpimrtdu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gt2dfjdzsii.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.bjfxy.top/Article/details/gt2pdfvrnmz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ocouqtlp.html

Ruby: def greet; "admin"; end
来源：http://dali.jyoumei.cn/Article/details/gt2vmmlcerc.html

C#:   public override string Greet() => "admin";
来源：http://dali.hammf.cn/Article/details/gt2chigfpdy.html

[G07] 调用父类方法
来源：http://dali.zhoulong.xyz/Article/details/gt2qcgyucmx.html

Py:   super().greet()
来源：http://dali.vqdsnc.cn/Article/details/gt2qxplylgq.html

PHP:  parent::greet();
来源：http://dali.xinyue.icu/Article/details/gt2mcilfheh.html

JS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2ewffigzv.html

TS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2shnhiqfa.html

Java: super.greet();
来源：http://dali.ivvv.top/Article/details/gt2ryblyaut.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yangfankeji.com/Article/details/gt2rucnldrd.html

Ruby: super
来源：http://dali.svipenyu.cn/Article/details/gt2xevycomt.html

C#:   base.Greet();
来源：http://dali.hywenlv.cn/Article/details/gt2oszjyess.html

[G08] 静态方法与属性
来源：http://dali.tian-w.cn/Article/details/gt2ramrkgqi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.dianchejie.cn/Article/details/gt2tgewaabb.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2lgpobyre.html

JS:   static f() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmqnkoun.html

TS:   static f(): void {}
来源：http://dali.yuxming.cn/Article/details/gt2pqaezmlx.html

Java: static void f() {}
来源：http://dali.tanke756.top/Article/details/gt2ukblvzue.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhengqikj.top/Article/details/gt2axjemlqu.html

Ruby: def self.f; end
来源：http://dali.tianlin.xyz/Article/details/gt2drsfphfk.html

C#:   public static void F() {}
来源：http://dali.sysykeji.top/Article/details/gt2twzthfgg.html

[G09] 接口 / 抽象类
来源：http://dali.fzhhl.top/Article/details/gt2nevctejr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gt2ehyugwad.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.andypj.xyz/Article/details/gt2hulsrwot.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.guannengcc.top/Article/details/gt2irxgeobc.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dgtrkcii.html

Java: interface Shape { double area(); }
来源：http://dali.jiagoushi.top/Article/details/gt2qgbfsdya.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yuxming.cn/Article/details/gt2dlkzlgak.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.gzhubu.top/Article/details/gt2kxkmytwx.html

C#:   interface IShape { double Area(); }
来源：http://dali.mhx1999.top/Article/details/gt2vaccnyop.html

[G10] 访问控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tiwmpcee.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.meibo888.top/Article/details/gt2yeasdckx.html

PHP:  public / protected / private
来源：http://dali.yueranfly.top/Article/details/gt2nofvtjgr.html

JS:   #private 字段；其余公开
来源：http://dali.hnxiangtu.top/Article/details/gt2aubthazb.html

TS:   public / protected / private
来源：http://dali.gaohongyu789.top/Article/details/gt2ctmmpeyu.html

Java: public / protected / private / 默认包级
来源：http://dali.chenjidiqi.icu/Article/details/gt2axargupg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.birdmap.top/Article/details/gt2jfijpqrz.html

Ruby: public / protected / private
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzynxoqq.html

C#:   public / protected / private / internal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hlkzrdmr.html

[G11] getter / setter
来源：http://dali.fzhhl.top/Article/details/gt2bapmzfsg.html

Py:   @property 与 @x.setter
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnanvfrb.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gt2vylhdeby.html

JS:   get name() { return this._name; }
来源：http://dali.yuanzhike.top/Article/details/gt2iwpmzovg.html

TS:   get name(): string { return this._name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pwhyoqyz.html

Java: public String getName() { return name; }
来源：http://dali.tanke756.top/Article/details/gt2rgkxtqxy.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2atyuzonp.html

Ruby: attr_accessor :name
来源：http://dali.0kj1m.cn/Article/details/gt2zjkgvsob.html

C#:   public string Name { get; set; }
来源：http://dali.dashuyun.cn/Article/details/gt2lcjtbnft.html

[G12] 对象转字符串
来源：http://dali.yuxming.cn/Article/details/gt2fampegct.html

Py:   def __str__(self): return self.name
来源：http://dali.yuxming.cn/Article/details/gt2sgoecjfx.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gt2nmvxxcak.html

JS:   toString() { return this.name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2lfoflfop.html

TS:   toString(): string { return this.name; }
来源：http://dali.cdnleiting.top/Article/details/gt2epnombdo.html

Java: @Override public String toString() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ywvfgodx.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2cnsncpyq.html

Ruby: def to_s; @name; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2moyxlcdh.html

C#:   public override string ToString() => Name;
来源：http://dali.yvedp.cn/Article/details/gt2rnvhkgmc.html

[G13] 判断对象类型
来源：http://dali.yuanzhike.top/Article/details/gt2wqajjsao.html

Py:   isinstance(u, User)
来源：http://dali.nanxuanxn.top/Article/details/gt2frrnpcdg.html

PHP:  $u instanceof User
来源：http://dali.zhiwuduotai.top/Article/details/gt2khskaydq.html

JS:   u instanceof User
来源：http://dali.jinqigfzy.top/Article/details/gt2gpboomgs.html

TS:   u instanceof User
来源：http://dali.dashuyun.cn/Article/details/gt2cftvzbwn.html

Java: u instanceof User
来源：http://dali.iojbl.cn/Article/details/gt2bmrzguuo.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gt2jmnvmphr.html

Ruby: u.is_a?(User)
来源：http://dali.hfpthk.cn/Article/details/gt2dtvrrqbf.html

C#:   u is User
来源：http://dali.chenlongwang.top/Article/details/gt2hwdobbkf.html

[G14] 数据类 / record
来源：http://dali.redwolf501.top/Article/details/gt2ixzkftwe.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wnbrcefi.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.jiagoushi.top/Article/details/gt2egbyaqfh.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.tanke756.top/Article/details/gt2oigbshtw.html

TS:   type User = { name: string; age: number };
来源：http://dali.hnqzz.top/Article/details/gt2wfaxeuud.html

Java: record User(String name, int age) {}
来源：http://dali.svipenyu.cn/Article/details/gt2thmpzvni.html

Go:   type User struct { Name string; Age int }
来源：http://dali.jqgfzy.top/Article/details/gt2iqdtoyyv.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.hnqzz.top/Article/details/gt2imeiffcj.html

C#:   record User(string Name, int Age);
来源：http://dali.snrcjt.cn/Article/details/gt2ptgedjqq.html

[G15] 枚举
来源：http://dali.tian-w.cn/Article/details/gt2npfwdzwg.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhixingplan.top/Article/details/gt2bkaishyv.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jiagoushi.top/Article/details/gt2pmlmublt.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tanke756.top/Article/details/gt2gnedpvha.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2jzjhoknd.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhoulong.xyz/Article/details/gt2pueyvisl.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.sxryk.cn/Article/details/gt2ffplyqud.html

Ruby: Color = %i[red green].freeze
来源：http://dali.snrcjt.cn/Article/details/gt2yktamova.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.fengsongda.top/Article/details/gt2wjcsnqds.html

[G16] 对象转数组 / 字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubsugzfs.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.havefunace.top/Article/details/gt2ohafnhoz.html

PHP:  get_object_vars($obj);
来源：http://dali.hnxiangtu.top/Article/details/gt2cfylbdqx.html

JS:   Object.entries(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2ulssfubi.html

TS:   Object.entries(obj)
来源：http://dali.nanxuanxn.top/Article/details/gt2zefismwp.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yuanzhike.top/Article/details/gt2odmcmiaj.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lcsstwvx.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2lvfhrxyt.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.meibo888.top/Article/details/gt2qbsfqtot.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2fptbaqxs.html

H. 异常与错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2lklvdzri.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2eeoyjhsh.html

[H01] try / catch 基础
来源：http://dali.jlsjyb.cn/Article/details/gt2jwrzivyb.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.tianlin.xyz/Article/details/gt2hautrytz.html


<!-- 参考信息 -->