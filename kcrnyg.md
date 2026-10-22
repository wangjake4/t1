代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2nqtlpuzn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gt2fqvakkyo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gt2wxemovnl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gt2ofnxmqju.html

[E02] 重复字符串
来源：http://dali.yongpay.top/Article/details/gt2oqdxsqye.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2upckwbdv.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xinyue.icu/Article/details/gt2arktsjmf.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zaofjbhq.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gt2xwjxzbuy.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gt2fwhsfweb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncupyzsd.html

Ruby: "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gt2ditwofbx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2ynsvptrx.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gt2bvwvnrvl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxuanxn.top/Article/details/gt2chpfxbgb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gt2tivdncff.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2xdjkgknm.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2ixnfvesz.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2mifxhmyy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gt2fhhfckxw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ppjwa.cn/Article/details/gt2vaosgicp.html

C#:   s.Substring(1, 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2jtxsuehc.html

[E04] 查找子串位置
来源：http://dali.cqqwz.cn/Article/details/gt2ybtodwyn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2cwcxtnsg.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wyrxscqh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuehvizt.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gt2nvupfyts.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gt2qdwsloqf.html

Go:   strings.Index(s, "x")
来源：http://dali.sysykeji.top/Article/details/gt2hvxiduey.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gt2lryliprf.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gt2fnutordr.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gt2kwfyefsc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gt2wqaldyap.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gt2gexzolif.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gt2olqzvktk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hfpthk.cn/Article/details/gt2oibcstnj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2locvjyur.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenlongwang.top/Article/details/gt2fowbuven.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlausklu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gt2dntdooxe.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2cukmzkif.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zdqjudy.top/Article/details/gt2hdorgsvi.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gt2mxzuqfji.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2qipwvohl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gt2wltplmpz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2vqycavzl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2pmopjnme.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gt2bqxoeugy.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2lpfqjvnw.html

[E07] 按分隔符拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scbabvmn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gt2vfqyfzlz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2ozeuphyw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj20258888.top/Article/details/gt2obxxlqan.html

TS:   s.split(",")
来源：http://dali.ivvv.top/Article/details/gt2lurhsajy.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sxryk.cn/Article/details/gt2xjncwnzo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yvedp.cn/Article/details/gt2rbdsozgr.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gt2fwpufkrd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sweek.top/Article/details/gt2trorsspm.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gt2sogmoknt.html

Py:   ",".join(items)
来源：http://dali.gogol.net.cn/Article/details/gt2pgwwfgdn.html

PHP:  implode(",", $items);
来源：http://dali.jqgufenzy.top/Article/details/gt2wbhgkwmc.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2ilblqoxi.html

TS:   items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2vzrdwhes.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2qmqrknhy.html

Go:   strings.Join(items, ",")
来源：http://dali.nwbrower.top/Article/details/gt2darcilqe.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gt2orcjrmtn.html

C#:   string.Join(",", items)
来源：http://dali.0kj1m.cn/Article/details/gt2frvkxksl.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gt2efttulkc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gt2tgholifx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuanzx.com/Article/details/gt2ycafrnfj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.bjfxy.top/Article/details/gt2izflvhrq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.redwolf501.top/Article/details/gt2jmvzhcui.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2btzfiuae.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.vqdsnc.cn/Article/details/gt2qmnmefut.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gt2eghacxam.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2exxmtbop.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ivvv.top/Article/details/gt2mrtegbuf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yongpay.top/Article/details/gt2ksfvuood.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hfpthk.cn/Article/details/gt2spfqmnok.html

JS:   "7".padStart(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gt2jpglkpwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.zycfv.cn/Article/details/gt2gemnkkgm.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dfrveapl.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2xhvzvwqm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zgfrehkv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gt2jaungwwj.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2euppyhah.html

Py:   s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2brjhlixe.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ngtjmxmp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2npykdfmq.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gt2xhxsdcco.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2oigxrxor.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jinqigufen.top/Article/details/gt2rzcfilxn.html

Ruby: s.reverse
来源：http://dali.ehwqpu.com/Article/details/gt2gmxaomlf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhixingplan.top/Article/details/gt2fgedewdi.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2tblgywse.html

Py:   s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdrrqznu.html

PHP:  substr_count($s, "a");
来源：http://dali.zhongyouzk.top/Article/details/gt2hymaawud.html

JS:   s.split("a").length - 1
来源：http://dali.hnxiangtu.top/Article/details/gt2roaivoms.html

TS:   s.split("a").length - 1
来源：http://dali.316326.xyz/Article/details/gt2fhftrbmj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2edoacpme.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbwmdzbq.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mjwwiazc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sufxvd.cn/Article/details/gt2mdttarwk.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gt2omxsbkkb.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgufenzy.top/Article/details/gt2eoihidyu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2nfxmthtd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2wymntfrf.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcftumxt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gt2nsvxkkad.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.0kj1m.cn/Article/details/gt2bqmqldbr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gt2kvnlcpyp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2kknscflh.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gt2cwqzeuej.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2qxacqupi.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.redwolf501.top/Article/details/gt2wfrgvrwz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gt2dswawhze.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gt2lluvihjg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gogol.net.cn/Article/details/gt2sicjbala.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gt2chwgnokv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gaohongyu789.top/Article/details/gt2uvqkuows.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhixingplan.top/Article/details/gt2srnmkcms.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gt2mjmphnrg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ofnpcryd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2oumdpyys.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2fuetmneq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zdqjudy.top/Article/details/gt2qtwmnnpq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ehwqpu.com/Article/details/gt2vurtszev.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gt2umfpimms.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ppjwa.cn/Article/details/gt2zybeovab.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtbvcqhn.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gt2noccgwpb.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2kwoafprw.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2slvjccqe.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2zdacoxvs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2bomykknk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2ahufthie.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2iwtctgnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.kuanghao11.cn/Article/details/gt2ebxqbhtz.html

C#:   1234567.ToString("N0")
来源：http://dali.shuidangran.top/Article/details/gt2phmorbuy.html

[E17] 首字母大写
来源：http://dali.gogol.net.cn/Article/details/gt2rmvqkayg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hysaishi.cn/Article/details/gt2qnbnsiyg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.pycfn.com/Article/details/gt2yurbpgjc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gt2uqgrxvej.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gt2cwncyxrq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2dfrqcfjr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gt2wmwckeew.html

Ruby: s.capitalize
来源：http://dali.ydzc1.top/Article/details/gt2zvfkbwby.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2zjxfxhou.html

[E18] 模板占位符替换
来源：http://dali.gotoacloud.top/Article/details/gt2klmmzofk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jlsjyb.cn/Article/details/gt2kqubcuyk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gt2tberyfcm.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2dncjczcn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gdhvhatg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2wakhngbz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2agwrqpfd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gt2ksxunyjb.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gt2ygxxrige.html

[E19] 多行文本按行拆分
来源：http://dali.fzhhl.top/Article/details/gt2txpkqlzn.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gt2phnibemr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2pmjyfnsj.html

JS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gt2ofamlrvh.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gt2hthhmuxk.html

Java: s.lines().toList()
来源：http://dali.sufxvd.cn/Article/details/gt2ylftfthz.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gt2ytrnzglu.html

Ruby: s.lines
来源：http://dali.fzhhl.top/Article/details/gt2imfllbmg.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wutncrnv.html

[E20] 判断字符串是否为空
来源：http://dali.yuanzhike.top/Article/details/gt2wexocrpw.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gt2pdbbhrxh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gt2ssttalvf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gt2nmlhzcfi.html

TS:   if (s === "") {}
来源：http://dali.shuidangran.top/Article/details/gt2atgrdibn.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2fgnfrtvj.html

Go:   if s == "" {}
来源：http://dali.c1oappe.top/Article/details/gt2pmpntous.html

Ruby: if s.empty?
来源：http://dali.0kj1m.cn/Article/details/gt2xqkfgwef.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.havefunace.top/Article/details/gt2mnndhijq.html

[E21] 超长截断加省略号
来源：http://dali.pengpengdd.cyou/Article/details/gt2kiigyeug.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuanzhike.top/Article/details/gt2pmwnbrzh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2xsidaesa.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2dfjtmgxw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2ozgycrbi.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtgyxgxm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.quarkkingdee.top/Article/details/gt2rgprwjrn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2iiyifgif.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gt2fviohqgw.html

[E22] 字节长度与字符长度
来源：http://dali.hysaishi.cn/Article/details/gt2ifqvhdqj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xziqi.cn/Article/details/gt2blbmqiwb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jbpbeodp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2klpetwjy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2vxjaoyht.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cheryme.top/Article/details/gt2ntafdsbn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gt2vhcjjqtt.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2hgksqpjn.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gt2uiwkwcaq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2avrfywlf.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2zpeqbnhc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dtcvjyqe.html

[F01] 读取整个文件
来源：http://dali.yongpay.top/Article/details/gt2iedeqhtf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hysaishi.cn/Article/details/gt2lkqmyduw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxfgujy.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zycfv.cn/Article/details/gt2owluhutf.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yjqjtmxx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2oergfzez.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.snrcjt.cn/Article/details/gt2mocvqvuk.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtucifsn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2ujdxiddc.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gt2wmoycrlw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dianchejie.cn/Article/details/gt2iwpfjxfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.tanke756.top/Article/details/gt2hoixaunk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cdnleiting.top/Article/details/gt2svveakij.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tsspcepu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2sfatezyq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gt2oparvnhy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gt2qgzcroog.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cqqwz.cn/Article/details/gt2axrjgswj.html

[F03] 写入文件（覆盖）
来源：http://dali.wangdashe.top/Article/details/gt2suqcfaqs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2oleebitg.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2scyqggkw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guannengcc.top/Article/details/gt2jugfuqlr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2ovmymfyr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gt2xcdeiufn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2owyzluvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guowangkeji.top/Article/details/gt2oonnaulp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.daxiang520.top/Article/details/gt2ixmssatv.html

[F04] 追加写入文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqmrgyue.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2trpyrtjn.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gt2rscbxwbo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2euksednn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gt2xwcdilja.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.meibo888.top/Article/details/gt2uypskyct.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gt2shzakrwy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2pfichehs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hywenlv.cn/Article/details/gt2zcnbrkxt.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gt2gtujoyds.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2rjvtezop.html

PHP:  file_exists("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2zuuvmnmb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2daootoho.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2jymzrdjx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2jezgbeot.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.0kj1m.cn/Article/details/gt2uydeqcnx.html

Ruby: File.exist?("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2mjaoiofr.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2sttzmqqt.html

[F06] 删除文件
来源：http://dali.yj20258888.top/Article/details/gt2vygunofx.html

Py:   os.remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2fmisqzmm.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2reybswhu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2sghleuie.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2opdgptov.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yanxiufei.cn/Article/details/gt2xnzpyqao.html

Go:   os.Remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2nqachuko.html

Ruby: File.delete("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2rsqkmekw.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gt2fqcewmos.html

[F07] 创建目录（含多级）
来源：http://dali.316326.xyz/Article/details/gt2uhdhsvzq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2oxhomypn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.havefunace.top/Article/details/gt2tkxrhxle.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gt2xhkzqwzb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.guowangkeji.top/Article/details/gt2zekiusgo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tanke756.top/Article/details/gt2pzkzezzi.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.andypj.xyz/Article/details/gt2ivfrhrjm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2yssnpjjh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sufxvd.cn/Article/details/gt2rkhecbxr.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpaposkm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.dashuyun.cn/Article/details/gt2uwzfpglq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.quarkkingdee.top/Article/details/gt2kogmwaam.html

JS:   fs.readdirSync("dir")
来源：http://dali.fzhhl.top/Article/details/gt2rarpyzmk.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gt2wezkmevv.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gt2stscrlxb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2bokkkrws.html

Ruby: Dir.children("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fedtagmx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2aruyuvsz.html

[F09] 获取文件大小
来源：http://dali.aibaodan.cn/Article/details/gt2qsgnziyh.html

Py:   os.path.getsize("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2dpwehsxm.html

PHP:  filesize("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2qgkefdge.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jyoumei.cn/Article/details/gt2bznikhhw.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tebriybj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2mbhquwbc.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2vwchefwg.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2puddjoed.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jyoumei.cn/Article/details/gt2zdxldnqp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.daria6918.cn/Article/details/gt2ppefqnma.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2dhrgqedo.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2cnmtbiyw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dhmnwqwx.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2falfvgka.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ppjwa.cn/Article/details/gt2nhnpmplj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gt2iqhzndhy.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2iipydwsb.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2vqiikgai.html

[F11] 复制与移动文件
来源：http://dali.dashuyun.cn/Article/details/gt2efhaoizb.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2sdphbomy.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nwbrower.top/Article/details/gt2rcwmzjvh.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gt2xvgdubnt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2bhnckymf.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjlscwxd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.tianlin.xyz/Article/details/gt2elmslsfb.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2fmqjtscr.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.birdmap.top/Article/details/gt2lfwuyebz.html

[F12] CSV 读写
来源：http://dali.shzxlz.cn/Article/details/gt2vlfnrmsn.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ybcxt.top/Article/details/gt2xpqzvsao.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.xuetiantiany.cn/Article/details/gt2qxnexnpa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yangfankeji.com/Article/details/gt2dciuummz.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2qqbuhbif.html


<!-- 参考信息 -->