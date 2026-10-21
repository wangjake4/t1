代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gttohijsqk.html

[D24] 字典 / Map 基本操作
来源：http://dali.hnxiangtu.top/Article/details/gtouqcknze.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yueranfly.top/Article/details/gtyuecnavq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtiynrphow.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hammf.cn/Article/details/gtyqraaxam.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtaqejybgt.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtolkfdqfw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.316326.xyz/Article/details/gtkmivzere.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gtovipcerg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hammf.cn/Article/details/gtwhehfitt.html

[D25] Set 集合去重与交并差
来源：http://dali.daria6918.cn/Article/details/gtynbyjaho.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtzhhkqkbl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigfzy.top/Article/details/gtpzpoqsyn.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gtgxrkplmd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.meibo888.top/Article/details/gtarazhoaz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrpqpbtej.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tanke756.top/Article/details/gtlllkyrgy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.haohaochexian.top/Article/details/gtzxggxscf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cheryme.top/Article/details/gtoxvzeuvu.html

[D26] 数组转字符串
来源：http://dali.andypj.xyz/Article/details/gtcqbwmokb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hfpthk.cn/Article/details/gtrgnclcqz.html

PHP:  implode(", ", $arr);
来源：http://dali.jianghu66.top/Article/details/gthverpenf.html

JS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gtwlllnxbr.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtkfwutqax.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtymxnnkmw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.andypj.xyz/Article/details/gtwzrkgouv.html

Ruby: arr.join(", ")
来源：http://dali.yj202588.top/Article/details/gtkgscjhbn.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gtmupfarhs.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbvlmelfz.html

E. 字符串处理
来源：http://dali.cashguo.top/Article/details/gtgaogajtd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtijfgybmn.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtwovzhpzt.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticisealc.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gtxebehddf.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jyoumei.cn/Article/details/gtckxzqgwk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.fzhhl.top/Article/details/gtvawjywbo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gtjbqzezud.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ydzc1.top/Article/details/gtwputhzbb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.feifeiyinyue.top/Article/details/gtyhpdefki.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gtikknoasg.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtseluvvba.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtgixrbikx.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtauxldbth.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtregptocs.html

TS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtspjmrzrc.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtrdzryoke.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.daxiang520.top/Article/details/gtkmxtuvqa.html

Ruby: "ab" * 3
来源：http://dali.hammf.cn/Article/details/gtzbcqxglj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jianghu66.top/Article/details/gtlygsklbj.html

[E03] 截取子串
来源：http://dali.c1oappe.top/Article/details/gtaohlapiw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtqtgfkmeb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtxmyzczts.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gthmekwvak.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiykrefje.html

Java: s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtgburjmjo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cashguo.top/Article/details/gtfjvrmmaq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.ivvv.top/Article/details/gtpxxnepze.html

C#:   s.Substring(1, 3)
来源：http://dali.sysykeji.top/Article/details/gtfwtnnhlu.html

[E04] 查找子串位置
来源：http://dali.xuetiantiany.cn/Article/details/gtmiuihtoz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ivvv.top/Article/details/gtqfgtwchs.html

PHP:  strpos($s, "x");
来源：http://dali.0kj1m.cn/Article/details/gtzncpsinf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtbbotzcuz.html

TS:   s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtockufhpu.html

Java: s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtchmujcsi.html

Go:   strings.Index(s, "x")
来源：http://dali.xinyue.icu/Article/details/gtfwstuzgc.html

Ruby: s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtwxoybsks.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtcxgpuava.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gtapqoadfx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.iojbl.cn/Article/details/gtvojqhtls.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtabugrwnc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gthvqrefmj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuetiantiany.cn/Article/details/gtkzzxkmkb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtvjbydbzw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.9152youxi.cn/Article/details/gtcpcjfrtq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.guowangkeji.top/Article/details/gtimduwmhr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtlefyzzdy.html

[E06] 替换子串
来源：http://dali.iojbl.cn/Article/details/gtdtninbkt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.wangdashe.top/Article/details/gtikvjpsag.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtvubluulp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfkuhqio.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtrjueahog.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtbjxjedmf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuanzx.com/Article/details/gtvfcisazs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtykfcpywz.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtfquelitk.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtkxcupnjl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtsqhrlauv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtuiezxygq.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigufen.top/Article/details/gtogmwgpon.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gthfqjlmij.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtnyttuyfv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pycfn.com/Article/details/gtzgaztxec.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtezciotdx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ydzc1.top/Article/details/gtfoigdebf.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtctqugakl.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gtdxnsxozt.html

PHP:  implode(",", $items);
来源：http://dali.xuanzx.com/Article/details/gtdyvzlqdw.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtcqrcretg.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtvqscywer.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtxfvvtjih.html

Go:   strings.Join(items, ",")
来源：http://dali.chenzaomai.com/Article/details/gtnoqkajpi.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gthcwcwqzt.html

C#:   string.Join(",", items)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcfcvowk.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtaizvldyv.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtejvcngnt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpxbwhkr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gttqilpczh.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gtvbxrmcot.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gthmqfhjxj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ppjwa.cn/Article/details/gtoemevmtj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtwytcauzp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtdeomdobr.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtchavahei.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtjcjrgbbw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zdqjudy.top/Article/details/gtcvpvxlqp.html

JS:   "7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtbenjfube.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtngrqyqym.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtuteezutr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gtwhrrvqvn.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtloydjphd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtdzgruave.html

[E11] 反转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphsxniqz.html

Py:   s[::-1]
来源：http://dali.cdnleiting.top/Article/details/gtvirtkqvq.html

PHP:  strrev($s);
来源：http://dali.meibo888.top/Article/details/gtbyeyuaei.html

JS:   [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gtfguqbwad.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtsmoryzqk.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.pycfn.com/Article/details/gtqxmvdjgc.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.snrcjt.cn/Article/details/gtlvgdimwy.html

Ruby: s.reverse
来源：http://dali.yuanzhike.top/Article/details/gtqcodxfee.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtwdhzhmpd.html

[E12] 统计某字符出现次数
来源：http://dali.fzhhl.top/Article/details/gtntdwavkl.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtbssnjvfr.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtiibjckkf.html

JS:   s.split("a").length - 1
来源：http://dali.yangfankeji.com/Article/details/gtqkfpijdm.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrlnjxgr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtqfjwywxe.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtqienmvqg.html

Ruby: s.count("a")
来源：http://dali.guowangkeji.top/Article/details/gtdsjcretg.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xylfe.cn/Article/details/gtygaprqmo.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtmvqyhzxh.html

Py:   for ch in s: print(ch)
来源：http://dali.yonumen.top/Article/details/gtwlptzfdy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhengqikj.top/Article/details/gtzgizhita.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.9152youxi.cn/Article/details/gtazsnceme.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtipmjviug.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gtxhsrtpsi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtamfkymjm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtlktbdvhq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtmqwvodkh.html

[E14] URL 编码与 Base64
来源：http://dali.xuetiantiany.cn/Article/details/gtehsjowxq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.havefunace.top/Article/details/gtunqphiaa.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jiagoushi.top/Article/details/gtgltdgigr.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtynyznrce.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtkmflgdxx.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtdxmwjioc.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hfpthk.cn/Article/details/gtneskxtxz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangshuangyany.cn/Article/details/gtubuxursc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tianlin.xyz/Article/details/gtsntcqlcc.html

[E15] HTML 转义 / 反转义
来源：http://dali.cdnleiting.top/Article/details/gtrrbtnhge.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cdnleiting.top/Article/details/gtkyopgfzt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gthrjyjxhm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtdcoriqtp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ivvv.top/Article/details/gtatmzklnr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gtrzzjqcja.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xuanzx.com/Article/details/gthlsmxwpq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jianghu66.top/Article/details/gtkpqfqhic.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtmeksvglp.html

[E16] 数字千分位
来源：http://dali.xylfe.cn/Article/details/gtrqpwnpyd.html

Py:   f"{1234567:,}"
来源：http://dali.ydzc1.top/Article/details/gtihevuowb.html

PHP:  number_format(1234567);
来源：http://dali.cucudq.cn/Article/details/gtjxuwajqm.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtghqfonri.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gttworhpyd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.andypj.xyz/Article/details/gtvjdjcsmx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.pycfn.com/Article/details/gtgorwixgm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gtylxqkjnh.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtatwgxvik.html

[E17] 首字母大写
来源：http://dali.hnxiangtu.top/Article/details/gtcjltpvom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hammf.cn/Article/details/gtfkxnsark.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gtctczkhfc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtlxorrwez.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtefmizdlq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtcaszuybp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.iojbl.cn/Article/details/gtgteegcjj.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrnxvjiv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.andypj.xyz/Article/details/gtqllbqrjb.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtnfmdifyu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.0kj1m.cn/Article/details/gtcmryvuqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtgvzppycd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtpyhrlcct.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtrplvdnde.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtijawcctw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrvkugue.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ehwqpu.com/Article/details/gtcvbebfgu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtrtcpmmzx.html

[E19] 多行文本按行拆分
来源：http://dali.cucudq.cn/Article/details/gthzfruvgm.html

Py:   s.splitlines()
来源：http://dali.tanke756.top/Article/details/gtmzlxnnmh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaykswfq.html

JS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtvzpwqpbw.html

TS:   s.split(/\r?\n/)
来源：http://dali.iojbl.cn/Article/details/gtupounyrw.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gthcfbyzru.html

Go:   strings.Split(s, "\n")
来源：http://dali.cheryme.top/Article/details/gtlnlvrzea.html

Ruby: s.lines
来源：http://dali.hnqzz.top/Article/details/gtivmupjug.html

C#:   s.Split('\n')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawfvldhe.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtmesmxsyk.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtihtigmxl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqrwfucv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhongyouzk.top/Article/details/gtqkrpccip.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbvkltnb.html

Java: if (s.isEmpty()) {}
来源：http://dali.ppjwa.cn/Article/details/gtzinjrypp.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gtvzqxtold.html

Ruby: if s.empty?
来源：http://dali.yongpay.top/Article/details/gtuyiakdsk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.snrcjt.cn/Article/details/gtlkwbbvbj.html

[E21] 超长截断加省略号
来源：http://dali.xinyue.icu/Article/details/gtzhbttuvu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.wangdashe.top/Article/details/gtyxttcrxu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtekgpfxjf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtaiictfhj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtpuvzkssn.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtvblwtjly.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sxryk.cn/Article/details/gtoonxaoru.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtshhaqtgo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtbtumjsmv.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtqckdbdst.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuxming.cn/Article/details/gtkcstfqpk.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.0kj1m.cn/Article/details/gtxcgtvhbd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtpyjjbzhw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtfytrfzny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.vqdsnc.cn/Article/details/gtloykcjfa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuanzhike.top/Article/details/gtbvpxplls.html

Ruby: s.bytesize;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtzqtqxkdg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtboyaflwk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtyyaiugcf.html

F. 文件与目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbppgffj.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtiaqbvthw.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtxikfjbrf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jiagoushi.top/Article/details/gthgyrtywd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtjvtlofsu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtmcnqqpqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtjeovvpxl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtjqpaillv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuetiantiany.cn/Article/details/gtkawtjvdw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtrnriwsjm.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gtqaqhphpk.html

[F02] 逐行读取文件
来源：http://dali.hongshengwenyu.top/Article/details/gteqefssau.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnqzz.top/Article/details/gtqeuyzsvu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtxzvfzyzh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtytasjynw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtyvbnyrhd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.kuanghao11.cn/Article/details/gtuhnbqvro.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zdqjudy.top/Article/details/gtczresopx.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.bjfxy.top/Article/details/gttdefuydq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenzaomai.com/Article/details/gtcfzzhutq.html

[F03] 写入文件（覆盖）
来源：http://dali.ivvv.top/Article/details/gthvpvstio.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gtudvjhyif.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtinspheyl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqqthcnb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gttdfddpmt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gtuzehmnud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtwvwseesu.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtdmazlkln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtgpxzgash.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtwtksqkgp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiwocoth.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ppjwa.cn/Article/details/gtalpnekep.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sxryk.cn/Article/details/gtgzaepesd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tanke756.top/Article/details/gtnqfekpjh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtgcmcgjym.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gtlcnihedx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gtnlooxapn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zdqjudy.top/Article/details/gtzqotbqcr.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuanzhike.top/Article/details/gthfgzxyus.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtoccewptr.html

PHP:  file_exists("a.txt");
来源：http://dali.tanke756.top/Article/details/gthlejwopj.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvukuzesb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvzjeuurj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.wangshuangyany.cn/Article/details/gtrmifefha.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuxming.cn/Article/details/gttbmkvych.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtshpatjak.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtdvxdrcvv.html

[F06] 删除文件
来源：http://dali.daria6918.cn/Article/details/gtfrafemif.html

Py:   os.remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtxrdzeexs.html

PHP:  unlink("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtvvoqdwyr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtseookmok.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtyraqmrju.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtblosxiao.html

Go:   os.Remove("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gterjahqnp.html

Ruby: File.delete("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtzggehpwk.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrytghvtr.html

[F07] 创建目录（含多级）
来源：http://dali.pycfn.com/Article/details/gthmfzntqp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ydzc1.top/Article/details/gtlegjplpl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtgrquwklb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtsasuzqto.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xuetiantiany.cn/Article/details/gtnqqlsihk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtpummbtzm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.feifeiyinyue.top/Article/details/gtwdjetsoq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.ydzc1.top/Article/details/gtcmjexzpm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zycfv.cn/Article/details/gtmvhgpusm.html

[F08] 遍历目录
来源：http://dali.nwbrower.top/Article/details/gttrporxck.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhengqikj.top/Article/details/gtlzzgyjzn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gotoacloud.top/Article/details/gtyskceagn.html

JS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gtowswatxf.html

TS:   fs.readdirSync("dir")
来源：http://dali.ehwqpu.com/Article/details/gtdmaibaku.html


<!-- 参考信息 -->