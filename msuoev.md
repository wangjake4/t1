代发 wailian999

C#:   s.Replace("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2rtxawndi.html

[E07] 按分隔符拆分
来源：http://dali.aibaodan.cn/Article/details/gt2kkqccecr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenlongwang.top/Article/details/gt2txtoypbo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2kqqiufcd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjhsawnc.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gt2tdpukspn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2nmwywiet.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggurjdvq.html

Ruby: s.split(",");  s.split
来源：http://dali.zhiwuduotai.top/Article/details/gt2awvsgbtt.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yangfankeji.com/Article/details/gt2wuklfohu.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gt2zbknnonv.html

Py:   ",".join(items)
来源：http://dali.chenzaomai.com/Article/details/gt2tghsiiec.html

PHP:  implode(",", $items);
来源：http://dali.snrcjt.cn/Article/details/gt2rmahjhum.html

JS:   items.join(",")
来源：http://dali.yj20258.top/Article/details/gt2lygtlgze.html

TS:   items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2ulkqmdpg.html

Java: String.join(",", items)
来源：http://dali.daria6918.cn/Article/details/gt2cjhfjjwr.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzkojmbd.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2gkwlhjyy.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gt2dipdzemx.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gt2ohodjjrx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sysykeji.top/Article/details/gt2rxehqtbo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gt2zrnixnjr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gt2dzdlpzhq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.0kj1m.cn/Article/details/gt2quuyqaal.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gt2aqrcyble.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gt2akbfhmkc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj202588.top/Article/details/gt2nvucnujg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2ilotfeey.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sysykeji.top/Article/details/gt2uiadlwmy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2bceemywo.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.dashuyun.cn/Article/details/gt2ieihorlt.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2awirzqit.html

TS:   "7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2jpletsuq.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgkgedgr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2gnuyvmdl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gt2gtzklhhh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gt2wvzdahtv.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gt2lsvcnmix.html

Py:   s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gt2yamgfgun.html

PHP:  strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2cixkxiuy.html

JS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2neatlkck.html

TS:   [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2euvbkxeq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.vqdsnc.cn/Article/details/gt2ghtqjhsl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gt2qofqpywt.html

Ruby: s.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2zcuiougx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gt2jhbfshyb.html

[E12] 统计某字符出现次数
来源：http://dali.zhongyouzk.top/Article/details/gt2wtydhmaj.html

Py:   s.count("a")
来源：http://dali.yj20258.top/Article/details/gt2mmdftwna.html

PHP:  substr_count($s, "a");
来源：http://dali.chenlongwang.top/Article/details/gt2baxxbqlj.html

JS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnekshii.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gt2goexfrfq.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gt2vhoqrqno.html

Go:   strings.Count(s, "a")
来源：http://dali.c1oappe.top/Article/details/gt2lvqumqxj.html

Ruby: s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2tqytjhid.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bvxiiucw.html

[E13] 逐字符遍历
来源：http://dali.redwolf501.top/Article/details/gt2jndiupqt.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gt2yyshmwqx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sysykeji.top/Article/details/gt2ophetjju.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.bjfxy.top/Article/details/gt2uysbmavr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gt2frfjovtu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jfyrfnur.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dashuyun.cn/Article/details/gt2vaijdksy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sweek.top/Article/details/gt2qjwmonwc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.birdmap.top/Article/details/gt2sutiogvd.html

[E14] URL 编码与 Base64
来源：http://dali.sufxvd.cn/Article/details/gt2jhrwmsgp.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hammf.cn/Article/details/gt2uetfonqm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2eztzeive.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gt2vgzgwaju.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lwpfvodj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gt2ttqhoppp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gt2zogqhmsb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sufxvd.cn/Article/details/gt2igcsklvq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hnqzz.top/Article/details/gt2zsxuuibe.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gt2uilafztk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.iojbl.cn/Article/details/gt2xrosnooz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2qnpfbtkz.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2cysavqdv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gt2ideendbp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gt2eobuhbyi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngtltbto.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2etwtkeae.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gt2hmjmjjdj.html

[E16] 数字千分位
来源：http://dali.smart0.xyz/Article/details/gt2nphblglp.html

Py:   f"{1234567:,}"
来源：http://dali.bjfxy.top/Article/details/gt2fdcqxymi.html

PHP:  number_format(1234567);
来源：http://dali.gotoacloud.top/Article/details/gt2xklzuipf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gt2gaaeqdxa.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gt2bnsmafct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2othvypfr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2sjzdaycj.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gt2nkplrqqh.html

C#:   1234567.ToString("N0")
来源：http://dali.sufxvd.cn/Article/details/gt2utgwongl.html

[E17] 首字母大写
来源：http://dali.c1oappe.top/Article/details/gt2flxelhxw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gt2mehsnsmm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xylfe.cn/Article/details/gt2olqnlwya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2bctjlqbv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.meibo888.top/Article/details/gt2gljdidfv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sufxvd.cn/Article/details/gt2ijnkvajb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dianchejie.cn/Article/details/gt2lhanvphu.html

Ruby: s.capitalize
来源：http://dali.yj20258.top/Article/details/gt2siejxxuo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gt2wjbchapg.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2fgpjtygv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gt2becdnakm.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sxryk.cn/Article/details/gt2kemxvuer.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxgamsym.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2yepnwnxu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2lliopixl.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.smart0.xyz/Article/details/gt2fhvpmnnk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gt2culhkkyx.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2vlleyluz.html

[E19] 多行文本按行拆分
来源：http://dali.pycfn.com/Article/details/gt2kunosjvr.html

Py:   s.splitlines()
来源：http://dali.havefunace.top/Article/details/gt2lhnqwodn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tian-w.cn/Article/details/gt2zcdyndgu.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gt2hqcalltv.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gt2yblfmabk.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgikirca.html

Go:   strings.Split(s, "\n")
来源：http://dali.shzxlz.cn/Article/details/gt2yksxkhiz.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gt2xgxgkwva.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gt2iuwxuoac.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2svbbhpzs.html

Py:   if not s:
来源：http://dali.fzhhl.top/Article/details/gt2lyudvbii.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2pcdkkbgf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.0kj1m.cn/Article/details/gt2lmfwzuqw.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gt2hssbpcsc.html

Java: if (s.isEmpty()) {}
来源：http://dali.zycfv.cn/Article/details/gt2tkcegokl.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2pufpmwie.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gt2kklsymne.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gt2raurwuvj.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gt2okhrpkvj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shuidangran.top/Article/details/gt2meaonxdz.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2tujxnmgj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gt2tzxdlmav.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2isvujhnl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnfnpgby.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.c1oappe.top/Article/details/gt2zgaetxbx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2ylvwtbjj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2rjjshxat.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gt2tgrdjxtl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.svipenyu.cn/Article/details/gt2olrgukym.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmcavxwv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gt2chdozikx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gt2xkmtrjom.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gt2nkelndmy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gt2oztvepfi.html

Ruby: s.bytesize;  s.length
来源：http://dali.sufxvd.cn/Article/details/gt2tpmrahpc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gt2dbldmatd.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2jiclehag.html

F. 文件与目录
来源：http://dali.quarkkingdee.top/Article/details/gt2rihykehb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xplcumdi.html

[F01] 读取整个文件
来源：http://dali.yuxming.cn/Article/details/gt2bbyjnrhz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2fvduapiu.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2seaanqev.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gt2ooqihalp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlnheoug.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2yzfmgeuo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangdashe.top/Article/details/gt2nhhqkdhh.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2xtzrldji.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yonumen.top/Article/details/gt2jrnwgtol.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2vclnxpyn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvnkthcg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zdqjudy.top/Article/details/gt2ghkhhbjk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gzhubu.top/Article/details/gt2ncjmdzyj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2zqfgpixd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.tianlin.xyz/Article/details/gt2dfnubsfc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gt2xneqmovy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gt2hcwjndnq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wttopwdj.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2vibfmbsc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2qmxudiwa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2kuddpqls.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2qnmhjwjd.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cwvogdks.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lhljdrev.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gt2bzdnyzmb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jyoumei.cn/Article/details/gt2gxtydcbt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2fruqtppb.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2bkqgitdf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.meibo888.top/Article/details/gt2ptijunbd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxmrmirh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nsedzpgn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gt2rwoynjjq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hysaishi.cn/Article/details/gt2gyecccha.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2tzvsefff.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxawbnje.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dianchejie.cn/Article/details/gt2tkhyndox.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gt2xvfxvtpu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.meibo888.top/Article/details/gt2oflmgjhx.html

PHP:  file_exists("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2rvreqvfu.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2atpcnial.html

TS:   fs.existsSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2rlkhrpdu.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iypzahsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gt2tvksqwlu.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2zitxfipu.html

C#:   File.Exists("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2rfghlylj.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnekmmhn.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2zcfnugvn.html

PHP:  unlink("a.txt");
来源：http://dali.tanke756.top/Article/details/gt2dppvbqbn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2wxlhufhf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2uludvypi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2kozdjqwo.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ystmyrmu.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2frcchiyq.html

C#:   File.Delete("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2bgqsemue.html

[F07] 创建目录（含多级）
来源：http://dali.guannengcc.top/Article/details/gt2bfwgrnew.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbahowl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gt2hfkqjgst.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdwopbdh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gt2beeqwetd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnqzz.top/Article/details/gt2xjjxczbi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.dianchejie.cn/Article/details/gt2vwnncdxx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ltevdyrx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2zmrnlcwo.html

[F08] 遍历目录
来源：http://dali.yanxiufei.cn/Article/details/gt2iqphmwvz.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yueranfly.top/Article/details/gt2xzseofkz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zegshpnd.html

JS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gt2fkbovpdg.html

TS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2phnvogci.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gt2yxnfeoek.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yueranfly.top/Article/details/gt2ezstewyo.html

Ruby: Dir.children("dir")
来源：http://dali.hysaishi.cn/Article/details/gt2xxjiakwy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ultrvexn.html

[F09] 获取文件大小
来源：http://dali.yanxiufei.cn/Article/details/gt2smkysukk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzufdied.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258888.top/Article/details/gt2flihpnzi.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2xfqwelot.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2fcsqdgjk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2ralivqwp.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj202588.top/Article/details/gt2fznmvivl.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2kuobmynl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jaspahbg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2szofgzby.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fcjjtgtw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wxpeglfh.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2kzhedyfc.html

TS:   path.extname("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2ajdueknb.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.nanxuanxn.top/Article/details/gt2pzvmjnkk.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zyhjpmxe.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuyflivv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gt2yjjqdypj.html

[F11] 复制与移动文件
来源：http://dali.dianchejie.cn/Article/details/gt2iouqfjah.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2lhkerwgg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmkywbrs.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whwiapcm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2cmbcdyft.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jyoumei.cn/Article/details/gt2mmiblkmg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jqgufenzy.top/Article/details/gt2ktpovzsq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2wpiwmkhe.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.guannengcc.top/Article/details/gt2aofhfgos.html

[F12] CSV 读写
来源：http://dali.wangdashe.top/Article/details/gt2tkhogtou.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2lpymcehs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgvkuhys.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2zaeqzqcd.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gt2jaukwmrt.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yonumen.top/Article/details/gt2ksoflidd.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zdqjudy.top/Article/details/gt2evtvvoso.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.quarkkingdee.top/Article/details/gt2tbswzicm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jiagoushi.top/Article/details/gt2xkqcftjj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ejpruyzw.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gt2ultkrmsh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsekqijz.html

[G01] 定义类
来源：http://dali.gzhubu.top/Article/details/gt2xxjtfrze.html

Py:   class User: pass
来源：http://dali.jinqigufen.top/Article/details/gt2nhstgpog.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2wprijjlh.html

JS:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2zhtxovdg.html

TS:   class User { name: string = ""; }
来源：http://dali.hfpthk.cn/Article/details/gt2cljnacpj.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2qlrnozja.html

Go:   type User struct { Name string }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xdbjjhqa.html

Ruby: class User; end
来源：http://dali.tian-w.cn/Article/details/gt2flzjydri.html

C#:   class User {}
来源：http://dali.svipenyu.cn/Article/details/gt2udzidgma.html

[G02] 构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zordktbc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkwoqkfo.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drohkgmp.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ybcxt.top/Article/details/gt2pwldqmxy.html

TS:   constructor(public name: string) {}
来源：http://dali.yj202588.top/Article/details/gt2tdenarfe.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2hwuyyipe.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hammf.cn/Article/details/gt2xggtjglt.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hysaishi.cn/Article/details/gt2kfldmoyo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ctxvvife.html

[G03] 实例属性
来源：http://dali.birdmap.top/Article/details/gt2sudnqvuo.html

Py:   self.name = "x"
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvadhuy.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gt2ecaibbsi.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2iuiqzwpv.html

TS:   name: string = "x";
来源：http://dali.nanxinkj.top/Article/details/gt2esexkomx.html

Java: private String name;
来源：http://dali.redwolf501.top/Article/details/gt2hllzmwpv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.zdqjudy.top/Article/details/gt2cxsdlvyq.html

Ruby: @name = "x"
来源：http://dali.nanxuanxn.top/Article/details/gt2yzbdtzis.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.jinqigfzy.top/Article/details/gt2tqjfxmrj.html

[G04] 定义方法
来源：http://dali.shzxlz.cn/Article/details/gt2mzzlseur.html

Py:   def greet(self): return self.name
来源：http://dali.jianghu66.top/Article/details/gt2udwerozo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gt2wxyeagud.html

JS:   greet() { return this.name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhbjhohz.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2wbblzyqc.html

Java: String greet() { return name; }
来源：http://dali.daria6918.cn/Article/details/gt2ihpeesnv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gt2mnbajjos.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gt2yhacdntm.html

C#:   public string Greet() => Name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtazeuyx.html

[G05] 继承
来源：http://dali.yj20258888.top/Article/details/gt2cczsbjzg.html

Py:   class Admin(User): pass
来源：http://dali.cashguo.top/Article/details/gt2ldmqbihk.html

PHP:  class Admin extends User {}
来源：http://dali.sysykeji.top/Article/details/gt2xdiljwgk.html

JS:   class Admin extends User {}
来源：http://dali.nwbrower.top/Article/details/gt2snwqbhlp.html

TS:   class Admin extends User {}
来源：http://dali.sweek.top/Article/details/gt2ngutassd.html


<!-- 参考信息 -->