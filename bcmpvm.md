代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258888.top/Article/details/gtukbiapuu.html

[D24] 字典 / Map 基本操作
来源：http://dali.jianghu66.top/Article/details/gtgxyktsfq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gttykdjvgt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fengsongda.top/Article/details/gtpizavpod.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtftnpqbjy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtegrpcwvo.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gtalragtxf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtilxxmqat.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gthtvjtulb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtocdhrbjh.html

[D25] Set 集合去重与交并差
来源：http://dali.yongpay.top/Article/details/gttizndspk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.haohaochexian.top/Article/details/gtmublfxbx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtclvwbahf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.iojbl.cn/Article/details/gtgurcmljr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gttxghzhei.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ppjwa.cn/Article/details/gteklppcsv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gttipcmyhp.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gttictijel.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinqigufen.top/Article/details/gtcnexchyl.html

[D26] 数组转字符串
来源：http://dali.tianlin.xyz/Article/details/gtppyfamjn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtszmbsqfk.html

PHP:  implode(", ", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtussfiefw.html

JS:   arr.join(", ")
来源：http://dali.snrcjt.cn/Article/details/gtbrwsstxq.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gthteqgomy.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtorphjens.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sxryk.cn/Article/details/gtmdbdfhkh.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtkqcupbrw.html

C#:   string.Join(", ", list)
来源：http://dali.hnqzz.top/Article/details/gtymjxpltt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbrlpuzf.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtnrtokjvg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtwizlyuam.html

[E01] 拼接字符串
来源：http://dali.yonumen.top/Article/details/gtejrocpts.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigufen.top/Article/details/gtmbswlkqq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtkyetwvpd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtxuqpqtfy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtdnacsbby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aizwys.cn/Article/details/gtgosvummp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sxryk.cn/Article/details/gtwedvidbn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtmgytwmke.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtxrqtroww.html

[E02] 重复字符串
来源：http://dali.yj20258888.top/Article/details/gtowtwnptc.html

Py:   "ab" * 3
来源：http://dali.iojbl.cn/Article/details/gtrtslxwrq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jyoumei.cn/Article/details/gtyebvcunf.html

JS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtxwlxthfl.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtfjqxvwoq.html

Java: "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gthgvuzbpk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jiagoushi.top/Article/details/gtlwjjnpts.html

Ruby: "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtctmzxsph.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtzygvunmn.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtitpynvrj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daxiang520.top/Article/details/gtawoyjyvc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtyhvebhjt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtsokfhhxt.html

TS:   s.slice(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtsodhaolt.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gtgdxpcpiw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtvvhkfzrr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtonfnielo.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gttajjmryz.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfykksxj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenlongwang.top/Article/details/gtnwaqxadz.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtthduoflj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.chenzaomai.com/Article/details/gtshhpbfqw.html

TS:   s.indexOf("x")
来源：http://dali.xylfe.cn/Article/details/gtuwbjvktl.html

Java: s.indexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtsosmroiv.html

Go:   strings.Index(s, "x")
来源：http://dali.cdnleiting.top/Article/details/gtptosunbm.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gtvwkqqilt.html

C#:   s.IndexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtudolkuob.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guowangkeji.top/Article/details/gtbahbzumk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cucudq.cn/Article/details/gtrpeqqufw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yonumen.top/Article/details/gtyspkzqge.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtxenogarx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhengqikj.top/Article/details/gtogoselxk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gtuvczmlqq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtvbjfomrk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yangfankeji.com/Article/details/gtsumnhnou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtvkynksnn.html

[E06] 替换子串
来源：http://dali.yvedp.cn/Article/details/gtuprztfho.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xziqi.cn/Article/details/gttfqgmqza.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cashguo.top/Article/details/gtfdnupfpo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gthgnkyuae.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtwtcnzwxs.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtopumiggy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gtfwzvysnq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtcrtmbcdw.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtcogewcjf.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjjbawfl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtvfodkauu.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtjjkrzecw.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nanxinkj.top/Article/details/gtuzodtybg.html

TS:   s.split(",")
来源：http://dali.9152youxi.cn/Article/details/gtxtuhhjtk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gtqubmntsh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cheryme.top/Article/details/gttakcygmn.html

Ruby: s.split(",");  s.split
来源：http://dali.316326.xyz/Article/details/gtgkctvmeo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwvgvpyna.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtbdmuimiv.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtvkzmykig.html

PHP:  implode(",", $items);
来源：http://dali.jyoumei.cn/Article/details/gtxehnoimn.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepotadwe.html

TS:   items.join(",")
来源：http://dali.dashuyun.cn/Article/details/gtjpunbqja.html

Java: String.join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwizsskfd.html

Go:   strings.Join(items, ",")
来源：http://dali.c1oappe.top/Article/details/gtgyzwtpbq.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtbidmqqgu.html

C#:   string.Join(",", items)
来源：http://dali.iojbl.cn/Article/details/gtmuwuyxxx.html

[E09] 去除所有空白字符
来源：http://dali.fengsongda.top/Article/details/gtwkhrkodv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtdggekuuq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sufxvd.cn/Article/details/gtyrxzujpb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtfkhxpzht.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yanxiufei.cn/Article/details/gtavijixoh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zdqjudy.top/Article/details/gtvkmkmmeb.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shangyingyoupin.top/Article/details/gtesxmshst.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvorsnvqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenlongwang.top/Article/details/gtgzimwiiq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yueranfly.top/Article/details/gtygahsehp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtqczzzxjl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtogfvccvl.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtxxheuvck.html

TS:   "7".padStart(3, "0")
来源：http://dali.hywenlv.cn/Article/details/gtfimogwbu.html

Java: String.format("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtztfybgjo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtikcvrufq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtwuxibzoo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.kuanghao11.cn/Article/details/gttgqtofae.html

[E11] 反转字符串
来源：http://dali.yj20258888.top/Article/details/gtosbejbtg.html

Py:   s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtkxczuclm.html

PHP:  strrev($s);
来源：http://dali.zhoulong.xyz/Article/details/gtopmwdlca.html

JS:   [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtflmylrpe.html

TS:   [...s].reverse().join("")
来源：http://dali.guowangkeji.top/Article/details/gtqckkxbwk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gtagchowsu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xinyue.icu/Article/details/gtsmvpnfys.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gtlzmohyqh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtdhxmjgou.html

[E12] 统计某字符出现次数
来源：http://dali.jqgfzy.top/Article/details/gtehaoqqcp.html

Py:   s.count("a")
来源：http://dali.gaohongyu789.top/Article/details/gthabbecco.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtlwwevkgm.html

JS:   s.split("a").length - 1
来源：http://dali.shangyingyoupin.top/Article/details/gtezoznnzs.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtvjgiewuf.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gtohignkku.html

Go:   strings.Count(s, "a")
来源：http://dali.cqqwz.cn/Article/details/gtyujuattj.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtrfxqplvh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtetsdvhrh.html

[E13] 逐字符遍历
来源：http://dali.aibaodan.cn/Article/details/gtoksxbcdl.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtetszoqep.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hnqzz.top/Article/details/gtoxjoxalf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gtfbybpdni.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtqswkhntm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtiukiqwdd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.vqdsnc.cn/Article/details/gtlnispznj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gzhubu.top/Article/details/gtqqaknyhg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.havefunace.top/Article/details/gtwbiikkoa.html

[E14] URL 编码与 Base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrajmytbz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtvkadkthr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtzhmdbalj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ydzc1.top/Article/details/gtaiblvadk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtzsvbvspb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaniqdvi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxdrxluk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gthinhwkvf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gzhubu.top/Article/details/gtbcjypeym.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtosmcvflk.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfnqxlvyg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtvtjkiryn.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtqybjljup.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtoyibboyw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yonumen.top/Article/details/gtugunwpdh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hysaishi.cn/Article/details/gtiohjfkel.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhoulong.xyz/Article/details/gteuxpkquu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtjvqkbzli.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtnrilkmmi.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtrmvyzvgh.html

PHP:  number_format(1234567);
来源：http://dali.nwbrower.top/Article/details/gthxpmpzgl.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtwhrnajux.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenjidiqi.icu/Article/details/gtyfevtxvw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtpjduncbr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhoulong.xyz/Article/details/gtusgtgsdf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gtrjbnzwkf.html

C#:   1234567.ToString("N0")
来源：http://dali.yangfankeji.com/Article/details/gtdgpnwgug.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtdugeunqd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtyxtjbrxp.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtzdshqvla.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadgsubky.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtflqlexsw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtycvpbzec.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.birdmap.top/Article/details/gtykcrqdxx.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtnvcxglcy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xuanzx.com/Article/details/gtdjfrxupd.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtgdomdkmk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtkgfkmuke.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtjmpdkuzt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtlllwybdc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtmdarjdkf.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gthgatrevg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtggwbmscb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gtvisvjuwh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cheryme.top/Article/details/gtdvmukier.html

[E19] 多行文本按行拆分
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhzkomjo.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtfopzizuz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtcyvebycp.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtblsqwlqe.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtqhfjfqwn.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtuefaszna.html

Go:   strings.Split(s, "\n")
来源：http://dali.gzhubu.top/Article/details/gttjbxxulu.html

Ruby: s.lines
来源：http://dali.jlsjyb.cn/Article/details/gtufrbgfng.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtxpkvwrlu.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gtdqpgrorp.html

Py:   if not s:
来源：http://dali.svipenyu.cn/Article/details/gttqoaatua.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmeoddio.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hywenlv.cn/Article/details/gtmtnpeyou.html

TS:   if (s === "") {}
来源：http://dali.hammf.cn/Article/details/gtatjpavks.html

Java: if (s.isEmpty()) {}
来源：http://dali.gzhubu.top/Article/details/gtvxgutalk.html

Go:   if s == "" {}
来源：http://dali.hongshengwenyu.top/Article/details/gttjagocjb.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gtysoqokqs.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hammf.cn/Article/details/gtmzhcrlbk.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtmwvwlwav.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtbgjpamwn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtgsqkocta.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gtjcdqfzbx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gtjslkykfr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gtgpyflccc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnxiangtu.top/Article/details/gteuqxyfew.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtmfvpzfej.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtpopwpdym.html

[E22] 字节长度与字符长度
来源：http://dali.sweek.top/Article/details/gttbfgemkt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gtydnqzizx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtetlmlcad.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gtsiwzxgrl.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gttxsfbize.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sweek.top/Article/details/gtzpshmamd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtsvpkeima.html

Ruby: s.bytesize;  s.length
来源：http://dali.jyoumei.cn/Article/details/gtttvszpvv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtqrcjrtcy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtuulpbepu.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtnptxxaie.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwezsahww.html

[F01] 读取整个文件
来源：http://dali.jinqigfzy.top/Article/details/gtkqkkxsgm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zdqjudy.top/Article/details/gtzaoqzkbx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtdftstpqv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gtffealonp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxcnnkwla.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxuanxn.top/Article/details/gtgkcojzen.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtugisdctw.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtnvablnpy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjakxmpdx.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gtlokppqnd.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetbtlwio.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cheryme.top/Article/details/gtpidapmwr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtphhcmmis.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yanxiufei.cn/Article/details/gtykyaotye.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjrxxdzp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtxvmstlpj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.fengsongda.top/Article/details/gtzllydzqi.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtpvblspbt.html

[F03] 写入文件（覆盖）
来源：http://dali.guowangkeji.top/Article/details/gtpqrzpjhf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gthqbastff.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.nanxuanxn.top/Article/details/gtikkflbic.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.aibaodan.cn/Article/details/gtlnqhbbyp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtkokilfoz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gtqejoleci.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tianlin.xyz/Article/details/gtoqpekmmr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gtqitydpsm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtuuykuxwl.html

[F04] 追加写入文件
来源：http://dali.dianchejie.cn/Article/details/gtvcabxrdc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gtkuqlulye.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhiwuduotai.top/Article/details/gtpzftbppz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtjlaqoylf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.smart0.xyz/Article/details/gtwqccmutq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sxryk.cn/Article/details/gtklhobprp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.daria6918.cn/Article/details/gtmejlmywp.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.svipenyu.cn/Article/details/gtgiajlxna.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtaxbsrkkf.html

[F05] 判断文件或目录是否存在
来源：http://dali.dashuyun.cn/Article/details/gtpfmkgces.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcuyesknz.html

PHP:  file_exists("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtmzkwqzze.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtlhatgufl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtdivdpezf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtdzdivtda.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.vqdsnc.cn/Article/details/gtjrqhhwdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtncvtivfv.html

C#:   File.Exists("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtkszkurko.html

[F06] 删除文件
来源：http://dali.xuetiantiany.cn/Article/details/gtbfzxssjz.html

Py:   os.remove("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfyhnqvom.html

PHP:  unlink("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtsvfclubo.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtsfmeryhy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlepcppl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtfvbpfzqp.html

Go:   os.Remove("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtovzqqqoi.html

Ruby: File.delete("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtjxvnzwvz.html

C#:   File.Delete("a.txt");
来源：http://dali.yj202588.top/Article/details/gtlfauwnuu.html

[F07] 创建目录（含多级）
来源：http://dali.sweek.top/Article/details/gtdcbetiam.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gthjfyctov.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxuanxn.top/Article/details/gtkzbocgqa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hywenlv.cn/Article/details/gtvbweczzh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtlpkadneb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jianghu66.top/Article/details/gtkyogfnbf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjcvqbvn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtvmhcwkbg.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.shzxlz.cn/Article/details/gtsotlnzdc.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gtfjyfysta.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtapvoitrp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhengqikj.top/Article/details/gtowcixcqb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj202588.top/Article/details/gtsnvhfiht.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gtopvwrlwo.html


<!-- 参考信息 -->