代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gt2zlkiupco.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2jwrhnnru.html

[E16] 数字千分位
来源：http://dali.yj202588.top/Article/details/gt2cpifounl.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gt2oeqwrgzm.html

PHP:  number_format(1234567);
来源：http://dali.yuanzhike.top/Article/details/gt2gkbcylen.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gt2waxttffy.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2ibtgeayo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2ylptmvui.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2bleoaxkv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gt2fnqixocr.html

C#:   1234567.ToString("N0")
来源：http://dali.ybcxt.top/Article/details/gt2hychnmve.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gt2xbqfeizp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.iojbl.cn/Article/details/gt2yvfbhbpd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gt2xtfwcjra.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fengsongda.top/Article/details/gt2ncymjldw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yangfankeji.com/Article/details/gt2vldkuosw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenzaomai.com/Article/details/gt2bzqjylbq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gzhubu.top/Article/details/gt2kxotsddg.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2maejbsai.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aizwys.cn/Article/details/gt2dhmhtxru.html

[E18] 模板占位符替换
来源：http://dali.chenzaomai.com/Article/details/gt2meqmyidk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxgcuddr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shangyingyoupin.top/Article/details/gt2awfbxhdc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dtaawwhk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yonumen.top/Article/details/gt2mixqgljp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2uotqvfhc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2iryfflsx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gt2tysrksfz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gt2ghvxkcco.html

[E19] 多行文本按行拆分
来源：http://dali.dianchejie.cn/Article/details/gt2eftojiuo.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccorulci.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zaicilxz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2aziqviry.html

TS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gt2nahhmgmd.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gt2fmrndyhs.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gt2jcbayvbo.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2uzctzanb.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2asbixueo.html

[E20] 判断字符串是否为空
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuifiojj.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2ffvhihbg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2fegudzuw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jiagoushi.top/Article/details/gt2ydbnqznc.html

TS:   if (s === "") {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2jeneylpn.html

Java: if (s.isEmpty()) {}
来源：http://dali.jianghu66.top/Article/details/gt2ttzajbup.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gt2fzqqknwg.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gt2fzshwhnc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gzhubu.top/Article/details/gt2aznveicm.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqavvbac.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gt2tjxctlht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gt2oznurlsa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yonumen.top/Article/details/gt2vsikyzvp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2gcytsqhe.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gt2zljnienv.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2efdhvmlh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2hjeykmob.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2dmfeskey.html

[E22] 字节长度与字符长度
来源：http://dali.meibo888.top/Article/details/gt2sghkesqv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tianlin.xyz/Article/details/gt2exsaniqv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gt2ikytlrsl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gt2sblysgzt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gt2gewtpkjd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2rrziqprr.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gt2gpqpvazj.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj20258.top/Article/details/gt2imxlrmkk.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gt2pggjpvfa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2qszyusui.html

F. 文件与目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygxxypjp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2kmyvamro.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gt2fgzzdmab.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gt2ykdvpbbi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aehfajoy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2zknqptbg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2tfslnwop.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhixingplan.top/Article/details/gt2pzbfizmm.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yongpay.top/Article/details/gt2crnkeaxc.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjxaoyvq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzdvbklq.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2hgyjloae.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yueranfly.top/Article/details/gt2whkmfqgs.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gt2geizthfx.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2iyktdznr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2hcqxnhzr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2xigdnhhx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gt2rgesmfbu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2jcibsrlg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2ichbfeox.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2sdohvauz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangshuangyany.cn/Article/details/gt2vurlqfch.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gt2pzblslzv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gt2airlryij.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gt2zdtsfgte.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.haohaochexian.top/Article/details/gt2eoevxizk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gt2aavvfnmw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zdqjudy.top/Article/details/gt2dxwtdgwp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2yjzofrfs.html

[F04] 追加写入文件
来源：http://dali.yonumen.top/Article/details/gt2batjpghj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gt2cimshhnt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gotoacloud.top/Article/details/gt2jmxqmoxm.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gt2nuzbzntf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2sjtcpcnq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gt2deqbvyis.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xinyue.icu/Article/details/gt2qqoobkhj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygitempc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangdashe.top/Article/details/gt2zhvvkqxv.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhengqikj.top/Article/details/gt2ieumtvia.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iytcjftz.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2vivjoxjn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2izatsbss.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2xzmqplgw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gt2vkjbnoyz.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gt2kbxayhkv.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2ozlupjmj.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ptatujri.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gt2xocuycxi.html

Py:   os.remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2xjsjcwvn.html

PHP:  unlink("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2wxznfurg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2rdqgpdjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2reyktgai.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hnxiangtu.top/Article/details/gt2czollqgo.html

Go:   os.Remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2yspjhqos.html

Ruby: File.delete("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2bjgklkgg.html

C#:   File.Delete("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2oeectjke.html

[F07] 创建目录（含多级）
来源：http://dali.bjfxy.top/Article/details/gt2pbpqcxjk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2mlmkmwco.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdinaiaz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2iocflahd.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gt2nhxymmyu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gt2awszqfjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gt2clwtlnxf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gt2krvredpm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gt2euhzzots.html

[F08] 遍历目录
来源：http://dali.hysaishi.cn/Article/details/gt2lpsjumxy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ooqwpsmi.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ymociccp.html

JS:   fs.readdirSync("dir")
来源：http://dali.xziqi.cn/Article/details/gt2jjwnlbvt.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gt2epnudust.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2xnjznifk.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2tdrvctis.html

Ruby: Dir.children("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2hwlojggr.html

C#:   Directory.GetFiles("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2qzqnjfeq.html

[F09] 获取文件大小
来源：http://dali.aizwys.cn/Article/details/gt2zgzojdzq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2vebscloe.html

PHP:  filesize("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2einrelff.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epatpojf.html

TS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2nilirojf.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gt2tznwhkzd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwmrcrmv.html

Ruby: File.size("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2orpzzgio.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.smart0.xyz/Article/details/gt2bvoufanx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dashuyun.cn/Article/details/gt2jcecazcp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2jmrqaxbg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2nootypri.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2numinwli.html

TS:   path.extname("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2zkxrfivl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvdeanv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kdjqawbi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2xprppylw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2vysipupr.html

[F11] 复制与移动文件
来源：http://dali.daxiang520.top/Article/details/gt2jrglmimo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2yuiqjgxp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.andypj.xyz/Article/details/gt2xgfnxofx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2luefswzz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fdjvgcye.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kpatjfef.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guowangkeji.top/Article/details/gt2ttqsmywu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2setpeoxe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.xinyue.icu/Article/details/gt2urzhygcy.html

[F12] CSV 读写
来源：http://dali.kuanghao11.cn/Article/details/gt2muulphma.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.fengsongda.top/Article/details/gt2bgenmwbk.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2sgdmomnu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2frmagqmu.html

TS:   // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krsvfzgp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gt2onpssxbp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2okvwqbbb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenlongwang.top/Article/details/gt2fhahsumc.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxhtpame.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mwbmxtjy.html

G. 面向对象
来源：http://dali.9152youxi.cn/Article/details/gt2fawrhfek.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2qylnkeyk.html

[G01] 定义类
来源：http://dali.fengsongda.top/Article/details/gt2ceirenfj.html

Py:   class User: pass
来源：http://dali.yj202588.top/Article/details/gt2mayqpjmz.html

PHP:  class User {}
来源：http://dali.pycfn.com/Article/details/gt2kwmfgtrq.html

JS:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2rzinweoh.html

TS:   class User { name: string = ""; }
来源：http://dali.c1oappe.top/Article/details/gt2engrtmru.html

Java: class User {}
来源：http://dali.zhijiandao.cn/Article/details/gt2khuoerpy.html

Go:   type User struct { Name string }
来源：http://dali.jqgfzy.top/Article/details/gt2ylzmrtzw.html

Ruby: class User; end
来源：http://dali.ivvv.top/Article/details/gt2uaydiwxs.html

C#:   class User {}
来源：http://dali.cheryme.top/Article/details/gt2lmacjrpm.html

[G02] 构造函数
来源：http://dali.xuanzx.com/Article/details/gt2aqnrtdpd.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gt2qyhivgbb.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2xtofwikz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.redwolf501.top/Article/details/gt2ltaxxjhi.html

TS:   constructor(public name: string) {}
来源：http://dali.snrcjt.cn/Article/details/gt2wgejqlix.html

Java: User(String name) { this.name = name; }
来源：http://dali.wangdashe.top/Article/details/gt2njtvqodx.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cashguo.top/Article/details/gt2ljlvwigd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gt2xioamxkm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwetoyow.html

[G03] 实例属性
来源：http://dali.bjfxy.top/Article/details/gt2etcqwldz.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gt2kwiakmag.html

PHP:  public string $name = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2mkfozavt.html

JS:   this.name = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2lddmihud.html

TS:   name: string = "x";
来源：http://dali.zdqjudy.top/Article/details/gt2euxjrimi.html

Java: private String name;
来源：http://dali.aizwys.cn/Article/details/gt2natvvetp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2psfnjiah.html

Ruby: @name = "x"
来源：http://dali.yuanzhike.top/Article/details/gt2djmmdiln.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.ehwqpu.com/Article/details/gt2uowvhqhm.html

[G04] 定义方法
来源：http://dali.jqgfzy.top/Article/details/gt2avtihrfb.html

Py:   def greet(self): return self.name
来源：http://dali.hnqzz.top/Article/details/gt2sgjprvki.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2xihiqacl.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2adpztfqi.html

TS:   greet(): string { return this.name; }
来源：http://dali.ehwqpu.com/Article/details/gt2veidmmhr.html

Java: String greet() { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bupqyecj.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gt2bvkyyloa.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gt2ihqofqfm.html

C#:   public string Greet() => Name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2nwcyqtoz.html

[G05] 继承
来源：http://dali.hnxiangtu.top/Article/details/gt2xarusgoc.html

Py:   class Admin(User): pass
来源：http://dali.vqdsnc.cn/Article/details/gt2djkxjwll.html

PHP:  class Admin extends User {}
来源：http://dali.daxiang520.top/Article/details/gt2thpyazvm.html

JS:   class Admin extends User {}
来源：http://dali.fzhhl.top/Article/details/gt2zrjgaglt.html

TS:   class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gt2jhylqovn.html

Java: class Admin extends User {}
来源：http://dali.andypj.xyz/Article/details/gt2upmvdfpm.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.vqdsnc.cn/Article/details/gt2mtksbkgd.html

Ruby: class Admin < User; end
来源：http://dali.jinqigfzy.top/Article/details/gt2iydyzbgh.html

C#:   class Admin : User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2nfiitbfx.html

[G06] 重写方法
来源：http://dali.snrcjt.cn/Article/details/gt2jikjggol.html

Py:   def greet(self): return "admin"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uurklotz.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2euwfqhsi.html

JS:   greet() { return "admin"; }
来源：http://dali.ybcxt.top/Article/details/gt2rdxbppnu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ykynhydd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gt2xtdlrwmj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2zuorpbsn.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258.top/Article/details/gt2hygckusd.html

C#:   public override string Greet() => "admin";
来源：http://dali.xinyue.icu/Article/details/gt2gqenwqym.html

[G07] 调用父类方法
来源：http://dali.zdqjudy.top/Article/details/gt2nrrelqmd.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2nsuvuuus.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gt2uagctrbc.html

JS:   super.greet();
来源：http://dali.zdqjudy.top/Article/details/gt2qvgxnucl.html

TS:   super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gt2zmccpswx.html

Java: super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2slprdkut.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.xylfe.cn/Article/details/gt2fgqkvyfo.html

Ruby: super
来源：http://dali.hywenlv.cn/Article/details/gt2vpprnqgp.html

C#:   base.Greet();
来源：http://dali.vqdsnc.cn/Article/details/gt2dmxjqnbr.html

[G08] 静态方法与属性
来源：http://dali.9152youxi.cn/Article/details/gt2agtqyxrq.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xinyue.icu/Article/details/gt2yjpkpwsy.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gt2mogdoudy.html

JS:   static f() {}
来源：http://dali.aizwys.cn/Article/details/gt2tbyelzhr.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2vcnahuuy.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gt2lenxelof.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.cqqwz.cn/Article/details/gt2jcivbbpm.html

Ruby: def self.f; end
来源：http://dali.cdnleiting.top/Article/details/gt2cpykvkos.html

C#:   public static void F() {}
来源：http://dali.zdqjudy.top/Article/details/gt2okhvydqz.html

[G09] 接口 / 抽象类
来源：http://dali.hammf.cn/Article/details/gt2dzeqstai.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2caodeelh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpqovfjs.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oqklmmwz.html

TS:   interface Shape { area(): number; }
来源：http://dali.sysykeji.top/Article/details/gt2yhisvkyp.html

Java: interface Shape { double area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2kwhosmob.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.daxiang520.top/Article/details/gt2yxmskdkj.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.yuxming.cn/Article/details/gt2tblaswzh.html

C#:   interface IShape { double Area(); }
来源：http://dali.havefunace.top/Article/details/gt2jfxouxhm.html

[G10] 访问控制
来源：http://dali.dashuyun.cn/Article/details/gt2cxbgzrad.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.chenzaomai.com/Article/details/gt2novyhhrt.html

PHP:  public / protected / private
来源：http://dali.zhengqikj.top/Article/details/gt2wkogfgsy.html

JS:   #private 字段；其余公开
来源：http://dali.shangyingyoupin.top/Article/details/gt2pacfvfnz.html

TS:   public / protected / private
来源：http://dali.andypj.xyz/Article/details/gt2jjkdxwnb.html

Java: public / protected / private / 默认包级
来源：http://dali.zhixingplan.top/Article/details/gt2stjtdnic.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.ybcxt.top/Article/details/gt2hxronntp.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2cvbbvqti.html

C#:   public / protected / private / internal
来源：http://dali.ppjwa.cn/Article/details/gt2kxajsngn.html

[G11] getter / setter
来源：http://dali.jqgufenzy.top/Article/details/gt2ouzofkae.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2cqftvddf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.haohaochexian.top/Article/details/gt2belqnokk.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gt2ieklytyw.html

TS:   get name(): string { return this._name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ladxgwqn.html

Java: public String getName() { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2fxsxtmsq.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.tianlin.xyz/Article/details/gt2kkppgsfg.html

Ruby: attr_accessor :name
来源：http://dali.c1oappe.top/Article/details/gt2mqvlwlnl.html

C#:   public string Name { get; set; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txodlolp.html

[G12] 对象转字符串
来源：http://dali.xylfe.cn/Article/details/gt2avhjrozs.html

Py:   def __str__(self): return self.name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmuoaowl.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2rpidywwl.html

JS:   toString() { return this.name; }
来源：http://dali.tianlin.xyz/Article/details/gt2aelnhwhc.html

TS:   toString(): string { return this.name; }
来源：http://dali.cucudq.cn/Article/details/gt2gwtpiquk.html

Java: @Override public String toString() { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2dfabyoou.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znbrdhlc.html

Ruby: def to_s; @name; end
来源：http://dali.jqgfzy.top/Article/details/gt2alkvfuie.html

C#:   public override string ToString() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2gulukemg.html

[G13] 判断对象类型
来源：http://dali.zhengqikj.top/Article/details/gt2glqenddy.html

Py:   isinstance(u, User)
来源：http://dali.daria6918.cn/Article/details/gt2dwbrpzdt.html

PHP:  $u instanceof User
来源：http://dali.gotoacloud.top/Article/details/gt2kfbnivgb.html

JS:   u instanceof User
来源：http://dali.shuidangran.top/Article/details/gt2btfndqek.html

TS:   u instanceof User
来源：http://dali.nwbrower.top/Article/details/gt2nlplrgwa.html

Java: u instanceof User
来源：http://dali.redwolf501.top/Article/details/gt2kxobaloj.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.aibaodan.cn/Article/details/gt2tofwjeji.html

Ruby: u.is_a?(User)
来源：http://dali.sufxvd.cn/Article/details/gt2yfbpnzkh.html

C#:   u is User
来源：http://dali.nanxinkj.top/Article/details/gt2ktlclcjb.html

[G14] 数据类 / record
来源：http://dali.kuanghao11.cn/Article/details/gt2vdpbczli.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.jinqigfzy.top/Article/details/gt2pdexaxmp.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.xylfe.cn/Article/details/gt2liowneac.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.jinqigufen.top/Article/details/gt2utomteuj.html


<!-- 参考信息 -->