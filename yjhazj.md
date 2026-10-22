代发 wailian999

[E18] 模板占位符替换
来源：http://dali.daria6918.cn/Article/details/gt2ydczgtpe.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2axiebfil.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gt2vykqfmlp.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2ujdokruh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2pjkgpzpf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pycfn.com/Article/details/gt2rvueashv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gt2gkoncnoq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hammf.cn/Article/details/gt2lazaiqon.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2sdfsxkih.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gt2bawzuerv.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gt2knrqyiox.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gt2fswkcrgg.html

JS:   s.split(/\r?\n/)
来源：http://dali.wangdashe.top/Article/details/gt2ibmelyej.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2mifhnxnp.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vroqbhba.html

Go:   strings.Split(s, "\n")
来源：http://dali.cdnleiting.top/Article/details/gt2zdleopov.html

Ruby: s.lines
来源：http://dali.sweek.top/Article/details/gt2hcwnhrik.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gt2igtpuhhu.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gt2sqirzgkg.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2oacsvpnd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhengqikj.top/Article/details/gt2vteqwppa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.havefunace.top/Article/details/gt2kltstjbv.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gt2foucxebr.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmrrovsx.html

Go:   if s == "" {}
来源：http://dali.tian-w.cn/Article/details/gt2iaaupaea.html

Ruby: if s.empty?
来源：http://dali.yvedp.cn/Article/details/gt2ambzlnri.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2xbmrrbdq.html

[E21] 超长截断加省略号
来源：http://dali.xuetiantiany.cn/Article/details/gt2huvunzsi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2tecejyqm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvphewpb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2moqhinwo.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2ndvlqmoe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2narfrriv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxebrmou.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slikomko.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2ajktayhn.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gt2wbcanlhx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2vakzmrad.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqkcoaaz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2xuzljarz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2zzvqayxx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dianchejie.cn/Article/details/gt2vvcozpgs.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.svipenyu.cn/Article/details/gt2bfzkxdmp.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2exjcyweb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxinkj.top/Article/details/gt2wmrkthgy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vudtkhxg.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gt2sgixwius.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2oduwvxnl.html

[F01] 读取整个文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjnbzjky.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnxiangtu.top/Article/details/gt2tyspyweb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2uvehgind.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gt2xhomfbyl.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2idgbimix.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2qryqrgei.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2dqqcdlmu.html

Ruby: File.read("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2dczvryna.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2pjnyabkb.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2zgdhwipi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2ynjrghuo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jxoryhhg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2xkjqaxfp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gt2ktgfowbg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2bosjetsd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aliinupk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cdnleiting.top/Article/details/gt2rsxyofnw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytqqedmi.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gt2kamolofs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.haohaochexian.top/Article/details/gt2xanmkadz.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gt2nkqxsjoy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2edrealao.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2ocbthjit.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yueranfly.top/Article/details/gt2hmxzzxxn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cheryme.top/Article/details/gt2ihllqvvn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gotoacloud.top/Article/details/gt2nsjjltsh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gt2viejoqfu.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gt2lrrkcwld.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hfpthk.cn/Article/details/gt2kordkcht.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2ulggdwjt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.redwolf501.top/Article/details/gt2hhvshnmj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2ryfvsagr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangdashe.top/Article/details/gt2tncfraie.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2icqbvzog.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cjoehklp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.chenjidiqi.icu/Article/details/gt2snxoszau.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2ekmezqyf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.birdmap.top/Article/details/gt2fwwzjftw.html

PHP:  file_exists("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2ycerjkjw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rdqdksfe.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2vmkjqptb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2nkucnxfw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2bdgslrip.html

Ruby: File.exist?("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2jrncrplt.html

C#:   File.Exists("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gpedzycn.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gt2vsfidbln.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2akxcibrk.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2ftaibewa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wkckztrq.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wmjyefmd.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gt2jujgsguo.html

Go:   os.Remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dzztzgtp.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2dxehxvct.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2giixychn.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gt2clmjcbbq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.meibo888.top/Article/details/gt2wuhijlcx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2wibuqwlq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2xzclwwfw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gt2kqypgmst.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gt2hyjvxnee.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.cheryme.top/Article/details/gt2mbwzjfzg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xdxgsjuu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tian-w.cn/Article/details/gt2yrmvxpjh.html

[F08] 遍历目录
来源：http://dali.yongpay.top/Article/details/gt2mccujaqf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rszvgzxs.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.smart0.xyz/Article/details/gt2ubjsktwm.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2xvaasgct.html

TS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2hmtnxiqt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2uauormqu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.svipenyu.cn/Article/details/gt2wiafzapu.html

Ruby: Dir.children("dir")
来源：http://dali.zycfv.cn/Article/details/gt2syanypoa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenlongwang.top/Article/details/gt2pntbxtdy.html

[F09] 获取文件大小
来源：http://dali.ydzc1.top/Article/details/gt2tpoixvwr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2yxmcsirp.html

PHP:  filesize("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgtrgsku.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tianlin.xyz/Article/details/gt2ktucprov.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zdqjudy.top/Article/details/gt2yqbztqkz.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fegtuezf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnqzz.top/Article/details/gt2qdbiqscd.html

Ruby: File.size("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2btpyewua.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2frckupyy.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sufxvd.cn/Article/details/gt2pbapkhjd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2qsyoedwc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2wbauwzql.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2myxnatjb.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2cgbtkert.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.kuanghao11.cn/Article/details/gt2wmduunnc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2frsepxug.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2oomlwcjr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2slgpurvz.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2rgcxytqe.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2wdbrkkzu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.smart0.xyz/Article/details/gt2egrjfpfp.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tian-w.cn/Article/details/gt2kdljfing.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2asdpjuar.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gt2zefcvvmd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.sysykeji.top/Article/details/gt2pckuujvm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2otochrxr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gt2tnvhizuw.html

[F12] CSV 读写
来源：http://dali.quarkkingdee.top/Article/details/gt2ntxqrjpi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2fpfzqdxp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yongpay.top/Article/details/gt2ntzjctgd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snhjpoik.html

TS:   // 同上
来源：http://dali.sufxvd.cn/Article/details/gt2upzkrwzt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.andypj.xyz/Article/details/gt2pxwxoelx.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pycfn.com/Article/details/gt2xownjpzb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhoulong.xyz/Article/details/gt2mvbvnlsj.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfoxmlkf.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2nabtxpbb.html

G. 面向对象
来源：http://dali.vqdsnc.cn/Article/details/gt2pdcxebyk.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2oljrohgc.html

[G01] 定义类
来源：http://dali.chenzaomai.com/Article/details/gt2gxmfpqpy.html

Py:   class User: pass
来源：http://dali.snrcjt.cn/Article/details/gt2vagdurhh.html

PHP:  class User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciqmtvef.html

JS:   class User {}
来源：http://dali.ehwqpu.com/Article/details/gt2vkgvccod.html

TS:   class User { name: string = ""; }
来源：http://dali.hywenlv.cn/Article/details/gt2ldiyciyt.html

Java: class User {}
来源：http://dali.yangfankeji.com/Article/details/gt2kzxrbtez.html

Go:   type User struct { Name string }
来源：http://dali.bjfxy.top/Article/details/gt2yxbpwtba.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aqzrbxlq.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2cjwhqmjr.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2cqbicjjb.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gt2nwimxkkb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2kyacqzfi.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2vcutmdjn.html

TS:   constructor(public name: string) {}
来源：http://dali.dashuyun.cn/Article/details/gt2cllogctq.html

Java: User(String name) { this.name = name; }
来源：http://dali.yj20258.top/Article/details/gt2lllhxhur.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2daucadhq.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.cqqwz.cn/Article/details/gt2yyvwfmpl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yuxming.cn/Article/details/gt2spxuqrty.html

[G03] 实例属性
来源：http://dali.smart0.xyz/Article/details/gt2vwxrrcfr.html

Py:   self.name = "x"
来源：http://dali.fengsongda.top/Article/details/gt2jqnoenqm.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gt2bwqyntdn.html

JS:   this.name = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gt2lvhqeyfz.html

TS:   name: string = "x";
来源：http://dali.fengsongda.top/Article/details/gt2doitjiwq.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2dnzdpyat.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2jcqpluki.html

Ruby: @name = "x"
来源：http://dali.hnqzz.top/Article/details/gt2injlwkhn.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sweek.top/Article/details/gt2dssovvrc.html

[G04] 定义方法
来源：http://dali.jinqigufen.top/Article/details/gt2ckgbhupk.html

Py:   def greet(self): return self.name
来源：http://dali.dashuyun.cn/Article/details/gt2sphsbrmp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2ivokchdk.html

JS:   greet() { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gt2xfdbryix.html

TS:   greet(): string { return this.name; }
来源：http://dali.ppjwa.cn/Article/details/gt2offpyflo.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2earxbmnk.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2cdojnaez.html

Ruby: def greet; @name; end
来源：http://dali.dianchejie.cn/Article/details/gt2bwjmuuno.html

C#:   public string Greet() => Name;
来源：http://dali.fengsongda.top/Article/details/gt2zmkchsyq.html

[G05] 继承
来源：http://dali.ppjwa.cn/Article/details/gt2drtnznhv.html

Py:   class Admin(User): pass
来源：http://dali.yanxiufei.cn/Article/details/gt2wlhhyrcl.html

PHP:  class Admin extends User {}
来源：http://dali.pycfn.com/Article/details/gt2gwuqcqlx.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qwlfogko.html

TS:   class Admin extends User {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsambucf.html

Java: class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2ibbjlpns.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.nwbrower.top/Article/details/gt2zmuinbad.html

Ruby: class Admin < User; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ypeywbad.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gt2knjvdgdw.html

[G06] 重写方法
来源：http://dali.dianchejie.cn/Article/details/gt2kugksueg.html

Py:   def greet(self): return "admin"
来源：http://dali.gotoacloud.top/Article/details/gt2yoqobexh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2hgowagrr.html

JS:   greet() { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2rakdddsj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.redwolf501.top/Article/details/gt2hkezhvst.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.hfpthk.cn/Article/details/gt2pyvbxzed.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.chenlongwang.top/Article/details/gt2sltkokrz.html

Ruby: def greet; "admin"; end
来源：http://dali.sufxvd.cn/Article/details/gt2udlsayak.html

C#:   public override string Greet() => "admin";
来源：http://dali.wangdashe.top/Article/details/gt2kuodustt.html

[G07] 调用父类方法
来源：http://dali.c1oappe.top/Article/details/gt2sbbmzext.html

Py:   super().greet()
来源：http://dali.wangdashe.top/Article/details/gt2qvnosimo.html

PHP:  parent::greet();
来源：http://dali.9152youxi.cn/Article/details/gt2nusnuijq.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2lsgfsxxu.html

TS:   super.greet();
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnompcnw.html

Java: super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2rcivrujw.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ppjwa.cn/Article/details/gt2pjmgelvb.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2dfceoftb.html

C#:   base.Greet();
来源：http://dali.xuanzx.com/Article/details/gt2ngfhapzm.html

[G08] 静态方法与属性
来源：http://dali.nanxuanxn.top/Article/details/gt2tbsdtknx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.tanke756.top/Article/details/gt2mevkvdba.html

PHP:  public static function f() {}
来源：http://dali.zhoulong.xyz/Article/details/gt2wrskbusq.html

JS:   static f() {}
来源：http://dali.xinyue.icu/Article/details/gt2yscpzrcu.html

TS:   static f(): void {}
来源：http://dali.0kj1m.cn/Article/details/gt2jqyyuxps.html

Java: static void f() {}
来源：http://dali.aizwys.cn/Article/details/gt2phhqjmzc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hfpthk.cn/Article/details/gt2qroirvjs.html

Ruby: def self.f; end
来源：http://dali.meibo888.top/Article/details/gt2hggzibcq.html

C#:   public static void F() {}
来源：http://dali.bjfxy.top/Article/details/gt2thskkpne.html

[G09] 接口 / 抽象类
来源：http://dali.cdnleiting.top/Article/details/gt2biblnjqv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhongyouzk.top/Article/details/gt2jsezfsrb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zakfdikt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.mhx1999.top/Article/details/gt2futiqget.html

TS:   interface Shape { area(): number; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2pakgvyfv.html

Java: interface Shape { double area(); }
来源：http://dali.dashuyun.cn/Article/details/gt2fwmxgmjw.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.hysaishi.cn/Article/details/gt2acjmbihw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.cdnleiting.top/Article/details/gt2tfvjyaei.html

C#:   interface IShape { double Area(); }
来源：http://dali.aizwys.cn/Article/details/gt2tedrbngt.html

[G10] 访问控制
来源：http://dali.yanxiufei.cn/Article/details/gt2fgrtreuo.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gt2vmejjiso.html

PHP:  public / protected / private
来源：http://dali.0kj1m.cn/Article/details/gt2jsnnhxov.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2xfdnucvq.html

TS:   public / protected / private
来源：http://dali.ppjwa.cn/Article/details/gt2zldehnii.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2cbhbsiav.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.svipenyu.cn/Article/details/gt2eubeemca.html

Ruby: public / protected / private
来源：http://dali.ivvv.top/Article/details/gt2yrdooxfn.html

C#:   public / protected / private / internal
来源：http://dali.pycfn.com/Article/details/gt2dzsqtfvs.html

[G11] getter / setter
来源：http://dali.andypj.xyz/Article/details/gt2wyyojtmf.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2getqzlnn.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ahhtzkus.html

JS:   get name() { return this._name; }
来源：http://dali.c1oappe.top/Article/details/gt2jzvhptck.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knxtlcug.html

Java: public String getName() { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2esmgeqlj.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jqgfzy.top/Article/details/gt2wicldixy.html

Ruby: attr_accessor :name
来源：http://dali.aizwys.cn/Article/details/gt2dwpzlwag.html

C#:   public string Name { get; set; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aesaimeo.html

[G12] 对象转字符串
来源：http://dali.guannengcc.top/Article/details/gt2rgskfuwp.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2oxrruutu.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2eihlfsqm.html

JS:   toString() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gt2enoasiex.html

TS:   toString(): string { return this.name; }
来源：http://dali.jyoumei.cn/Article/details/gt2deqnmqmm.html

Java: @Override public String toString() { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2yimcebyp.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhoulong.xyz/Article/details/gt2qdowdjxy.html

Ruby: def to_s; @name; end
来源：http://dali.zhengqikj.top/Article/details/gt2brznpmfl.html

C#:   public override string ToString() => Name;
来源：http://dali.yongpay.top/Article/details/gt2ystgndek.html

[G13] 判断对象类型
来源：http://dali.fengsongda.top/Article/details/gt2renvyjmx.html

Py:   isinstance(u, User)
来源：http://dali.jqgufenzy.top/Article/details/gt2agdgrnpe.html

PHP:  $u instanceof User
来源：http://dali.svipenyu.cn/Article/details/gt2zbqyqeql.html

JS:   u instanceof User
来源：http://dali.hysaishi.cn/Article/details/gt2vlbczmnm.html

TS:   u instanceof User
来源：http://dali.316326.xyz/Article/details/gt2wcpmhzkt.html

Java: u instanceof User
来源：http://dali.yueranfly.top/Article/details/gt2gjqbzduq.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.havefunace.top/Article/details/gt2noxpzfvk.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2fsiafsda.html

C#:   u is User
来源：http://dali.hnxiangtu.top/Article/details/gt2jjuroqag.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gt2sxdfchwo.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.birdmap.top/Article/details/gt2dldmuolo.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.sweek.top/Article/details/gt2hcyugaqv.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigfzy.top/Article/details/gt2mjxopbyz.html

TS:   type User = { name: string; age: number };
来源：http://dali.yuanzhike.top/Article/details/gt2qriwygsu.html

Java: record User(String name, int age) {}
来源：http://dali.sxryk.cn/Article/details/gt2blwsodno.html

Go:   type User struct { Name string; Age int }
来源：http://dali.chenzaomai.com/Article/details/gt2qzgsjdtm.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.ivvv.top/Article/details/gt2myylxdsy.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gt2ubjfkwwe.html

[G15] 枚举
来源：http://dali.jiagoushi.top/Article/details/gt2sqbgswvp.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.daria6918.cn/Article/details/gt2wlswesdl.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.ivvv.top/Article/details/gt2ujnxcmci.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.fzhhl.top/Article/details/gt2qsligyab.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2qaemluii.html

Java: enum Color { RED, GREEN }
来源：http://dali.hfpthk.cn/Article/details/gt2stqcnfmr.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.nwbrower.top/Article/details/gt2oztldetd.html

Ruby: Color = %i[red green].freeze
来源：http://dali.nanxuanxn.top/Article/details/gt2aasopfjj.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmolisho.html

[G16] 对象转数组 / 字典
来源：http://dali.xinyue.icu/Article/details/gt2rthwbioe.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccsdabqn.html

PHP:  get_object_vars($obj);
来源：http://dali.ydzc1.top/Article/details/gt2ggbtsown.html

JS:   Object.entries(obj)
来源：http://dali.jiagoushi.top/Article/details/gt2hgsncpuu.html

TS:   Object.entries(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rhhqfhww.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.smart0.xyz/Article/details/gt2nxwdxqhd.html


<!-- 参考信息 -->