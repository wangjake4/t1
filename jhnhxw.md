代发 wailian999

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rocewdhw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2hzmmiycw.html

[E16] 数字千分位
来源：http://dali.sweek.top/Article/details/gt2fgkofocp.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gt2gaxpdccx.html

PHP:  number_format(1234567);
来源：http://dali.zhoulong.xyz/Article/details/gt2vchemivu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gt2bkrjmdro.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fooxqtwr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yongpay.top/Article/details/gt2kzefkyls.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2ywqxmrlh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gt2ivgwkgyu.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gt2swnusvjo.html

[E17] 首字母大写
来源：http://dali.zhengqikj.top/Article/details/gt2ariclgkm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtbjquyw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxvevjyo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gt2vbtccwpd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2usknuwrb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xylfe.cn/Article/details/gt2kctrvmlw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gt2puwjxlxo.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gt2erdaeaoa.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gogol.net.cn/Article/details/gt2ocquycxl.html

[E18] 模板占位符替换
来源：http://dali.c1oappe.top/Article/details/gt2ykkmqyba.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gzhubu.top/Article/details/gt2ofjvmnov.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yangfankeji.com/Article/details/gt2theqgebi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xylfe.cn/Article/details/gt2xljekyow.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ehwqpu.com/Article/details/gt2elaoknwz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gt2pinviwph.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gt2xyrdniry.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gt2gdukifmg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gt2zejxpzqf.html

[E19] 多行文本按行拆分
来源：http://dali.tanke756.top/Article/details/gt2muujqppr.html

Py:   s.splitlines()
来源：http://dali.yvedp.cn/Article/details/gt2jdejxwkx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksvgfohw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jyoumei.cn/Article/details/gt2vddryigp.html

TS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gt2wrgjdpyq.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2cblkcheh.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2pnyputxb.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjyfxynh.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gt2iunyhowq.html

[E20] 判断字符串是否为空
来源：http://dali.jlsjyb.cn/Article/details/gt2nhtqacrc.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gt2yaacpjhm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.guannengcc.top/Article/details/gt2sepbtlph.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jyoumei.cn/Article/details/gt2bcupcpcm.html

TS:   if (s === "") {}
来源：http://dali.jiagoushi.top/Article/details/gt2gjlaylne.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zakhhets.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gt2sbynffok.html

Ruby: if s.empty?
来源：http://dali.guannengcc.top/Article/details/gt2iaoivqxq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yonumen.top/Article/details/gt2nfaffgls.html

[E21] 超长截断加省略号
来源：http://dali.ydzc1.top/Article/details/gt2hjpbmfqh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.andypj.xyz/Article/details/gt2kvrytyzv.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2laekjpfw.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2vjbqeybp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2xxfjukwr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ycphowcq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daria6918.cn/Article/details/gt2qhhziekt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gt2rbktbedc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2zmvlcwvf.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258888.top/Article/details/gt2wigwfqnp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gt2psmzrzyb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2dwixbtal.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gt2vdmdpghe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2munqlnmi.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.nanxuanxn.top/Article/details/gt2gnqdlwdo.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2aqjpimfo.html

Ruby: s.bytesize;  s.length
来源：http://dali.cheryme.top/Article/details/gt2keexzuvf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2ownzggnw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gt2eayqzhwb.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdajffcr.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2rinpmgtg.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gt2nlttrcyj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gt2msjeiynq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gt2nwofpghl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gt2eziplkxt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gt2exabbpup.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gt2dojbwcop.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gt2ddrnouog.html

Ruby: File.read("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2slddkbpz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.birdmap.top/Article/details/gt2bmcrjsas.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gt2gfnhcdxx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2ncvpsazj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2qfryvdmo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jiagoushi.top/Article/details/gt2wuhockuk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2szvyrzuu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gt2tgfkjopl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xziqi.cn/Article/details/gt2hanbexfb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gt2zzgqvqgj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxuanxn.top/Article/details/gt2jlgeirod.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2elnzxnby.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2ophzhngv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gt2ktrsqdjg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gt2xhtbhpua.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2hojvfeor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gt2ozzvyolu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2jjclfxhg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gt2kdzqzeqq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2rkdpumyy.html

[F04] 追加写入文件
来源：http://dali.cucudq.cn/Article/details/gt2rkkqqylf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gt2ybvpzday.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jiagoushi.top/Article/details/gt2epzmbstu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2mfcjdvoy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2rfdbepwa.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cdnleiting.top/Article/details/gt2gfbixomq.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2pvwzyllc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gt2egirectr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258888.top/Article/details/gt2vrrmgfum.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2cvnnomou.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenjidiqi.icu/Article/details/gt2olxajywe.html

PHP:  file_exists("a.txt");
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqqkgvvd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2jrglgivh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pejtxsxy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.meibo888.top/Article/details/gt2lumaxxgr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ydzc1.top/Article/details/gt2rqkxepjj.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2yhdvcsxd.html

C#:   File.Exists("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2rxkpmxms.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2evhibufb.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2bbsmlbgq.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2iinydvuu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkhrjrck.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrdohzhg.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2cgpewvzn.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dwepmrac.html

Ruby: File.delete("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2wpesprcl.html

C#:   File.Delete("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gt2sqoqvmdt.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gt2hxqcuryp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gt2aoykgpvq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvcycaqx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjqivjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2xnkydkqk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2hmbcwtiq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gt2ovqbdznl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvxeqgnm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gt2tgbddxth.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gt2pjokmles.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gt2tyjbanfj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gt2kgmenacl.html

JS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2kkdplfvr.html

TS:   fs.readdirSync("dir")
来源：http://dali.yonumen.top/Article/details/gt2cchbhsdt.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2cmdwpyvv.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.vqdsnc.cn/Article/details/gt2flzeedbh.html

Ruby: Dir.children("dir")
来源：http://dali.jianghu66.top/Article/details/gt2fhooydip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.andypj.xyz/Article/details/gt2kuadqgsm.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wbzrydpa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pwrgumfd.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2yifjnnow.html

JS:   fs.statSync("a.txt").size
来源：http://dali.daria6918.cn/Article/details/gt2ciqanule.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gt2dvjicesq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2cdkuumgm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhixingplan.top/Article/details/gt2avhfmaru.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnprbnnk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ymdqkhty.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.sxryk.cn/Article/details/gt2xytuilme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2hwiqfmps.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hammf.cn/Article/details/gt2azyjyvjj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nshxhoju.html

TS:   path.extname("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2kxlmevbd.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ybcxt.top/Article/details/gt2ieyasvbq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2tzcxopoj.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2aczqcpxu.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bqdozbpi.html

[F11] 复制与移动文件
来源：http://dali.aibaodan.cn/Article/details/gt2enprgigy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2fqwklpuj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpqzgqqv.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2mafqxsmx.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2qrattbed.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.gogol.net.cn/Article/details/gt2btevjofr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.haohaochexian.top/Article/details/gt2jdrrulgb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ddhgfdzu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2xrdmatbj.html

[F12] CSV 读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2dypuepza.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sujetdql.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj202588.top/Article/details/gt2gzgluygk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gt2lcegaluv.html

TS:   // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2ouelntge.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cdnleiting.top/Article/details/gt2jadyxcay.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinqigfzy.top/Article/details/gt2uklrbqat.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2cvpducnw.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.c1oappe.top/Article/details/gt2ghbvwvor.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2kvmmttsl.html

G. 面向对象
来源：http://dali.hfpthk.cn/Article/details/gt2fzzgpnkq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2wkmebsyb.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2hchwtghj.html

Py:   class User: pass
来源：http://dali.xuetiantiany.cn/Article/details/gt2tsfeqvne.html

PHP:  class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2pkjcocgp.html

JS:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tqyfzxky.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gt2xcdadold.html

Java: class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2rfdssvzk.html

Go:   type User struct { Name string }
来源：http://dali.ybcxt.top/Article/details/gt2txngtkos.html

Ruby: class User; end
来源：http://dali.hysaishi.cn/Article/details/gt2qtcncyir.html

C#:   class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2xygncrmh.html

[G02] 构造函数
来源：http://dali.yongpay.top/Article/details/gt2tsbrhlyj.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gt2azpdrwag.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.cqqwz.cn/Article/details/gt2uogeengn.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gt2kribzmkz.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2injynmxp.html

Java: User(String name) { this.name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2ylwzskny.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ybcxt.top/Article/details/gt2xxksagwd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.0kj1m.cn/Article/details/gt2dcdpmzhf.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jiagoushi.top/Article/details/gt2xoyydxtu.html

[G03] 实例属性
来源：http://dali.yvedp.cn/Article/details/gt2igxcqbqi.html

Py:   self.name = "x"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ioalvvdq.html

PHP:  public string $name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dhmitpby.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2mtneynui.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2cwhwzemy.html

Java: private String name;
来源：http://dali.xinyue.icu/Article/details/gt2ehlepokt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenlongwang.top/Article/details/gt2evgbqflk.html

Ruby: @name = "x"
来源：http://dali.aizwys.cn/Article/details/gt2aauzliex.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.meibo888.top/Article/details/gt2xdwdivds.html

[G04] 定义方法
来源：http://dali.andypj.xyz/Article/details/gt2spiavbvl.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2blldleub.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2twskospl.html

JS:   greet() { return this.name; }
来源：http://dali.haohaochexian.top/Article/details/gt2dpnyyzsq.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2gaoqtlph.html

Java: String greet() { return name; }
来源：http://dali.yj202588.top/Article/details/gt2bldmdbij.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2vmokqlme.html

Ruby: def greet; @name; end
来源：http://dali.shzxlz.cn/Article/details/gt2tpjmizup.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gt2alychczb.html

[G05] 继承
来源：http://dali.ivvv.top/Article/details/gt2nrzmstit.html

Py:   class Admin(User): pass
来源：http://dali.shzxlz.cn/Article/details/gt2ujmwsnoe.html

PHP:  class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gt2ntytrfus.html

JS:   class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhbbovxz.html

TS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2zgsohxwz.html

Java: class Admin extends User {}
来源：http://dali.cqqwz.cn/Article/details/gt2ycctfggp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yueranfly.top/Article/details/gt2ilnwnznw.html

Ruby: class Admin < User; end
来源：http://dali.hnqzz.top/Article/details/gt2uixwcipt.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gt2uejoazwk.html

[G06] 重写方法
来源：http://dali.yuanzhike.top/Article/details/gt2bixtkqzd.html

Py:   def greet(self): return "admin"
来源：http://dali.hnqzz.top/Article/details/gt2snismqko.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gt2ajjxzzlt.html

JS:   greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2afgbssdn.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vkmeehgc.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.daxiang520.top/Article/details/gt2dvfpnwew.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hfpthk.cn/Article/details/gt2sdwqocjj.html

Ruby: def greet; "admin"; end
来源：http://dali.zhoulong.xyz/Article/details/gt2wfmjoiut.html

C#:   public override string Greet() => "admin";
来源：http://dali.sufxvd.cn/Article/details/gt2rczszcmi.html

[G07] 调用父类方法
来源：http://dali.bjfxy.top/Article/details/gt2jqbpqhjz.html

Py:   super().greet()
来源：http://dali.dashuyun.cn/Article/details/gt2jlvgjhtm.html

PHP:  parent::greet();
来源：http://dali.daria6918.cn/Article/details/gt2kygwqjrf.html

JS:   super.greet();
来源：http://dali.jyoumei.cn/Article/details/gt2kdsaaevk.html

TS:   super.greet();
来源：http://dali.havefunace.top/Article/details/gt2vfilnjvs.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2gjdsldwf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.redwolf501.top/Article/details/gt2rvqfstyv.html

Ruby: super
来源：http://dali.havefunace.top/Article/details/gt2qyusegcw.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbcbodnv.html

[G08] 静态方法与属性
来源：http://dali.gotoacloud.top/Article/details/gt2qvrysvwb.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.zdqjudy.top/Article/details/gt2irlywypw.html

PHP:  public static function f() {}
来源：http://dali.jlsjyb.cn/Article/details/gt2mefvkkut.html

JS:   static f() {}
来源：http://dali.snrcjt.cn/Article/details/gt2mzsnikqj.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gt2xysxppsv.html

Java: static void f() {}
来源：http://dali.andypj.xyz/Article/details/gt2ifpjnhcd.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinqigufen.top/Article/details/gt2pwblhdrv.html

Ruby: def self.f; end
来源：http://dali.andypj.xyz/Article/details/gt2pjzqpugx.html

C#:   public static void F() {}
来源：http://dali.quarkkingdee.top/Article/details/gt2iyzpvmdb.html

[G09] 接口 / 抽象类
来源：http://dali.feifeiyinyue.top/Article/details/gt2kyiosglt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.hnxiangtu.top/Article/details/gt2kmszstia.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yangfankeji.com/Article/details/gt2nvavjxbw.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.gaohongyu789.top/Article/details/gt2qmwrnmgu.html

TS:   interface Shape { area(): number; }
来源：http://dali.yj20258.top/Article/details/gt2tikkwozy.html

Java: interface Shape { double area(); }
来源：http://dali.aizwys.cn/Article/details/gt2niorsfmo.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.0kj1m.cn/Article/details/gt2ctxkytdo.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.mhx1999.top/Article/details/gt2ryrjairo.html

C#:   interface IShape { double Area(); }
来源：http://dali.zhoulong.xyz/Article/details/gt2npuubvat.html

[G10] 访问控制
来源：http://dali.cdnleiting.top/Article/details/gt2axsgxzhe.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hywenlv.cn/Article/details/gt2ihxcylvs.html

PHP:  public / protected / private
来源：http://dali.yj20258.top/Article/details/gt2xgutdkgu.html

JS:   #private 字段；其余公开
来源：http://dali.wangshuangyany.cn/Article/details/gt2svrxjplf.html

TS:   public / protected / private
来源：http://dali.mhx1999.top/Article/details/gt2xyckklhi.html

Java: public / protected / private / 默认包级
来源：http://dali.hnqzz.top/Article/details/gt2efdrinys.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.dashuyun.cn/Article/details/gt2uwvbsitw.html

Ruby: public / protected / private
来源：http://dali.yuxming.cn/Article/details/gt2bswvwwtm.html

C#:   public / protected / private / internal
来源：http://dali.yj20258888.top/Article/details/gt2rjibjeoy.html

[G11] getter / setter
来源：http://dali.jyoumei.cn/Article/details/gt2whznpfkk.html

Py:   @property 与 @x.setter
来源：http://dali.ivvv.top/Article/details/gt2prywancp.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lfxsaghw.html

JS:   get name() { return this._name; }
来源：http://dali.yueranfly.top/Article/details/gt2xymhxkcg.html

TS:   get name(): string { return this._name; }
来源：http://dali.zhengqikj.top/Article/details/gt2subclihr.html

Java: public String getName() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qqcdfxpl.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.pycfn.com/Article/details/gt2qndvyysp.html

Ruby: attr_accessor :name
来源：http://dali.hysaishi.cn/Article/details/gt2hazideuv.html

C#:   public string Name { get; set; }
来源：http://dali.chenlongwang.top/Article/details/gt2brhpzjtp.html

[G12] 对象转字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2ukvwjayb.html

Py:   def __str__(self): return self.name
来源：http://dali.hnxiangtu.top/Article/details/gt2flxllkvg.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.yuanzhike.top/Article/details/gt2errsckxz.html

JS:   toString() { return this.name; }
来源：http://dali.meibo888.top/Article/details/gt2oqzbhrin.html

TS:   toString(): string { return this.name; }
来源：http://dali.pycfn.com/Article/details/gt2ibearutx.html

Java: @Override public String toString() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2fdnixkrr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gt2ubwhifne.html

Ruby: def to_s; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2swhmnkog.html

C#:   public override string ToString() => Name;
来源：http://dali.hnqzz.top/Article/details/gt2xlmbwzbj.html

[G13] 判断对象类型
来源：http://dali.tian-w.cn/Article/details/gt2tvuxaobn.html

Py:   isinstance(u, User)
来源：http://dali.meibo888.top/Article/details/gt2crqmvwoy.html

PHP:  $u instanceof User
来源：http://dali.fzhhl.top/Article/details/gt2acajpbog.html

JS:   u instanceof User
来源：http://dali.yj20258.top/Article/details/gt2idbznkjt.html

TS:   u instanceof User
来源：http://dali.hongshengwenyu.top/Article/details/gt2hrepmzgn.html

Java: u instanceof User
来源：http://dali.yj202588.top/Article/details/gt2fxtcdsvs.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.shangyingyoupin.top/Article/details/gt2curlclkp.html

Ruby: u.is_a?(User)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oxooumpn.html

C#:   u is User
来源：http://dali.wangshuangyany.cn/Article/details/gt2auxgstdw.html

[G14] 数据类 / record
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfnqjefl.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.daria6918.cn/Article/details/gt2cpajdslb.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bpqqmgqf.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.zhixingplan.top/Article/details/gt2roucfacg.html


<!-- 参考信息 -->