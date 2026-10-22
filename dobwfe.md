代发 wailian999

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vlszsvmb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gt2mnlzgmmz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gt2drxitjwu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2orlcvxgo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ppjwa.cn/Article/details/gt2touzlfck.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2whdceedq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xuetiantiany.cn/Article/details/gt2xmeokwca.html

JS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2kodwcclx.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gt2qbpvplsh.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gt2htvohsue.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gt2kfmocohp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2zhjvaaeg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2wtgxsitx.html

[E11] 反转字符串
来源：http://dali.yvedp.cn/Article/details/gt2krhexyke.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2negjbtre.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gt2qzswmyam.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggibnfgi.html

TS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2chwqdvir.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gt2zrpddcjf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctkplrgz.html

Ruby: s.reverse
来源：http://dali.chenlongwang.top/Article/details/gt2kybtuniw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cashguo.top/Article/details/gt2cpqvumor.html

[E12] 统计某字符出现次数
来源：http://dali.yvedp.cn/Article/details/gt2xaxqzkmy.html

Py:   s.count("a")
来源：http://dali.sweek.top/Article/details/gt2efpfjmkq.html

PHP:  substr_count($s, "a");
来源：http://dali.yuanzhike.top/Article/details/gt2httqyxji.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gt2qxhffpkd.html

TS:   s.split("a").length - 1
来源：http://dali.haohaochexian.top/Article/details/gt2ivoemxyt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnflftj.html

Go:   strings.Count(s, "a")
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxxwctp.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2zvsejvdy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.iojbl.cn/Article/details/gt2fkqdxwqs.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2zxuptrvi.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2klzpsptd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyunhbqc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gt2mbprisrm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2eqibtnaz.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gngrmsmn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2pmbziqnc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cjytsozv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ecvnxifv.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gt2ubugmofd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yueranfly.top/Article/details/gt2julvsfoj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxfgtflg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gt2zftifrdw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.redwolf501.top/Article/details/gt2owktvvru.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xinyue.icu/Article/details/gt2vkhztzup.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yangfankeji.com/Article/details/gt2lrqhotbz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sysykeji.top/Article/details/gt2flsxwcii.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gt2rdfotjps.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gt2nrfrefrd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2tqdfbdzv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.wangdashe.top/Article/details/gt2ewnhkani.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gt2umhrfdep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgfzy.top/Article/details/gt2giiforwb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gt2sqrdhcah.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yuanzhike.top/Article/details/gt2onqoqpfm.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.iojbl.cn/Article/details/gt2fypggelk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ybcxt.top/Article/details/gt2adxgvxid.html

[E16] 数字千分位
来源：http://dali.tanke756.top/Article/details/gt2terqamaq.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gt2flmblpkf.html

PHP:  number_format(1234567);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ykfqoamv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2ebopntci.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.bjfxy.top/Article/details/gt2ynphwddn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.nwbrower.top/Article/details/gt2vpstszeq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sfhmcygg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2rqrqkjyv.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gt2jnxpbety.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gt2muyphvpg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gt2qmkgdkdf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.bjfxy.top/Article/details/gt2qhlgkckk.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gt2piybpnqw.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgfzy.top/Article/details/gt2xkewipnp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shzxlz.cn/Article/details/gt2oqnjgtej.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2dzzbtlyk.html

Ruby: s.capitalize
来源：http://dali.andypj.xyz/Article/details/gt2vbvyfxmr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.meibo888.top/Article/details/gt2kwnqdmbk.html

[E18] 模板占位符替换
来源：http://dali.zhengqikj.top/Article/details/gt2excrlhfp.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.andypj.xyz/Article/details/gt2flovdtoc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aimilwmq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gt2djmyvrzq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gt2dmoptber.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2pshhpitb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ivvv.top/Article/details/gt2bchurggw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gzhubu.top/Article/details/gt2ncnwobbu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gt2nlwrdvmi.html

[E19] 多行文本按行拆分
来源：http://dali.daxiang520.top/Article/details/gt2qixztjzt.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2vghlgfqz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.meibo888.top/Article/details/gt2pfamhioa.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2lkcfdggw.html

TS:   s.split(/\r?\n/)
来源：http://dali.hfpthk.cn/Article/details/gt2ddqhkpxm.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2nwoldyrg.html

Go:   strings.Split(s, "\n")
来源：http://dali.sweek.top/Article/details/gt2odtygvkw.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gt2xslasmju.html

C#:   s.Split('\n')
来源：http://dali.xuetiantiany.cn/Article/details/gt2nfixbfqn.html

[E20] 判断字符串是否为空
来源：http://dali.guannengcc.top/Article/details/gt2owzpbcfr.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gt2eigtaasu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gt2uvgkbwyt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2suhdcttn.html

TS:   if (s === "") {}
来源：http://dali.zhixingplan.top/Article/details/gt2ckmveiet.html

Java: if (s.isEmpty()) {}
来源：http://dali.yvedp.cn/Article/details/gt2zccjymbe.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2hdrsevqf.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2stonwjkr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ivvv.top/Article/details/gt2eprropas.html

[E21] 超长截断加省略号
来源：http://dali.yj20258.top/Article/details/gt2eedqeakb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ppjwa.cn/Article/details/gt2myxfeovf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2fsqaudcd.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2ltccrswz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2vcplnuxr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gt2wvmmsvtw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2bdvpfhzo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gt2uctysnxh.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2smcbeayj.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gt2wwgyorps.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gt2dlhkjruy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gt2fbhguepk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhixingplan.top/Article/details/gt2mjscvtnz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hywenlv.cn/Article/details/gt2jhyqicvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.chenlongwang.top/Article/details/gt2gqtbavca.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yueranfly.top/Article/details/gt2iccjrdsm.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangdashe.top/Article/details/gt2utuodybf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gt2ilizrdrn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hhdlqmlc.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gt2fkmitvnq.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ttneukqy.html

[F01] 读取整个文件
来源：http://dali.ydzc1.top/Article/details/gt2bxkiysgf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnwtocwd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2lxifjgql.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2pavggqfi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2rjexnxyl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2sxshxfma.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gt2kagwrkhs.html

Ruby: File.read("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2asypmqdx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2qlmluciv.html

[F02] 逐行读取文件
来源：http://dali.fzhhl.top/Article/details/gt2bhaxbjms.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.nanxinkj.top/Article/details/gt2yzzximkw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2uacswcnm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2ijjavrzx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2qpxtmoye.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itiejldl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.bjfxy.top/Article/details/gt2domuiovu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gt2arsfkiyc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shzxlz.cn/Article/details/gt2twmbayqm.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2oirmoknf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2qgeuistw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jlsjyb.cn/Article/details/gt2dsaslrbb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2vvpzjnwr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2dezdyqgl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gt2eowpiqvz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gt2pjlxoenr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.daria6918.cn/Article/details/gt2qtaawnzr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gt2rssloawf.html

[F04] 追加写入文件
来源：http://dali.chenzaomai.com/Article/details/gt2ahgrzsop.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pycfn.com/Article/details/gt2wowbytqv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hywenlv.cn/Article/details/gt2dqrtdcef.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gt2qsxsubdt.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gt2jsqafvxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.guannengcc.top/Article/details/gt2iejwupat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ppjwa.cn/Article/details/gt2wgkoazzw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2mrzdrvhg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2oxshxuvo.html

[F05] 判断文件或目录是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2iuuqkmdi.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.iojbl.cn/Article/details/gt2rahztjal.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2mzashyah.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmstsynx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2zmgjkycs.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gt2wbqxlosy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhijiandao.cn/Article/details/gt2uccxzvdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2nnhlsnpa.html

C#:   File.Exists("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2hhecepzt.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gt2rasdmlyl.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2srkecdix.html

PHP:  unlink("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gt2vbjeqljd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2wtouxkkz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2ayqkbdgi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2mtdzvdsg.html

Go:   os.Remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lptrsnzz.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uvzqxumy.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2fuyyshwj.html

[F07] 创建目录（含多级）
来源：http://dali.tianlin.xyz/Article/details/gt2sstdnafr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2hvmwpnvw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2cevxnwtu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gt2iabmmybo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gt2cgpgswqw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2afjtjyjl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gzhubu.top/Article/details/gt2pzumykbm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gt2xvmroumj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehgjlwgk.html

[F08] 遍历目录
来源：http://dali.yvedp.cn/Article/details/gt2jurygpvj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2xsfnkyqz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenzaomai.com/Article/details/gt2oudbxvpe.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2poevnxzt.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gt2hkevkiff.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2gstbnocw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2cdyiflkw.html

Ruby: Dir.children("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2lrlnyhxy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ydzc1.top/Article/details/gt2fqvyrluh.html

[F09] 获取文件大小
来源：http://dali.pycfn.com/Article/details/gt2prphhmng.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ojmryvht.html

PHP:  filesize("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2cuphjkdx.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwgkvmk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jianghu66.top/Article/details/gt2pgrxigbb.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2wqnllvzt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gt2qcdoqdjc.html

Ruby: File.size("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2fziibufz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dianchejie.cn/Article/details/gt2kpxsamyl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2ryucmjab.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ivhommhv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2clvlajhf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtokhlxj.html

TS:   path.extname("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2fjayfkgs.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gt2cjlddqur.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2owjemrxm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nowwpgcb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsgyuftm.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gt2qjubuvdo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2rlamgljz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2suxqnzzw.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2emcvsrpv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yonumen.top/Article/details/gt2wppiavxa.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yanxiufei.cn/Article/details/gt2najeeadx.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gt2jgqodusx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gt2envnkepa.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gt2hndpucgs.html

[F12] CSV 读写
来源：http://dali.cashguo.top/Article/details/gt2kzbrgecd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sysykeji.top/Article/details/gt2amqadjlg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2ymsindtg.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2gfaklzsx.html

TS:   // 同上
来源：http://dali.havefunace.top/Article/details/gt2iasutdqa.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhoulong.xyz/Article/details/gt2kzoxzcrv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.nanxuanxn.top/Article/details/gt2pyxuivxu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hnqzz.top/Article/details/gt2ijdgotnq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.daria6918.cn/Article/details/gt2awffvxjo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dqdvdsan.html

G. 面向对象
来源：http://dali.redwolf501.top/Article/details/gt2hndjrwnl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ncnvmtfh.html

[G01] 定义类
来源：http://dali.yangfankeji.com/Article/details/gt2lgcoiscu.html

Py:   class User: pass
来源：http://dali.yangfankeji.com/Article/details/gt2sxtlpfsy.html

PHP:  class User {}
来源：http://dali.9152youxi.cn/Article/details/gt2hpqddtvy.html

JS:   class User {}
来源：http://dali.yj20258888.top/Article/details/gt2irksmxux.html

TS:   class User { name: string = ""; }
来源：http://dali.iojbl.cn/Article/details/gt2rndqmzox.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lqeehhox.html

Go:   type User struct { Name string }
来源：http://dali.jqgufenzy.top/Article/details/gt2oircmuvs.html

Ruby: class User; end
来源：http://dali.quarkkingdee.top/Article/details/gt2sbsruryb.html

C#:   class User {}
来源：http://dali.jiagoushi.top/Article/details/gt2coussjzr.html

[G02] 构造函数
来源：http://dali.sxryk.cn/Article/details/gt2vdjpbany.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cheryme.top/Article/details/gt2onovjrdi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ookjdwhr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.tian-w.cn/Article/details/gt2cxnxodkf.html

TS:   constructor(public name: string) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2druwqmsv.html

Java: User(String name) { this.name = name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2chnnwquc.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.snrcjt.cn/Article/details/gt2ybvwphiz.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258.top/Article/details/gt2ulcuccbk.html

C#:   public User(string name) { Name = name; }
来源：http://dali.sysykeji.top/Article/details/gt2cgndrwnk.html

[G03] 实例属性
来源：http://dali.kuanghao11.cn/Article/details/gt2xliajoie.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2zbawycsu.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gt2bmdqmpxm.html

JS:   this.name = "x";
来源：http://dali.tianlin.xyz/Article/details/gt2xmdoxtcr.html

TS:   name: string = "x";
来源：http://dali.dashuyun.cn/Article/details/gt2qampavvo.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gt2lvegksmp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.kuanghao11.cn/Article/details/gt2wjxgihpx.html

Ruby: @name = "x"
来源：http://dali.pycfn.com/Article/details/gt2xhffzkvu.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.daria6918.cn/Article/details/gt2biqdcley.html

[G04] 定义方法
来源：http://dali.zhiwuduotai.top/Article/details/gt2avzvuojb.html

Py:   def greet(self): return self.name
来源：http://dali.yangfankeji.com/Article/details/gt2jmuhhyax.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2upxeqpzz.html

JS:   greet() { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hsrandlx.html

TS:   greet(): string { return this.name; }
来源：http://dali.svipenyu.cn/Article/details/gt2jhnsisfr.html

Java: String greet() { return name; }
来源：http://dali.svipenyu.cn/Article/details/gt2uueqglwr.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gt2dibuefvg.html

Ruby: def greet; @name; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbxlurkg.html

C#:   public string Greet() => Name;
来源：http://dali.fzhhl.top/Article/details/gt2azkfxkum.html

[G05] 继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eihpfams.html

Py:   class Admin(User): pass
来源：http://dali.pengpengdd.cyou/Article/details/gt2kijhkwty.html

PHP:  class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2tsiarfuv.html

JS:   class Admin extends User {}
来源：http://dali.guannengcc.top/Article/details/gt2ortdwtoa.html

TS:   class Admin extends User {}
来源：http://dali.nanxuanxn.top/Article/details/gt2tqdboufj.html

Java: class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpkuzhwg.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ivvv.top/Article/details/gt2vauwepax.html

Ruby: class Admin < User; end
来源：http://dali.jyoumei.cn/Article/details/gt2vwhpnbdu.html

C#:   class Admin : User {}
来源：http://dali.havefunace.top/Article/details/gt2izbldyho.html

[G06] 重写方法
来源：http://dali.sweek.top/Article/details/gt2dycizmsq.html

Py:   def greet(self): return "admin"
来源：http://dali.jianghu66.top/Article/details/gt2wepcfrcv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndspxtsd.html

JS:   greet() { return "admin"; }
来源：http://dali.sysykeji.top/Article/details/gt2ehgpsleu.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gt2hudaynbi.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2oyivysaf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.c1oappe.top/Article/details/gt2eotmxwzz.html

Ruby: def greet; "admin"; end
来源：http://dali.hnqzz.top/Article/details/gt2bsxvbyra.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2ovyuenpg.html

[G07] 调用父类方法
来源：http://dali.smart0.xyz/Article/details/gt2tnhndkxp.html

Py:   super().greet()
来源：http://dali.aizwys.cn/Article/details/gt2xdkpegfj.html

PHP:  parent::greet();
来源：http://dali.shuidangran.top/Article/details/gt2bmfrlfvl.html

JS:   super.greet();
来源：http://dali.yj20258.top/Article/details/gt2bmmixymv.html

TS:   super.greet();
来源：http://dali.fengsongda.top/Article/details/gt2qodsmumr.html

Java: super.greet();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2coaetyws.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylwtufle.html

Ruby: super
来源：http://dali.zhixingplan.top/Article/details/gt2nzngvygq.html

C#:   base.Greet();
来源：http://dali.guowangkeji.top/Article/details/gt2lscnhpik.html

[G08] 静态方法与属性
来源：http://dali.ehwqpu.com/Article/details/gt2dfyhkpbg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.pengpengdd.cyou/Article/details/gt2kawvivpj.html


<!-- 参考信息 -->