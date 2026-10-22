代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gt2udpxpktm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.fengsongda.top/Article/details/gt2vmlergog.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gt2woybywft.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenlongwang.top/Article/details/gt2ajirxllx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jyoumei.cn/Article/details/gt2fcxtynne.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhixingplan.top/Article/details/gt2yeezwtcy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gt2jtrjsdvl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.smart0.xyz/Article/details/gt2vqjdfntq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cheryme.top/Article/details/gt2oiencrsg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cucudq.cn/Article/details/gt2jljyfogx.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2rflpjyck.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gt2uwxgjjes.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2rviicexm.html

PHP:  implode(", ", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2ekfdvhgq.html

JS:   arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gt2tkjhliti.html

TS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gt2rmxsaqlg.html

Java: String.join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gt2luxuxnot.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cqqwz.cn/Article/details/gt2ozrmrxxt.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2friorygu.html

C#:   string.Join(", ", list)
来源：http://dali.chenlongwang.top/Article/details/gt2prswniqi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iorlbfhc.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2iznjylia.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2smsadyes.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2nzmktlqv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.daxiang520.top/Article/details/gt2yrvyjzss.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gt2gpwkpjdw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2jnlyalqs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ybcxt.top/Article/details/gt2wbtryycj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cltrwxer.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gt2htgxfqka.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jqgufenzy.top/Article/details/gt2bcmuuonk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vqneolzt.html

[E02] 重复字符串
来源：http://dali.gzhubu.top/Article/details/gt2ngxruzpr.html

Py:   "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gt2nycjkqmf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcwrdevv.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mrhisfro.html

TS:   "ab".repeat(3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jdivqssv.html

Java: "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dwlxitkt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlsjvwqh.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gt2dczddcnj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gt2riyotaaj.html

[E03] 截取子串
来源：http://dali.aibaodan.cn/Article/details/gt2ypfblxmz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.fzhhl.top/Article/details/gt2hdoixbre.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sweek.top/Article/details/gt2pfffdgsw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2irsxotvo.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gt2esovndmz.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gt2xouwfxnx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gt2lljctaot.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2wnzrimvb.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gt2dfpnsevu.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gt2tdcolrgi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gt2jwjyxgoc.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gt2yhwietuz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinqigufen.top/Article/details/gt2dgputtox.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gt2boqiyvhu.html

Java: s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gt2ihcqigcl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gt2zfroyupj.html

Ruby: s.index("x")
来源：http://dali.jqgufenzy.top/Article/details/gt2zkmxfqoj.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2atzoabrb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iaekuhtq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gt2kkuksfaa.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gt2aarkychw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypyjoyec.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gt2jhhlploh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gt2ukdjadhg.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gt2ffpqgbix.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gt2muxevurv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gt2ruyqdgsj.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gt2kfcclfeu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2acbycbdv.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gt2xebozypb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2krqxccpd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2yrimzsgy.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2fveasfsi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.vqdsnc.cn/Article/details/gt2qkgmalad.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gt2kxlxvdyk.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2kmsogrcc.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmizneuh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhongyouzk.top/Article/details/gt2xxfsxxxo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.fengsongda.top/Article/details/gt2bfulfhxz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenlongwang.top/Article/details/gt2bsnzlara.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gt2xnjwohri.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.smart0.xyz/Article/details/gt2xlhthzyt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gt2jpzfbcex.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gt2pcpqxvbe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbrdotwi.html

[E08] 数组按分隔符合并
来源：http://dali.dashuyun.cn/Article/details/gt2bwkyuugu.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gt2wxhlkwwn.html

PHP:  implode(",", $items);
来源：http://dali.zhoulong.xyz/Article/details/gt2ysovqaee.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gt2ptnswhdq.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gt2acfrebtp.html

Java: String.join(",", items)
来源：http://dali.yvedp.cn/Article/details/gt2ysqkogbj.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gt2jbxyyjsk.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gt2tatxfolk.html

C#:   string.Join(",", items)
来源：http://dali.guannengcc.top/Article/details/gt2qawgjswv.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gt2lxsfnbsz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kckdnuwx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.316326.xyz/Article/details/gt2dctklyhb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2evaagmxp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2oimejrzk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gt2pbjefftv.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.316326.xyz/Article/details/gt2qqxiismy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.tianlin.xyz/Article/details/gt2pivzuhmn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gt2esdyophz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gt2uknacvzl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2mezzemxc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tian-w.cn/Article/details/gt2lfnclxtw.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2lhbtbhmg.html

TS:   "7".padStart(3, "0")
来源：http://dali.shuidangran.top/Article/details/gt2qdiqleej.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gt2dfqrzycd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gt2atieanqf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xinyue.icu/Article/details/gt2vudgqyhk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjyygbc.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2guprjxxr.html

Py:   s[::-1]
来源：http://dali.fengsongda.top/Article/details/gt2gfecvyne.html

PHP:  strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gt2ybrdixwn.html

JS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tpyyyqna.html

TS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gt2tcrlsuze.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.smart0.xyz/Article/details/gt2fpxhkqkn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.vqdsnc.cn/Article/details/gt2hfcllxvy.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gt2kjtjexwp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2yzgknymb.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2hyuqttcd.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gt2jnkjuopj.html

PHP:  substr_count($s, "a");
来源：http://dali.guowangkeji.top/Article/details/gt2gevfsjls.html

JS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gt2skggktzu.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gt2wguycklm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sysykeji.top/Article/details/gt2hymnuwzu.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2yohqdoms.html

Ruby: s.count("a")
来源：http://dali.sweek.top/Article/details/gt2vogdzxyb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gt2tfmxnwnf.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gt2riuiypgr.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2drykdsev.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cgdvvzjn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gt2xmjslmtg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gt2nwcguvxx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2affkkovj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gt2swtgonho.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.andypj.xyz/Article/details/gt2iguuivay.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xinyue.icu/Article/details/gt2rrlxywgi.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gt2nzziygfd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gt2dvlqjenw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ezxwdkpv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gt2edrnfgrt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zeozyuru.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yongpay.top/Article/details/gt2nzkctaej.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zycfv.cn/Article/details/gt2nrixvhpv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gt2ziqbgfus.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ydzc1.top/Article/details/gt2gncqfsbp.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zbnubjob.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gt2wysbufoc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yj20258888.top/Article/details/gt2nqsufjwc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jfccnkyi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2rmuzkkra.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rkxokhql.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2bjxkkoel.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yonumen.top/Article/details/gt2iyihxllx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sysykeji.top/Article/details/gt2dsnhzgzv.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2kqemsrmv.html

Py:   f"{1234567:,}"
来源：http://dali.xziqi.cn/Article/details/gt2tvhmodga.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gt2lrhwvhcd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gt2eexeuqmg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yueranfly.top/Article/details/gt2uahnbvvj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gt2nskozxaq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.iojbl.cn/Article/details/gt2hidpmyyq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gt2zoyyztwg.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2numaonch.html

[E17] 首字母大写
来源：http://dali.tanke756.top/Article/details/gt2pvbzbvdl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gt2yypquguh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gt2zlozkxbn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2ykwdcwfz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hfpthk.cn/Article/details/gt2idmgpmus.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gt2lyvogect.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbiltpci.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gt2lcixpbkv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jiagoushi.top/Article/details/gt2qusmzmfq.html

[E18] 模板占位符替换
来源：http://dali.dashuyun.cn/Article/details/gt2pogeyvfc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gt2zkftsjkg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2dututsbd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gt2rixhghzp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gt2bnvjvpuy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2xuklvzib.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gt2vziuncxi.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gt2djncbmbn.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.iojbl.cn/Article/details/gt2hvuvdlni.html

[E19] 多行文本按行拆分
来源：http://dali.yonumen.top/Article/details/gt2jbcdjmcp.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gt2oggsvvit.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gt2xjhncfij.html

JS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2agdjuesh.html

TS:   s.split(/\r?\n/)
来源：http://dali.nanxinkj.top/Article/details/gt2tsoknvct.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2yuhzuqsy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gt2ndqeoeww.html

Ruby: s.lines
来源：http://dali.cashguo.top/Article/details/gt2wcjhnucp.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kvvjtjfj.html

[E20] 判断字符串是否为空
来源：http://dali.zhixingplan.top/Article/details/gt2ndnrgoek.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gt2bdhfhhvd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yongpay.top/Article/details/gt2hwocqmju.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.andypj.xyz/Article/details/gt2oasnspnb.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gt2uirfzlxa.html

Java: if (s.isEmpty()) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2eaukcasr.html

Go:   if s == "" {}
来源：http://dali.hfpthk.cn/Article/details/gt2zjornccx.html

Ruby: if s.empty?
来源：http://dali.hysaishi.cn/Article/details/gt2ssvoynvj.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gt2iepeacbi.html

[E21] 超长截断加省略号
来源：http://dali.tianlin.xyz/Article/details/gt2chdbooef.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuanzx.com/Article/details/gt2pnaudcnx.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gt2tzuovhlk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2pkjqpojn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gt2jbathtwg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yvedp.cn/Article/details/gt2rsuugloe.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwndkzaq.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gt2gnyzdqbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2yopgbjdv.html

[E22] 字节长度与字符长度
来源：http://dali.shzxlz.cn/Article/details/gt2pltatzzu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.smart0.xyz/Article/details/gt2ldxkoxtk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gt2ennmvwix.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2qbgztrmn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2dgmwtkff.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.0kj1m.cn/Article/details/gt2itcxivfg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2smijtfpq.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gt2ryhuelgo.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gt2kqfeewai.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhnthuku.html

F. 文件与目录
来源：http://dali.cheryme.top/Article/details/gt2qysnyfkd.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2gbqhsypf.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gt2eyccgmpc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdmuhaiw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ydzc1.top/Article/details/gt2djvmfzzr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gt2evfyzkrg.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2bsbzkwjm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2rcbdpktp.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jyoumei.cn/Article/details/gt2emgsikhq.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2bwqshkwp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2bncfhujn.html

[F02] 逐行读取文件
来源：http://dali.yj20258.top/Article/details/gt2xulejfhy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tscjdent.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.daria6918.cn/Article/details/gt2wblcmuid.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2phuuyrov.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2hntogfwx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cucudq.cn/Article/details/gt2jvueptwi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gt2tyeeyjeh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.birdmap.top/Article/details/gt2rrakajbh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ykxuptkg.html

[F03] 写入文件（覆盖）
来源：http://dali.daria6918.cn/Article/details/gt2qaauubov.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gt2jgikgjso.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gt2xlqhotsk.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gt2lgkvhjlv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gt2rkqtekzw.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzzcyaii.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gt2cmctneyn.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2vinzhjuj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eduhwzvl.html

[F04] 追加写入文件
来源：http://dali.daria6918.cn/Article/details/gt2vbgmfgbs.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aizwys.cn/Article/details/gt2wghfynxi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gt2omgqwkke.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2ocmugobq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktvzwddc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ydzc1.top/Article/details/gt2vrxuswrj.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gogol.net.cn/Article/details/gt2pwkgvfaa.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yvedp.cn/Article/details/gt2eyrabjgh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ppjwa.cn/Article/details/gt2kbpiigms.html

[F05] 判断文件或目录是否存在
来源：http://dali.daria6918.cn/Article/details/gt2ekdbhgxg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xziqi.cn/Article/details/gt2deyuknuy.html

PHP:  file_exists("a.txt");
来源：http://dali.shuidangran.top/Article/details/gt2asudnsyq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2prdggrog.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2htuckjgf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2drxntsrv.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shuidangran.top/Article/details/gt2qrbfccor.html

Ruby: File.exist?("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jiqoryln.html

C#:   File.Exists("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2dvgswzrp.html

[F06] 删除文件
来源：http://dali.iojbl.cn/Article/details/gt2xleerejh.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wnvjffqi.html

PHP:  unlink("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2zqkrmqtu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2blovukzs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gt2ekagsbzj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2zfzxgkxv.html

Go:   os.Remove("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2lmmiegul.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gt2ilrclhjs.html

C#:   File.Delete("a.txt");
来源：http://dali.cashguo.top/Article/details/gt2psbtjpjv.html

[F07] 创建目录（含多级）
来源：http://dali.aibaodan.cn/Article/details/gt2wpjzufqc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2cagvehij.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.gzhubu.top/Article/details/gt2ivnwmica.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gt2mwqonmrr.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2jburpyeu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yonumen.top/Article/details/gt2kgpnjwst.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gt2jbphmlok.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gt2csadapkb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gt2gsrxqxbe.html

[F08] 遍历目录
来源：http://dali.feifeiyinyue.top/Article/details/gt2vkifmdzq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hfpthk.cn/Article/details/gt2dxfqshlm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2fnlqqqbh.html

JS:   fs.readdirSync("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2pkatiynk.html

TS:   fs.readdirSync("dir")
来源：http://dali.havefunace.top/Article/details/gt2zxlytyuo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxyogobm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2tkfmquyx.html

Ruby: Dir.children("dir")
来源：http://dali.nanxuanxn.top/Article/details/gt2akyurvlk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.hywenlv.cn/Article/details/gt2hnmvjwuh.html

[F09] 获取文件大小
来源：http://dali.zhoulong.xyz/Article/details/gt2fmfwjgvc.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2ubfnluwa.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2skjofyni.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ivvv.top/Article/details/gt2jsndxiag.html


<!-- 参考信息 -->