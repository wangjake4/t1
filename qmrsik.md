代发 wailian999

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hysaishi.cn/Article/details/gt2urhgbswe.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gt2lprqlsqk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigufen.top/Article/details/gt2wzhwlwkn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.haohaochexian.top/Article/details/gt2cqjppxaz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfuvkbjc.html

[E15] HTML 转义 / 反转义
来源：http://dali.iojbl.cn/Article/details/gt2iquzvljn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2rfwjxspq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2ijrjeobw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jwkmuuxm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gt2hrfexibe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdcwdnsa.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iqnpdhyd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2fbogriwi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gt2jtsgdwqy.html

[E16] 数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxusszln.html

Py:   f"{1234567:,}"
来源：http://dali.hnqzz.top/Article/details/gt2rcavdilj.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2penxzuzr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shzxlz.cn/Article/details/gt2yzbxnhht.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gt2zasxdgva.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2alypwlij.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.svipenyu.cn/Article/details/gt2xkjatvbt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ybcxt.top/Article/details/gt2gjvcsmmj.html

C#:   1234567.ToString("N0")
来源：http://dali.9152youxi.cn/Article/details/gt2umnmanmd.html

[E17] 首字母大写
来源：http://dali.jinqigufen.top/Article/details/gt2bhjefbfw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2vzxbmrcx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2clqdaqnm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xinyue.icu/Article/details/gt2hgkkaqbl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gotoacloud.top/Article/details/gt2vunvxczy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gt2jjkiypop.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gt2kjffqqxw.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gt2crfxiiae.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gt2trxxosyu.html

[E18] 模板占位符替换
来源：http://dali.mhx1999.top/Article/details/gt2mbcuhzdj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenzaomai.com/Article/details/gt2qqaqvrwd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhixingplan.top/Article/details/gt2tjoxflit.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gt2bycwkpjc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gt2gycseeiz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2psrjpdgn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2qjadmwpi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ndwrmlat.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.9152youxi.cn/Article/details/gt2qhmrftlt.html

[E19] 多行文本按行拆分
来源：http://dali.sxryk.cn/Article/details/gt2szjlerdj.html

Py:   s.splitlines()
来源：http://dali.hnqzz.top/Article/details/gt2aphyxvkf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2oegtiukj.html

JS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gt2cvwapagr.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2wdrtjlwb.html

Java: s.lines().toList()
来源：http://dali.hammf.cn/Article/details/gt2mrsjxszr.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gt2nslfiegg.html

Ruby: s.lines
来源：http://dali.guannengcc.top/Article/details/gt2nsthjpwy.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gt2usagdcfz.html

[E20] 判断字符串是否为空
来源：http://dali.birdmap.top/Article/details/gt2jpzdepht.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gt2tzyqugsl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gt2svwmmgzj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gt2yuhrlxvf.html

TS:   if (s === "") {}
来源：http://dali.jyoumei.cn/Article/details/gt2vwjbnlvd.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kfzcnajd.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gt2btoshwla.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gt2vwjbyxkc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2waciozqt.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gt2swnfvwls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pycfn.com/Article/details/gt2oznapjrh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2zmkngmfp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2prtdvtuj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2wwngbtry.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2pgerfpuu.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gt2qwroeskl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gt2cdrrdhsl.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqicuhal.html

[E22] 字节长度与字符长度
来源：http://dali.zhoulong.xyz/Article/details/gt2btxzqwdh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2miqndlaa.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2bowjcuvz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2rscaetqc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2hzvivngu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2nbhrzsjq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hywenlv.cn/Article/details/gt2hwwsqofw.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2ektjylvq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gt2ihbqnnjm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2zfhgeaoc.html

F. 文件与目录
来源：http://dali.jinqigfzy.top/Article/details/gt2abrxrbes.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pwdjaixs.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2traieniq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shangyingyoupin.top/Article/details/gt2idrytpcw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sweek.top/Article/details/gt2csqsrtkq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnxiangtu.top/Article/details/gt2lipkubrx.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2qqirrlbu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2tzoykexy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gt2auoyjupv.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jytexsmb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2prcpmgjx.html

[F02] 逐行读取文件
来源：http://dali.jianghu66.top/Article/details/gt2vbucehsn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.bjfxy.top/Article/details/gt2rwmeirsp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2iuwbyxzp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2soznrumj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2rhcrtggh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gt2evmobmlx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2yafxwtbf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bxlmtvbj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2kqnzdksg.html

[F03] 写入文件（覆盖）
来源：http://dali.yonumen.top/Article/details/gt2rpfftwqn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yuanzhike.top/Article/details/gt2ixtibela.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2drtxslpx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybkauvka.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2sbuoblfz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2czdeklab.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gt2uxxepeiz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gt2vginkskf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nwbrower.top/Article/details/gt2qvgdhehr.html

[F04] 追加写入文件
来源：http://dali.bjfxy.top/Article/details/gt2kjajirbx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfcndleh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cqqwz.cn/Article/details/gt2dympilqx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2tfqiibzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2ezgawwka.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2yfscpbon.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2ojqtdemv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gt2lallzkjx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2sozgneal.html

[F05] 判断文件或目录是否存在
来源：http://dali.jlsjyb.cn/Article/details/gt2febayybm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2zglaiufy.html

PHP:  file_exists("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvswglat.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2ibobkkjr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2obbxozyl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gt2ocadnxgm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.c1oappe.top/Article/details/gt2kdjibmwu.html

Ruby: File.exist?("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2mocrtmyr.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2jtijwfwv.html

[F06] 删除文件
来源：http://dali.nanxinkj.top/Article/details/gt2jilnthjv.html

Py:   os.remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2xegpydiz.html

PHP:  unlink("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2zsfchill.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2ncttideb.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2oyzrrick.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2xeskbect.html

Go:   os.Remove("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2tdjoceio.html

Ruby: File.delete("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2lxsitwpn.html

C#:   File.Delete("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2relflgrk.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2wwezebfx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2qxepcljh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yj202588.top/Article/details/gt2fygpnjde.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jyoumei.cn/Article/details/gt2fexqycos.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tawkesbc.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zdqjudy.top/Article/details/gt2kdacqljt.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2andxkimn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hywenlv.cn/Article/details/gt2ftxhurim.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2jirvmrqu.html

[F08] 遍历目录
来源：http://dali.zhoulong.xyz/Article/details/gt2eoptwajb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2bzaatpei.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.sweek.top/Article/details/gt2eutvddcs.html

JS:   fs.readdirSync("dir")
来源：http://dali.guowangkeji.top/Article/details/gt2pdjwotqx.html

TS:   fs.readdirSync("dir")
来源：http://dali.daxiang520.top/Article/details/gt2runqdutq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdhcmfj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nxsxpehy.html

Ruby: Dir.children("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2ncgcqscb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2ilqqurov.html

[F09] 获取文件大小
来源：http://dali.yj202588.top/Article/details/gt2idbnvdhj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2cfiasrmw.html

PHP:  filesize("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gt2kuslmgfx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cqqwz.cn/Article/details/gt2ilkbwgcc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2esmtebin.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2rvycsolp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gogol.net.cn/Article/details/gt2otwimyzb.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2fshjovai.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hnxiangtu.top/Article/details/gt2daxqhywb.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.birdmap.top/Article/details/gt2vbvklpsj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2swhwxwio.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlonacao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2droqejku.html

TS:   path.extname("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2vsihutqk.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2ejlmtxjc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2inqkxbqz.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2bbivammx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2gfywjqhk.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gt2jmjwxdwo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2cvtjthmi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2nmjavyic.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2tbitntzk.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2culrjfgt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.vqdsnc.cn/Article/details/gt2sdahgyeb.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yj202588.top/Article/details/gt2oerukndv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2jahqsljx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2syqjifqm.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2xyzpxwkc.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2squmzyui.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbliavqs.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gt2dcrovzec.html

TS:   // 同上
来源：http://dali.hammf.cn/Article/details/gt2vnpabkox.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jyoumei.cn/Article/details/gt2dfwjpbyo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdhjzheg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sysykeji.top/Article/details/gt2incmihex.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hysaishi.cn/Article/details/gt2bzdyylel.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ryuashxu.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gt2xnyoiakp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2iyyjbujn.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2lismzmho.html

Py:   class User: pass
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnxlebcr.html

PHP:  class User {}
来源：http://dali.0kj1m.cn/Article/details/gt2bxfapbvs.html

JS:   class User {}
来源：http://dali.ivvv.top/Article/details/gt2xpjevrvn.html

TS:   class User { name: string = ""; }
来源：http://dali.hammf.cn/Article/details/gt2aiicvchr.html

Java: class User {}
来源：http://dali.xziqi.cn/Article/details/gt2vvqejnjz.html

Go:   type User struct { Name string }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hcxplkcz.html

Ruby: class User; end
来源：http://dali.tanke756.top/Article/details/gt2zvvwcxvi.html

C#:   class User {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2bseatgob.html

[G02] 构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2sinoeiis.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yj20258.top/Article/details/gt2avgjwrdq.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2relpjfln.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cdnleiting.top/Article/details/gt2chlorfcq.html

TS:   constructor(public name: string) {}
来源：http://dali.gogol.net.cn/Article/details/gt2pydaurno.html

Java: User(String name) { this.name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2rwyiblsu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jqgufenzy.top/Article/details/gt2ttcvnxsh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gt2fgiwlzct.html

C#:   public User(string name) { Name = name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdhbmwrm.html

[G03] 实例属性
来源：http://dali.dianchejie.cn/Article/details/gt2edwsztst.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2oyoeqgvu.html

PHP:  public string $name = "x";
来源：http://dali.pycfn.com/Article/details/gt2ygjdkswp.html

JS:   this.name = "x";
来源：http://dali.xuanzx.com/Article/details/gt2ppfvkztz.html

TS:   name: string = "x";
来源：http://dali.gotoacloud.top/Article/details/gt2ddnjcvmu.html

Java: private String name;
来源：http://dali.yuxming.cn/Article/details/gt2ackgpxbl.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yanxiufei.cn/Article/details/gt2cocnxzkg.html

Ruby: @name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2zxmngrto.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xinyue.icu/Article/details/gt2cszubeiy.html

[G04] 定义方法
来源：http://dali.smart0.xyz/Article/details/gt2akerrklg.html

Py:   def greet(self): return self.name
来源：http://dali.fengsongda.top/Article/details/gt2lebpupga.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nwbrower.top/Article/details/gt2vzlfzgwn.html

JS:   greet() { return this.name; }
来源：http://dali.havefunace.top/Article/details/gt2axjyeeni.html

TS:   greet(): string { return this.name; }
来源：http://dali.ybcxt.top/Article/details/gt2uofcuptc.html

Java: String greet() { return name; }
来源：http://dali.cheryme.top/Article/details/gt2srtyoemw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yonumen.top/Article/details/gt2rttuzbla.html

Ruby: def greet; @name; end
来源：http://dali.yueranfly.top/Article/details/gt2oafnxihw.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2yiganrpm.html

[G05] 继承
来源：http://dali.yongpay.top/Article/details/gt2slkxejmi.html

Py:   class Admin(User): pass
来源：http://dali.nanxinkj.top/Article/details/gt2qnovqifz.html

PHP:  class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gt2owgoeult.html

JS:   class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gt2vmjmjzhx.html

TS:   class Admin extends User {}
来源：http://dali.hfpthk.cn/Article/details/gt2spyhqreu.html

Java: class Admin extends User {}
来源：http://dali.cdnleiting.top/Article/details/gt2ztigubdw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2efiajqhz.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gt2uhuroqxx.html

C#:   class Admin : User {}
来源：http://dali.chenzaomai.com/Article/details/gt2adevkcsz.html

[G06] 重写方法
来源：http://dali.tanke756.top/Article/details/gt2rvqzjiff.html

Py:   def greet(self): return "admin"
来源：http://dali.jyoumei.cn/Article/details/gt2effmoymq.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2cubybznh.html

JS:   greet() { return "admin"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ossodpdy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.meibo888.top/Article/details/gt2bgevdxqn.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2crjvngxi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gt2ltcvxcou.html

Ruby: def greet; "admin"; end
来源：http://dali.birdmap.top/Article/details/gt2hczpawzb.html

C#:   public override string Greet() => "admin";
来源：http://dali.ybcxt.top/Article/details/gt2lmnrujon.html

[G07] 调用父类方法
来源：http://dali.redwolf501.top/Article/details/gt2qlwufmls.html

Py:   super().greet()
来源：http://dali.c1oappe.top/Article/details/gt2ebcnkydj.html

PHP:  parent::greet();
来源：http://dali.yj20258888.top/Article/details/gt2etzienaj.html

JS:   super.greet();
来源：http://dali.iojbl.cn/Article/details/gt2tsndaeqk.html

TS:   super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2vmdbtlqz.html

Java: super.greet();
来源：http://dali.xylfe.cn/Article/details/gt2ypwcadjp.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinqigufen.top/Article/details/gt2pobmybtz.html

Ruby: super
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlzpijfo.html

C#:   base.Greet();
来源：http://dali.yanxiufei.cn/Article/details/gt2azuucebv.html

[G08] 静态方法与属性
来源：http://dali.fengsongda.top/Article/details/gt2pwyfswmi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxjfpsyi.html

PHP:  public static function f() {}
来源：http://dali.daria6918.cn/Article/details/gt2txdkicky.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gt2rnhjlfkb.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gt2qbqtylrk.html

Java: static void f() {}
来源：http://dali.gogol.net.cn/Article/details/gt2gnxeelrw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgfzy.top/Article/details/gt2ewgnxegn.html

Ruby: def self.f; end
来源：http://dali.daria6918.cn/Article/details/gt2rtwqajee.html

C#:   public static void F() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyaoxvcq.html

[G09] 接口 / 抽象类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulcvghgt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.dashuyun.cn/Article/details/gt2aifxqjuh.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jgrmkfyr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.cashguo.top/Article/details/gt2ggwjhoth.html

TS:   interface Shape { area(): number; }
来源：http://dali.316326.xyz/Article/details/gt2vlrrauer.html

Java: interface Shape { double area(); }
来源：http://dali.svipenyu.cn/Article/details/gt2rosyooal.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojhjyhga.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.chenzaomai.com/Article/details/gt2tscaseab.html

C#:   interface IShape { double Area(); }
来源：http://dali.bjfxy.top/Article/details/gt2sbuytwit.html

[G10] 访问控制
来源：http://dali.aibaodan.cn/Article/details/gt2ygayhzkd.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.hnqzz.top/Article/details/gt2hebzzzkh.html

PHP:  public / protected / private
来源：http://dali.jinqigufen.top/Article/details/gt2kzbykiow.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gt2zxkwtegv.html

TS:   public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2mevhgseb.html

Java: public / protected / private / 默认包级
来源：http://dali.yj20258888.top/Article/details/gt2yvmefahk.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.guowangkeji.top/Article/details/gt2aelgotsf.html

Ruby: public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2tsczguyi.html

C#:   public / protected / private / internal
来源：http://dali.nanxinkj.top/Article/details/gt2asnpkxpo.html

[G11] getter / setter
来源：http://dali.birdmap.top/Article/details/gt2zsulynqo.html

Py:   @property 与 @x.setter
来源：http://dali.dashuyun.cn/Article/details/gt2zsijcolf.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.fengsongda.top/Article/details/gt2xakzvsyl.html

JS:   get name() { return this._name; }
来源：http://dali.dianchejie.cn/Article/details/gt2ngicimop.html

TS:   get name(): string { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gt2bzrfdwkd.html

Java: public String getName() { return name; }
来源：http://dali.daxiang520.top/Article/details/gt2nnpokdje.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2menrqumi.html

Ruby: attr_accessor :name
来源：http://dali.gzhubu.top/Article/details/gt2whojovfr.html

C#:   public string Name { get; set; }
来源：http://dali.vqdsnc.cn/Article/details/gt2woytkhvr.html

[G12] 对象转字符串
来源：http://dali.ydzc1.top/Article/details/gt2tbodbtkq.html

Py:   def __str__(self): return self.name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvxzhzoa.html

PHP:  public function __toString(): string { return $this->name; }
来源：http://dali.aibaodan.cn/Article/details/gt2ozhkeema.html

JS:   toString() { return this.name; }
来源：http://dali.9152youxi.cn/Article/details/gt2wduiwtbh.html

TS:   toString(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2nswiqemj.html

Java: @Override public String toString() { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlpyvbcr.html

Go:   func (u User) String() string { return u.Name }
来源：http://dali.zhongyouzk.top/Article/details/gt2dzcpsilq.html

Ruby: def to_s; @name; end
来源：http://dali.vqdsnc.cn/Article/details/gt2kuxfgrzu.html

C#:   public override string ToString() => Name;
来源：http://dali.shzxlz.cn/Article/details/gt2wemensym.html

[G13] 判断对象类型
来源：http://dali.mhx1999.top/Article/details/gt2qwmhejtk.html


<!-- 参考信息 -->