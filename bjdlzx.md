代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2edypsiss.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gt2xkegavao.html

[D25] Set 集合去重与交并差
来源：http://dali.ppjwa.cn/Article/details/gt2apacarej.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guowangkeji.top/Article/details/gt2wxdaoirq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.redwolf501.top/Article/details/gt2btxiiqbw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zdqjudy.top/Article/details/gt2oufvjqhd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gt2mesvqbgx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gt2flutuzoo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tian-w.cn/Article/details/gt2hnyieoez.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rtqbovmi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gt2xngcuzbb.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncpfidmb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gt2ugbqjath.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2nbsdemfe.html

JS:   arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gt2cdduplhu.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gt2qtfizklc.html

Java: String.join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gt2ttmzicky.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2llpdqpic.html

Ruby: arr.join(", ")
来源：http://dali.guannengcc.top/Article/details/gt2mmficejl.html

C#:   string.Join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gt2xcoswsmp.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2sfhokrry.html

E. 字符串处理
来源：http://dali.yj20258.top/Article/details/gt2tcahqpws.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2hrlokyci.html

[E01] 拼接字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwwgytnv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jlsjyb.cn/Article/details/gt2gbzexulw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gt2wgkhxfcs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aibaodan.cn/Article/details/gt2bvcfdgzn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2etslteuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ivvv.top/Article/details/gt2jrkwsvfu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sufxvd.cn/Article/details/gt2westqqca.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xinyue.icu/Article/details/gt2zhuqpetk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2yecosmiw.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2xjxtojjq.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vzsznuqk.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2lbjxlhju.html

JS:   "ab".repeat(3)
来源：http://dali.tanke756.top/Article/details/gt2qvhiyvid.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlocmswz.html

Java: "ab".repeat(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxjgxwjz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gt2wbhyllnf.html

Ruby: "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gt2znsvmqua.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.feifeiyinyue.top/Article/details/gt2heeytyxf.html

[E03] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gt2sgvhgfbe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjyahnay.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kdwluuxj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2cciykgdb.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gt2hxfvvzwc.html

Java: s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2xodtlntr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2zktzzygu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2xglgxqjz.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cppcmzbu.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gt2emnqpytj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.fengsongda.top/Article/details/gt2bemjgkwk.html

PHP:  strpos($s, "x");
来源：http://dali.mhx1999.top/Article/details/gt2iulffotw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ybcxt.top/Article/details/gt2xudwpqqb.html

TS:   s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2gghrdyzr.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gt2zbjltcsh.html

Go:   strings.Index(s, "x")
来源：http://dali.316326.xyz/Article/details/gt2tdmaquwq.html

Ruby: s.index("x")
来源：http://dali.sxryk.cn/Article/details/gt2vnmwgjgr.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gt2gsfwnajh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gt2hgyzgrdb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tanke756.top/Article/details/gt2aemomnno.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.quarkkingdee.top/Article/details/gt2baaywxxm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gt2covyjozl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gt2ldtfvgmv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2pqdcvfav.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sxryk.cn/Article/details/gt2carslcgw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2njphjhrf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gt2nzznfjyy.html

[E06] 替换子串
来源：http://dali.svipenyu.cn/Article/details/gt2dtpolcsd.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hfpthk.cn/Article/details/gt2rowgupbp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rqmzdcac.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvilkgmz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gt2hiwxmetb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gt2xrodsmfm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gt2crupcqns.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gt2obakniar.html

C#:   s.Replace("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gt2gvfaoxul.html

[E07] 按分隔符拆分
来源：http://dali.c1oappe.top/Article/details/gt2ngloiyzm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yonumen.top/Article/details/gt2tpmuhcab.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gt2jhaxgyaz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gt2wyrgeevp.html

TS:   s.split(",")
来源：http://dali.zhiwuduotai.top/Article/details/gt2izipbajh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ztdjcayj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aizwys.cn/Article/details/gt2lcjfpgls.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2ovbxisme.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gt2oerbdjqh.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gt2yrvqfkdo.html

Py:   ",".join(items)
来源：http://dali.nanxinkj.top/Article/details/gt2kclnizjm.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gt2zfxoprsf.html

JS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2dqnbtoos.html

TS:   items.join(",")
来源：http://dali.daxiang520.top/Article/details/gt2padtxnzr.html

Java: String.join(",", items)
来源：http://dali.zhixingplan.top/Article/details/gt2cxjxjfiq.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2geztylix.html

Ruby: items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2izxwndwe.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gt2xflstazh.html

[E09] 去除所有空白字符
来源：http://dali.yangfankeji.com/Article/details/gt2lqcmhrjx.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gt2molcftjj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tian-w.cn/Article/details/gt2dhxasviv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gt2nbhsgqyp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hywenlv.cn/Article/details/gt2pprvygfu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gt2qklvovoa.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2eczztere.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xylfe.cn/Article/details/gt2epbwvoql.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yuanzhike.top/Article/details/gt2htezwtjt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gt2csbwifnf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2xdshywee.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.bjfxy.top/Article/details/gt2vnohwsji.html

JS:   "7".padStart(3, "0")
来源：http://dali.cdnleiting.top/Article/details/gt2pfpdmnxc.html

TS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2qypovebb.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbhfexwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gt2embxinus.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gt2dthrygsk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gt2gpwqzfwv.html

[E11] 反转字符串
来源：http://dali.smart0.xyz/Article/details/gt2auhrjwzu.html

Py:   s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2armzkgtm.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2sfomtlim.html

JS:   [...s].reverse().join("")
来源：http://dali.gogol.net.cn/Article/details/gt2gubevhpb.html

TS:   [...s].reverse().join("")
来源：http://dali.dianchejie.cn/Article/details/gt2vnmwljpy.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigufen.top/Article/details/gt2fayytvxp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnqzz.top/Article/details/gt2kymexocq.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gt2shbcvion.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gt2ozogqgfh.html

[E12] 统计某字符出现次数
来源：http://dali.havefunace.top/Article/details/gt2rfjmzqcc.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gt2ooisxgzh.html

PHP:  substr_count($s, "a");
来源：http://dali.zhixingplan.top/Article/details/gt2kanzvldm.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2vkssawut.html

TS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gt2ohlxwrdi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gt2mgtxqyji.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2fdkrxnqo.html

Ruby: s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gt2rghyzmvo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.kuanghao11.cn/Article/details/gt2fcgumdhx.html

[E13] 逐字符遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2aamttcyy.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gt2zmuwxgge.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ayttjfph.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gt2bbmnlcsw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmptwbmx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2vszevdke.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnqzz.top/Article/details/gt2zpoivobu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.c1oappe.top/Article/details/gt2cinxbnye.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2hzftgqlu.html

[E14] URL 编码与 Base64
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmddugwk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gt2hxwdmvjd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gt2jjjcnlln.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gt2koljvrhd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2meolabpv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gt2ungttcqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258.top/Article/details/gt2zxoyczal.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hqqlljiv.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.guowangkeji.top/Article/details/gt2hpeqyrgr.html

[E15] HTML 转义 / 反转义
来源：http://dali.dianchejie.cn/Article/details/gt2kytcgqpr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangdashe.top/Article/details/gt2khnnembk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj202588.top/Article/details/gt2xhkrhcvb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2spscpjqx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxinkj.top/Article/details/gt2nrojxvtx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gt2czycvccz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.fengsongda.top/Article/details/gt2veqcudbf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gt2lldgjcfr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2aughtonf.html

[E16] 数字千分位
来源：http://dali.chenjidiqi.icu/Article/details/gt2andnioun.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gt2ztutznxe.html

PHP:  number_format(1234567);
来源：http://dali.pycfn.com/Article/details/gt2skjnpvgs.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gt2eyuheekk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gt2ctbpyubv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gt2lsvgdanr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gt2gjiqjkao.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2tgostbeg.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2zngehqtd.html

[E17] 首字母大写
来源：http://dali.hywenlv.cn/Article/details/gt2gwgfshek.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgfzy.top/Article/details/gt2bjnsvblx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.316326.xyz/Article/details/gt2kuvtrkgm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2yhgwtksh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gt2tofrucjl.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydjjuwyt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuetiantiany.cn/Article/details/gt2iotpaese.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2auoxqvyz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gt2nqceuxje.html

[E18] 模板占位符替换
来源：http://dali.ybcxt.top/Article/details/gt2wjurcakg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigfzy.top/Article/details/gt2sxomqmoc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2mlyihygi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fybkxphf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2azdneuuf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2udfuofkp.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2zxlotouf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.vqdsnc.cn/Article/details/gt2oxskjand.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jqgfzy.top/Article/details/gt2xjdrfsma.html

[E19] 多行文本按行拆分
来源：http://dali.chenjidiqi.icu/Article/details/gt2kkmxkjcg.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2wtoecqfa.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2luxetbmm.html

JS:   s.split(/\r?\n/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2toxrffka.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gt2lsxqninn.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gt2esnkaitn.html

Go:   strings.Split(s, "\n")
来源：http://dali.birdmap.top/Article/details/gt2obgeexrq.html

Ruby: s.lines
来源：http://dali.hywenlv.cn/Article/details/gt2vvxjnery.html

C#:   s.Split('\n')
来源：http://dali.smart0.xyz/Article/details/gt2mhugtwts.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gt2doeaisyu.html

Py:   if not s:
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zckoytox.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gt2uuinrimj.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gt2urdspgib.html

TS:   if (s === "") {}
来源：http://dali.yj202588.top/Article/details/gt2lafyswzw.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gt2cjwqatkd.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gt2hlmxmzsb.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmhqqjbv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gt2uedbrmjg.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2wfvntkhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gt2uyphqszg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gt2xqawlgaf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2hohlktnn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gt2wjbsetkh.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gt2dibukrik.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gt2lvhhevwn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gt2phuicqlb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2smoeguxy.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gt2tocfhqsu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gt2vgytlive.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.feifeiyinyue.top/Article/details/gt2vowogict.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ppjwa.cn/Article/details/gt2gkjmqiyt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2qeheudyn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gt2msqvlpws.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.kuanghao11.cn/Article/details/gt2uuyigiix.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvxcjdbu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hfpthk.cn/Article/details/gt2zpaudmxr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2lunzwiuv.html

F. 文件与目录
来源：http://dali.shangyingyoupin.top/Article/details/gt2uezhzxjf.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2ovxuseig.html

[F01] 读取整个文件
来源：http://dali.daria6918.cn/Article/details/gt2devurcup.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhixingplan.top/Article/details/gt2jukmhzpw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2scgtygto.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gt2lgvjtwou.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cashguo.top/Article/details/gt2dkrgoxyn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2scqjumuo.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenzaomai.com/Article/details/gt2jndqpfgk.html

Ruby: File.read("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dzkwzwfo.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangdashe.top/Article/details/gt2psugclxv.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gt2myqhwjdl.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2ynxudnhv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vnhfzorq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usjknhmk.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gt2zusvdydx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhoulong.xyz/Article/details/gt2kxlwopij.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gt2oodhglkt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqcmpbs.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2llczqytx.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2mpnrkomg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yonumen.top/Article/details/gt2lzyxsqio.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2iodfdfkq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhengqikj.top/Article/details/gt2ofcwbuze.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2afiahowc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenzaomai.com/Article/details/gt2fjmgwiqx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.snrcjt.cn/Article/details/gt2cngdkbjj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gt2ccjhvzen.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gt2bydjjkre.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gt2snirwugv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.haohaochexian.top/Article/details/gt2uwrlyatx.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.dianchejie.cn/Article/details/gt2olsmxnyf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2csoegveo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gt2gtrgpozp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2oqoqdeos.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yueranfly.top/Article/details/gt2ylpfyjzz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.fengsongda.top/Article/details/gt2gtupkxbt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2whiwmdgz.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gt2dqltytda.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gt2vsxvwvdo.html

PHP:  file_exists("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2vjihmpyl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2briipdmv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2qoungmcd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gt2tgqzwkjj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gt2mnaectno.html

Ruby: File.exist?("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2ykikzjnt.html

C#:   File.Exists("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2brovjokx.html

[F06] 删除文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftreiswr.html

Py:   os.remove("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2yjrlujsp.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gt2tcajdhai.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rzdlxqbs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2suqobqjo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gt2slnbfjda.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2dbiqtvbj.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2pwojuwwq.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2zpfektsk.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2itykojen.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2deblywie.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hysaishi.cn/Article/details/gt2kamgvcow.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2vcawpeqy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ydzc1.top/Article/details/gt2qgssubfn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gt2aniqjghj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gt2rdennehw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.guannengcc.top/Article/details/gt2eyobsieh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.quarkkingdee.top/Article/details/gt2ywgkzzpf.html

[F08] 遍历目录
来源：http://dali.guannengcc.top/Article/details/gt2iqubqchc.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hnxiangtu.top/Article/details/gt2wglgutof.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xinyue.icu/Article/details/gt2sjextzxh.html

JS:   fs.readdirSync("dir")
来源：http://dali.ivvv.top/Article/details/gt2lcvdncpd.html

TS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2bgydwuku.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.zdqjudy.top/Article/details/gt2rfrixlrl.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2bdeetsqs.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gt2ztcepjmh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcmaufzk.html

[F09] 获取文件大小
来源：http://dali.zdqjudy.top/Article/details/gt2jtzsjoow.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2qfcfvavn.html

PHP:  filesize("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2kfcfbgcv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gt2owauiblq.html


<!-- 参考信息 -->