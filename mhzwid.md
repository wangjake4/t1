代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2lhvkmvel.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.iojbl.cn/Article/details/gt2jjqlycoh.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gt2gvwssrno.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2hkrrclns.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2mbpjyyxk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yuanzhike.top/Article/details/gt2wlstitpw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gt2tuzwtnjy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2llonjcyp.html

[E02] 重复字符串
来源：http://dali.sysykeji.top/Article/details/gt2bnxmvust.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2szyskuzv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xpbifmoh.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2ansawlpq.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2waktifec.html

Java: "ab".repeat(3)
来源：http://dali.jiagoushi.top/Article/details/gt2wchrgynk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2cntjpirc.html

Ruby: "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2dpaqrhho.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sufxvd.cn/Article/details/gt2xvgasezn.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2fbvnvspu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2jgfwxlyk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2orjhtips.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2adovjvsg.html

TS:   s.slice(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2mrufsouo.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2urnjhmzv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hammf.cn/Article/details/gt2omxbctjv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.andypj.xyz/Article/details/gt2cvxdtgzl.html

C#:   s.Substring(1, 3)
来源：http://dali.yvedp.cn/Article/details/gt2dmxkkdsm.html

[E04] 查找子串位置
来源：http://dali.jlsjyb.cn/Article/details/gt2mcxyvijf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2ghoblear.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2kdkwuttm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gt2hszuiazi.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2umdsbmcd.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2uczuwfhr.html

Go:   strings.Index(s, "x")
来源：http://dali.yonumen.top/Article/details/gt2svvydetc.html

Ruby: s.index("x")
来源：http://dali.xylfe.cn/Article/details/gt2ilaipkcw.html

C#:   s.IndexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2fosulafo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj20258888.top/Article/details/gt2meojjwxx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenzaomai.com/Article/details/gt2memxjtir.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckwvtcez.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gt2fuwbpbap.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gt2raporjez.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2wzpzxgzu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gt2yqzhwokx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jpbrftfn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gt2mbnwpwvh.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gt2ejasjgpd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tugnspuy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gt2klbwutez.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2vuriohfu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gt2evpoctam.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gt2iqfpyiug.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2iuonxuyw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2cuysesbq.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2eokwrcfa.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gt2ekhiagjg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gt2mpinvymw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2oirkqrth.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gt2stqhyogx.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gt2uswcjwed.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kjcxcyay.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gt2zviwvgtk.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gt2qodvcxrp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.aibaodan.cn/Article/details/gt2xyibueae.html

[E08] 数组按分隔符合并
来源：http://dali.cheryme.top/Article/details/gt2mvlonvmo.html

Py:   ",".join(items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gehlahqi.html

PHP:  implode(",", $items);
来源：http://dali.yuxming.cn/Article/details/gt2cfleadvr.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gt2tliwofvc.html

TS:   items.join(",")
来源：http://dali.aizwys.cn/Article/details/gt2ndsmcpmd.html

Java: String.join(",", items)
来源：http://dali.cdnleiting.top/Article/details/gt2pbuoipzd.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acpbestv.html

Ruby: items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2bvqenzzo.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gt2tdegkdch.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gt2cbxtdykk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2gerjpwya.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2htadpxiw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnxiangtu.top/Article/details/gt2ioxdqzjq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gt2wwtidbfh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.andypj.xyz/Article/details/gt2pleswgwi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gt2tsyzjfqa.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xinyue.icu/Article/details/gt2ociyixzs.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ddatngkt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.quarkkingdee.top/Article/details/gt2arpgclat.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.meibo888.top/Article/details/gt2hhvfbmma.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yongpay.top/Article/details/gt2zmrlhqqu.html

JS:   "7".padStart(3, "0")
来源：http://dali.yuxming.cn/Article/details/gt2acjphkek.html

TS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpytlujd.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2dgrtusay.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsxmxams.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gt2fzmjiypj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2fajtfefr.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2jhugmaag.html

Py:   s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gt2ssfxiuok.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gt2cucurjml.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2mvevdgqa.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2uvswvxfy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ydzc1.top/Article/details/gt2wpzdcnuj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tbzcygwv.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2wpovtrak.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ubfqtgbk.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gt2enjqpjlg.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gt2uknhvzry.html

PHP:  substr_count($s, "a");
来源：http://dali.quarkkingdee.top/Article/details/gt2ezglxwtg.html

JS:   s.split("a").length - 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gwajyqcb.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gt2fjpijbgi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqrognhc.html

Go:   strings.Count(s, "a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tehdcsed.html

Ruby: s.count("a")
来源：http://dali.tianlin.xyz/Article/details/gt2xaeeqsqv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gt2jwmlutsp.html

[E13] 逐字符遍历
来源：http://dali.fzhhl.top/Article/details/gt2hiheodwo.html

Py:   for ch in s: print(ch)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ayfhtbog.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gt2ancmowuj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2bukhjgvb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ljspngdu.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xepxuuiv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2yjobhgmr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2kaoxcsig.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.haohaochexian.top/Article/details/gt2vrixwmxe.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gt2qylanjzw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xinyue.icu/Article/details/gt2ttsiqrlw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gt2aajgikyw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cashguo.top/Article/details/gt2tfeqscwq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gwmjkffb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gt2wfvalzxb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ppjwa.cn/Article/details/gt2cadrenyf.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gt2cieulrtq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guannengcc.top/Article/details/gt2vavvveqr.html

[E15] HTML 转义 / 反转义
来源：http://dali.havefunace.top/Article/details/gt2ckjykzoc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lrqqjsor.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gt2asklwznf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvfyehdd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gt2luklzmoa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jianghu66.top/Article/details/gt2cosyclmj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tianlin.xyz/Article/details/gt2cluwqspl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gt2xvaxgnck.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yuanzhike.top/Article/details/gt2sohxlrcw.html

[E16] 数字千分位
来源：http://dali.vqdsnc.cn/Article/details/gt2vievowff.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gt2bpxzqlkp.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gt2pzqeszfq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2hrteqfgw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gt2irrpdkvh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gzhubu.top/Article/details/gt2jukwozpp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinqigfzy.top/Article/details/gt2itaiabhl.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhixingplan.top/Article/details/gt2swwtspth.html

C#:   1234567.ToString("N0")
来源：http://dali.quarkkingdee.top/Article/details/gt2exffnqoj.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gt2gqxafack.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuanzx.com/Article/details/gt2upgdzxvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gt2wzuhvvnn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gt2lpfttlqd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2fnpcuuvv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guowangkeji.top/Article/details/gt2rqntqnxb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gt2gggkguyd.html

Ruby: s.capitalize
来源：http://dali.0kj1m.cn/Article/details/gt2zmxroepr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.fengsongda.top/Article/details/gt2pasiibbc.html

[E18] 模板占位符替换
来源：http://dali.wangdashe.top/Article/details/gt2glytahws.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yueranfly.top/Article/details/gt2fhhsowsb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gt2venepoyc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2pqikqdxv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tianlin.xyz/Article/details/gt2uqrjmmgv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2lrneevty.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2fohwnuxy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ppjwa.cn/Article/details/gt2hpdyqcts.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gt2wfhzjbqn.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gt2cvgkksbm.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gt2vhchkihf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gt2vzlrzayc.html

JS:   s.split(/\r?\n/)
来源：http://dali.jinqigufen.top/Article/details/gt2qrwqrcoz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gt2veyknakh.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gt2wnqjqwho.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2npmwydch.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gt2xrcbbfip.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gt2qtutzvve.html

[E20] 判断字符串是否为空
来源：http://dali.jinqigufen.top/Article/details/gt2pxazablg.html

Py:   if not s:
来源：http://dali.meibo888.top/Article/details/gt2nremqjmr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zycfv.cn/Article/details/gt2jbanbafr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.redwolf501.top/Article/details/gt2lehybptu.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gt2zgvybhju.html

Java: if (s.isEmpty()) {}
来源：http://dali.sufxvd.cn/Article/details/gt2xipcdmdq.html

Go:   if s == "" {}
来源：http://dali.chenlongwang.top/Article/details/gt2fwiusosd.html

Ruby: if s.empty?
来源：http://dali.cqqwz.cn/Article/details/gt2cotrawwi.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.pycfn.com/Article/details/gt2oixtuhzb.html

[E21] 超长截断加省略号
来源：http://dali.0kj1m.cn/Article/details/gt2pzadkrzv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gt2ycxueurt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gt2xkonzrbl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nwbrower.top/Article/details/gt2eemddsoh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2xclnxbhi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2dncarllx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gt2gjupsevs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gt2nnljmzvd.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2zzvtdvsl.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gt2wrehjgqh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2yvtvkrxx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2jhfaydxx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2ejvkgvus.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2fflrwyhy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2nzvecmrt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.guannengcc.top/Article/details/gt2pvutolbo.html

Ruby: s.bytesize;  s.length
来源：http://dali.yvedp.cn/Article/details/gt2zkvesfjf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gt2bvmfelnp.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fzmhdwkk.html

F. 文件与目录
来源：http://dali.haohaochexian.top/Article/details/gt2mtsmtsdk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2wdnoovxm.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gt2tausueoe.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gt2enjhzgld.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2jscxkpxq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yueranfly.top/Article/details/gt2uhhudgjn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gotoacloud.top/Article/details/gt2nrsyahpv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gt2rvesvanz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cqqwz.cn/Article/details/gt2djquybqu.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2kjevhzcs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2volohxez.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gt2tqkqsabc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yongpay.top/Article/details/gt2zpenptmo.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2kohbyodz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2zhaewffw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwkthbtk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gt2bxyqdmok.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gt2ywxvusly.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.smart0.xyz/Article/details/gt2epgxzvit.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gt2qywpqyxn.html

[F03] 写入文件（覆盖）
来源：http://dali.sweek.top/Article/details/gt2rdxcdcru.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.ppjwa.cn/Article/details/gt2izemwsia.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gt2qejtvvkb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gt2ppxmduqn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2codaadga.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenlongwang.top/Article/details/gt2eggmcsyq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj202588.top/Article/details/gt2ghkkshev.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shzxlz.cn/Article/details/gt2aieyhumr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gt2qjsxyfpl.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gt2fefouehy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gt2izkcycgw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gogol.net.cn/Article/details/gt2uziphtob.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2mpyyuydv.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gt2scgavtxf.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.pycfn.com/Article/details/gt2lpmsxobz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shzxlz.cn/Article/details/gt2gewvkxvq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tygtiyge.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgfzy.top/Article/details/gt2uzjxdpim.html

[F05] 判断文件或目录是否存在
来源：http://dali.yvedp.cn/Article/details/gt2xbijrzsw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gt2vyiumday.html

PHP:  file_exists("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2igwupiqv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2jatjjlsx.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bwawasib.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gt2inchyake.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ehwqpu.com/Article/details/gt2ivxowkkg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2riqaotfm.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2tstfofid.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gt2ucuosqli.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2owscvjon.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2jhxaavmi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2erhidvgy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2uwdfmqya.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gt2lraxbwbi.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2jmrkwfxl.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2biyaetan.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2wqdpbopz.html

[F07] 创建目录（含多级）
来源：http://dali.nanxinkj.top/Article/details/gt2llzrhlzt.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gt2wnbgosoe.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sweek.top/Article/details/gt2cibnifzw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.vqdsnc.cn/Article/details/gt2wlrocqjg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj202588.top/Article/details/gt2pbckolgx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hammf.cn/Article/details/gt2cyriwjot.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.fzhhl.top/Article/details/gt2qmlioikz.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.haohaochexian.top/Article/details/gt2wcyvbnpv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.gotoacloud.top/Article/details/gt2fwdbqugt.html

[F08] 遍历目录
来源：http://dali.vqdsnc.cn/Article/details/gt2qquvbrnu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2cdywtjpu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2czrzlqdd.html

JS:   fs.readdirSync("dir")
来源：http://dali.yongpay.top/Article/details/gt2fkspkisl.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2jlnooaqo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2thwjjcap.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtfjwbyh.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gt2olsaqtpt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xtjgsapf.html

[F09] 获取文件大小
来源：http://dali.ppjwa.cn/Article/details/gt2oakrsorw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yongpay.top/Article/details/gt2fisyrjbj.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigufen.top/Article/details/gt2mspnkavw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2aboquval.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ehwqpu.com/Article/details/gt2ryzmyefa.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2zswfessl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shzxlz.cn/Article/details/gt2wytpxewi.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oapzrrng.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.tianlin.xyz/Article/details/gt2cluaminz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhiwuduotai.top/Article/details/gt2segfssph.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hesvlnpx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2ltjqkhis.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2jgvvnrgj.html

TS:   path.extname("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2cfmvlmqg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gotoacloud.top/Article/details/gt2pseeoqwh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2rhjzxzzx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2xdgxexef.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2xcykclho.html

[F11] 复制与移动文件
来源：http://dali.yvedp.cn/Article/details/gt2ebliqytd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqxhsrdl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ksrezsxy.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2jljersoa.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2smisgngt.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.jinqigufen.top/Article/details/gt2zcxfhhpr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2bcgntaqs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2tiddynws.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.bjfxy.top/Article/details/gt2omufzpbt.html

[F12] CSV 读写
来源：http://dali.c1oappe.top/Article/details/gt2abbkwqql.html


<!-- 参考信息 -->