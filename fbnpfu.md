代发 wailian999

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2gakxwmnc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2xntibhuz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gt2adxhkxoj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2jglgaqhy.html

C#:   s.Replace("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2pvayeioh.html

[E07] 按分隔符拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2gitobtlx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gt2rmjmuuxs.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tapctxil.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daxiang520.top/Article/details/gt2hkwdvfia.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gt2lqoenupq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2pltxciva.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.shzxlz.cn/Article/details/gt2ngaufscg.html

Ruby: s.split(",");  s.split
来源：http://dali.daria6918.cn/Article/details/gt2tykdubvv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gt2usddkila.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gt2ijfhrhjw.html

Py:   ",".join(items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uykcrtvs.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gt2rfzuiahq.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2hxmxhmlf.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2jjnahuav.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2rqgfrrxc.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gt2behfabhb.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2iepsuvoz.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2nuvxdxhv.html

[E09] 去除所有空白字符
来源：http://dali.jyoumei.cn/Article/details/gt2jtuqxrkx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gt2wukforwt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2kmdppgrm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gt2olzhughg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2jfxmcaeu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nueqrfad.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hnxiangtu.top/Article/details/gt2qmcexhiy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shzxlz.cn/Article/details/gt2lhwjqrre.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2ubexvfwr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jlsjyb.cn/Article/details/gt2tzzikujc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tummkasw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2iwyxnvms.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gt2imjiemvh.html

TS:   "7".padStart(3, "0")
来源：http://dali.ivvv.top/Article/details/gt2cbplfqgd.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2gvbyhvjt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gt2zabiqnzv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2vlpdrbxg.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnxiangtu.top/Article/details/gt2gabtelgh.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2byfqtkwk.html

Py:   s[::-1]
来源：http://dali.redwolf501.top/Article/details/gt2wwaxbwrt.html

PHP:  strrev($s);
来源：http://dali.dianchejie.cn/Article/details/gt2mntiyfzd.html

JS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gt2jqsqqxtg.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gt2lbnilzzj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.aizwys.cn/Article/details/gt2xhmzydbu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvtcgvjq.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2rxxaynpn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sxryk.cn/Article/details/gt2fibqvxic.html

[E12] 统计某字符出现次数
来源：http://dali.ehwqpu.com/Article/details/gt2wxvxkeya.html

Py:   s.count("a")
来源：http://dali.ybcxt.top/Article/details/gt2ukelmmut.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gt2zxmwftji.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gt2bmltdzjb.html

TS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gt2wkuxbogc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenzaomai.com/Article/details/gt2ikpjjiqf.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gt2jqkjpfuv.html

Ruby: s.count("a")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgvkpmwv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2cfulqhoo.html

[E13] 逐字符遍历
来源：http://dali.316326.xyz/Article/details/gt2awgdfjqu.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2glerabzs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahghgsq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2sierwoye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gt2ydxwybdt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2nzixxjvr.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gt2fcngpqbi.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jyoumei.cn/Article/details/gt2cwcjvjsc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gt2yeciagsx.html

[E14] URL 编码与 Base64
来源：http://dali.chenlongwang.top/Article/details/gt2mzxwbazy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.hysaishi.cn/Article/details/gt2pdbwmfnz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhoulong.xyz/Article/details/gt2gxqvoscb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gt2rotqbsdx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gt2paiesgai.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gt2gvdutrvi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fymgygwe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gt2tvwoohwg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hammf.cn/Article/details/gt2eymachgo.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gt2yywxqqmy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.andypj.xyz/Article/details/gt2nzqpvkwz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnxiangtu.top/Article/details/gt2nhfxqwqp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aizwys.cn/Article/details/gt2hgpnnivo.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2oygzftxz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.vqdsnc.cn/Article/details/gt2islnbmwv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gt2pjtodikq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jyoumei.cn/Article/details/gt2nfqugnbx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zoeujlli.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2mxobkasa.html

Py:   f"{1234567:,}"
来源：http://dali.yonumen.top/Article/details/gt2osgraqxn.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvbbeysw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2fhdycvri.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gt2rzigljrp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2faexkvnk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ehwqpu.com/Article/details/gt2ncnoybcm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hnqzz.top/Article/details/gt2xjiccpkr.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2jfvsorja.html

[E17] 首字母大写
来源：http://dali.hysaishi.cn/Article/details/gt2tshyjszh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gt2yejdwbmd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hnqzz.top/Article/details/gt2geqbvlvq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ivvv.top/Article/details/gt2ausjkmdb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lxwdkmrx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qiszkzai.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cashguo.top/Article/details/gt2jqexicph.html

Ruby: s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2dbyabwqd.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hammf.cn/Article/details/gt2xjspztsy.html

[E18] 模板占位符替换
来源：http://dali.havefunace.top/Article/details/gt2vlcldiik.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.dianchejie.cn/Article/details/gt2tukpnmvp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyqjfovy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2hzougwui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2mmqcelta.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2wfdvivro.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2uotlsrvw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2emwsrplj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gt2rfmhrwat.html

[E19] 多行文本按行拆分
来源：http://dali.mhx1999.top/Article/details/gt2ulugrtwx.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gt2xbwurblg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.tanke756.top/Article/details/gt2usigjslf.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnqzz.top/Article/details/gt2afnfcjjc.html

TS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gt2fzqrlzzx.html

Java: s.lines().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmshgrwg.html

Go:   strings.Split(s, "\n")
来源：http://dali.pycfn.com/Article/details/gt2kjjiqcgp.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2ifxmxyds.html

C#:   s.Split('\n')
来源：http://dali.jianghu66.top/Article/details/gt2kndqeqov.html

[E20] 判断字符串是否为空
来源：http://dali.havefunace.top/Article/details/gt2cmqpqbdj.html

Py:   if not s:
来源：http://dali.9152youxi.cn/Article/details/gt2qajakoyk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gt2yakhghqa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsbcethk.html

TS:   if (s === "") {}
来源：http://dali.sxryk.cn/Article/details/gt2tduvbffo.html

Java: if (s.isEmpty()) {}
来源：http://dali.9152youxi.cn/Article/details/gt2ldceocgx.html

Go:   if s == "" {}
来源：http://dali.meibo888.top/Article/details/gt2cdksdmrk.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gt2fmcmlzxp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2mtobffkq.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gt2usgzgvwy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gt2tuplyscm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acqxxkvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gt2anbgkgza.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2yclvzgvs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2pvyfxxcg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zycfv.cn/Article/details/gt2ehrmnzva.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.chenzaomai.com/Article/details/gt2ihpiwsce.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gt2tjbffrfv.html

[E22] 字节长度与字符长度
来源：http://dali.pycfn.com/Article/details/gt2naaukkcl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guowangkeji.top/Article/details/gt2psatwuvm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gt2xkuizzvo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.mhx1999.top/Article/details/gt2hdjyhler.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2bsmfcdfx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gt2uixkvovk.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hysaishi.cn/Article/details/gt2xvecxeyq.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2xetlidfm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yongpay.top/Article/details/gt2zmxpfkip.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2kpcrhqdj.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sbapcjpf.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2xeqqjnkj.html

[F01] 读取整个文件
来源：http://dali.yonumen.top/Article/details/gt2ztuedsqn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.dianchejie.cn/Article/details/gt2uoorjacb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.316326.xyz/Article/details/gt2zejhrgnc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xziqi.cn/Article/details/gt2zayqwnwi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yfupctwk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gt2hzfbxldy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jlsjyb.cn/Article/details/gt2ebfhvpnl.html

Ruby: File.read("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vzrnwrgz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2usvpxhms.html

[F02] 逐行读取文件
来源：http://dali.yj20258888.top/Article/details/gt2etqyxztz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ydzc1.top/Article/details/gt2vzrbagsd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.meibo888.top/Article/details/gt2mgqkniyh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2gdtkfqsr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2upbsifje.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gt2henkogfu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhixingplan.top/Article/details/gt2vmymumfp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daria6918.cn/Article/details/gt2pzfxuclp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gt2ackurbub.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gt2gxogiljt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2texndqvn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gt2hcousizh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tanke756.top/Article/details/gt2smsgeusv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2kyukwpdo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.pycfn.com/Article/details/gt2hvegundk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gogol.net.cn/Article/details/gt2bedjupak.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2nrhvugxd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2ngcwbjvf.html

[F04] 追加写入文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jszjozey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hnqzz.top/Article/details/gt2tjnmzeyi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.c1oappe.top/Article/details/gt2gdujnzzf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2arnwrdii.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2ixfcraoi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qanazqgp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gt2eypqrxrp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gt2nnijiesl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.0kj1m.cn/Article/details/gt2hmvsdlht.html

[F05] 判断文件或目录是否存在
来源：http://dali.zycfv.cn/Article/details/gt2zvfkiyxp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aizwys.cn/Article/details/gt2vdmacbaa.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gt2gihhngug.html

JS:   fs.existsSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gt2hwpeqpre.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wrmbhgrw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2wvaywpbc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gt2xoihckfm.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2fnwnrptz.html

C#:   File.Exists("a.txt")
来源：http://dali.iojbl.cn/Article/details/gt2pnqtyank.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2hrhafduz.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2dugmuysh.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gt2ritcacla.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2ysctwrws.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2aaalblwl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2gotcoexd.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2bfutdvfn.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2lpqewpse.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2eimdrbck.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2jtlhlzpy.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2fpbpliff.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tanke756.top/Article/details/gt2isecpsut.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2whxaiaze.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gt2kkukakau.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.nwbrower.top/Article/details/gt2klpjlsdb.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gt2owvcdvtt.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yonumen.top/Article/details/gt2fgfuoutq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gt2nnhfhqvu.html

[F08] 遍历目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxxhqvjh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuxffkiv.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hvcjqizt.html

JS:   fs.readdirSync("dir")
来源：http://dali.dianchejie.cn/Article/details/gt2wuubeexg.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mgmugqbn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.meibo888.top/Article/details/gt2xnscffyl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tijabxnu.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gt2labzepch.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2steekuxn.html

[F09] 获取文件大小
来源：http://dali.shzxlz.cn/Article/details/gt2jldmiiwa.html

Py:   os.path.getsize("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2rkybezkn.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2dlctwcdg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2ovukhydl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.pengpengdd.cyou/Article/details/gt2mumtfeit.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gt2hiewxydf.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2vapadnop.html

Ruby: File.size("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2kcoxsske.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrruqibi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangshuangyany.cn/Article/details/gt2vfcrpqwm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2enjmzaqz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2vustjfew.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2dxmurjnq.html

TS:   path.extname("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mybtiyhq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.316326.xyz/Article/details/gt2juvmqkfc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2qssltbrp.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2heriacvy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2bfstnxze.html

[F11] 复制与移动文件
来源：http://dali.svipenyu.cn/Article/details/gt2zdtwpibi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.birdmap.top/Article/details/gt2skigrbxu.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gt2tstmsick.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2twizkqfz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxwybsod.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.fzhhl.top/Article/details/gt2qeyjcpcg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2unovwjdz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gzhubu.top/Article/details/gt2evkjpasb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gt2jvqqgeyx.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gt2pqniuqrw.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tanke756.top/Article/details/gt2mlaecmxj.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ppjwa.cn/Article/details/gt2gbsksfjb.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guowangkeji.top/Article/details/gt2vpexeqrt.html

TS:   // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2rfrobilm.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2erphlcqi.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cheryme.top/Article/details/gt2pxibynsu.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyyikgca.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.haohaochexian.top/Article/details/gt2zjdduvyn.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2jodjbljv.html

G. 面向对象
来源：http://dali.feifeiyinyue.top/Article/details/gt2xewzffos.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2wvjhkxsi.html

[G01] 定义类
来源：http://dali.vqdsnc.cn/Article/details/gt2zcbuzgqs.html

Py:   class User: pass
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwvodtkx.html

PHP:  class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2hycvqonj.html

JS:   class User {}
来源：http://dali.hysaishi.cn/Article/details/gt2jnngjzfp.html

TS:   class User { name: string = ""; }
来源：http://dali.daxiang520.top/Article/details/gt2oxnsqstk.html

Java: class User {}
来源：http://dali.cheryme.top/Article/details/gt2xbdvveqr.html

Go:   type User struct { Name string }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktobfsxo.html

Ruby: class User; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmjdktcf.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gt2itywippf.html

[G02] 构造函数
来源：http://dali.iojbl.cn/Article/details/gt2ummhjgia.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.gogol.net.cn/Article/details/gt2giusemxi.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ydzc1.top/Article/details/gt2gdjxekdt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gt2ktkcgkie.html

TS:   constructor(public name: string) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzxhhjnj.html

Java: User(String name) { this.name = name; }
来源：http://dali.jinqigufen.top/Article/details/gt2xiucqktk.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvvaemgb.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2prbckybw.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2meauzuca.html

[G03] 实例属性
来源：http://dali.yongpay.top/Article/details/gt2aiwohpkb.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gt2zpfqurbn.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gt2cnthjdkc.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2jpdzuxym.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gt2qffnblyj.html

Java: private String name;
来源：http://dali.bjfxy.top/Article/details/gt2ykgwnwbq.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.pengpengdd.cyou/Article/details/gt2xznpjvzj.html

Ruby: @name = "x"
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcgbqpjo.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj202588.top/Article/details/gt2vwzseriu.html

[G04] 定义方法
来源：http://dali.guowangkeji.top/Article/details/gt2pzyruaml.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2umkrcfku.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ehwqpu.com/Article/details/gt2wuawywed.html

JS:   greet() { return this.name; }
来源：http://dali.c1oappe.top/Article/details/gt2zhzwelhp.html

TS:   greet(): string { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gt2wskglqdn.html

Java: String greet() { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwqyrkkb.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mztdmenn.html

Ruby: def greet; @name; end
来源：http://dali.jiagoushi.top/Article/details/gt2inbaseyy.html

C#:   public string Greet() => Name;
来源：http://dali.xuanzx.com/Article/details/gt2lpnxxkrp.html

[G05] 继承
来源：http://dali.bjfxy.top/Article/details/gt2zsaoasju.html


<!-- 参考信息 -->