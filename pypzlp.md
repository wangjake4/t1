代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtmgpbdeqj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zhiwuduotai.top/Article/details/gtonmcrvod.html

Go:   // 手写循环
来源：http://dali.wangdashe.top/Article/details/gtxsopwcvq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtzircrsgc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gtthinwqlx.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhengqikj.top/Article/details/gtewmbdcxr.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtqtimbmpq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shuidangran.top/Article/details/gtuogcdgux.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.bjfxy.top/Article/details/gtsoonqztn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtcuvrtwgt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gttzrgphgr.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gtgdcyntwh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.svipenyu.cn/Article/details/gtphgurhxx.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtxkxmaiti.html

[D25] Set 集合去重与交并差
来源：http://dali.hnxiangtu.top/Article/details/gtfudetxrw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yj202588.top/Article/details/gtgxzuobdi.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gtoolrodxc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtmlcvxybm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gthaehfdwv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtaczowvbl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sufxvd.cn/Article/details/gtwpnoixsg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtqhwugvox.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.vqdsnc.cn/Article/details/gtqjtdvasp.html

[D26] 数组转字符串
来源：http://dali.jinqigufen.top/Article/details/gtspwxrbxd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.redwolf501.top/Article/details/gtixdtdtta.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gtizdhycwv.html

JS:   arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtwsmvlnbi.html

TS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtmzkbedqx.html

Java: String.join(", ", list)
来源：http://dali.316326.xyz/Article/details/gtznzoxzas.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gzhubu.top/Article/details/gtqnkoepxb.html

Ruby: arr.join(", ")
来源：http://dali.chenlongwang.top/Article/details/gtkheauhvy.html

C#:   string.Join(", ", list)
来源：http://dali.hysaishi.cn/Article/details/gtzvmvpvna.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtfwjlcaas.html

E. 字符串处理
来源：http://dali.nwbrower.top/Article/details/gtxdvraupd.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdovbursx.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtsbiibhpx.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hnxiangtu.top/Article/details/gtokfcfkox.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzlxoeieu.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sysykeji.top/Article/details/gtkskjctjd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtjgdjvrvi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zdqjudy.top/Article/details/gtgdubrjcv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.mhx1999.top/Article/details/gtsygrpxjw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuuvtkee.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtsvypgliu.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtawzbalbu.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gthvvyaaqi.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtuarfzyfm.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttoexyqqg.html

TS:   "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtdykoikmy.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqocgycln.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yueranfly.top/Article/details/gtjetmvesa.html

Ruby: "ab" * 3
来源：http://dali.zhixingplan.top/Article/details/gtfeoeqsgl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtwxevtxvb.html

[E03] 截取子串
来源：http://dali.sxryk.cn/Article/details/gthgdbnbjs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.havefunace.top/Article/details/gtbpnvxfvi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gtmzdcgktp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtfdbjnfoo.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gtifjezjjd.html

Java: s.substring(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtcwnodmed.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gthzrpbeeo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daxiang520.top/Article/details/gtbizvwmqa.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtfoqjiyoa.html

[E04] 查找子串位置
来源：http://dali.jqgufenzy.top/Article/details/gtllfdpego.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtnvtegowg.html

PHP:  strpos($s, "x");
来源：http://dali.yonumen.top/Article/details/gtqpzldwlx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdidaetvz.html

TS:   s.indexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gtmelepypk.html

Java: s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtfinhbxoc.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtfzbkzbkk.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gturwrawtk.html

C#:   s.IndexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseqiruaz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sxryk.cn/Article/details/gtwdzxztvq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.tian-w.cn/Article/details/gtoncjcpvi.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtrdouopqm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtwxnamypz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ehwqpu.com/Article/details/gtgkqjrhye.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqlzfzdy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tian-w.cn/Article/details/gthlmilbvc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hywenlv.cn/Article/details/gtekcahlwq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhxbrwqe.html

[E06] 替换子串
来源：http://dali.jinghuilouyu.cn/Article/details/gtemrzscyl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtivmugtik.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtezydqmhx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtutmkcspb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtgdkudyzq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gtuaixoice.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhoulong.xyz/Article/details/gteldldvcu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.meibo888.top/Article/details/gtapvilerl.html

C#:   s.Replace("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gttuyahikm.html

[E07] 按分隔符拆分
来源：http://dali.zycfv.cn/Article/details/gtgragagqj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xziqi.cn/Article/details/gtdtzahhpx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtbwptlinl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.bjfxy.top/Article/details/gtvgqpwytt.html

TS:   s.split(",")
来源：http://dali.cqqwz.cn/Article/details/gtnxryplqf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.pengpengdd.cyou/Article/details/gtijjczmge.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtzpvrnubf.html

Ruby: s.split(",");  s.split
来源：http://dali.haohaochexian.top/Article/details/gtkhtbyqjw.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.guannengcc.top/Article/details/gtovfbvbxo.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtengbfnkv.html

Py:   ",".join(items)
来源：http://dali.daria6918.cn/Article/details/gttrjkwhrm.html

PHP:  implode(",", $items);
来源：http://dali.ivvv.top/Article/details/gtwatudgsv.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gttgiepfmm.html

TS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtazrnupvs.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gthypujjzn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtfilruxta.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujxnvbrf.html

C#:   string.Join(",", items)
来源：http://dali.fengsongda.top/Article/details/gtkavtvcjy.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtpkhqbwir.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fengsongda.top/Article/details/gtuhydlzyk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gtevidcnqw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtsufatlok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtsvzannzh.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gtsikomxqm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xinyue.icu/Article/details/gtpkycbvxg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.quarkkingdee.top/Article/details/gtqhvrxguj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtysnzwpzt.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yj20258.top/Article/details/gtsipfyolz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtnshrmfyg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.feifeiyinyue.top/Article/details/gtjcpiejov.html

JS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtsayvcvjm.html

TS:   "7".padStart(3, "0")
来源：http://dali.haohaochexian.top/Article/details/gtqplwmqpw.html

Java: String.format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrixgkpnq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtwltzzdlo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtlsukwawd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhigrgje.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gteurftequ.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtptqhsalr.html

PHP:  strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gtuhmlrjct.html

JS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdccjwcwo.html

TS:   [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gtzsbhueax.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtzpvblwuf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtsqclfyue.html

Ruby: s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gtblvnpvne.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.fzhhl.top/Article/details/gtdjpumglz.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtzqrqywuu.html

Py:   s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtnmjpckix.html

PHP:  substr_count($s, "a");
来源：http://dali.xuanzx.com/Article/details/gtokysyzrm.html

JS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gtoxdjojqo.html

TS:   s.split("a").length - 1
来源：http://dali.zhixingplan.top/Article/details/gtgfaicclp.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xylfe.cn/Article/details/gthiscylan.html

Go:   strings.Count(s, "a")
来源：http://dali.mhx1999.top/Article/details/gtjovvybpy.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtlfpipqdf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtaapoutfy.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtslpwcbhs.html

Py:   for ch in s: print(ch)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtscwqevju.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fzhhl.top/Article/details/gtzufnrpau.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtxgihsmvh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtabbjfzkc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gteeyoyhuf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gzhubu.top/Article/details/gtslwtuyfo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtnxdoakvr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtkkkwviik.html

[E14] URL 编码与 Base64
来源：http://dali.yanxiufei.cn/Article/details/gtevuqbqdf.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.quarkkingdee.top/Article/details/gtbrvshgcw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yuxming.cn/Article/details/gttzzhnkoy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtsyhbvyka.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtkkoulhfx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtkdtqynyy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtxjmjdemt.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tianlin.xyz/Article/details/gtdquvpcjq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shuidangran.top/Article/details/gtetktfqdj.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtypitijks.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gtdebpklps.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hammf.cn/Article/details/gtzqixkvls.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtbjuqzreh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cucudq.cn/Article/details/gtcijbqwox.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hywenlv.cn/Article/details/gtklztflod.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ybcxt.top/Article/details/gtyfgfqdvb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtqitvenbg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hysaishi.cn/Article/details/gthtnkrpqh.html

[E16] 数字千分位
来源：http://dali.havefunace.top/Article/details/gtbdfgwjxx.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtnwrghpdm.html

PHP:  number_format(1234567);
来源：http://dali.feifeiyinyue.top/Article/details/gtjvcszppb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.nwbrower.top/Article/details/gtzahdnaco.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtrnqrsxfg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.feifeiyinyue.top/Article/details/gtoiyuvusb.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gttqlfzcqp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtxlgetvdj.html

C#:   1234567.ToString("N0")
来源：http://dali.zhengqikj.top/Article/details/gtpsvpdcgp.html

[E17] 首字母大写
来源：http://dali.cashguo.top/Article/details/gtlnogcnmg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnqzz.top/Article/details/gtywukearj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gtwbemvbfv.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiyutnty.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtqewjxgqa.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gtxgkqdwrk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sweek.top/Article/details/gtegzsbobt.html

Ruby: s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gtvzpcvnlr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xylfe.cn/Article/details/gtylatrshe.html

[E18] 模板占位符替换
来源：http://dali.yvedp.cn/Article/details/gtglsgsgkt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhongyouzk.top/Article/details/gteyetuvef.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gtovkpfols.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gtlyucfhmu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtrpyhifnq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtiqdvshdv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtwtlghwjy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gtcmablknm.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gogol.net.cn/Article/details/gtesvwiaqy.html

[E19] 多行文本按行拆分
来源：http://dali.zdqjudy.top/Article/details/gtgvfynzan.html

Py:   s.splitlines()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfossrqea.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gzhubu.top/Article/details/gtcmgyhcia.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwakcoyvb.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtfmavtjhr.html

Java: s.lines().toList()
来源：http://dali.zhixingplan.top/Article/details/gtlwwefepl.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gttqtxyihp.html

Ruby: s.lines
来源：http://dali.meibo888.top/Article/details/gtgcfasaor.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtgfycqkbd.html

[E20] 判断字符串是否为空
来源：http://dali.xziqi.cn/Article/details/gtvwuvocrs.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gtscwpfgbo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hammf.cn/Article/details/gtrpwpsuxx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtkmtnmrqw.html

TS:   if (s === "") {}
来源：http://dali.daxiang520.top/Article/details/gthhpubehy.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gtujoyyqyu.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtnotcjxie.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gtgocaezqg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtlkgkaphn.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gtacbbfhlr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gtrjjtnlqq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gtlvdiaqry.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.0kj1m.cn/Article/details/gtsslnzvxb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtoxjoxgmg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtnoikdmzh.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigufen.top/Article/details/gtkbgiilhn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhtvvpul.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtcuirslfk.html

[E22] 字节长度与字符长度
来源：http://dali.pengpengdd.cyou/Article/details/gtngvezbdo.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtgsnftjgx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yueranfly.top/Article/details/gtcvtlpymt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtmriekbts.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gtiswxtvby.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtxbrhtvyn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtkjbgqkwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.9152youxi.cn/Article/details/gteewrjsst.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtoumbubvs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttecbbfzz.html

F. 文件与目录
来源：http://dali.zhiwuduotai.top/Article/details/gtgwozsuev.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtefuexizd.html

[F01] 读取整个文件
来源：http://dali.yj20258888.top/Article/details/gtghswarrr.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gaohongyu789.top/Article/details/gtshypvgig.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtcphabjic.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.bjfxy.top/Article/details/gtkvhovonz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtnruuocql.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gtcruzvabn.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdvlnfdr.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtrjtmydda.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtkhnuymtb.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtcwbvcgjm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtwebupman.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuxming.cn/Article/details/gtaxgnugik.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gaohongyu789.top/Article/details/gtneopafjs.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtojharbsm.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gtdouexdyl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.birdmap.top/Article/details/gtzdohdyhk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtgfpitojj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gtpctzwbmc.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gthxbirxui.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gthkjhcgaj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gttvzjmhyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtwpztboqv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtvhnyqbid.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gtevngsxfi.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtxjzybxdm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtbmtacjfp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtpvoenzki.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpbyupip.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gttdbwwuul.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtcbhcjidb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtuijqnjzw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtveisuclc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuetiantiany.cn/Article/details/gtznbsivwh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtxtuplqnh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gtszfdvwcw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yanxiufei.cn/Article/details/gtqphrtuur.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigfzy.top/Article/details/gtxxlxkytx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hywenlv.cn/Article/details/gtsjowmqak.html

PHP:  file_exists("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtjpvbsvta.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtoldztzpp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttcecniti.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwivobml.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtrejwbndg.html

Ruby: File.exist?("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtwkggwjoq.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtslhjjtqg.html

[F06] 删除文件
来源：http://dali.mhx1999.top/Article/details/gtjzmpfpkc.html

Py:   os.remove("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtzitgapoa.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtiacmnpxq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtcidkfumk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtucqvmlpi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gteykwfsjn.html

Go:   os.Remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtemwdkdog.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtnhdpflmn.html

C#:   File.Delete("a.txt");
来源：http://dali.zycfv.cn/Article/details/gthtshkdml.html

[F07] 创建目录（含多级）
来源：http://dali.sufxvd.cn/Article/details/gtxdemddhq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtyupndkbi.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtbcuvbsrn.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gthiaazqlx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ppjwa.cn/Article/details/gtlvundonl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hywenlv.cn/Article/details/gtktosvzdh.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj20258888.top/Article/details/gtcrysimtn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hnqzz.top/Article/details/gtjwpukrkw.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhoulong.xyz/Article/details/gtaayjynbw.html

[F08] 遍历目录
来源：http://dali.nanxuanxn.top/Article/details/gtzxiwjviy.html


<!-- 参考信息 -->