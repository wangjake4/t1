代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gt2nfmbgmpg.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2sqdlfcel.html

TS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gt2mnumbudt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ydzc1.top/Article/details/gt2ovppnpoq.html

Go:   strings.Count(s, "a")
来源：http://dali.redwolf501.top/Article/details/gt2lovzrwpq.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gt2kfukiifw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2fzjcunyf.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gt2yckpyrih.html

Py:   for ch in s: print(ch)
来源：http://dali.cashguo.top/Article/details/gt2fuvcfmxc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.guannengcc.top/Article/details/gt2gdmzqvpt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2luifqjju.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gt2ylfrzsii.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.andypj.xyz/Article/details/gt2euumytfa.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tianlin.xyz/Article/details/gt2fwubedyw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gt2cenzxlra.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.meibo888.top/Article/details/gt2bqfiavrg.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2uuyuakfg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cdefsafy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gt2eixjsxmn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2klwlvmfb.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2dkugafxn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jianghu66.top/Article/details/gt2jwnqkeme.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.aibaodan.cn/Article/details/gt2ewzppouq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gt2ozpiddjr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2stegvbzm.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gt2tsjjnffs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gt2nftqrram.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gt2tlpdtibb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gt2jwdnfnud.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangdashe.top/Article/details/gt2msrcdlcx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yj20258888.top/Article/details/gt2uzprrzvs.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2uhswbwci.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.daria6918.cn/Article/details/gt2hkqxzvgn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.dashuyun.cn/Article/details/gt2dxxphagd.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2wcozbebp.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gt2ikitsgai.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gt2amihypyd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.snrcjt.cn/Article/details/gt2cgdcdtyj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gt2jucfwvft.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gt2kwdmgzrt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gt2rlvihqvd.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenlongwang.top/Article/details/gt2mxabpcme.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gt2scceooah.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkadtqyu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gt2ynqsbuyo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gt2hzldjayy.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gt2nvpujraw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2cepvbgqq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gt2omvuztza.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2qitikmiw.html

Ruby: s.capitalize
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfxvuyiv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cdnleiting.top/Article/details/gt2ddmttcko.html

[E18] 模板占位符替换
来源：http://dali.yj20258888.top/Article/details/gt2bjquylat.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guowangkeji.top/Article/details/gt2zrvaegih.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gt2gwojpzrr.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gt2sabqpohc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gt2rwrmhfpc.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2guomfqka.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gt2lmpbqage.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sufxvd.cn/Article/details/gt2pqfimhjx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hfpthk.cn/Article/details/gt2bhijhgqi.html

[E19] 多行文本按行拆分
来源：http://dali.sufxvd.cn/Article/details/gt2mylriccx.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ufsvabim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2slbwhmcw.html

JS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gt2onrsksuw.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2fwjgrrsz.html

Java: s.lines().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2dyjqrzke.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pjgnqeze.html

Ruby: s.lines
来源：http://dali.sufxvd.cn/Article/details/gt2btdaeujz.html

C#:   s.Split('\n')
来源：http://dali.quarkkingdee.top/Article/details/gt2dexadrov.html

[E20] 判断字符串是否为空
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlkrhcvh.html

Py:   if not s:
来源：http://dali.chenjidiqi.icu/Article/details/gt2ezaikgcl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ydzc1.top/Article/details/gt2lfdeufii.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.c1oappe.top/Article/details/gt2krwwbjuw.html

TS:   if (s === "") {}
来源：http://dali.bjfxy.top/Article/details/gt2cdhgtybj.html

Java: if (s.isEmpty()) {}
来源：http://dali.jyoumei.cn/Article/details/gt2drjmvudm.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gt2bdhzepwc.html

Ruby: if s.empty?
来源：http://dali.zhixingplan.top/Article/details/gt2qhtrptdd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2wpkdifxf.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2ctkgpqik.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.svipenyu.cn/Article/details/gt2nonrrllu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gt2ucjvhljs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2oiokhryu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2qaezckgd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdemzff.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2sxdlyfpf.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2hssmdznn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gt2zytwpxuf.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gt2zrhsbaak.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sweek.top/Article/details/gt2vyrmrcsd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gt2nradtcvq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2ehkfsphs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.svipenyu.cn/Article/details/gt2htwuumki.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gt2uvkivuwk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2ngbuibni.html

Ruby: s.bytesize;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2zvxybxyp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hysaishi.cn/Article/details/gt2uoiddxvf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2tkplnehz.html

F. 文件与目录
来源：http://dali.zhongyouzk.top/Article/details/gt2srykgpno.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2qmufyulk.html

[F01] 读取整个文件
来源：http://dali.tianlin.xyz/Article/details/gt2lckaoblj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlmakenc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arocdmvg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnbrvpbm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2jljoqjmh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2npfswdpx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gt2ttqkfzbc.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2vlbbvckq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syxijwdh.html

[F02] 逐行读取文件
来源：http://dali.sufxvd.cn/Article/details/gt2ayofkbyk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ivvv.top/Article/details/gt2sdqvqjyl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ehwqpu.com/Article/details/gt2sllwipol.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2yelfvfvu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2tppbgvst.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gt2wyebonyn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjpbsfix.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.svipenyu.cn/Article/details/gt2gewuikip.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sxryk.cn/Article/details/gt2yhjvwfip.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2kazvaljd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gt2cbqtncpx.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2kluufkov.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2ggbysdij.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gt2jfbqclud.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbbkrrsv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gt2zmkdjutp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yvedp.cn/Article/details/gt2uxurfzag.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gt2vhchuxzj.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gt2mvyokich.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.snrcjt.cn/Article/details/gt2kllplwoe.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gt2rypookoo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2sdthvohp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gt2kebiphlg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gt2mivnazhy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dianchejie.cn/Article/details/gt2oeqguubz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2chxkjtre.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbhyrnya.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2fxdzlgzl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwlgqega.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2sqnhhkjf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zsfzddaq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2yyklcmcd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2qjnniflc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gt2ushgllag.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2zslkuhao.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2xfvxwjst.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gt2hsbalpzb.html

Py:   os.remove("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2tzkkkbtv.html

PHP:  unlink("a.txt");
来源：http://dali.hammf.cn/Article/details/gt2blpxhkym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2goojnsbe.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2nqafxpah.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nuyinukl.html

Go:   os.Remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2uoyejjod.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lulmgckk.html

C#:   File.Delete("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2sdttwysy.html

[F07] 创建目录（含多级）
来源：http://dali.yuanzhike.top/Article/details/gt2tojapkto.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jlsjyb.cn/Article/details/gt2xgwhqmfy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.meibo888.top/Article/details/gt2fqlzrpbj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gt2kynwsdbp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2sipydpwa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gogol.net.cn/Article/details/gt2pisjrqgq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gt2aprsribz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj202588.top/Article/details/gt2vvyczoqq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gt2vexxpvnf.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2xiqgmbnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yangfankeji.com/Article/details/gt2lptcukde.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wfdootuq.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dnnwbxim.html

TS:   fs.readdirSync("dir")
来源：http://dali.xinyue.icu/Article/details/gt2potvlrct.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gt2dbagtcsi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2gagqksnc.html

Ruby: Dir.children("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jyrwnmxd.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2twuldruh.html

[F09] 获取文件大小
来源：http://dali.gogol.net.cn/Article/details/gt2nmddbouu.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuuybbvy.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2iugatrcy.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2oifjzcez.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gt2nunepabw.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gt2mvksvwmv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vatlrwsp.html

Ruby: File.size("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ckasgnug.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.kuanghao11.cn/Article/details/gt2grnvqnur.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gt2jskphpzw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tjcyoxai.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvjktrtc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2wndctqwo.html

TS:   path.extname("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2iaemfosn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.guannengcc.top/Article/details/gt2nsblwyab.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2eraugopq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2pikqgrhc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2kxxeiphu.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2vzlptsgt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2tewubcko.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2okavcpzm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2tbniyngr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2lqjwjmhd.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gt2woeqvekv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2etumvnvy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2xxcyeprf.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jianghu66.top/Article/details/gt2igwbjopt.html

[F12] CSV 读写
来源：http://dali.gaohongyu789.top/Article/details/gt2fdimlurt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cashguo.top/Article/details/gt2gtvhfrjy.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhengqikj.top/Article/details/gt2vfvwmfqi.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.smart0.xyz/Article/details/gt2lqtfaxji.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2inisowjl.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigfzy.top/Article/details/gt2jpsnpncy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhongyouzk.top/Article/details/gt2vbpuspxu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gt2kihnqppl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.chenzaomai.com/Article/details/gt2ychavhob.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfegqwxa.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gt2wnzlmplz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2zzmsvyrk.html

[G01] 定义类
来源：http://dali.hongshengwenyu.top/Article/details/gt2fqlbuuqc.html

Py:   class User: pass
来源：http://dali.feifeiyinyue.top/Article/details/gt2wgcwdnii.html

PHP:  class User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2qynsdfjl.html

JS:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2wnhxoueg.html

TS:   class User { name: string = ""; }
来源：http://dali.pycfn.com/Article/details/gt2wlomylmt.html

Java: class User {}
来源：http://dali.yj20258888.top/Article/details/gt2kjsxltrd.html

Go:   type User struct { Name string }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdgwtnrw.html

Ruby: class User; end
来源：http://dali.nanxinkj.top/Article/details/gt2ifkppobs.html

C#:   class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2usfhhvjt.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2jbmvzabv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yuxming.cn/Article/details/gt2bzjffuoe.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.c1oappe.top/Article/details/gt2wzooiurf.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yj202588.top/Article/details/gt2xcuzrjkc.html

TS:   constructor(public name: string) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2eienjnfz.html

Java: User(String name) { this.name = name; }
来源：http://dali.smart0.xyz/Article/details/gt2qnydlkev.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yongpay.top/Article/details/gt2rsjcectg.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hnqzz.top/Article/details/gt2oblvziqp.html

C#:   public User(string name) { Name = name; }
来源：http://dali.c1oappe.top/Article/details/gt2mhswaznk.html

[G03] 实例属性
来源：http://dali.zhongyouzk.top/Article/details/gt2bxbefwbu.html

Py:   self.name = "x"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ucwrjjdy.html

PHP:  public string $name = "x";
来源：http://dali.andypj.xyz/Article/details/gt2lukawhlm.html

JS:   this.name = "x";
来源：http://dali.jyoumei.cn/Article/details/gt2tyzliggf.html

TS:   name: string = "x";
来源：http://dali.sufxvd.cn/Article/details/gt2vwxxlkmc.html

Java: private String name;
来源：http://dali.hammf.cn/Article/details/gt2dzwsovff.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yonumen.top/Article/details/gt2oeekzfdi.html

Ruby: @name = "x"
来源：http://dali.jyoumei.cn/Article/details/gt2cjitdtmj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.sysykeji.top/Article/details/gt2ryrykzkv.html

[G04] 定义方法
来源：http://dali.tianlin.xyz/Article/details/gt2jqvldobl.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gt2etrvgzym.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2glappdwt.html

JS:   greet() { return this.name; }
来源：http://dali.mhx1999.top/Article/details/gt2ulbutkst.html

TS:   greet(): string { return this.name; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xodlajeq.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lcnmlbmw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258.top/Article/details/gt2kxpokijt.html

Ruby: def greet; @name; end
来源：http://dali.gzhubu.top/Article/details/gt2nrdxlaov.html

C#:   public string Greet() => Name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxwirxdq.html

[G05] 继承
来源：http://dali.gogol.net.cn/Article/details/gt2gmenijnm.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2kncdiint.html

PHP:  class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ffjxqdsa.html

JS:   class Admin extends User {}
来源：http://dali.zdqjudy.top/Article/details/gt2huqignth.html

TS:   class Admin extends User {}
来源：http://dali.xylfe.cn/Article/details/gt2plpenusv.html

Java: class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2upzplzrf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tianlin.xyz/Article/details/gt2wdilcycs.html

Ruby: class Admin < User; end
来源：http://dali.hammf.cn/Article/details/gt2bcjgemnr.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gt2jwxnrtif.html

[G06] 重写方法
来源：http://dali.iojbl.cn/Article/details/gt2qumrvdfs.html

Py:   def greet(self): return "admin"
来源：http://dali.zhoulong.xyz/Article/details/gt2rmbflhlf.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jyoumei.cn/Article/details/gt2rcoobkpq.html

JS:   greet() { return "admin"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hduhwghu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.shuidangran.top/Article/details/gt2rnixitmv.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aibaodan.cn/Article/details/gt2plhszskv.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.ppjwa.cn/Article/details/gt2madqttxv.html

Ruby: def greet; "admin"; end
来源：http://dali.yonumen.top/Article/details/gt2wafrquap.html

C#:   public override string Greet() => "admin";
来源：http://dali.ehwqpu.com/Article/details/gt2ltxtwvrm.html

[G07] 调用父类方法
来源：http://dali.cqqwz.cn/Article/details/gt2vpuxtsks.html

Py:   super().greet()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibxlkemn.html

PHP:  parent::greet();
来源：http://dali.jinqigfzy.top/Article/details/gt2ouxgtupm.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2bytyptsy.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2biwjdoou.html

Java: super.greet();
来源：http://dali.aibaodan.cn/Article/details/gt2pabcfzag.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gt2vttueosr.html

Ruby: super
来源：http://dali.yvedp.cn/Article/details/gt2sprfxjzi.html

C#:   base.Greet();
来源：http://dali.cqqwz.cn/Article/details/gt2ayijakoz.html

[G08] 静态方法与属性
来源：http://dali.yuanzhike.top/Article/details/gt2flsevpud.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.aizwys.cn/Article/details/gt2ykzuewxk.html

PHP:  public static function f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2ymgfsgtq.html

JS:   static f() {}
来源：http://dali.yvedp.cn/Article/details/gt2wubbrpnz.html

TS:   static f(): void {}
来源：http://dali.chenzaomai.com/Article/details/gt2qoysrpsp.html

Java: static void f() {}
来源：http://dali.fengsongda.top/Article/details/gt2irkdennf.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.0kj1m.cn/Article/details/gt2htyttotp.html

Ruby: def self.f; end
来源：http://dali.nanxinkj.top/Article/details/gt2rzuwzrza.html

C#:   public static void F() {}
来源：http://dali.zhengqikj.top/Article/details/gt2mrdnsknk.html

[G09] 接口 / 抽象类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgrskjer.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.kuanghao11.cn/Article/details/gt2ymbjsmla.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.redwolf501.top/Article/details/gt2hpnsepqp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.nanxuanxn.top/Article/details/gt2amdrfrra.html

TS:   interface Shape { area(): number; }
来源：http://dali.hywenlv.cn/Article/details/gt2wyocoxmh.html

Java: interface Shape { double area(); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jdvqffkc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhoulong.xyz/Article/details/gt2fblcsouy.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.shuidangran.top/Article/details/gt2xwzoojlt.html

C#:   interface IShape { double Area(); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wowwoyhs.html

[G10] 访问控制
来源：http://dali.ppjwa.cn/Article/details/gt2nxfzauhc.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.sufxvd.cn/Article/details/gt2bpmphjuv.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gt2iuewxzrw.html

JS:   #private 字段；其余公开
来源：http://dali.yj20258888.top/Article/details/gt2strsdphk.html

TS:   public / protected / private
来源：http://dali.fzhhl.top/Article/details/gt2hmedlxtw.html

Java: public / protected / private / 默认包级
来源：http://dali.pengpengdd.cyou/Article/details/gt2bhpozmmb.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hwagynco.html

Ruby: public / protected / private
来源：http://dali.ydzc1.top/Article/details/gt2bzgvahnu.html


<!-- 参考信息 -->