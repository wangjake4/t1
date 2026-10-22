代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.quarkkingdee.top/Article/details/gtfhpzprmm.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gteorvdpzz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yj202588.top/Article/details/gtfjrouoqw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtjlxzoibb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yj20258.top/Article/details/gtkccdfisb.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yj20258.top/Article/details/gtldxqulpg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.feifeiyinyue.top/Article/details/gtijruotuv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.mhx1999.top/Article/details/gtztuqlmen.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gthhvieifq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtpfptyauh.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gttkcgvrzs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtydpmwbeq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtwxbqfcyc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yuxming.cn/Article/details/gtcdqgibhi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gogol.net.cn/Article/details/gtsjpxozvl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gthwbuveep.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtaupyzrqt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.fengsongda.top/Article/details/gtjxmyswoc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtqtpdvgqm.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkwnclka.html

Py:   ", ".join(map(str, arr))
来源：http://dali.vqdsnc.cn/Article/details/gthlnmlvrx.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gthbxurbuo.html

JS:   arr.join(", ")
来源：http://dali.zhoulong.xyz/Article/details/gttpbnbqag.html

TS:   arr.join(", ")
来源：http://dali.tianlin.xyz/Article/details/gtygfzqjvc.html

Java: String.join(", ", list)
来源：http://dali.pengpengdd.cyou/Article/details/gtszjkhihd.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtbzijrrpz.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtcbylfmov.html

C#:   string.Join(", ", list)
来源：http://dali.cqqwz.cn/Article/details/gtzropktcn.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtumyxjfyj.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gtpssehaax.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtlzdgeshv.html

[E01] 拼接字符串
来源：http://dali.hammf.cn/Article/details/gtuwzzznln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtgqhkeguu.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtzfgvmpkt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtspkpqzpv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtihtrhzem.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtwxculstj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yangfankeji.com/Article/details/gtdsshqscb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cheryme.top/Article/details/gtrbizzmxs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtylsecmse.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gthnpksopc.html

Py:   "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtjseyyefe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllmlusbs.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtywuykogs.html

TS:   "ab".repeat(3)
来源：http://dali.zhengqikj.top/Article/details/gtasdltqyo.html

Java: "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtoumhadad.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtmjqfidym.html

Ruby: "ab" * 3
来源：http://dali.zhijiandao.cn/Article/details/gtafbporfq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtwqtgatpm.html

[E03] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowxsvoyi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtmyrrfyyl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtleifbovf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtzcvxrrxl.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtevhigseg.html

Java: s.substring(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gtlvquyczd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqudglte.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtueqzoxwr.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtviiqqdsu.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtacbejkis.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtlpgasnjt.html

PHP:  strpos($s, "x");
来源：http://dali.guannengcc.top/Article/details/gtttjmtbec.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtewklrfez.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtioctfsqq.html

Java: s.indexOf("x")
来源：http://dali.gzhubu.top/Article/details/gtqhnmqgdl.html

Go:   strings.Index(s, "x")
来源：http://dali.gzhubu.top/Article/details/gtphsogjac.html

Ruby: s.index("x")
来源：http://dali.ivvv.top/Article/details/gtibmhvvdl.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtqbroamer.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jinqigufen.top/Article/details/gtcykzpeis.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xinyue.icu/Article/details/gteujwysyh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gtsqdkpyia.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigfzy.top/Article/details/gttxoglatt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cucudq.cn/Article/details/gtmsuuptxy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtkmkyzxmy.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gtdhqgwrcx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbmcokci.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtarozvkuy.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gtdogblgyf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtgfqoxoll.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtzevxdklm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gtodyjsobr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtpvzrwwjd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gtchwowbxx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfowotrsk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtdtqnlwqw.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxzzxzti.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtewhizfyj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtvftscmku.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yueranfly.top/Article/details/gtpejmrutf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yvedp.cn/Article/details/gtwbuxfoci.html

TS:   s.split(",")
来源：http://dali.cheryme.top/Article/details/gtkxnnpsnb.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtowbyusus.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gtzqgxlakx.html

Ruby: s.split(",");  s.split
来源：http://dali.feifeiyinyue.top/Article/details/gtechadhra.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtynlpqzvv.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gtvlgtxnox.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtmzytxpha.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtljoaioww.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gtbqwkdiui.html

TS:   items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtrfobelbt.html

Java: String.join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gtxqvwrmiw.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtnvyhsxkg.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtryreysba.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtiprsqivf.html

[E09] 去除所有空白字符
来源：http://dali.wangshuangyany.cn/Article/details/gtucpjlnki.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ppjwa.cn/Article/details/gtdkoyhgxo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtzwwaukbb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gteuoesbbf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtitwukzvp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtlwsewdyl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvmslnpx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cdnleiting.top/Article/details/gtbiofungy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtibyyhztp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.gotoacloud.top/Article/details/gteaovusmp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gttheniytn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.aizwys.cn/Article/details/gtlrgzhslv.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtgfnrujlo.html

TS:   "7".padStart(3, "0")
来源：http://dali.yj20258.top/Article/details/gtmzfdftxi.html

Java: String.format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtudvlurqr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtvtzbffzf.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtpuirfddy.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwijamnxo.html

[E11] 反转字符串
来源：http://dali.guowangkeji.top/Article/details/gttrezdkze.html

Py:   s[::-1]
来源：http://dali.yangfankeji.com/Article/details/gtzisoduww.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gtvmfkzucz.html

JS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtjtbpwaup.html

TS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtomztvrcq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenjidiqi.icu/Article/details/gtfbdtwzeu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.smart0.xyz/Article/details/gtsncrmbxm.html

Ruby: s.reverse
来源：http://dali.nwbrower.top/Article/details/gtooysjytk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gtsdyiylmo.html

[E12] 统计某字符出现次数
来源：http://dali.ybcxt.top/Article/details/gtqrzconly.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtvfhpvdgk.html

PHP:  substr_count($s, "a");
来源：http://dali.hongshengwenyu.top/Article/details/gtttlvgbrt.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtxuwniyjj.html

TS:   s.split("a").length - 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxqumnij.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gtacnldizs.html

Go:   strings.Count(s, "a")
来源：http://dali.sxryk.cn/Article/details/gtehfuxqpf.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezndvjgc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtgdqtjgyh.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtqlsdezjc.html

Py:   for ch in s: print(ch)
来源：http://dali.xinyue.icu/Article/details/gtxazbsxdp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pycfn.com/Article/details/gtxcubrcmx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnxxesrgr.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gthqdlzxmh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtuqamagzy.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.kuanghao11.cn/Article/details/gtvabxqqxs.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tian-w.cn/Article/details/gtfbdqsqam.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmlrlpmjd.html

[E14] URL 编码与 Base64
来源：http://dali.svipenyu.cn/Article/details/gtrbqoujvs.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiplvzqt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.quarkkingdee.top/Article/details/gtuyfnmpuz.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cheryme.top/Article/details/gtcmpylctz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.snrcjt.cn/Article/details/gtlsjceoal.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tanke756.top/Article/details/gtwerglvie.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtzdquwoak.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj202588.top/Article/details/gtyxfetsbr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ehwqpu.com/Article/details/gtnjzfqhyh.html

[E15] HTML 转义 / 反转义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksnpclgp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtrvqpcnjr.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.nwbrower.top/Article/details/gtyxjhuehy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtjtozvabh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gtmcpkqegh.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hnqzz.top/Article/details/gtmlrzvklc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtgqohgzuk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtcejmezqm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtggylnctz.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtoqnwqkfo.html

Py:   f"{1234567:,}"
来源：http://dali.guannengcc.top/Article/details/gtrtzjxvas.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtszfaeqeg.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gtsygnisop.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtdqvfoxme.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtjwhpukwh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhixingplan.top/Article/details/gtlselrnlu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtxjpdxqhq.html

C#:   1234567.ToString("N0")
来源：http://dali.iojbl.cn/Article/details/gtffpfwzel.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gtgjjgkfbw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.daria6918.cn/Article/details/gtvwtolpzx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.c1oappe.top/Article/details/gtdmsafprs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxrkokpg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtvuyaqeut.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.snrcjt.cn/Article/details/gtkoyzytoo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtzgenxqud.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gthkogdchc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtdesyxkil.html

[E18] 模板占位符替换
来源：http://dali.ivvv.top/Article/details/gtulmoosgu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tanke756.top/Article/details/gtiylbxfnb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtmcahpblv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtwveplvqn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtlxticntv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtvhaouhip.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gtspkjenxl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yuxming.cn/Article/details/gtndhssibf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtriawxofq.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtdpacjxut.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gtnxisaczv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxtgxngga.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwcyhlkk.html

TS:   s.split(/\r?\n/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwgxxydf.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtdmymeujc.html

Go:   strings.Split(s, "\n")
来源：http://dali.xylfe.cn/Article/details/gtlqsczbgr.html

Ruby: s.lines
来源：http://dali.hysaishi.cn/Article/details/gtfzrvkqvz.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtlozgloff.html

[E20] 判断字符串是否为空
来源：http://dali.jyoumei.cn/Article/details/gtlqlhbqlz.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtoojuzfiz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ivvv.top/Article/details/gtwxgdqkhw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ivvv.top/Article/details/gtqeqduxcb.html

TS:   if (s === "") {}
来源：http://dali.gzhubu.top/Article/details/gtnmzwpueo.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtfdhcyfjq.html

Go:   if s == "" {}
来源：http://dali.yuanzhike.top/Article/details/gtdpdihjil.html

Ruby: if s.empty?
来源：http://dali.ivvv.top/Article/details/gtdzuetuzo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtobyfskmz.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gthlgyjsez.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gtyynqcdrp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtnrmkpjzx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtoputmkbr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtaclpiudp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtjjyhlttf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cashguo.top/Article/details/gtigfetryj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtpfogqgzm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtliwpryqr.html

[E22] 字节长度与字符长度
来源：http://dali.xinyue.icu/Article/details/gtuuapihui.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ybcxt.top/Article/details/gtwpbnjvma.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtlrlvksiw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtikpmroys.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtvaahvpuj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtiygwzloc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yongpay.top/Article/details/gtarngbdfm.html

Ruby: s.bytesize;  s.length
来源：http://dali.shangyingyoupin.top/Article/details/gtuibinvfa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gotoacloud.top/Article/details/gtvajxpopa.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtsqivqjit.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxtdqbjqk.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtfarkotvd.html

[F01] 读取整个文件
来源：http://dali.vqdsnc.cn/Article/details/gtljutjghk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sysykeji.top/Article/details/gtdvobqeda.html

PHP:  file_get_contents("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtpkksmidw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shuidangran.top/Article/details/gtjzzgtrur.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yongpay.top/Article/details/gtpgcxtvks.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatwoipxc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jqgufenzy.top/Article/details/gttoqlgdiz.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtcojjgaki.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gtjuwiqsby.html

[F02] 逐行读取文件
来源：http://dali.tianlin.xyz/Article/details/gtczhwqtib.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.meibo888.top/Article/details/gtksbfaxhu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpityudlu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.aizwys.cn/Article/details/gtguplcmvh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.quarkkingdee.top/Article/details/gtfksilsru.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xuanzx.com/Article/details/gtokuttrbl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hongshengwenyu.top/Article/details/gtyllndmer.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.haohaochexian.top/Article/details/gtffrzrixd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.ppjwa.cn/Article/details/gtmxdwmtdy.html

[F03] 写入文件（覆盖）
来源：http://dali.cucudq.cn/Article/details/gthjqgjkyo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guowangkeji.top/Article/details/gtzefguuzj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.andypj.xyz/Article/details/gtdekfuwwx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsszpwlov.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtehyveoei.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtzmmblcoj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gotoacloud.top/Article/details/gtdmgieqxw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gttoiqiriz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtvuvycham.html

[F04] 追加写入文件
来源：http://dali.tanke756.top/Article/details/gtsurrzfmt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nanxuanxn.top/Article/details/gtaooxbzwc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtuphbnqmv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtacpeiuoa.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhongyouzk.top/Article/details/gtnnvdzdls.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.dianchejie.cn/Article/details/gtjydooxgf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.haohaochexian.top/Article/details/gtxrcwnulv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xuanzx.com/Article/details/gtegmxbdzb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqllpisxr.html

[F05] 判断文件或目录是否存在
来源：http://dali.tian-w.cn/Article/details/gtssfjkmqh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gthliazsai.html

PHP:  file_exists("a.txt");
来源：http://dali.sxryk.cn/Article/details/gtrfvatidi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttgolyxbu.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtvgfeatjc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtawnuprmj.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gteerfcgjw.html

Ruby: File.exist?("a.txt")
来源：http://dali.yonumen.top/Article/details/gthhdmoqai.html

C#:   File.Exists("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtxaqwvmqh.html

[F06] 删除文件
来源：http://dali.smart0.xyz/Article/details/gtchkwwqjr.html

Py:   os.remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdlzstsa.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtbjyssppi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtmkfwajuw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtgrpmtqtn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gtlrxxfbeo.html

Go:   os.Remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkpxtrdey.html

Ruby: File.delete("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvwulkrom.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtkahifqec.html

[F07] 创建目录（含多级）
来源：http://dali.ehwqpu.com/Article/details/gtqypvonri.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcpgobya.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hammf.cn/Article/details/gthriprkmg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuxming.cn/Article/details/gtnhdvbomz.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuanzx.com/Article/details/gtrwnqyvfq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hysaishi.cn/Article/details/gticxxnggl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtkhppxluc.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zycfv.cn/Article/details/gtpyvcymqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.fzhhl.top/Article/details/gtsvcacnfc.html

[F08] 遍历目录
来源：http://dali.cdnleiting.top/Article/details/gtpmnylepr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtigwxvykx.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.meibo888.top/Article/details/gtcwhwkhuz.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gtgvqhcrwm.html

TS:   fs.readdirSync("dir")
来源：http://dali.hammf.cn/Article/details/gtpyhtdhig.html


<!-- 参考信息 -->