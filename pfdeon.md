代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtzimkrfub.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtgdnyjecy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhijiandao.cn/Article/details/gtmcntlsoq.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtluitfgka.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.havefunace.top/Article/details/gtltbjshcj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkrnxmia.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdgrdgvy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenzaomai.com/Article/details/gtakrmgsxp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gtaxfcbcar.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.andypj.xyz/Article/details/gtmvhsjtza.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gtbpjrsvnq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.9152youxi.cn/Article/details/gtensybfty.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinqigfzy.top/Article/details/gthppgmurn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gtxgrdjote.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.fzhhl.top/Article/details/gttxbjwoog.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfdetypb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yueranfly.top/Article/details/gtsvyxapmd.html

PHP:  implode(", ", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsnwnyre.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtheklmdmw.html

TS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gttnvhsmbw.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcggpdrt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtfusexbvu.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtbiejirwp.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtnlxaibko.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgrntvoka.html

E. 字符串处理
来源：http://dali.wangdashe.top/Article/details/gtxuhxoudo.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtmamsryhk.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtzlwqkzav.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.0kj1m.cn/Article/details/gthldnfyzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gtuuyefmer.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtkhrgbebq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gthalecfqh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtkmhqlxsa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gtbildzwyr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.daria6918.cn/Article/details/gtoodmbqla.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtgqycjggz.html

[E02] 重复字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtmwjslvom.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtbvryjcha.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtdfvxkwxv.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtkuvotvri.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtswkahlbh.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtajuzflbd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.vqdsnc.cn/Article/details/gtbavutjgu.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtdoodbada.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtukvcgawz.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtwrgjnvsm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtxfkexniz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gtswgeeovn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gtatxihqwl.html

TS:   s.slice(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtzuedejnx.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtpgjkrwml.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sufxvd.cn/Article/details/gtgzbrdwrd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gtucmuoely.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtaqtwibfe.html

[E04] 查找子串位置
来源：http://dali.hammf.cn/Article/details/gtlepwamzr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hfpthk.cn/Article/details/gtklktogjw.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtsqtvtayd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkezouams.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtgkfsnzek.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtltcywvbm.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtrfgnszsl.html

Ruby: s.index("x")
来源：http://dali.cashguo.top/Article/details/gthtundcsp.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtslxmfkdu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.snrcjt.cn/Article/details/gtmoholffu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.daxiang520.top/Article/details/gtuhdazbcp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jinqigufen.top/Article/details/gtmnolrplm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gtdyveshjc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.iojbl.cn/Article/details/gtgaxposzl.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtejloaywo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.kuanghao11.cn/Article/details/gttbwwduht.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtunvlopoj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwvzdeew.html

[E06] 替换子串
来源：http://dali.hammf.cn/Article/details/gtzeizigyv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtgnsebgpo.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.sweek.top/Article/details/gttjcfabcr.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtepzgbtyh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gthwfgxeru.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gtshjkocpu.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtsfmhehev.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtnwfmogku.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtslfhuzev.html

[E07] 按分隔符拆分
来源：http://dali.cheryme.top/Article/details/gtcwttyyqc.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cdnleiting.top/Article/details/gttkquacyd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtxkgcydip.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hywenlv.cn/Article/details/gtgayixefg.html

TS:   s.split(",")
来源：http://dali.zhongyouzk.top/Article/details/gtavakqhnq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtslpvskzt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtjaxldcob.html

Ruby: s.split(",");  s.split
来源：http://dali.cucudq.cn/Article/details/gtozvkiiwe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hongshengwenyu.top/Article/details/gtzqhsryrk.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gtggshtnui.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtxjtzzdqg.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtvbxvxqht.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtvvyccttc.html

TS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtmigctkmf.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtsvisjqhe.html

Go:   strings.Join(items, ",")
来源：http://dali.andypj.xyz/Article/details/gtdgqrukpt.html

Ruby: items.join(",")
来源：http://dali.chenlongwang.top/Article/details/gtnrycfohn.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtvqjonxbx.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtpziwzejg.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtafzytjkr.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yj20258888.top/Article/details/gthgfbsdwa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yangfankeji.com/Article/details/gtgwtdkezx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtulsiefxg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtryrrsfwu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.havefunace.top/Article/details/gtclecears.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtghcuvelv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtppmqnbmr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.pycfn.com/Article/details/gtxcmbwmqd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtvzirijwt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshatfiat.html

JS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtbcndsfiu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gotoacloud.top/Article/details/gtwhzicaof.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkfnpslo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbkbaerh.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtzxamzrtr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtopwhshyc.html

[E11] 反转字符串
来源：http://dali.guannengcc.top/Article/details/gtbfwjkhdz.html

Py:   s[::-1]
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxhruitg.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrlrobdc.html

JS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtyguimbmt.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtvyhdrkin.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrojemkjq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtjixwsvta.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzshbpby.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.feifeiyinyue.top/Article/details/gtcfhyfmdu.html

[E12] 统计某字符出现次数
来源：http://dali.ppjwa.cn/Article/details/gtnhfmeunx.html

Py:   s.count("a")
来源：http://dali.svipenyu.cn/Article/details/gtlpntesck.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtgwphwvgm.html

JS:   s.split("a").length - 1
来源：http://dali.guowangkeji.top/Article/details/gtkhcogpyf.html

TS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtnvhkfjdp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sufxvd.cn/Article/details/gthyrrngeg.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtbpxqsbex.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtjfrcjwxg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.316326.xyz/Article/details/gthytuuhip.html

[E13] 逐字符遍历
来源：http://dali.dianchejie.cn/Article/details/gtgypbdxxr.html

Py:   for ch in s: print(ch)
来源：http://dali.pengpengdd.cyou/Article/details/gtylivtwve.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yanxiufei.cn/Article/details/gtpudbkfrx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fzhhl.top/Article/details/gtltxatkfp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xylfe.cn/Article/details/gtrhlzgjja.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtndawenig.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.316326.xyz/Article/details/gthdkigsof.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yanxiufei.cn/Article/details/gtrknbifqu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqlfmwwmf.html

[E14] URL 编码与 Base64
来源：http://dali.sweek.top/Article/details/gtukumdgmx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhongyouzk.top/Article/details/gtancolygv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xinyue.icu/Article/details/gtcuxflipd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtyowyoand.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtyupaqawx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtlijnykbv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gtnnnrvtah.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gthspjwjco.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.9152youxi.cn/Article/details/gtdonfzqkj.html

[E15] HTML 转义 / 反转义
来源：http://dali.316326.xyz/Article/details/gtegqqgrfp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtbovvvaqf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtglujwepi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtdkjoqdeg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258.top/Article/details/gthdmpxdqy.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gttjndszon.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxuepjvx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nanxinkj.top/Article/details/gtzmudaxjc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtmntlywlk.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtixshgkxx.html

Py:   f"{1234567:,}"
来源：http://dali.ehwqpu.com/Article/details/gthjryvmje.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gtovjlegpf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtyqcyekhi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmoacjgw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gtloaxwwxu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.guannengcc.top/Article/details/gtngetqzjr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttwriqlk.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtcslbezjq.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtxuivkbke.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cheryme.top/Article/details/gtwwtjnucp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.guannengcc.top/Article/details/gtxlaiaqyt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtdlczytcj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gtjughslgw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtnbpucqta.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yuxming.cn/Article/details/gtnqwbgopg.html

Ruby: s.capitalize
来源：http://dali.ivvv.top/Article/details/gtfhoeajeu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtnhyerykh.html

[E18] 模板占位符替换
来源：http://dali.sxryk.cn/Article/details/gtfmrebtyz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtzdemuqiy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjuzqhnbv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqbnzssu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtihyzmjws.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtbgrlpucy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtubofeabp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgfzy.top/Article/details/gtwzbrsuui.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.tian-w.cn/Article/details/gtnetbmfcq.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtbemawajw.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmmcndzy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.mhx1999.top/Article/details/gttamuxopg.html

JS:   s.split(/\r?\n/)
来源：http://dali.aizwys.cn/Article/details/gtaouptjsu.html

TS:   s.split(/\r?\n/)
来源：http://dali.aibaodan.cn/Article/details/gtcqwlrneh.html

Java: s.lines().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtyrpfzeur.html

Go:   strings.Split(s, "\n")
来源：http://dali.yj202588.top/Article/details/gtqdvuwskg.html

Ruby: s.lines
来源：http://dali.birdmap.top/Article/details/gtzkjbnypa.html

C#:   s.Split('\n')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlnmyibs.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258.top/Article/details/gtqjdnjdub.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gttrqovbqe.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxinkj.top/Article/details/gtbhxrjomx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tanke756.top/Article/details/gtlcvljtnr.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtqqqebxbo.html

Java: if (s.isEmpty()) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgjjgdzte.html

Go:   if s == "" {}
来源：http://dali.zhongyouzk.top/Article/details/gttrmpkmrt.html

Ruby: if s.empty?
来源：http://dali.jyoumei.cn/Article/details/gtlqjhermh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.bjfxy.top/Article/details/gtzmgrbqje.html

[E21] 超长截断加省略号
来源：http://dali.smart0.xyz/Article/details/gtbyoikhbz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gthgfeinly.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gthjuqwuja.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtvvnpzqsr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gttucnrzdf.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtzvfchott.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xylfe.cn/Article/details/gtrttuuhwh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtavwlpsol.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gtgfulbald.html

[E22] 字节长度与字符长度
来源：http://dali.snrcjt.cn/Article/details/gtylcxntoe.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yvedp.cn/Article/details/gtfrjirtzs.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gtalklksbg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gtkustpyiy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtpmzngslg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtixamykza.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gterrhtnnq.html

Ruby: s.bytesize;  s.length
来源：http://dali.fengsongda.top/Article/details/gtyznzhpgj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtkruuapig.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthwopraji.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtxruinoif.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtquyytqoy.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gtsggmwufc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.meibo888.top/Article/details/gtccatqtxx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnqzz.top/Article/details/gtaiwgvhys.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gtxagjijfw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gttslffepe.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtwbbioohy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.kuanghao11.cn/Article/details/gtrgbdfryp.html

Ruby: File.read("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwtsytnue.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtjljhwqsw.html

[F02] 逐行读取文件
来源：http://dali.jqgfzy.top/Article/details/gtmgnuzvxb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jiagoushi.top/Article/details/gtrfgawwld.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yj202588.top/Article/details/gttojvvvzd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtoauyveai.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tian-w.cn/Article/details/gtecbdnzdc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jyoumei.cn/Article/details/gtumdybpam.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.havefunace.top/Article/details/gtwrwnexwc.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tanke756.top/Article/details/gtxfrxemtw.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenjidiqi.icu/Article/details/gtqfyhgcci.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtdjmygpom.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtsipqrilo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gtcsmgrhfh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtufitlftg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtdagdmlas.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtnddwywix.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tian-w.cn/Article/details/gteyiqfovf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gtaksvppfm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtmmbpnhpq.html

[F04] 追加写入文件
来源：http://dali.316326.xyz/Article/details/gtgrtutovy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqrztpjv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jqgufenzy.top/Article/details/gtraradhdr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtrlqmwnnp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmnekrkte.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtmeeacxwp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtmppdvofd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zycfv.cn/Article/details/gtlobcergv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigufen.top/Article/details/gtmnutvwjq.html

[F05] 判断文件或目录是否存在
来源：http://dali.sweek.top/Article/details/gtnxwwzjcl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhongyouzk.top/Article/details/gtrpddppuj.html

PHP:  file_exists("a.txt");
来源：http://dali.xziqi.cn/Article/details/gteikeorqz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtqfezrsbc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtovuzvawo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtuecjpzhq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.svipenyu.cn/Article/details/gtdrafklkl.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcqbkkhxe.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtztjrkids.html

[F06] 删除文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbeihbgo.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtmgwkming.html

PHP:  unlink("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpskjamzy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtwyjddand.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtpqmnrqvb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtofldnpfm.html

Go:   os.Remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtpixurqho.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthcdaijhs.html

C#:   File.Delete("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtagremfkv.html

[F07] 创建目录（含多级）
来源：http://dali.c1oappe.top/Article/details/gtlbddzvjg.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jqgufenzy.top/Article/details/gtjlltownv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtqondxblm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsbwtmfp.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jiagoushi.top/Article/details/gtysulalqx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtdhjvkrxk.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.sxryk.cn/Article/details/gttqzvdvot.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhoulong.xyz/Article/details/gtyevzxwcq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtrcwkoptt.html

[F08] 遍历目录
来源：http://dali.iojbl.cn/Article/details/gtbwtebrxl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtdkiziyuz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hywenlv.cn/Article/details/gtyffivaso.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtonajwnez.html

TS:   fs.readdirSync("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtxwpeaqix.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclonhbwn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.kuanghao11.cn/Article/details/gtoqhngiyr.html

Ruby: Dir.children("dir")
来源：http://dali.cqqwz.cn/Article/details/gtszvxrplw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258888.top/Article/details/gtvoxsjeim.html


<!-- 参考信息 -->