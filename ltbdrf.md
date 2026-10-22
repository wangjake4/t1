代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.birdmap.top/Article/details/gt2jqkksohq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gt2gjlnxuua.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gt2ghkkdkmb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2drceborb.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2vmxywqkf.html

Py:   "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2xibrhdwn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gt2zhjrypdu.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gt2hfznxejm.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gt2zgutlwoq.html

Java: "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gt2keymkmsk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hammf.cn/Article/details/gt2bhcczfhq.html

Ruby: "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gt2reahxeqp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tian-w.cn/Article/details/gt2eyhuuuub.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfmrkufn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yangfankeji.com/Article/details/gt2hofnedyx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2ekgdwchk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gt2uhzqavhw.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2gjlkytpg.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2zrhfgjqg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2bzixrbml.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsumejii.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgufenzy.top/Article/details/gt2kayrodqc.html

[E04] 查找子串位置
来源：http://dali.chenjidiqi.icu/Article/details/gt2pnuswmbw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgzbvnzd.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gt2osrukypq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gt2yxbjegda.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2hkisygpp.html

Java: s.indexOf("x")
来源：http://dali.yuanzhike.top/Article/details/gt2bgbfmxdz.html

Go:   strings.Index(s, "x")
来源：http://dali.0kj1m.cn/Article/details/gt2uxackllm.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2tvbsjsvr.html

C#:   s.IndexOf("x")
来源：http://dali.xziqi.cn/Article/details/gt2zhhihfil.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yongpay.top/Article/details/gt2pcemwpqz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gt2cdehrarg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.316326.xyz/Article/details/gt2qiceqokz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kqeyaemf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gt2zpxrauzq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxqqzzsd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gt2pdfnzfbp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gt2iezrkjvd.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2vtmspllc.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gt2jofjtjjz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gt2cnexcjpd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uuwjshio.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2oxypimbt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2pczcszkd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gt2isnbucns.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gtkyhipm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ognztcqi.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gt2igyuywfa.html

[E07] 按分隔符拆分
来源：http://dali.nwbrower.top/Article/details/gt2uwgezqcv.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gt2srknkizn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2hxdoiogf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.gaohongyu789.top/Article/details/gt2rkddfaiy.html

TS:   s.split(",")
来源：http://dali.zhoulong.xyz/Article/details/gt2gynvmirq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.havefunace.top/Article/details/gt2xnjbaccv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2zuibiubl.html

Ruby: s.split(",");  s.split
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqtodtny.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daria6918.cn/Article/details/gt2owaujvju.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gt2xnmtkjla.html

Py:   ",".join(items)
来源：http://dali.quarkkingdee.top/Article/details/gt2vaqhfmsf.html

PHP:  implode(",", $items);
来源：http://dali.aibaodan.cn/Article/details/gt2etnbimtw.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gt2trkkxkei.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2tpplepfj.html

Java: String.join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gt2wxxrrprk.html

Go:   strings.Join(items, ",")
来源：http://dali.svipenyu.cn/Article/details/gt2cnwvbrep.html

Ruby: items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gt2naqhuxge.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gt2rpkidztw.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gt2epburrci.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yanxiufei.cn/Article/details/gt2ojxibrjm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2slotccsf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2mzqqytfh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hammf.cn/Article/details/gt2lgseautq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gt2vcgxbszd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gt2lsuyhjws.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gt2hzuxqebw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sufxvd.cn/Article/details/gt2ezabevvo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtzanxkl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhongyouzk.top/Article/details/gt2vegrdeji.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gt2eogoctlz.html

JS:   "7".padStart(3, "0")
来源：http://dali.xziqi.cn/Article/details/gt2mfbeakhj.html

TS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gt2crmpleoi.html

Java: String.format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2aphftdrl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2ngacjgyg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhixingplan.top/Article/details/gt2xulihxib.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ydzc1.top/Article/details/gt2qudzafuj.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gt2iagivlgj.html

Py:   s[::-1]
来源：http://dali.yj202588.top/Article/details/gt2dacvfvie.html

PHP:  strrev($s);
来源：http://dali.ivvv.top/Article/details/gt2gibjvaoj.html

JS:   [...s].reverse().join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uaixrcyy.html

TS:   [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gt2lkvpncyx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gt2iehuudon.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gt2esiswmiu.html

Ruby: s.reverse
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnangefp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuxming.cn/Article/details/gt2nnjiibjb.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gt2eslkryio.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gt2janjhxld.html

PHP:  substr_count($s, "a");
来源：http://dali.jianghu66.top/Article/details/gt2beceiewe.html

JS:   s.split("a").length - 1
来源：http://dali.yvedp.cn/Article/details/gt2caubvkhh.html

TS:   s.split("a").length - 1
来源：http://dali.yueranfly.top/Article/details/gt2qqrjrmur.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gt2ertdvuxn.html

Go:   strings.Count(s, "a")
来源：http://dali.nwbrower.top/Article/details/gt2llacezoq.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gt2aztvfmrf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jiagoushi.top/Article/details/gt2itqjdjgz.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2miickoca.html

Py:   for ch in s: print(ch)
来源：http://dali.feifeiyinyue.top/Article/details/gt2smcndxey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.chenlongwang.top/Article/details/gt2udsdohfc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gt2rwgasqhe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ydzc1.top/Article/details/gt2amoayfpv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2luihriyf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2juanhtpk.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hysaishi.cn/Article/details/gt2epfxbxxu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qwbgkzih.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owvwhrkr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.wangshuangyany.cn/Article/details/gt2vhcbsxdq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gt2jtdqoxts.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhoulong.xyz/Article/details/gt2auugfnoo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2reodfihg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gt2esethdeu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yongpay.top/Article/details/gt2hpvkuctv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gt2sqnanwvu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.andypj.xyz/Article/details/gt2kllhwrkd.html

[E15] HTML 转义 / 反转义
来源：http://dali.gzhubu.top/Article/details/gt2zxdxlbmg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2iwmnswoa.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gt2drpgrwxj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nanxinkj.top/Article/details/gt2zbjiavag.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2drkyjvyn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eiezlunp.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2jtbgaqdg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwhlmltw.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gt2obhqrfbo.html

[E16] 数字千分位
来源：http://dali.yueranfly.top/Article/details/gt2pcpmpild.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gt2ozfybphg.html

PHP:  number_format(1234567);
来源：http://dali.ehwqpu.com/Article/details/gt2kbduetln.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.feifeiyinyue.top/Article/details/gt2npwkzwbd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2ooophstv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gt2wlvooiuw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yongpay.top/Article/details/gt2xzbztooh.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.c1oappe.top/Article/details/gt2fjonyfta.html

C#:   1234567.ToString("N0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvkdxmuf.html

[E17] 首字母大写
来源：http://dali.birdmap.top/Article/details/gt2xjdrsmbe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gt2vmslxnay.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jianghu66.top/Article/details/gt2sclnhqvn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gt2vbsvyyyq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gt2olgwbsxj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sxryk.cn/Article/details/gt2vvxjpjxn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gt2fpblcjrz.html

Ruby: s.capitalize
来源：http://dali.pengpengdd.cyou/Article/details/gt2gzdafrqu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2orddqaii.html

[E18] 模板占位符替换
来源：http://dali.xziqi.cn/Article/details/gt2xfiybapu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cdnleiting.top/Article/details/gt2wdeqwtor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gt2rovrgava.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2bzsusvjk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gt2boxcesds.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gt2wowhvdzy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2nxjobyro.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gt2mndtpbvb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gt2uhqxjsrm.html

[E19] 多行文本按行拆分
来源：http://dali.gotoacloud.top/Article/details/gt2gochcppp.html

Py:   s.splitlines()
来源：http://dali.birdmap.top/Article/details/gt2avapfxbe.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2alahmbwh.html

JS:   s.split(/\r?\n/)
来源：http://dali.chenzaomai.com/Article/details/gt2ejgwaiku.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gt2kgijiyyk.html

Java: s.lines().toList()
来源：http://dali.316326.xyz/Article/details/gt2uviultxc.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koankfwh.html

Ruby: s.lines
来源：http://dali.tian-w.cn/Article/details/gt2vjuycggt.html

C#:   s.Split('\n')
来源：http://dali.tianlin.xyz/Article/details/gt2norvmnzj.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gt2ltfcsheq.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gt2fazyqrdk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gt2ziiryrgy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.meibo888.top/Article/details/gt2vegjumfz.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gt2akcqckkd.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgshgxyh.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gt2dywfalvo.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gt2ngyfsyks.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gt2vwzsymjo.html

[E21] 超长截断加省略号
来源：http://dali.jinqigfzy.top/Article/details/gt2ekovzxhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.kuanghao11.cn/Article/details/gt2eartvotk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gt2fiwhyoke.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gt2xnzzulsu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2thbozjqc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2teezutxz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nwbrower.top/Article/details/gt2dflzfupw.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2jrksqnxt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yueranfly.top/Article/details/gt2eaemxzej.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2krypgcqx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2ytlbhqne.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yongpay.top/Article/details/gt2bzaggsli.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yueranfly.top/Article/details/gt2vdxbnjfx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenzaomai.com/Article/details/gt2tntnjnvj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xziqi.cn/Article/details/gt2yrncdxjz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gt2nkxfzkos.html

Ruby: s.bytesize;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2fpquetkn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.smart0.xyz/Article/details/gt2ggtqiujj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2kvejhgpl.html

F. 文件与目录
来源：http://dali.ydzc1.top/Article/details/gt2ghzkndex.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2wagknsun.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gt2gdujbacj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.fengsongda.top/Article/details/gt2zrmszhfm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2xrwqoqfw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.wangshuangyany.cn/Article/details/gt2efzhexjr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2jyqxwcqk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gt2himjfqud.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bgtoxboo.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uqvzoxpr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zycfv.cn/Article/details/gt2ohdsorus.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gt2ugzucngq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zycfv.cn/Article/details/gt2zerxtqis.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gt2gogpwkzg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pzzvsxyp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.havefunace.top/Article/details/gt2zusjrhev.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2obvbudub.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gt2mkszesol.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gt2itrzcujj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj202588.top/Article/details/gt2xerjzzez.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2kyvtapkq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2nzsfofxn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cashguo.top/Article/details/gt2gfsqtfnw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yangfankeji.com/Article/details/gt2ledouuqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nwbrower.top/Article/details/gt2gouopqze.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2wdjvwqqf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydejebcg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2uejxbmrb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hysaishi.cn/Article/details/gt2vjwyqzam.html

[F04] 追加写入文件
来源：http://dali.yangfankeji.com/Article/details/gt2ohyojqxo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2dugjbgas.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.cucudq.cn/Article/details/gt2fwlovagp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gt2lecjvzeo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gt2njdhgrne.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2tqtbymzm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.316326.xyz/Article/details/gt2johrgabi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.316326.xyz/Article/details/gt2hxcqkssn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2aleiccjz.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gt2fiponwxs.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinqigufen.top/Article/details/gt2drtanrmd.html

PHP:  file_exists("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2ehkbojkk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gt2nqudntji.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2lfnkguuf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2vvolyjyc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbalpmgl.html

Ruby: File.exist?("a.txt")
来源：http://dali.meibo888.top/Article/details/gt2utaimutx.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvynpjox.html

[F06] 删除文件
来源：http://dali.fengsongda.top/Article/details/gt2mhzugmbj.html

Py:   os.remove("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2vtzkkmmp.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2gqibdqnt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2vdcthwdy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2ltnzfkeh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2chdopusf.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2uiepumov.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2gtisqval.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2fehnqmpw.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2dgivhrsb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.dashuyun.cn/Article/details/gt2knoepkua.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gt2kpmshtul.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gt2nwceuzvm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2qhgqjpoa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gt2hhfzgqyu.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gt2hguvarzp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gt2clmdqhzy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xziqi.cn/Article/details/gt2irfppbsq.html

[F08] 遍历目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxleykpc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zfizqafq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2btlyozyl.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gt2yrpnfzao.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2vyfrunaw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyfxsbwg.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.daxiang520.top/Article/details/gt2qywyguff.html

Ruby: Dir.children("dir")
来源：http://dali.yueranfly.top/Article/details/gt2narjgwpg.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yanxiufei.cn/Article/details/gt2onxlvgxc.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2orfdgrcv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dpmaxnpl.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2amjnrruz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cashguo.top/Article/details/gt2gnbzzzof.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gt2dnrkzukj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gt2bastypqc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qbtgevzs.html

Ruby: File.size("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ftdcgihr.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrpgmzkz.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.fengsongda.top/Article/details/gt2tynhvogt.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2kwfpknmu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yonumen.top/Article/details/gt2wjpzophu.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2cqedawjw.html

TS:   path.extname("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2psqxdkvg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hysaishi.cn/Article/details/gt2zzjrsarf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2tgxnctkh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2yxsrizqg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2qjffmebp.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2xpvwgsyz.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2phjzlepx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2oldnxkce.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2yvasamrd.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2ijuxweqr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gt2iosthhhn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gt2yepnmyji.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gt2imlgaamj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zdqjudy.top/Article/details/gt2mozhfbko.html

[F12] CSV 读写
来源：http://dali.yvedp.cn/Article/details/gt2vzkudtni.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hammf.cn/Article/details/gt2kkhqrfnq.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwsyrsip.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ehwqpu.com/Article/details/gt2tbaqfrkh.html

TS:   // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iuganifj.html


<!-- 参考信息 -->