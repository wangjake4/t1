代发 wailian999

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnxiangtu.top/Article/details/gt2ujeckmzy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj202588.top/Article/details/gt2dgqgwdji.html

C#:   1234567.ToString("N0")
来源：http://dali.cqqwz.cn/Article/details/gt2xvypxmmo.html

[E17] 首字母大写
来源：http://dali.zycfv.cn/Article/details/gt2uykncdgq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gt2muiyudvp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sztmnqns.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tianlin.xyz/Article/details/gt2tdvqeofl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2imjdrgue.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lopmrtsk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gt2mmjhomna.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gt2gbldptdp.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2hqfwhzai.html

[E18] 模板占位符替换
来源：http://dali.316326.xyz/Article/details/gt2llvxintn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.havefunace.top/Article/details/gt2jjstzyao.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gt2wrvtbjah.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2mdsvivkh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gt2uwxeenrc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2hlibbzpv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bcbiwogs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2uyllauxr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gt2eqrzzjee.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gt2gwfrtdkv.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2euwokyxy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258.top/Article/details/gt2afvpcbwi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gt2oauxreou.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2pozlqucv.html

Java: s.lines().toList()
来源：http://dali.chenlongwang.top/Article/details/gt2nlghhekn.html

Go:   strings.Split(s, "\n")
来源：http://dali.jyoumei.cn/Article/details/gt2vntrpvxm.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gt2apygbeqp.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2qysynjls.html

[E20] 判断字符串是否为空
来源：http://dali.dashuyun.cn/Article/details/gt2llaaolro.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gt2ltzfumvh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj202588.top/Article/details/gt2xsaqryuy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2ooupbqte.html

TS:   if (s === "") {}
来源：http://dali.fzhhl.top/Article/details/gt2gjwsuxta.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2objzihnn.html

Go:   if s == "" {}
来源：http://dali.yueranfly.top/Article/details/gt2rugeekwo.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2nxasirey.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ydzc1.top/Article/details/gt2uznsjjgh.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kyvukpti.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gt2oxeeuknz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.meibo888.top/Article/details/gt2yittemce.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2lvjevioy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2xzunnnqt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2omfgpzfx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2onsypfxn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2clpdjtoc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gt2oorewqlt.html

[E22] 字节长度与字符长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qqdhietl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hfpthk.cn/Article/details/gt2pnpapdum.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gt2wgnwdzyh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sxryk.cn/Article/details/gt2zugyconp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gt2gpdbntpt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tanke756.top/Article/details/gt2jaxyhlew.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.9152youxi.cn/Article/details/gt2meynnumk.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gt2ifwhcpuz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zaymzmdo.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xwgfrxpp.html

F. 文件与目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufbvobcr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2udxdhuss.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybrgqrfz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.daxiang520.top/Article/details/gt2syuycnoc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2werdaamu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zdqjudy.top/Article/details/gt2ppquevyo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hysaishi.cn/Article/details/gt2cunioehm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuanzx.com/Article/details/gt2lgzlgtnk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gt2ttchzbxq.html

Ruby: File.read("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2drkmhvqd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shzxlz.cn/Article/details/gt2pcfllbhl.html

[F02] 逐行读取文件
来源：http://dali.yangfankeji.com/Article/details/gt2mfzvbksk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcsypgkd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.havefunace.top/Article/details/gt2jutsxtri.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lwavkdzp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gt2svmrkstn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2fifzhivo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2wumjdxtg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gt2epsmmdsw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gt2vwwpehnn.html

[F03] 写入文件（覆盖）
来源：http://dali.yuanzhike.top/Article/details/gt2bhoaqrmn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cqqwz.cn/Article/details/gt2umtrfaua.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gt2bdjwejzz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2jelsgnhs.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gt2dbljggiv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cdnleiting.top/Article/details/gt2rdhtrmeb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2cxvzitte.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gt2ydphutct.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmwdjkvj.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gt2wwhudvhb.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2zgfsvdpv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.quarkkingdee.top/Article/details/gt2telcltxz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2sdzekzgm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gt2irhwffiy.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guowangkeji.top/Article/details/gt2pmiwjwvg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cashguo.top/Article/details/gt2katjzljf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2ptypbjzp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gt2swabdjpr.html

[F05] 判断文件或目录是否存在
来源：http://dali.svipenyu.cn/Article/details/gt2vfjcxaup.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tianlin.xyz/Article/details/gt2zscbghvn.html

PHP:  file_exists("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrktevnp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmisfmtg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2qmslklvw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbcztto.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gt2aidepnwd.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2ajheejtg.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2stgnwduo.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gt2dhldesem.html

Py:   os.remove("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2jlrnkqac.html

PHP:  unlink("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsutdfgp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ubjbptth.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2xpejtmmg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gt2xfgeksiy.html

Go:   os.Remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2chcsefgr.html

Ruby: File.delete("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2nnlxzjqz.html

C#:   File.Delete("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2jvpyrnwh.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gt2pbbddajc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivhkkfnz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2oqpxltvs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hnqzz.top/Article/details/gt2zcvjelew.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryggupfg.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2fduhrpip.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gt2jyooekvz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gt2whrvbipu.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2qdcepfil.html

[F08] 遍历目录
来源：http://dali.fengsongda.top/Article/details/gt2ritnnvcn.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yvedp.cn/Article/details/gt2ermujmnf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxlqreqq.html

JS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2hddfmaob.html

TS:   fs.readdirSync("dir")
来源：http://dali.chenzaomai.com/Article/details/gt2pezfsfys.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2ysdbwpwu.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.wangdashe.top/Article/details/gt2igvnvzez.html

Ruby: Dir.children("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2ynbcvdck.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2riejrnvy.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2xqcmghwo.html

Py:   os.path.getsize("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2jwvoucrv.html

PHP:  filesize("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2cvpchxzd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2ivtkgchx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.fengsongda.top/Article/details/gt2mjvxefto.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2gmglxzun.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.tian-w.cn/Article/details/gt2xpeeehba.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2sgzeqsoh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zdqjudy.top/Article/details/gt2gbzwmoem.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.vqdsnc.cn/Article/details/gt2vjkipgbs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2lmtjfzro.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2xfjdbxrj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2ssezakjb.html

TS:   path.extname("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2flcwjgyi.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gt2ftztopti.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2vcjmdpky.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2emzksgdl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2lldgrngr.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gt2ouzjihyq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gt2mbwybikd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2exyluyig.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gt2niycaqrg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pqsidloe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.c1oappe.top/Article/details/gt2nkgoopah.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tian-w.cn/Article/details/gt2lmbrepdo.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gt2yyopstvd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gt2xggtybgw.html

[F12] CSV 读写
来源：http://dali.chenlongwang.top/Article/details/gt2daajkmoz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dianisaq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgfzy.top/Article/details/gt2cpzvubtb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2emsmeyze.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2xftrhduk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpphgwtc.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2qeyveend.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2gosqhioi.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.316326.xyz/Article/details/gt2hgkphxcf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wyimegqr.html

G. 面向对象
来源：http://dali.jinqigufen.top/Article/details/gt2cgdbwzxr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2vmocrjmn.html

[G01] 定义类
来源：http://dali.tianlin.xyz/Article/details/gt2frelvvty.html

Py:   class User: pass
来源：http://dali.wangdashe.top/Article/details/gt2sspavfpy.html

PHP:  class User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2asvahuup.html

JS:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2gkmvxowh.html

TS:   class User { name: string = ""; }
来源：http://dali.sxryk.cn/Article/details/gt2gmlbvixz.html

Java: class User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2edgaevds.html

Go:   type User struct { Name string }
来源：http://dali.gogol.net.cn/Article/details/gt2rhflqboy.html

Ruby: class User; end
来源：http://dali.sweek.top/Article/details/gt2fllipfdu.html

C#:   class User {}
来源：http://dali.fengsongda.top/Article/details/gt2ivcqylre.html

[G02] 构造函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2qryhwadk.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sufxvd.cn/Article/details/gt2tzlecmvy.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2eueysckb.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gogol.net.cn/Article/details/gt2dsyljfhr.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2vgyuytax.html

Java: User(String name) { this.name = name; }
来源：http://dali.ppjwa.cn/Article/details/gt2wibuxypi.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2mwuvctpl.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.guannengcc.top/Article/details/gt2xwwnnvgv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2vkloufqa.html

[G03] 实例属性
来源：http://dali.gogol.net.cn/Article/details/gt2fgilkcyx.html

Py:   self.name = "x"
来源：http://dali.cqqwz.cn/Article/details/gt2awaenizl.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2jnjfdmxi.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2snjadxnx.html

TS:   name: string = "x";
来源：http://dali.guannengcc.top/Article/details/gt2zzmluhtg.html

Java: private String name;
来源：http://dali.nanxuanxn.top/Article/details/gt2qazezmsg.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.shuidangran.top/Article/details/gt2ltbclmmu.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2qimfhhoo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gt2tmngqodc.html

[G04] 定义方法
来源：http://dali.aizwys.cn/Article/details/gt2vuhhucvv.html

Py:   def greet(self): return self.name
来源：http://dali.nanxinkj.top/Article/details/gt2pmnvwqbu.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ybcxt.top/Article/details/gt2vlpzgldi.html

JS:   greet() { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2ncrzgoxb.html

TS:   greet(): string { return this.name; }
来源：http://dali.xuanzx.com/Article/details/gt2odaeznkl.html

Java: String greet() { return name; }
来源：http://dali.birdmap.top/Article/details/gt2raxwytjw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hfpthk.cn/Article/details/gt2snhquubv.html

Ruby: def greet; @name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2drazclwb.html

C#:   public string Greet() => Name;
来源：http://dali.zhongyouzk.top/Article/details/gt2sldpnzbk.html

[G05] 继承
来源：http://dali.hysaishi.cn/Article/details/gt2wtxzzsjd.html

Py:   class Admin(User): pass
来源：http://dali.sweek.top/Article/details/gt2hzzxutym.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2iblrijtf.html

JS:   class Admin extends User {}
来源：http://dali.zhengqikj.top/Article/details/gt2qpcutvwk.html

TS:   class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gt2priefmht.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2imeihuwt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ppjwa.cn/Article/details/gt2sbepmhbk.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gt2lfyzhhjc.html

C#:   class Admin : User {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2roxiyctu.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gt2gxsahvzw.html

Py:   def greet(self): return "admin"
来源：http://dali.zhongyouzk.top/Article/details/gt2xxtmpmxo.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.mhx1999.top/Article/details/gt2qmzqshxf.html

JS:   greet() { return "admin"; }
来源：http://dali.fzhhl.top/Article/details/gt2uutmctmf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gt2txqogiai.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2vfwzhaqr.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgfzy.top/Article/details/gt2mzrnlnkp.html

Ruby: def greet; "admin"; end
来源：http://dali.zhongyouzk.top/Article/details/gt2oortpbaz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ivvv.top/Article/details/gt2pkqdmbti.html

[G07] 调用父类方法
来源：http://dali.yj20258.top/Article/details/gt2twetqimz.html

Py:   super().greet()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kvvnflut.html

PHP:  parent::greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pbnaymae.html

JS:   super.greet();
来源：http://dali.ehwqpu.com/Article/details/gt2eauhgabr.html

TS:   super.greet();
来源：http://dali.chenjidiqi.icu/Article/details/gt2yozplnhc.html

Java: super.greet();
来源：http://dali.gzhubu.top/Article/details/gt2aevcqrnm.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jqgufenzy.top/Article/details/gt2xmefuoqr.html

Ruby: super
来源：http://dali.hnxiangtu.top/Article/details/gt2eoeksdbh.html

C#:   base.Greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2qpbypiqx.html

[G08] 静态方法与属性
来源：http://dali.meibo888.top/Article/details/gt2ickwlfwx.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.mhx1999.top/Article/details/gt2grcnvfgv.html

PHP:  public static function f() {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxhtmbqc.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svlwpoxo.html

TS:   static f(): void {}
来源：http://dali.yanxiufei.cn/Article/details/gt2jyvpgzpx.html

Java: static void f() {}
来源：http://dali.c1oappe.top/Article/details/gt2rprmovff.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.andypj.xyz/Article/details/gt2htydsvaw.html

Ruby: def self.f; end
来源：http://dali.yuanzhike.top/Article/details/gt2httrfhjw.html

C#:   public static void F() {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iglgzijy.html

[G09] 接口 / 抽象类
来源：http://dali.yvedp.cn/Article/details/gt2fvfysjuc.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2ikufqlva.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.316326.xyz/Article/details/gt2ywwrzajl.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.0kj1m.cn/Article/details/gt2crdvzlsz.html

TS:   interface Shape { area(): number; }
来源：http://dali.tanke756.top/Article/details/gt2fotxodll.html

Java: interface Shape { double area(); }
来源：http://dali.pycfn.com/Article/details/gt2hazaujjy.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.cashguo.top/Article/details/gt2jrfluhgf.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2ifsxrkqz.html

C#:   interface IShape { double Area(); }
来源：http://dali.shzxlz.cn/Article/details/gt2nlmlewip.html

[G10] 访问控制
来源：http://dali.shangyingyoupin.top/Article/details/gt2pqooxjes.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.dianchejie.cn/Article/details/gt2fvsgxopw.html

PHP:  public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2ybfnkmcu.html

JS:   #private 字段；其余公开
来源：http://dali.sxryk.cn/Article/details/gt2mjwehwia.html

TS:   public / protected / private
来源：http://dali.dianchejie.cn/Article/details/gt2sqihaamj.html

Java: public / protected / private / 默认包级
来源：http://dali.vqdsnc.cn/Article/details/gt2hjuybvfb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.wangdashe.top/Article/details/gt2xzzdpztl.html

Ruby: public / protected / private
来源：http://dali.kuanghao11.cn/Article/details/gt2dzuwamiq.html

C#:   public / protected / private / internal
来源：http://dali.xziqi.cn/Article/details/gt2gaiygens.html

[G11] getter / setter
来源：http://dali.chenzaomai.com/Article/details/gt2vttjafeq.html

Py:   @property 与 @x.setter
来源：http://dali.svipenyu.cn/Article/details/gt2zxysgzrg.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2yryjdjkn.html

JS:   get name() { return this._name; }
来源：http://dali.guowangkeji.top/Article/details/gt2hroeyhjx.html

TS:   get name(): string { return this._name; }
来源：http://dali.hnqzz.top/Article/details/gt2coariwyb.html

Java: public String getName() { return name; }
来源：http://dali.sweek.top/Article/details/gt2nygolant.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2szfwxchh.html

Ruby: attr_accessor :name
来源：http://dali.havefunace.top/Article/details/gt2ozinxvmq.html

C#:   public string Name { get; set; }
来源：http://dali.zhoulong.xyz/Article/details/gt2jvskjkak.html

[G12] 对象转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hweeheep.html

Py:   def __str__(self): return self.name
来源：http://dali.redwolf501.top/Article/details/gt2xvrznktt.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrxluqlh.html

JS:   toString() { return this.name; }
来源：http://dali.zdqjudy.top/Article/details/gt2hdoiqwkh.html

TS:   toString(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2junedmry.html

Java: @Override public String toString() { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2kntahtre.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbbfpoqi.html

Ruby: def to_s; @name; end
来源：http://dali.meibo888.top/Article/details/gt2tfkeblco.html

C#:   public override string ToString() => Name;
来源：http://dali.ivvv.top/Article/details/gt2kduoieie.html

[G13] 判断对象类型
来源：http://dali.0kj1m.cn/Article/details/gt2mzhrcudv.html

Py:   isinstance(u, User)
来源：http://dali.andypj.xyz/Article/details/gt2gkmftlvy.html

PHP:  $u instanceof User
来源：http://dali.birdmap.top/Article/details/gt2phqalpso.html

JS:   u instanceof User
来源：http://dali.cheryme.top/Article/details/gt2zeehzxvl.html

TS:   u instanceof User
来源：http://dali.tianlin.xyz/Article/details/gt2hpemnwsq.html

Java: u instanceof User
来源：http://dali.pycfn.com/Article/details/gt2cgwlztxw.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.nanxinkj.top/Article/details/gt2nhjliuvd.html

Ruby: u.is_a?(User)
来源：http://dali.xuanzx.com/Article/details/gt2yfsnldkv.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gt2wbwkbcoi.html

[G14] 数据类 / record
来源：http://dali.xuetiantiany.cn/Article/details/gt2tfylrbgz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.yvedp.cn/Article/details/gt2xwksuwwx.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.9152youxi.cn/Article/details/gt2zvxnjlwx.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2hybdpeim.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkzyvft.html

Java: record User(String name, int age) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2jktocesu.html

Go:   type User struct { Name string; Age int }
来源：http://dali.yonumen.top/Article/details/gt2xrsgkqbx.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.quarkkingdee.top/Article/details/gt2hnrxtnya.html

C#:   record User(string Name, int Age);
来源：http://dali.316326.xyz/Article/details/gt2orxxbgbe.html

[G15] 枚举
来源：http://dali.iojbl.cn/Article/details/gt2gcxulzcy.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tdbvksub.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.jianghu66.top/Article/details/gt2zjamisdu.html


<!-- 参考信息 -->