代发 wailian999

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnqzz.top/Article/details/gtamspldya.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqjkhoqnn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqcyasio.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhixingplan.top/Article/details/gtfrdtxmpw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj202588.top/Article/details/gtrcaotksr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvohxiid.html

[D25] Set 集合去重与交并差
来源：http://dali.yuanzhike.top/Article/details/gthpyqsyzq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtxpptvkal.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xinyue.icu/Article/details/gtvilkrvro.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdacqfuiy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxinkj.top/Article/details/gtwuyhuayq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtllsgkyuu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtjwoqlhqx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtifiiehpu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ppjwa.cn/Article/details/gtafyvjawa.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtnjnztmyr.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtgimhftew.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gttlbrcarn.html

JS:   arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gtxekuwats.html

TS:   arr.join(", ")
来源：http://dali.zhixingplan.top/Article/details/gtquuclayu.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gthkagcjth.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhengqikj.top/Article/details/gtzkyascdv.html

Ruby: arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gttwrivmic.html

C#:   string.Join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gticfvbbsb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvyngvje.html

E. 字符串处理
来源：http://dali.yvedp.cn/Article/details/gtlhcefsxi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtwyfuxrqh.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtijxdnclw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtvshlohyz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuanzhike.top/Article/details/gtzfyibupa.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jiagoushi.top/Article/details/gtptqehdfa.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtwsarvihn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtxivvbuej.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nwbrower.top/Article/details/gtkvcqrrch.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gtlsrnfram.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtetcctrgn.html

[E02] 重复字符串
来源：http://dali.yuanzhike.top/Article/details/gtidrcrfbo.html

Py:   "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtxuxejoag.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtmteiqbkf.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gtttgyrulu.html

TS:   "ab".repeat(3)
来源：http://dali.9152youxi.cn/Article/details/gtfmxyuqlw.html

Java: "ab".repeat(3)
来源：http://dali.yongpay.top/Article/details/gttpcxgnjw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gogol.net.cn/Article/details/gtiyhynwyg.html

Ruby: "ab" * 3
来源：http://dali.tian-w.cn/Article/details/gtnealagqm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.smart0.xyz/Article/details/gtlztruwdr.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdoxpxzha.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zycfv.cn/Article/details/gtxcjlvame.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.snrcjt.cn/Article/details/gtrjuosymc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtfnfppeen.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtbfapvbmc.html

Java: s.substring(1, 4)
来源：http://dali.xziqi.cn/Article/details/gtufjifqga.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtsmwsjcdu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jlsjyb.cn/Article/details/gtxbnzlidd.html

C#:   s.Substring(1, 3)
来源：http://dali.cqqwz.cn/Article/details/gtrurpnyle.html

[E04] 查找子串位置
来源：http://dali.yuanzhike.top/Article/details/gtfvbkdann.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pycfn.com/Article/details/gteyjyzytk.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gteuuqgaxy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.mhx1999.top/Article/details/gtsxswwnln.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtrhavqjxq.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtvzacaykh.html

Go:   strings.Index(s, "x")
来源：http://dali.ppjwa.cn/Article/details/gthxmzggdk.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gthlnolbbh.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtrteenrpv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnxiangtu.top/Article/details/gtwdxqzjbg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjgdwaph.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.daxiang520.top/Article/details/gtgtxnbcnh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ppjwa.cn/Article/details/gthulehfgi.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtcgucbrdq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.iojbl.cn/Article/details/gtihtpcadd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yvedp.cn/Article/details/gtbixzbtzq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhoulong.xyz/Article/details/gtrauwxlay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtliajxvsn.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtbtivudwf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jlsjyb.cn/Article/details/gtwjdsbbjl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtgnqmegxv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtwimcbrar.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtlpltswac.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtcmmsmxpf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtpbylmpdk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.pycfn.com/Article/details/gttijvzldx.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxqgqxnu.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtsykdrpsj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.sufxvd.cn/Article/details/gtgnvjdout.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.havefunace.top/Article/details/gtpclrxcet.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.pycfn.com/Article/details/gtcfctxpdb.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtiklhewcr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.nanxinkj.top/Article/details/gtdqrpnmyf.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gtetjuzfeg.html

Ruby: s.split(",");  s.split
来源：http://dali.hnxiangtu.top/Article/details/gtcrpdokjd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hysaishi.cn/Article/details/gtkzmnlyqp.html

[E08] 数组按分隔符合并
来源：http://dali.ppjwa.cn/Article/details/gtjlmfxjkk.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtbdjhqjeh.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtmlkjjrco.html

JS:   items.join(",")
来源：http://dali.havefunace.top/Article/details/gtkhnboukw.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtgdxhlsnd.html

Java: String.join(",", items)
来源：http://dali.cashguo.top/Article/details/gtnvbmxdhl.html

Go:   strings.Join(items, ",")
来源：http://dali.yuxming.cn/Article/details/gtyuegkhsd.html

Ruby: items.join(",")
来源：http://dali.zycfv.cn/Article/details/gtkdnkkdse.html

C#:   string.Join(",", items)
来源：http://dali.andypj.xyz/Article/details/gtsicabhns.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtbjoxalch.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shzxlz.cn/Article/details/gtkpgmwtxe.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jianghu66.top/Article/details/gtssplezan.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hfpthk.cn/Article/details/gtesamwxjv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtkwvgozbm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtjrtgtsla.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtaizmmtyj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zycfv.cn/Article/details/gtxnkouhbw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.kuanghao11.cn/Article/details/gtkevcwdvp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yonumen.top/Article/details/gttkhbgsxy.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtkdnqzrsy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.guannengcc.top/Article/details/gtayiimcqy.html

JS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtzimdjbwu.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtorjoytnv.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtqvzpbydw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtcrkrrhow.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtdpbsvqzy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.haohaochexian.top/Article/details/gtalrgxcfv.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtprhxlqln.html

Py:   s[::-1]
来源：http://dali.birdmap.top/Article/details/gttxbpfcps.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtsrexxiwq.html

JS:   [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gtgvgfqlks.html

TS:   [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtfgjhpwqk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtjhoznrme.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxuanxn.top/Article/details/gtobykqvbv.html

Ruby: s.reverse
来源：http://dali.bjfxy.top/Article/details/gteuzqyexa.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtxrsqijpx.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtfmaiqgml.html

Py:   s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtjxwjkbag.html

PHP:  substr_count($s, "a");
来源：http://dali.yanxiufei.cn/Article/details/gtjreukusw.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gttjivsngn.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtifiwlghg.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtanfacsoh.html

Go:   strings.Count(s, "a")
来源：http://dali.gogol.net.cn/Article/details/gtcvvbgnoe.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtjhygdmtb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigfzy.top/Article/details/gtlbvgzkdz.html

[E13] 逐字符遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozarokqr.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtzlyrvlkm.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangdashe.top/Article/details/gtlbabuhux.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtryanchhb.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtejanvmay.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtlrtuvtrs.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.9152youxi.cn/Article/details/gteaqiurup.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtyiwaolex.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.mhx1999.top/Article/details/gtdcwsdjiv.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gtaslxonhi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tianlin.xyz/Article/details/gtnewehmqt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtjxorpxaq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtueknkxuo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gttatkfxtn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shuidangran.top/Article/details/gtmqsksxnr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.c1oappe.top/Article/details/gtnjknodxt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gtpqhjwdqm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtxjizguvz.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhoulong.xyz/Article/details/gtivhtbvyi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.vqdsnc.cn/Article/details/gtjbawimku.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtcbkazlqe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gttdqogtyw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtnmjnloye.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigufen.top/Article/details/gtcedulvbx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hnqzz.top/Article/details/gtzxmtdhqe.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtldnsxcqd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yvedp.cn/Article/details/gtkctokwvv.html

[E16] 数字千分位
来源：http://dali.tian-w.cn/Article/details/gtspfkrgca.html

Py:   f"{1234567:,}"
来源：http://dali.shangyingyoupin.top/Article/details/gtkzdxaaur.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtpmrhuhfj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtpnamtzfq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.smart0.xyz/Article/details/gtomdkbcmx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtnwakvndu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtjalookkr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtjxooeele.html

C#:   1234567.ToString("N0")
来源：http://dali.dashuyun.cn/Article/details/gtoyepvgwo.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtixgzsgnj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtkrvkgfgt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtlquwnnor.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtxynsvxvi.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtllystswz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtseexyuxv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gotoacloud.top/Article/details/gtbvxpvnxv.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtgvlrrdwh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhoulong.xyz/Article/details/gtdzzkskuy.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtrmxleksf.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hfpthk.cn/Article/details/gtidukppss.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.pengpengdd.cyou/Article/details/gtasjvaqkk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gthqbruvpu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtekmcbluq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gtfyqqyqro.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtsrtralhg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtpbxbyddj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.meibo888.top/Article/details/gtinbnruym.html

[E19] 多行文本按行拆分
来源：http://dali.ivvv.top/Article/details/gthevalvni.html

Py:   s.splitlines()
来源：http://dali.jinqigufen.top/Article/details/gtyribxtkk.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daxiang520.top/Article/details/gtcohoirkv.html

JS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtzfccljph.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gthtlhmcac.html

Java: s.lines().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrxmlmod.html

Go:   strings.Split(s, "\n")
来源：http://dali.jlsjyb.cn/Article/details/gtmuqneauw.html

Ruby: s.lines
来源：http://dali.ehwqpu.com/Article/details/gtagdnmibm.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtpxweqhnh.html

[E20] 判断字符串是否为空
来源：http://dali.svipenyu.cn/Article/details/gtzjytxuoc.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gthzolpwzu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtlmktshsm.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nanxuanxn.top/Article/details/gtgdvzmkse.html

TS:   if (s === "") {}
来源：http://dali.xylfe.cn/Article/details/gtjyawkepu.html

Java: if (s.isEmpty()) {}
来源：http://dali.xinyue.icu/Article/details/gtuztuzbkb.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gtjcvygtps.html

Ruby: if s.empty?
来源：http://dali.birdmap.top/Article/details/gtvugnmdpt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.guowangkeji.top/Article/details/gtleuorchn.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gtmfdetpum.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.9152youxi.cn/Article/details/gtgbpllsor.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.guannengcc.top/Article/details/gtbcltpifk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtusvczoqu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtuyexcigu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtboomyllh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtolyiaknz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinqigufen.top/Article/details/gtyyuuyzxa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtuswkgywt.html

[E22] 字节长度与字符长度
来源：http://dali.cucudq.cn/Article/details/gtvsdarhcz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xylfe.cn/Article/details/gthqbmmfmt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtlgyxvwgn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtctehpcdp.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gteohzsbze.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.tian-w.cn/Article/details/gtikdytdcz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.wangshuangyany.cn/Article/details/gttjlhhmsv.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gtcnlpktof.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yuanzhike.top/Article/details/gtkpdikcmm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gteaylpcxo.html

F. 文件与目录
来源：http://dali.yangfankeji.com/Article/details/gtntthmdxw.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtorhsluvp.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtctgjkxzv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jianghu66.top/Article/details/gtllxkphaz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gttrrlauyb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sysykeji.top/Article/details/gtuigasbsy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtqrqhfsjn.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtuoaabfse.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.pengpengdd.cyou/Article/details/gtrvxldvui.html

Ruby: File.read("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfeoohhpw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hysaishi.cn/Article/details/gtamdgeipu.html

[F02] 逐行读取文件
来源：http://dali.guowangkeji.top/Article/details/gtgcuvjoie.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.c1oappe.top/Article/details/gtwdrssdmz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtssbyxwug.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtzbvjazke.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.tianlin.xyz/Article/details/gtrglvmfgy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtaljhbhag.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzrakjkn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtazihmrsg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.fengsongda.top/Article/details/gtpzzuugbk.html

[F03] 写入文件（覆盖）
来源：http://dali.yongpay.top/Article/details/gtfduqrwfp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.nanxuanxn.top/Article/details/gthyvswdwq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtrymjuzcb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtwmqaaphw.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtoiqyifgl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtuqptlivd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtgrwycuma.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gtaneujnbu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtwcbhwkxk.html

[F04] 追加写入文件
来源：http://dali.snrcjt.cn/Article/details/gtvughikkr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtowsbaedq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj20258.top/Article/details/gttznumwhe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxdlwexa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtbaksfccz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hfpthk.cn/Article/details/gtfnpaknpy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ivvv.top/Article/details/gtyqlvpvdr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tanke756.top/Article/details/gtoxolrxfn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tanke756.top/Article/details/gtemtpffra.html

[F05] 判断文件或目录是否存在
来源：http://dali.9152youxi.cn/Article/details/gtbrzxwfyb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.xylfe.cn/Article/details/gtskcefeja.html

PHP:  file_exists("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtgyrwltnk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gttyecmpgn.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnngonhvc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgfzy.top/Article/details/gtzpvlrqmd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgufenzy.top/Article/details/gtwirhbvdh.html

Ruby: File.exist?("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtzvtvjszm.html

C#:   File.Exists("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtgbgnyves.html

[F06] 删除文件
来源：http://dali.xuanzx.com/Article/details/gttxokuzqw.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtiymeblnw.html

PHP:  unlink("a.txt");
来源：http://dali.tian-w.cn/Article/details/gtonyorfam.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtsgoccpai.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtebkxuyte.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtgdvicuwt.html

Go:   os.Remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtlzuijicy.html

Ruby: File.delete("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtkstbgyqa.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzinrtjqt.html

[F07] 创建目录（含多级）
来源：http://dali.jianghu66.top/Article/details/gtugftpcon.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gthebmgkma.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhxqsgii.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtgwgsfjmf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.snrcjt.cn/Article/details/gtjigtjehu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guannengcc.top/Article/details/gtkfrvdhoc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gtxlrjzqjf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258.top/Article/details/gtphcsuzzv.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtoecaqrgr.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gtqsfjlbgk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtbjddbtie.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tanke756.top/Article/details/gtnjfryqwc.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtxmqqjwrc.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtofeglshn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtbdytryfo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gthaowxfxe.html

Ruby: Dir.children("dir")
来源：http://dali.hnqzz.top/Article/details/gthllztokv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoncptvbm.html


<!-- 参考信息 -->