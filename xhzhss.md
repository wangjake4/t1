代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.meibo888.top/Article/details/gtcndxiifo.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigfzy.top/Article/details/gtigqnauqh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtxewfdnmi.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxpyystoe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtdhymkwtt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtxderpttb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtegulihbn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.gzhubu.top/Article/details/gtctqckstm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxinkj.top/Article/details/gtklktesqq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gttiavzskc.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtklgltliw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.snrcjt.cn/Article/details/gtszdhcyvw.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtmodvzlsb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jlsjyb.cn/Article/details/gtjazohavo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hysaishi.cn/Article/details/gthviqrdob.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtqgpuciiy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.quarkkingdee.top/Article/details/gtizgguoms.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yuxming.cn/Article/details/gtczkprfsu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtskcgzlkg.html

[D26] 数组转字符串
来源：http://dali.pycfn.com/Article/details/gtddgrvxpg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtsxfysbrk.html

PHP:  implode(", ", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtusdnhauu.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtjmffiidr.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtplctdigu.html

Java: String.join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtavfucbol.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gttkdpqixk.html

Ruby: arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtyqcdtbch.html

C#:   string.Join(", ", list)
来源：http://dali.aibaodan.cn/Article/details/gtsrjpfibe.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtriscmvcd.html

E. 字符串处理
来源：http://dali.jqgfzy.top/Article/details/gteakbppta.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtkmrcdqoo.html

[E01] 拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtcikljkoo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.vqdsnc.cn/Article/details/gtewjjcpoy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtktnfwhjg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gtpdphnlqz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtujlerdjz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtufmaqmvn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jianghu66.top/Article/details/gtwwcwaryo.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tanke756.top/Article/details/gtdqmmubet.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtowdlbref.html

[E02] 重复字符串
来源：http://dali.hnqzz.top/Article/details/gtefitcjfq.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gteeranhyn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtatywzkzw.html

JS:   "ab".repeat(3)
来源：http://dali.xinyue.icu/Article/details/gtcoqzfmmg.html

TS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtinltqloh.html

Java: "ab".repeat(3)
来源：http://dali.smart0.xyz/Article/details/gtqtpzqncz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.smart0.xyz/Article/details/gtgtmxiywf.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtegogiatz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shzxlz.cn/Article/details/gtgjzbqnmd.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtaybzotci.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.feifeiyinyue.top/Article/details/gtoljqmcyi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jinqigufen.top/Article/details/gtgkljtlnu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtasgvgvmq.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtwicsupni.html

Java: s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtnefjyedt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gtakcexjph.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxuanxn.top/Article/details/gtyeemaxkg.html

C#:   s.Substring(1, 3)
来源：http://dali.fzhhl.top/Article/details/gthqllduem.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtnoutdrto.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtsvtlbbel.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gttgflfzax.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnbdesxos.html

TS:   s.indexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtftpdwrkf.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtoreixbce.html

Go:   strings.Index(s, "x")
来源：http://dali.hnqzz.top/Article/details/gtokmfyssl.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrnmyyrr.html

C#:   s.IndexOf("x")
来源：http://dali.yongpay.top/Article/details/gtwofrmual.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtxhmqvrcd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gthfvdzcax.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtunyatamo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gtksfgaksp.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtpuxfpgkc.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtfpvarqgh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttctrvzee.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrpazvfn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhixingplan.top/Article/details/gtnakflfge.html

[E06] 替换子串
来源：http://dali.yj20258888.top/Article/details/gtbjmsemuj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtrbwawmfm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gtskzmnreb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtseblwool.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtucouyqfe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtgqwdprcp.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsvjvxdq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmbgswcow.html

C#:   s.Replace("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gteeyqqpzr.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gtwuhtrsay.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtmbkrxivz.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yangfankeji.com/Article/details/gtdwnjnjgf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aizwys.cn/Article/details/gtbywlwkwo.html

TS:   s.split(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxufvrix.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zycfv.cn/Article/details/gtzpyfnczx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.tanke756.top/Article/details/gtiqhlafir.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtrqwilkty.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtezvcjdtq.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtartdrxwr.html

Py:   ",".join(items)
来源：http://dali.xziqi.cn/Article/details/gtgzcansyi.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtynymjfml.html

JS:   items.join(",")
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzixdxvc.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtudgjtykr.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtrplrosqh.html

Go:   strings.Join(items, ",")
来源：http://dali.jiagoushi.top/Article/details/gtnrsbzpda.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gthtfegwtm.html

C#:   string.Join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtfqkwmqxs.html

[E09] 去除所有空白字符
来源：http://dali.sufxvd.cn/Article/details/gtruirbfxp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xylfe.cn/Article/details/gtdhstkvfu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gtefmwmoli.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gtkupiqrgx.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.nanxuanxn.top/Article/details/gtfdvirfpj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.quarkkingdee.top/Article/details/gtaaczaytg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gthmuydpmr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jiagoushi.top/Article/details/gtsxavmlkc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtpucnasxi.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtirhwwcfl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtvljgoifi.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.snrcjt.cn/Article/details/gtadkbsowz.html

JS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtlrubhfzt.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtcmvkkbhv.html

Java: String.format("%03d", 7)
来源：http://dali.iojbl.cn/Article/details/gtycfujmqi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cucudq.cn/Article/details/gtxgjhuseg.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtvrflhnxe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.fzhhl.top/Article/details/gtwxcdpnvp.html

[E11] 反转字符串
来源：http://dali.yuanzhike.top/Article/details/gtxrecaitz.html

Py:   s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gtlvowmtxh.html

PHP:  strrev($s);
来源：http://dali.hysaishi.cn/Article/details/gtsutbpkxm.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtblpsorqh.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvghsjraa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkusofhu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yangfankeji.com/Article/details/gtbionpqtf.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gthymqvdpl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtyvrkbakr.html

[E12] 统计某字符出现次数
来源：http://dali.sweek.top/Article/details/gtvgkpbddf.html

Py:   s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtpbdztxhk.html

PHP:  substr_count($s, "a");
来源：http://dali.aizwys.cn/Article/details/gtltgdcobj.html

JS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtrrjlklwc.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtabeiissx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.svipenyu.cn/Article/details/gtnajohwod.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtmokynomo.html

Ruby: s.count("a")
来源：http://dali.hywenlv.cn/Article/details/gtngpniabz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.andypj.xyz/Article/details/gtpxeppeyf.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtmdffqlbe.html

Py:   for ch in s: print(ch)
来源：http://dali.zhiwuduotai.top/Article/details/gtuiknppjs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtpcywkqrp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gticnqedug.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtocqxamdo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cashguo.top/Article/details/gtctrfkftv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gtfiutbqjq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gtrhsnkqhz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtkrqcofoz.html

[E14] URL 编码与 Base64
来源：http://dali.ybcxt.top/Article/details/gtxyvpmwpi.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yvedp.cn/Article/details/gtxuikofqk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtpzgbzgxs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.quarkkingdee.top/Article/details/gtjgcffnen.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgfzy.top/Article/details/gtblcvkmwf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtryxotdcz.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gotoacloud.top/Article/details/gtihkchirg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsplqxbws.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jlsjyb.cn/Article/details/gtpjpydpfk.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gtptmibasl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslxdtbck.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gtpfrncqid.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.kuanghao11.cn/Article/details/gtdmkbbwac.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhongyouzk.top/Article/details/gtamoymaiv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.feifeiyinyue.top/Article/details/gtyohinkaj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtszsnmnog.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj202588.top/Article/details/gtcufornme.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtflaporfz.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gttountvzc.html

Py:   f"{1234567:,}"
来源：http://dali.svipenyu.cn/Article/details/gtzxfwfshg.html

PHP:  number_format(1234567);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfejalcy.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xinyue.icu/Article/details/gtlicvorpg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhzehrwu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.smart0.xyz/Article/details/gtzfpcowhd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hfpthk.cn/Article/details/gtbibyvkwa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yangfankeji.com/Article/details/gtheupwxuz.html

C#:   1234567.ToString("N0")
来源：http://dali.ehwqpu.com/Article/details/gtfbsreoqp.html

[E17] 首字母大写
来源：http://dali.zhijiandao.cn/Article/details/gtlbrniftg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gtdmncbdvd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yvedp.cn/Article/details/gtxsxvpzpr.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtyovkdgpk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gtkfwqomvi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtogfqmwsv.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yj20258888.top/Article/details/gtklkdwbxg.html

Ruby: s.capitalize
来源：http://dali.daria6918.cn/Article/details/gttpgjarws.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gtlpinnaru.html

[E18] 模板占位符替换
来源：http://dali.xuanzx.com/Article/details/gtrpwbciof.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ydzc1.top/Article/details/gtxquiiwcb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ybcxt.top/Article/details/gtxufawoze.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtswtkkpui.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtwpzufbyd.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gtzdcwoefu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtnakbqcmg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuanzhike.top/Article/details/gthqxfdpfm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hongshengwenyu.top/Article/details/gtavtqaica.html

[E19] 多行文本按行拆分
来源：http://dali.cashguo.top/Article/details/gtjfelwnlw.html

Py:   s.splitlines()
来源：http://dali.gaohongyu789.top/Article/details/gtglgxxemm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yj20258888.top/Article/details/gtsygotajl.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gtkuavfrcr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtatzyeatd.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtrsplywtr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ivvv.top/Article/details/gtyjedzdyb.html

Ruby: s.lines
来源：http://dali.jiagoushi.top/Article/details/gtdcorvxuq.html

C#:   s.Split('\n')
来源：http://dali.haohaochexian.top/Article/details/gtftoenuqq.html

[E20] 判断字符串是否为空
来源：http://dali.bjfxy.top/Article/details/gtmetjpbes.html

Py:   if not s:
来源：http://dali.birdmap.top/Article/details/gtsznhkust.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jqgufenzy.top/Article/details/gtijzenicw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtuofxnkju.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtsajanamt.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtoaxfgcpf.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtgunhlnoc.html

Ruby: if s.empty?
来源：http://dali.cdnleiting.top/Article/details/gtlwlivqpr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtyvdpmihp.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtdgnggviz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tian-w.cn/Article/details/gtxmbtswht.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtupmbmylu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtpkhetaxl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gttnpcpplg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtgcxtgost.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gtufwaroyn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gtjanrwbog.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtxqpkhwwn.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtnlosqwqj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sysykeji.top/Article/details/gtiywnxwxk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.guowangkeji.top/Article/details/gtzccnpvmw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gtwiyaikre.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gteqynqisv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yangfankeji.com/Article/details/gtxsdlvnag.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhongyouzk.top/Article/details/gtlztnsufu.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtturowytc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ybcxt.top/Article/details/gthehytakq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gteiuwvjbo.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtzvqkzupq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtruswgvgu.html

[F01] 读取整个文件
来源：http://dali.cdnleiting.top/Article/details/gtuaxkwbky.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.guowangkeji.top/Article/details/gtbqgtiwxo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtnlcraewk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hfpthk.cn/Article/details/gtegqxptck.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtpkbnxqze.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pycfn.com/Article/details/gtsjdrfnvx.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtgiydkytk.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtlbtslovm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtmnzhmkjx.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrudcmakn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sysykeji.top/Article/details/gtwwyqtodb.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtuvjndonm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvfmwbtm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gtbeyjjtjm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtdfrkblvk.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gthitxgskf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtrjspzneq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hongshengwenyu.top/Article/details/gtulnkvbfv.html

[F03] 写入文件（覆盖）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgmwavlsg.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jinghuilouyu.cn/Article/details/gtkllrpshm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyntfwtuv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtvbbqqktl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtskarlgow.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xuetiantiany.cn/Article/details/gthecfcpvh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhoulong.xyz/Article/details/gtwraagavx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtxrkxntja.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtcscyyttr.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtbrqkuheu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gtrqzzcudv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.mhx1999.top/Article/details/gtxdggcred.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbwvfgkw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gttxdrkdyo.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gtynspmguf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoitpjxdb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yonumen.top/Article/details/gttchbqzxy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nanxuanxn.top/Article/details/gteslmnqch.html

[F05] 判断文件或目录是否存在
来源：http://dali.jyoumei.cn/Article/details/gtmyitkwdz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.smart0.xyz/Article/details/gttjqxknqc.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtzrpxolww.html

JS:   fs.existsSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtkfwsjptm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gthcyoiwos.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cdnleiting.top/Article/details/gtnksolchc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tian-w.cn/Article/details/gthkpfowzw.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtsccnybem.html

C#:   File.Exists("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtyizoxvza.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtojvtfqrh.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpnfujobm.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtqmlvizoq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gtsjnudmow.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtcioeqtez.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gtbvbppfax.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwiqqcifw.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtygmkrytg.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtjjdkbjxc.html

[F07] 创建目录（含多级）
来源：http://dali.jqgufenzy.top/Article/details/gtiyvnbyxj.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtkajvztgn.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yueranfly.top/Article/details/gtmzkksrim.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtkehlntpw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shangyingyoupin.top/Article/details/gtwbmvlpca.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuanzhike.top/Article/details/gtrhelefoj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.haohaochexian.top/Article/details/gtogkfmuft.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.snrcjt.cn/Article/details/gtmtialbhe.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gtoagagdew.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtyipnhynx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.tianlin.xyz/Article/details/gtyaxpokvg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yuanzhike.top/Article/details/gtgwpwgjlb.html

JS:   fs.readdirSync("dir")
来源：http://dali.yangfankeji.com/Article/details/gtmicgbfzk.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtaskanoal.html


<!-- 参考信息 -->