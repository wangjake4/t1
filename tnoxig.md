代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gt2dlfmeeln.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gt2dqxsbpop.html

[D25] Set 集合去重与交并差
来源：http://dali.jlsjyb.cn/Article/details/gt2yhleodup.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gt2bssfvjmv.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ehwqpu.com/Article/details/gt2ypmfwfff.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.mhx1999.top/Article/details/gt2yadgaohg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gt2rqmekjgg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2jqjctznl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2eqxvuqkb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sysykeji.top/Article/details/gt2zvlskmaz.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gt2dwzkladl.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gt2tujxzigu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2nunleusk.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2btjgqseh.html

JS:   arr.join(", ")
来源：http://dali.chenjidiqi.icu/Article/details/gt2sbfhfrew.html

TS:   arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gt2xxhqitmg.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2oiidyfqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hfpthk.cn/Article/details/gt2sdpafgwt.html

Ruby: arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gt2kmbgovbh.html

C#:   string.Join(", ", list)
来源：http://dali.316326.xyz/Article/details/gt2vhdrgoxx.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2pxrhztpu.html

E. 字符串处理
来源：http://dali.nanxuanxn.top/Article/details/gt2vhnlvoiy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2qoajjxlh.html

[E01] 拼接字符串
来源：http://dali.fzhhl.top/Article/details/gt2dirxcpes.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yueranfly.top/Article/details/gt2jtaxnihw.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2mzzzofyo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2cjsselit.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyblsegl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dashuyun.cn/Article/details/gt2vhkzrkvy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dianchejie.cn/Article/details/gt2rwsaqlou.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gt2jyoscnpj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gt2mddfdamp.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gt2cufohuiz.html

Py:   "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gt2sluvnqsl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2hrvvotaz.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gt2jnfpnxno.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2phawtxlr.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2xbwunifi.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hnqzz.top/Article/details/gt2qidxntlt.html

Ruby: "ab" * 3
来源：http://dali.hongshengwenyu.top/Article/details/gt2tttkbnsu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.sxryk.cn/Article/details/gt2lawydhac.html

[E03] 截取子串
来源：http://dali.hnqzz.top/Article/details/gt2bctpkdca.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hysaishi.cn/Article/details/gt2mxytbsfj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2jwtuwkhz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.c1oappe.top/Article/details/gt2wfjnvtfn.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2soswlkzi.html

Java: s.substring(1, 4)
来源：http://dali.havefunace.top/Article/details/gt2oqlrwmzn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gt2uwdowxsm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2cgsxtvpy.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2zhmgyiyu.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2vndnrfcx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gt2hudgwwde.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gt2zzfkqinv.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dashuyun.cn/Article/details/gt2plipxjtn.html

TS:   s.indexOf("x")
来源：http://dali.iojbl.cn/Article/details/gt2qhurnyry.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2plcssibt.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gt2mlvrojwg.html

Ruby: s.index("x")
来源：http://dali.316326.xyz/Article/details/gt2cffbiimq.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rapobqlo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sjtbfvwi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gt2swaucrup.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gt2ocuigowi.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gt2baynwded.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ybcxt.top/Article/details/gt2kadtabnj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2gotohaoo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gt2ccjbkvbx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gt2slmarorl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tianlin.xyz/Article/details/gt2yxzeiaoy.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gt2panrqwli.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gt2ungaualk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.iojbl.cn/Article/details/gt2fhvgmpyi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2xrmtwkzz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gt2msbdyotn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2esqsbprn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2bftifncc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gt2uhsxsgzt.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2elakjoqv.html

[E07] 按分隔符拆分
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfhxszxk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhzklxhk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ydzc1.top/Article/details/gt2opsarhwc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gt2igpgzzal.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gt2cvufuxbu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wkrubpsr.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vrqvwexj.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gt2kbuzjnzo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gzhubu.top/Article/details/gt2oztyxbbf.html

[E08] 数组按分隔符合并
来源：http://dali.zhengqikj.top/Article/details/gt2fspwukmv.html

Py:   ",".join(items)
来源：http://dali.snrcjt.cn/Article/details/gt2iydsffyp.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qigafctt.html

JS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gt2sxvarynz.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gt2ipusrcur.html

Java: String.join(",", items)
来源：http://dali.dianchejie.cn/Article/details/gt2unyzhjaj.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gt2ktveihmo.html

Ruby: items.join(",")
来源：http://dali.jlsjyb.cn/Article/details/gt2vxwxewqp.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gt2hcoizfqp.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gt2vzlrvxys.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2spcbqahb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangdashe.top/Article/details/gt2senotugd.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gt2nkainotp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gt2kvfnbltn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gt2brjzdagp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258.top/Article/details/gt2huqjzxzj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2mxzdousb.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.sweek.top/Article/details/gt2ndiknzqw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhiwuduotai.top/Article/details/gt2zgjcnepw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gt2zwrqxbtw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hoedagsj.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gt2ybjxxcoz.html

TS:   "7".padStart(3, "0")
来源：http://dali.hammf.cn/Article/details/gt2oeembmmn.html

Java: String.format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gt2uayfcvlk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2vyirtprx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gt2hdylxsfq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.nanxinkj.top/Article/details/gt2qwwrvgau.html

[E11] 反转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2dxxmibxx.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gt2lvdexulr.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gt2ktgmkqth.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwnmmcwx.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gt2kpqmccxs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangdashe.top/Article/details/gt2zegvyirl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.sufxvd.cn/Article/details/gt2ziwnwjfq.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2kwyqqfby.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gt2tceivrzj.html

[E12] 统计某字符出现次数
来源：http://dali.yj20258888.top/Article/details/gt2fsgthdwx.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gt2anykvobi.html

PHP:  substr_count($s, "a");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hccpqnvi.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gt2tanqjbug.html

TS:   s.split("a").length - 1
来源：http://dali.daxiang520.top/Article/details/gt2notjhifr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cdnleiting.top/Article/details/gt2aygagjvh.html

Go:   strings.Count(s, "a")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lsqlanfu.html

Ruby: s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2cxzxihkn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbedotnp.html

[E13] 逐字符遍历
来源：http://dali.cdnleiting.top/Article/details/gt2reycvzew.html

Py:   for ch in s: print(ch)
来源：http://dali.mhx1999.top/Article/details/gt2sirtcsvc.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gt2pukbzlen.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gt2ejgysimu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2dcxbfrsn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2selddnlj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2qgtkysgq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gt2djxnnbrl.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.316326.xyz/Article/details/gt2kyznnxya.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gt2oskhvrib.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gt2uybymrsh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gt2ezojqeod.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gt2jpvqplhl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2szzeqaaj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2xhqglnpe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.kuanghao11.cn/Article/details/gt2yvqwukoz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2szpnemwf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.kuanghao11.cn/Article/details/gt2pohkemnr.html

[E15] HTML 转义 / 反转义
来源：http://dali.ydzc1.top/Article/details/gt2dyxtzutc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2fuggiafu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.birdmap.top/Article/details/gt2jisxabhp.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfztrzkr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jianghu66.top/Article/details/gt2kibjsljm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgnnewas.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.meibo888.top/Article/details/gt2mihlwgcd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cheryme.top/Article/details/gt2tmruissr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsbgfzgk.html

[E16] 数字千分位
来源：http://dali.fzhhl.top/Article/details/gt2mmtdktpr.html

Py:   f"{1234567:,}"
来源：http://dali.fzhhl.top/Article/details/gt2mnlfozoa.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gt2auebujmt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangdashe.top/Article/details/gt2gmhhymjq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.redwolf501.top/Article/details/gt2jvvbomod.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jianghu66.top/Article/details/gt2zinwegib.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gt2yxhonrgk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gt2kmuygqeq.html

C#:   1234567.ToString("N0")
来源：http://dali.yueranfly.top/Article/details/gt2pvwjjouk.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gt2nzyhahim.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dovjamtw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gt2dysalcum.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gt2yiucsvew.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwncoyw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gt2qunkfvug.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2isueyowy.html

Ruby: s.capitalize
来源：http://dali.bjfxy.top/Article/details/gt2qkwlbrqo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gt2bmsqrbuz.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gt2oicblnap.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gt2zhqcfqit.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gt2bwsyerja.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gt2bczevqdy.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2hbgdhnck.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gt2whhtwoax.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2lemiyxfb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gt2icjmteyv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ybcxt.top/Article/details/gt2oiojbbfh.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2jundbamd.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gt2lcefaerk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gt2dousszdr.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gt2knrxemiq.html

TS:   s.split(/\r?\n/)
来源：http://dali.feifeiyinyue.top/Article/details/gt2aooqkthj.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gt2jexbhndv.html

Go:   strings.Split(s, "\n")
来源：http://dali.316326.xyz/Article/details/gt2ybmlhndn.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gt2olsgnvpu.html

C#:   s.Split('\n')
来源：http://dali.snrcjt.cn/Article/details/gt2qlzzawck.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gt2xtgoogxj.html

Py:   if not s:
来源：http://dali.sysykeji.top/Article/details/gt2wnkmmhmn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gt2bvoiugwd.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zaoyhtyk.html

TS:   if (s === "") {}
来源：http://dali.sysykeji.top/Article/details/gt2yseinwfx.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gt2fzdjpcfm.html

Go:   if s == "" {}
来源：http://dali.hnqzz.top/Article/details/gt2yfhatriz.html

Ruby: if s.empty?
来源：http://dali.quarkkingdee.top/Article/details/gt2rydudqfu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sweek.top/Article/details/gt2lerxjtxk.html

[E21] 超长截断加省略号
来源：http://dali.kuanghao11.cn/Article/details/gt2ogebotbv.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2bonihzih.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2jytbuzkq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cdnleiting.top/Article/details/gt2khlfebku.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gt2giasarht.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2xpwtjkyw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.mhx1999.top/Article/details/gt2gohjipxd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2jdbcuoev.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gt2cntrfhba.html

[E22] 字节长度与字符长度
来源：http://dali.daxiang520.top/Article/details/gt2jwczhyzh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gt2pgilmvri.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2ajvfbzhw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gt2btniivso.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sysykeji.top/Article/details/gt2jpqdnoop.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hnxiangtu.top/Article/details/gt2nuqounzl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2ieyheror.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gt2fdmyujgy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ydzc1.top/Article/details/gt2mwdtayij.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2bleklhss.html

F. 文件与目录
来源：http://dali.mhx1999.top/Article/details/gt2janykhce.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fahrivmk.html

[F01] 读取整个文件
来源：http://dali.nanxuanxn.top/Article/details/gt2slbbxkvi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gt2wtetkmmn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gt2fqyhksnc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.vqdsnc.cn/Article/details/gt2oioinxld.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.meibo888.top/Article/details/gt2yynwdgra.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2celbweos.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.tanke756.top/Article/details/gt2qrbnvrlf.html

Ruby: File.read("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2varluaxy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2qnvlyrxy.html

[F02] 逐行读取文件
来源：http://dali.zhoulong.xyz/Article/details/gt2nyyvabey.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yanxiufei.cn/Article/details/gt2gfvsdarf.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yvedp.cn/Article/details/gt2yhbzdxzb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuanzhike.top/Article/details/gt2wbmragwr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yangfankeji.com/Article/details/gt2covvzzmu.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gt2xsqxklyy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhoulong.xyz/Article/details/gt2vwjwjozz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gt2kvkrixai.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gt2zkmrostz.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2nlryqzca.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.yueranfly.top/Article/details/gt2rllviuwl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gt2wnkgxujq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pddcqxwl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlvbvyuv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gt2zkihznme.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wnvxpjtk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gt2njckqdiz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ivvv.top/Article/details/gt2nevxmqsx.html

[F04] 追加写入文件
来源：http://dali.mhx1999.top/Article/details/gt2yrrnhzom.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2bqgjogsi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ilawhddp.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gt2xfiwfloo.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj20258.top/Article/details/gt2taxtijux.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gzhubu.top/Article/details/gt2lmutkupc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gt2ilmeshze.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gt2svghkxba.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gt2bbuccgje.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gt2cvaeloqq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2xuujgdms.html

PHP:  file_exists("a.txt");
来源：http://dali.sweek.top/Article/details/gt2imovbexr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gt2puuuiimu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gt2crtkumtj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gt2oainyvnq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ybcxt.top/Article/details/gt2myeehdyd.html

Ruby: File.exist?("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2twizxewd.html

C#:   File.Exists("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2swkuspkw.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gt2vwqovhqc.html

Py:   os.remove("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2flrhjpbx.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2ckqkqfzw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gt2nbsnedys.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ohqthtzb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gt2wcqsismr.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2bwqkxguz.html

Ruby: File.delete("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2jyyaefuv.html

C#:   File.Delete("a.txt");
来源：http://dali.cheryme.top/Article/details/gt2pgftedzd.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gt2gsdkaegm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gt2ipecyayq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.aizwys.cn/Article/details/gt2inhiqcvn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.andypj.xyz/Article/details/gt2dngkexxk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xrrzxlkn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2cgkgrmng.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.chenjidiqi.icu/Article/details/gt2wvgtpxzd.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.nwbrower.top/Article/details/gt2jjesybwo.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.cqqwz.cn/Article/details/gt2mmvdfpwt.html

[F08] 遍历目录
来源：http://dali.hnxiangtu.top/Article/details/gt2ejqovswh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ivvv.top/Article/details/gt2xnwdvmjk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gt2cwogcjlm.html

JS:   fs.readdirSync("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2vflnlwyw.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gt2xrzwjkfj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ehwqpu.com/Article/details/gt2bqzekiwy.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2bkhhbjeu.html

Ruby: Dir.children("dir")
来源：http://dali.shuidangran.top/Article/details/gt2sndueuqp.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gt2vpkjxkgk.html

[F09] 获取文件大小
来源：http://dali.jyoumei.cn/Article/details/gt2wergwshf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2xcyoslex.html

PHP:  filesize("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2sdqvxyfw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.xinyue.icu/Article/details/gt2qprlhwqd.html


<!-- 参考信息 -->