代发 wailian999

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2wxatkkeb.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wrnluaku.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2hgedwobj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gt2tvgkqrdk.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gt2mgmypxmq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ztvmagrc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhengqikj.top/Article/details/gt2mtwljjai.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2xnqhowao.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2ngieqxlt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2fwdhxcpp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ymqsepdb.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gt2hbfaubmg.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2abkkgooq.html

[E07] 按分隔符拆分
来源：http://dali.gzhubu.top/Article/details/gt2verqxpdc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.aibaodan.cn/Article/details/gt2ulodfkjg.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2qvptrbmx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.316326.xyz/Article/details/gt2ploekcsd.html

TS:   s.split(",")
来源：http://dali.redwolf501.top/Article/details/gt2ifgqubeu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gt2dzsxpwfk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2iujpciin.html

Ruby: s.split(",");  s.split
来源：http://dali.xuanzx.com/Article/details/gt2xizjmfkn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gt2sdxhfdow.html

[E08] 数组按分隔符合并
来源：http://dali.aibaodan.cn/Article/details/gt2awcxpkdw.html

Py:   ",".join(items)
来源：http://dali.aibaodan.cn/Article/details/gt2mnubwsxa.html

PHP:  implode(",", $items);
来源：http://dali.hnqzz.top/Article/details/gt2lwxeewwq.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2kfrwdotl.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2xmcvpvtg.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gt2aurayzvp.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gt2yhyyvyav.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2uvntlfwm.html

C#:   string.Join(",", items)
来源：http://dali.tian-w.cn/Article/details/gt2vzficfke.html

[E09] 去除所有空白字符
来源：http://dali.yuxming.cn/Article/details/gt2izgncbmc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gt2amlmxzst.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2feokqinj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2hqdtwbff.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hszoexhk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.haohaochexian.top/Article/details/gt2uidciovg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2gbznuxhb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.0kj1m.cn/Article/details/gt2wovusiye.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shzxlz.cn/Article/details/gt2whpavjzg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258888.top/Article/details/gt2uuimyela.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gt2vsoraxos.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sufxvd.cn/Article/details/gt2xcdnbetk.html

JS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iwccfrqe.html

TS:   "7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gt2zcibkdbz.html

Java: String.format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gt2kqtkkcxn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcmtqkg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gt2yidmxbag.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgufenzy.top/Article/details/gt2houppvqa.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzbeupwa.html

Py:   s[::-1]
来源：http://dali.guannengcc.top/Article/details/gt2uquqjkcr.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gt2ckxcsmpt.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gt2egqzbuku.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2qijhabqe.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cqqwz.cn/Article/details/gt2soeuwlyz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gt2kgvigrzr.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2mextctzw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2rufjhmdt.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gt2swcboqsc.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2ykdkcmso.html

PHP:  substr_count($s, "a");
来源：http://dali.guannengcc.top/Article/details/gt2uhxfaghk.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gt2dufzthan.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gt2olqtmleb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258.top/Article/details/gt2kutwkvno.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2ifqcotnw.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gt2xwqxywec.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gt2miujbhiz.html

[E13] 逐字符遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ujsepudj.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pgvmkhoz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2bwarwibl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2asokmxsz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2pkpjyamx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gt2lyvqvjch.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yudydhlp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gt2gfdgzgrr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2brfkrfet.html

[E14] URL 编码与 Base64
来源：http://dali.tianlin.xyz/Article/details/gt2cztcdbtc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yanxiufei.cn/Article/details/gt2edhssakw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gtdkldim.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrkyxluf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gt2xrbfttuy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2onngcqpa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkmregvm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gt2mekvynmj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2gbbedryj.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gt2xbqneoqg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ezqnsmop.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gt2hwemajuj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezlsnikf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owjfijpa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcoczmuv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2uukppbvt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gt2ojljhziy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cheryme.top/Article/details/gt2puzuwbee.html

[E16] 数字千分位
来源：http://dali.shzxlz.cn/Article/details/gt2nclqpdvs.html

Py:   f"{1234567:,}"
来源：http://dali.ppjwa.cn/Article/details/gt2pbfmmxlj.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2codrbgwv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gt2lcxzcpym.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gt2djqikixh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gt2tzsujgco.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sxryk.cn/Article/details/gt2oudagiyo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swhblvhj.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gt2ddlyeomr.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rpntaqzh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2einjznca.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2qdfdwmyr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2offxgpmp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gt2tylrzbwj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2pcdtegmj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2wrjmfiaj.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gt2tdzcvscv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gt2jktatisr.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gt2zfouosmy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bzuonucu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2qsdlmhku.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ydzc1.top/Article/details/gt2tgsrvlrp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gt2ijcesqqs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2hvuysqqw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2rsdjfufj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zdqjudy.top/Article/details/gt2aqpltnvh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hnqzz.top/Article/details/gt2fafioicm.html

[E19] 多行文本按行拆分
来源：http://dali.yuxming.cn/Article/details/gt2ccuxibxa.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2zskhjaei.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hammf.cn/Article/details/gt2juuhbskt.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjiujpuf.html

TS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2xbarxcfx.html

Java: s.lines().toList()
来源：http://dali.redwolf501.top/Article/details/gt2gprmpnpd.html

Go:   strings.Split(s, "\n")
来源：http://dali.fengsongda.top/Article/details/gt2salfzogn.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2jwarpfap.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gt2fonunltq.html

[E20] 判断字符串是否为空
来源：http://dali.jqgufenzy.top/Article/details/gt2aqsngfwh.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwindttd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gt2aaobbtqe.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilyohblx.html

TS:   if (s === "") {}
来源：http://dali.316326.xyz/Article/details/gt2sjzilbmc.html

Java: if (s.isEmpty()) {}
来源：http://dali.fzhhl.top/Article/details/gt2dbxtztlo.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2oxmurskz.html

Ruby: if s.empty?
来源：http://dali.gzhubu.top/Article/details/gt2nfgudvvy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gt2fswyphmd.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2txnyqten.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gt2zpzegykw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gt2anmjpaji.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2ryreicit.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2rciwnlqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhcapavs.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gt2ezigcygw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2jgohoibd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2yhlvlrfx.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gt2gvjzegya.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.redwolf501.top/Article/details/gt2foifajdm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2qaiswavk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jyoumei.cn/Article/details/gt2etjmghbg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2hwbfqcvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2swxcnlwb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2fkalqoce.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2tzfbxmbh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2cheztpgk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2actfakxh.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gt2anjkfewv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2cpxbjwkc.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gt2eulcirxb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gt2jkuwqqvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2cpomkvfc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gt2jwmzpgjk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztahisvh.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2dukbabng.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fengsongda.top/Article/details/gt2tikovcgl.html

Ruby: File.read("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2uysfiwzl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2mldqdyfl.html

[F02] 逐行读取文件
来源：http://dali.nwbrower.top/Article/details/gt2gnwxglyu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2twwtyyug.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2lzqvygsd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.redwolf501.top/Article/details/gt2qxekffcp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shuidangran.top/Article/details/gt2qqgmyyzz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2ckckuugm.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.gogol.net.cn/Article/details/gt2oxvtedow.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cashguo.top/Article/details/gt2ynjototo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gt2jzacflgu.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gt2ymvnrztw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gt2sspzwzrk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2omsjkldx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.pycfn.com/Article/details/gt2afxardvf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2qpxiuehi.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj202588.top/Article/details/gt2glmdatmg.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daria6918.cn/Article/details/gt2xhcskcyq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzdsfizi.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2zdimiahg.html

[F04] 追加写入文件
来源：http://dali.yj20258.top/Article/details/gt2isuogakw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2ljzfarza.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gt2obcwsidw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yongpay.top/Article/details/gt2ziszyvng.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2yjwkuyls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2ooastvli.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gt2ymbbgfdi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenzaomai.com/Article/details/gt2lwsqbmti.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gt2uzsgthdg.html

[F05] 判断文件或目录是否存在
来源：http://dali.aizwys.cn/Article/details/gt2ftwjoqpm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qbxamuas.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2jccrrnda.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwymwcar.html

TS:   fs.existsSync("a.txt")
来源：http://dali.pycfn.com/Article/details/gt2pbwiletx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2pimomavt.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guowangkeji.top/Article/details/gt2gxaeqjsc.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2pglqxnob.html

C#:   File.Exists("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbkbvspm.html

[F06] 删除文件
来源：http://dali.snrcjt.cn/Article/details/gt2wzxdctws.html

Py:   os.remove("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2crhsougg.html

PHP:  unlink("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2uopiqrxa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2bfftekyk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2dstunbgq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2zhttqxho.html

Go:   os.Remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2uicqzmfy.html

Ruby: File.delete("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2olsseycg.html

C#:   File.Delete("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2hdjdtiyg.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gt2ixzfvckt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmzgiasc.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2plpoxfco.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gt2wedbjogo.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cheryme.top/Article/details/gt2ibycckkr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gt2lgmrxmsz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zdqjudy.top/Article/details/gt2phwbqqbl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gt2kxnalwba.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2syxjoiqa.html

[F08] 遍历目录
来源：http://dali.cashguo.top/Article/details/gt2zmfmavpw.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkvxnvj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjhvtthg.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnxiangtu.top/Article/details/gt2bzxxwyry.html

TS:   fs.readdirSync("dir")
来源：http://dali.fengsongda.top/Article/details/gt2wyfjlrct.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gt2omdumppd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2rxyuidcs.html

Ruby: Dir.children("dir")
来源：http://dali.316326.xyz/Article/details/gt2elqslfxt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gt2pyftuphq.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2sghdhrqt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2expnglma.html

PHP:  filesize("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2nmsnqmmw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gt2ekwxnjhc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yj202588.top/Article/details/gt2edogckem.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gt2qojybbpt.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jqgufenzy.top/Article/details/gt2scjqwiif.html

Ruby: File.size("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2olhzqozf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj20258.top/Article/details/gt2sxmfqidm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.havefunace.top/Article/details/gt2gjgnonou.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2jxecfxga.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sweek.top/Article/details/gt2rdruscbr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gt2ujadrvgl.html

TS:   path.extname("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2sqydoafw.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ydzc1.top/Article/details/gt2ebljjifj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkddmlvi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2phhhximr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2lptgvyvs.html

[F11] 复制与移动文件
来源：http://dali.iojbl.cn/Article/details/gt2dzyvbsxb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.wangdashe.top/Article/details/gt2xhsfgpgs.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2mxhvtdgg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gt2ewnndcat.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gt2gakqzmtf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gt2aznhtogm.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gt2kftxamcr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2pqlrtzcd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.ydzc1.top/Article/details/gt2sxhfbmec.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gt2lbuljnad.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gt2cgbtdurv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhoulong.xyz/Article/details/gt2ysyaathk.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.guannengcc.top/Article/details/gt2djbohvyb.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2mbahbyqx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.smart0.xyz/Article/details/gt2imjsuvsf.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqyjubdb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ydzc1.top/Article/details/gt2cptfduli.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ehwqpu.com/Article/details/gt2tgqpfoni.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2rekyfjzh.html

G. 面向对象
来源：http://dali.0kj1m.cn/Article/details/gt2qxflcbzq.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2prcxydci.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2gwvqwafx.html

Py:   class User: pass
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkzxosdi.html

PHP:  class User {}
来源：http://dali.tian-w.cn/Article/details/gt2ymmcxhqi.html

JS:   class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2nmmaxwbl.html

TS:   class User { name: string = ""; }
来源：http://dali.guowangkeji.top/Article/details/gt2tyinfscz.html

Java: class User {}
来源：http://dali.hfpthk.cn/Article/details/gt2prnwlhgt.html

Go:   type User struct { Name string }
来源：http://dali.ppjwa.cn/Article/details/gt2mmmzokkt.html

Ruby: class User; end
来源：http://dali.yongpay.top/Article/details/gt2nloaocvq.html

C#:   class User {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btltcgck.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2dfaktyjy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.dianchejie.cn/Article/details/gt2fxknfwno.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.guannengcc.top/Article/details/gt2ekwwfjeq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gt2ouozoqem.html

TS:   constructor(public name: string) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fkqykmkm.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gt2hryqoxwg.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.kuanghao11.cn/Article/details/gt2syjfblhm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.316326.xyz/Article/details/gt2xxtyniek.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2bhpeccqo.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gt2xfkubauw.html

Py:   self.name = "x"
来源：http://dali.snrcjt.cn/Article/details/gt2hvvwwooi.html

PHP:  public string $name = "x";
来源：http://dali.gzhubu.top/Article/details/gt2roeucrrz.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gt2kartdpfq.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gt2tqfzlycw.html

Java: private String name;
来源：http://dali.chenlongwang.top/Article/details/gt2wunjlntb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vakgczdd.html

Ruby: @name = "x"
来源：http://dali.jqgufenzy.top/Article/details/gt2xkrrrbzq.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewrtmigl.html

[G04] 定义方法
来源：http://dali.jqgufenzy.top/Article/details/gt2bdawoeyw.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2uoqmjiwh.html


<!-- 参考信息 -->