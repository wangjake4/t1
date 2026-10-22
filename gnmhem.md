代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2zghsomkr.html

TS:   s.slice(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2mezlkjqs.html

Java: s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2kldfpipo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gt2gxtqwrdx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gt2ibgqeral.html

C#:   s.Substring(1, 3)
来源：http://dali.jiagoushi.top/Article/details/gt2pyjscgln.html

[E04] 查找子串位置
来源：http://dali.xylfe.cn/Article/details/gt2xtfvefmc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qsrvalpj.html

PHP:  strpos($s, "x");
来源：http://dali.quarkkingdee.top/Article/details/gt2drywikxl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgvrplik.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gt2vbkdkmrd.html

Java: s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gt2xtmnvvys.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gt2eeqsfeee.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gt2meebtukw.html

C#:   s.IndexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2dvfqiibc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gt2bdflrnpa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gt2yeyhpazg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gt2pzxcmajq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2azmksdzq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2scpheuui.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gt2rcfawckv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yueranfly.top/Article/details/gt2vcojnqiz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gt2nckknbzh.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gt2ecfzcurp.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gt2ivpobnxe.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gicinviq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jiagoushi.top/Article/details/gt2zlyidevi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2aifhbynq.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gt2ziiwqxsw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gt2bifqfjvk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2dryompwk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2rhleirjk.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2czztoegg.html

[E07] 按分隔符拆分
来源：http://dali.wangdashe.top/Article/details/gt2qvbxfswc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ppjwa.cn/Article/details/gt2ainywdht.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2noesjgnz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.redwolf501.top/Article/details/gt2mulvoemo.html

TS:   s.split(",")
来源：http://dali.dianchejie.cn/Article/details/gt2vpjpqksa.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gt2ugxmabia.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gt2rbwtcsvc.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gt2jipqnadg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gt2nxiubleh.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gt2pqgsfutp.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gt2zlnhdiof.html

PHP:  implode(",", $items);
来源：http://dali.cheryme.top/Article/details/gt2nyopmcpd.html

JS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gt2samnvggp.html

TS:   items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqjqgpkk.html

Java: String.join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2uhcaxdtw.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gt2rzrizpij.html

Ruby: items.join(",")
来源：http://dali.vqdsnc.cn/Article/details/gt2rvpelkpd.html

C#:   string.Join(",", items)
来源：http://dali.nwbrower.top/Article/details/gt2etpxiyzz.html

[E09] 去除所有空白字符
来源：http://dali.jinqigufen.top/Article/details/gt2mbegyiev.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xuanzx.com/Article/details/gt2eaurgzoj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zduavjvm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gt2aozjumwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guaglwhv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.havefunace.top/Article/details/gt2msssaquk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2yrmqcsoa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ibiwdydd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsglyyjw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpuciflx.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pymjeyvr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2zkkmljkk.html

JS:   "7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gawyjrnt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2urgmnvju.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gt2fmypfqyh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2wmnlyshr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2rgeumswm.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ybcxt.top/Article/details/gt2bqwmbcig.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2evynivhe.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gt2luppkets.html

PHP:  strrev($s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dpxlqgaw.html

JS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2rptbxrmo.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gt2heopxvkj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.redwolf501.top/Article/details/gt2nngajpjn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gt2azrnkstg.html

Ruby: s.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gt2xwguplpm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gt2ouprihxe.html

[E12] 统计某字符出现次数
来源：http://dali.yuxming.cn/Article/details/gt2pjttsvtx.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2inwenhpo.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gt2uphfgfqp.html

JS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2tyodavdk.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gt2nggxovfg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gt2ukdwsfiy.html

Go:   strings.Count(s, "a")
来源：http://dali.quarkkingdee.top/Article/details/gt2dxkmxmxy.html

Ruby: s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxqobnip.html

C#:   s.Count(c => c == 'a')
来源：http://dali.dashuyun.cn/Article/details/gt2kvzjxwij.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2qabdpegh.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gt2ijlmixmx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.c1oappe.top/Article/details/gt2ceemgiiu.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkgkfcmn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gt2yyqykmiq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cyqyrktq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.havefunace.top/Article/details/gt2kyesjrak.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gt2jjhsbaxt.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gt2ohfkaimf.html

[E14] URL 编码与 Base64
来源：http://dali.tanke756.top/Article/details/gt2apwxuppc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bcrfgdqm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gt2lbmbaepp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cucudq.cn/Article/details/gt2bmxdfavc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gt2imevinew.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ppjwa.cn/Article/details/gt2wbyaooor.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gt2igvlymir.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.sxryk.cn/Article/details/gt2fsekkvqm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2syeiuezz.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gt2vufsrqmf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gt2tolbhzzs.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2txrozywm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhengqikj.top/Article/details/gt2ikxpunjp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gt2rmhyoowy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.9152youxi.cn/Article/details/gt2usfumnev.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gt2oljgvjty.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2jskravbh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gt2czulmmnf.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2llblbufr.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gt2rpzepalf.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gt2qkotchge.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lzpuktzd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2wkqazszz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cucudq.cn/Article/details/gt2bznzkexj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtmyvkqc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gt2dqmqxtwt.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gt2rnuksmxq.html

[E17] 首字母大写
来源：http://dali.bjfxy.top/Article/details/gt2puxfbfpv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xylfe.cn/Article/details/gt2imufzpfy.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gt2atyyvgwz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2axlsmnge.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2zwraaqbb.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xziqi.cn/Article/details/gt2jpemcejs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yanxiufei.cn/Article/details/gt2hoxlhvuq.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gt2uyhjqoju.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gt2gexrxgug.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckxxyiyr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ngvrdglj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.birdmap.top/Article/details/gt2adpgajlv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2thptgjke.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2yifnkmba.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gt2nynpczfv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gt2lxkhofta.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.snrcjt.cn/Article/details/gt2vfkygsuc.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2hzapytuk.html

[E19] 多行文本按行拆分
来源：http://dali.yanxiufei.cn/Article/details/gt2yztexkne.html

Py:   s.splitlines()
来源：http://dali.ppjwa.cn/Article/details/gt2hqfmdqag.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2ptlhuaga.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gt2anbuutpa.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gt2cafnxfek.html

Java: s.lines().toList()
来源：http://dali.nwbrower.top/Article/details/gt2gssxuyov.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj20258888.top/Article/details/gt2nscnqlmz.html

Ruby: s.lines
来源：http://dali.yuxming.cn/Article/details/gt2rcrkyuxz.html

C#:   s.Split('\n')
来源：http://dali.feifeiyinyue.top/Article/details/gt2zayikpda.html

[E20] 判断字符串是否为空
来源：http://dali.cashguo.top/Article/details/gt2sxrxyssj.html

Py:   if not s:
来源：http://dali.xuetiantiany.cn/Article/details/gt2pfglxfeh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gt2fgqswrkm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2kzjjidft.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2rfjgpnht.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuanzx.com/Article/details/gt2pmggdniw.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gt2aipbezig.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gt2miectqwx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2toydijdm.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gt2wuvfctnw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gt2ebyaqhlw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gt2hdtcyjfb.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gt2vlzelaar.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtqikaan.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.sxryk.cn/Article/details/gt2uxfnamji.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.fengsongda.top/Article/details/gt2zuosjwsn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gt2azicfgoc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tian-w.cn/Article/details/gt2xgxhnjwr.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2wiyjuplf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yangfankeji.com/Article/details/gt2qlerhspm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xylfe.cn/Article/details/gt2qiffetxb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xylfe.cn/Article/details/gt2luxpqagz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuanzhike.top/Article/details/gt2zyghjmqv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gt2pygpdnrx.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gt2gduanltc.html

Ruby: s.bytesize;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2osstkurd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yvedp.cn/Article/details/gt2mbhiwcil.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2rxhfpckf.html

F. 文件与目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zawkxzgf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bshklzkj.html

[F01] 读取整个文件
来源：http://dali.zhoulong.xyz/Article/details/gt2zjlkolxi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gt2ocwzoinh.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2dfdxbkzl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pknakiij.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2aocicwkx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2vwsrvxiq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yangfankeji.com/Article/details/gt2xgkitwmb.html

Ruby: File.read("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2jxdswswj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2tpinhdhm.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gt2jdvvegnb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2gifytbju.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gt2nihrpuri.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gt2hfefkqzv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zvbwwrfs.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2jwqxtndl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.pycfn.com/Article/details/gt2ojajkcpk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gt2xpdyjyem.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhoulong.xyz/Article/details/gt2foslvzwo.html

[F03] 写入文件（覆盖）
来源：http://dali.andypj.xyz/Article/details/gt2ygkcrxkx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gt2hdfithcu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2uzlrjenp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daria6918.cn/Article/details/gt2sfkrcowg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gt2thqavuav.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.smart0.xyz/Article/details/gt2netazkjs.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhixingplan.top/Article/details/gt2pxwynxix.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.gaohongyu789.top/Article/details/gt2fnxnrgzz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2behqqarl.html

[F04] 追加写入文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhaafzuj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2yaksohlb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxinkj.top/Article/details/gt2wqsmeimu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hywenlv.cn/Article/details/gt2ezafghap.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2gufxiggh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2xmahpsjc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2cuzprgaf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lhwldchi.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2cfwcadjz.html

[F05] 判断文件或目录是否存在
来源：http://dali.gogol.net.cn/Article/details/gt2cwhrbkcs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuanzhike.top/Article/details/gt2mnzqcehd.html

PHP:  file_exists("a.txt");
来源：http://dali.pycfn.com/Article/details/gt2pajxfhcm.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gt2fhkxjizo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ybwdoaqa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shzxlz.cn/Article/details/gt2btfdnhbg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.guannengcc.top/Article/details/gt2smcbtatt.html

Ruby: File.exist?("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ltpoabbt.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2kdrmvzlc.html

[F06] 删除文件
来源：http://dali.pycfn.com/Article/details/gt2uhsvvdvc.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2mobhszdw.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2bltqaite.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2jjyzastc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2pvaijzuo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gbeufnex.html

Go:   os.Remove("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ibsrnnin.html

Ruby: File.delete("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2tdapcqpn.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2ehdpjpmd.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gt2nwrseqpz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gt2ngaawffb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.tian-w.cn/Article/details/gt2gjxskfrx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gt2xapqdfch.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xinyue.icu/Article/details/gt2xtmjjpqh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gt2okmwabej.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyorkdif.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gt2nuwldhnr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenzaomai.com/Article/details/gt2ilswdgdz.html

[F08] 遍历目录
来源：http://dali.dashuyun.cn/Article/details/gt2xpaafznf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.guannengcc.top/Article/details/gt2rzggpggx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nwbrower.top/Article/details/gt2hvioxuxv.html

JS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gt2dpehswjn.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2cbnzasnn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gt2sawjlvwi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zdqjudy.top/Article/details/gt2tuajbsip.html

Ruby: Dir.children("dir")
来源：http://dali.zhengqikj.top/Article/details/gt2fzegewgs.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yonumen.top/Article/details/gt2iisouazb.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2mghbzuwc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2arbcumcy.html

PHP:  filesize("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2zxqkjnnt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gt2bzjbeqsl.html

TS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2rucaevog.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gt2hulplxsc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtcfbbux.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nnutjgko.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2cwrdgkup.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.iojbl.cn/Article/details/gt2ubkwclxf.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gt2vbbbqntw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.0kj1m.cn/Article/details/gt2vuqhpton.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gt2sheknaxn.html

TS:   path.extname("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2mxblifos.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhiwuduotai.top/Article/details/gt2hesulktz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2uaanxpwr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2xigibhou.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2xhvrjcfd.html

[F11] 复制与移动文件
来源：http://dali.ppjwa.cn/Article/details/gt2fkjqjqyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2gtjxjpmr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xylfe.cn/Article/details/gt2kfcoullu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2uzhfypdz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsghvowp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2splvqxty.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ehwqpu.com/Article/details/gt2punctcja.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2coowjzeq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhijiandao.cn/Article/details/gt2faxiuzkj.html

[F12] CSV 读写
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llnrhkxj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.kuanghao11.cn/Article/details/gt2cikhhqqz.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gt2atyemtht.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gotoacloud.top/Article/details/gt2jnyheoal.html

TS:   // 同上
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xeqexnsc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cucudq.cn/Article/details/gt2qgdueect.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gt2lrstvnsb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2repncilu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.xinyue.icu/Article/details/gt2mxrmddrr.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2jewimdif.html

G. 面向对象
来源：http://dali.wangshuangyany.cn/Article/details/gt2qqzhxcbx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2rfinvrcf.html

[G01] 定义类
来源：http://dali.bjfxy.top/Article/details/gt2sbqjzrrl.html

Py:   class User: pass
来源：http://dali.zhixingplan.top/Article/details/gt2tabuaffs.html

PHP:  class User {}
来源：http://dali.gzhubu.top/Article/details/gt2qzdyphzn.html

JS:   class User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rbmybwbb.html

TS:   class User { name: string = ""; }
来源：http://dali.yangfankeji.com/Article/details/gt2lxcewgbl.html

Java: class User {}
来源：http://dali.jianghu66.top/Article/details/gt2pnvvdpra.html

Go:   type User struct { Name string }
来源：http://dali.tianlin.xyz/Article/details/gt2kegykxqi.html

Ruby: class User; end
来源：http://dali.ybcxt.top/Article/details/gt2mpwthprn.html

C#:   class User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qnhygign.html


<!-- 参考信息 -->