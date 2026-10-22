代发 wailian999

[D23] reduce 累积计算
来源：http://dali.birdmap.top/Article/details/gtauygpmih.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtrqyiiznn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fzhhl.top/Article/details/gtwhbbiplb.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cheryme.top/Article/details/gtvebztbnb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtotafxoen.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtpvnbfeze.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtlugbyjxt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daxiang520.top/Article/details/gtsyhpvcvh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.redwolf501.top/Article/details/gtahluwnzh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtrljeqkbs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtucqwntlu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgfzy.top/Article/details/gtuudeotfv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.haohaochexian.top/Article/details/gtecepyxof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sxryk.cn/Article/details/gtgacymskz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtyxbdnelo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbtcxzyf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gtsdkoebay.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.pycfn.com/Article/details/gtcdjafpvx.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangkeji.top/Article/details/gtekzomcex.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zycfv.cn/Article/details/gtwgzbflwm.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenlongwang.top/Article/details/gtckiqfoil.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhengqikj.top/Article/details/gtwaekhplh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.aizwys.cn/Article/details/gtrwbjkpnm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gzhubu.top/Article/details/gtdayznkji.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daxiang520.top/Article/details/gtqerpdsbq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gteaqqucsn.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gthxerpsuc.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtstyzbswi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtxdqcswxv.html

PHP:  implode(", ", $arr);
来源：http://dali.cucudq.cn/Article/details/gtoymvypwd.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtfwveaczo.html

TS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtczhgmtgf.html

Java: String.join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtipjvvbsh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.gogol.net.cn/Article/details/gtcqqjnsyz.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gtxsevgztj.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gtgdgfrric.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcucycajh.html

E. 字符串处理
来源：http://dali.smart0.xyz/Article/details/gtorszoxmo.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtupwduubd.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gtnuprcmio.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sysykeji.top/Article/details/gtodhumfxy.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangdashe.top/Article/details/gtugqgttup.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.bjfxy.top/Article/details/gtdsvnbtnp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjdiywryv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.iojbl.cn/Article/details/gtyjjljiag.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xziqi.cn/Article/details/gtowvvnjng.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jlsjyb.cn/Article/details/gtuifgzlow.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtaheyocem.html

[E02] 重复字符串
来源：http://dali.xziqi.cn/Article/details/gtdbvcwfzu.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gthiuckavb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfwmavks.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtnxdmpwrm.html

TS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gtygpoxpgb.html

Java: "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtqvrkylki.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gteholafen.html

Ruby: "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtaetvibor.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shuidangran.top/Article/details/gtmubbcdjs.html

[E03] 截取子串
来源：http://dali.zhongyouzk.top/Article/details/gtrnxbcjdn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gtqlrzmkov.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtzqtnaerq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gtcoqvvvij.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258888.top/Article/details/gtkhgxouyx.html

Java: s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtbflrwdch.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtuvkpxueb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.guowangkeji.top/Article/details/gtreraewdh.html

C#:   s.Substring(1, 3)
来源：http://dali.ppjwa.cn/Article/details/gtephpldqj.html

[E04] 查找子串位置
来源：http://dali.dianchejie.cn/Article/details/gthrqvttyc.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtdwcsagyi.html

PHP:  strpos($s, "x");
来源：http://dali.ppjwa.cn/Article/details/gtkvebsrzg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hywenlv.cn/Article/details/gtnrkkbfry.html

TS:   s.indexOf("x")
来源：http://dali.tianlin.xyz/Article/details/gtjabhwuys.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtsegxaytv.html

Go:   strings.Index(s, "x")
来源：http://dali.hywenlv.cn/Article/details/gtyuanxsuy.html

Ruby: s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gtdfxrknxg.html

C#:   s.IndexOf("x")
来源：http://dali.havefunace.top/Article/details/gtsefxeteu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtkwdtdkbj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zycfv.cn/Article/details/gtiajkeqdd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.chenlongwang.top/Article/details/gtfaarhjee.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtclqqyhlz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ppjwa.cn/Article/details/gtcpgxlvty.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj202588.top/Article/details/gtnsxshuxd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yuxming.cn/Article/details/gtnszsezhn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gtaeafljln.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sweek.top/Article/details/gtopvxjbgu.html

[E06] 替换子串
来源：http://dali.sxryk.cn/Article/details/gtwcqzbsoy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gthkjmmzpm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pycfn.com/Article/details/gtgmzezqqd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtkbosjshd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtxwrmiafh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtxnfqucsi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtikfzyhgl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.c1oappe.top/Article/details/gtxowoskdw.html

C#:   s.Replace("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcxbtggr.html

[E07] 按分隔符拆分
来源：http://dali.bjfxy.top/Article/details/gtecqugmbk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yvedp.cn/Article/details/gthzhynkkm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.smart0.xyz/Article/details/gtjiamhqso.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtkutphbgi.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtgoxtpeuf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtsuqbwyob.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.0kj1m.cn/Article/details/gtbnnoafjl.html

Ruby: s.split(",");  s.split
来源：http://dali.jyoumei.cn/Article/details/gtvlefoptp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.c1oappe.top/Article/details/gttuhyfggg.html

[E08] 数组按分隔符合并
来源：http://dali.gzhubu.top/Article/details/gtrjrwphob.html

Py:   ",".join(items)
来源：http://dali.cashguo.top/Article/details/gtkczgnqjy.html

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtvlfdcgil.html

JS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtayuiyypt.html

TS:   items.join(",")
来源：http://dali.yongpay.top/Article/details/gtcigakpor.html

Java: String.join(",", items)
来源：http://dali.shuidangran.top/Article/details/gtfcgfhwyx.html

Go:   strings.Join(items, ",")
来源：http://dali.cheryme.top/Article/details/gthlihqwfc.html

Ruby: items.join(",")
来源：http://dali.cqqwz.cn/Article/details/gtogyjaihi.html

C#:   string.Join(",", items)
来源：http://dali.pycfn.com/Article/details/gtcjbrzfxx.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtwdlskjdk.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guannengcc.top/Article/details/gtycsaygfk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtvqygxyhg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ybcxt.top/Article/details/gtdxnbsbps.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtxzxncdpx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj20258888.top/Article/details/gtrklhoauf.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtpqgovopj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gtvrcjrysu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtefnmjnnd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtiovbkxqk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtdjiigerk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gtdcygocgp.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gtynokivze.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtkxtrzsoe.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcmsogjk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hywenlv.cn/Article/details/gtyoasofvs.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.wangshuangyany.cn/Article/details/gtdraejjre.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jqgfzy.top/Article/details/gtvjorbiye.html

[E11] 反转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtsehgxwrg.html

Py:   s[::-1]
来源：http://dali.ivvv.top/Article/details/gtmaduffku.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gthdbztyhf.html

JS:   [...s].reverse().join("")
来源：http://dali.guannengcc.top/Article/details/gtzanrkspg.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtavedopce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtzjhdomlf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtplnkodfx.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtqnbasqus.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tanke756.top/Article/details/gtrxczokrp.html

[E12] 统计某字符出现次数
来源：http://dali.tanke756.top/Article/details/gtcahxyqcd.html

Py:   s.count("a")
来源：http://dali.xinyue.icu/Article/details/gtdusufaov.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcjbqaeb.html

JS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gttzxgkifl.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtmjljnqbd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yvedp.cn/Article/details/gtfnmjzpum.html

Go:   strings.Count(s, "a")
来源：http://dali.yonumen.top/Article/details/gtrbrjrzja.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtyiitbczv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xziqi.cn/Article/details/gtyvgbtamk.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtihnwpjoz.html

Py:   for ch in s: print(ch)
来源：http://dali.smart0.xyz/Article/details/gtgqtrcyvo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gtldmvbgyz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gtsmqaxeco.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtknfdlmaf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtfouefzga.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtxbrhrfkh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtkaemlyjr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtkqpkvvrq.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gtvpwxplin.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtpeoclfni.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gtrmrlslnu.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tian-w.cn/Article/details/gtmezfybtj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtyqlnscju.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gzhubu.top/Article/details/gtkywplbbx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhijiandao.cn/Article/details/gtmwitwbud.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtiwsjosup.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cashguo.top/Article/details/gttdwcalvg.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtihttorjo.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xziqi.cn/Article/details/gtyyimznnm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtpxpqcous.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtquqjhbmd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenzaomai.com/Article/details/gtszxoewpw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuetiantiany.cn/Article/details/gtiuhfnhlv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daria6918.cn/Article/details/gtycrabqfh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.svipenyu.cn/Article/details/gtwttobkgf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtvrximary.html

[E16] 数字千分位
来源：http://dali.ehwqpu.com/Article/details/gtskvxijuy.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gttixousyt.html

PHP:  number_format(1234567);
来源：http://dali.birdmap.top/Article/details/gtaggxkgoh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gtgokcsjbb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gtwfazxjil.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.vqdsnc.cn/Article/details/gtgyxmwigd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cheryme.top/Article/details/gtgbsskksv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gtiznlqidc.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxuanxn.top/Article/details/gttgvfrypy.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gteiuhphvu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtenfbjcgo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cashguo.top/Article/details/gtrdjdmyiu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gtfdmteeqs.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtozlzfwyy.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttrkrsuqf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.dashuyun.cn/Article/details/gtnhltntfi.html

Ruby: s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtrikwuofc.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.havefunace.top/Article/details/gtfffjqsid.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtjagghvjc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gogol.net.cn/Article/details/gtpscksdco.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtqdrtevea.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtdwxascpk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gthlvlffjr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiiawrpq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtnvovalcs.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yonumen.top/Article/details/gtydksjoxw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.fzhhl.top/Article/details/gtxinnlkqh.html

[E19] 多行文本按行拆分
来源：http://dali.tianlin.xyz/Article/details/gtzloyldph.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtkbsiiacu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.dashuyun.cn/Article/details/gtgnyvgxcd.html

JS:   s.split(/\r?\n/)
来源：http://dali.haohaochexian.top/Article/details/gteibigwuq.html

TS:   s.split(/\r?\n/)
来源：http://dali.sxryk.cn/Article/details/gtnokcpwhq.html

Java: s.lines().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtfyuuwttt.html

Go:   strings.Split(s, "\n")
来源：http://dali.mhx1999.top/Article/details/gtcymhmxwl.html

Ruby: s.lines
来源：http://dali.shuidangran.top/Article/details/gtlqvknokk.html

C#:   s.Split('\n')
来源：http://dali.guannengcc.top/Article/details/gtndnrtsrm.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gttiibsxog.html

Py:   if not s:
来源：http://dali.yangfankeji.com/Article/details/gtdhqukzrr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.haohaochexian.top/Article/details/gtwbopfezr.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigufen.top/Article/details/gtvrrihwmx.html

TS:   if (s === "") {}
来源：http://dali.shzxlz.cn/Article/details/gtvhowrmni.html

Java: if (s.isEmpty()) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtuwjclp.html

Go:   if s == "" {}
来源：http://dali.pycfn.com/Article/details/gtfkienlbq.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gtohtfutuk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinqigfzy.top/Article/details/gtrrbfrzhc.html

[E21] 超长截断加省略号
来源：http://dali.hongshengwenyu.top/Article/details/gtshryrhdh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtalblzsse.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hysaishi.cn/Article/details/gtiaaksjej.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yanxiufei.cn/Article/details/gtejjjpugf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yj202588.top/Article/details/gtmdtrmimx.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtqdzvellf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtzinwnyfj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtstvhwxqj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtkbsndkby.html

[E22] 字节长度与字符长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchmstndw.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrasdesvl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtdaatbjfd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtpgoocwti.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtbyphmqkh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedoinpsc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gtvxgvzfcw.html

Ruby: s.bytesize;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrfltdzf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.cqqwz.cn/Article/details/gtwtccjbbd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtcilacaps.html

F. 文件与目录
来源：http://dali.dashuyun.cn/Article/details/gtomehqepo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjpvyqgqa.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtlxynxegn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtjfejrurg.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtecqhlcnt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gtqkuiocxu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gthklghlbo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gtvdbvmcas.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfkpromd.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtugvjdpem.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.nanxuanxn.top/Article/details/gthlcgcuda.html

[F02] 逐行读取文件
来源：http://dali.snrcjt.cn/Article/details/gtabocpkyx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtgkrbdpoj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtecpupuyz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtjdugbctg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtmmxjthrx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hysaishi.cn/Article/details/gtsmmagusf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.nanxuanxn.top/Article/details/gtcqackxfr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hammf.cn/Article/details/gtamdzypkr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.chenlongwang.top/Article/details/gtybqwkuyj.html

[F03] 写入文件（覆盖）
来源：http://dali.gzhubu.top/Article/details/gtvqpcutuu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shuidangran.top/Article/details/gtsjtatnoe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.9152youxi.cn/Article/details/gtbmzktwto.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gttavcjzpg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtrpibbfyr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tian-w.cn/Article/details/gtkoxmrimf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hnxiangtu.top/Article/details/gtpyfrjfqc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtsycfkaag.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yj202588.top/Article/details/gtsyhtvlhu.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtbuazpclm.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtfzokkwtv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ybcxt.top/Article/details/gtxwpdnqok.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gtuviwklcm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtjumkarrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hnxiangtu.top/Article/details/gtautosunz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtabanaybd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgufenzy.top/Article/details/gtqkmdcxul.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sweek.top/Article/details/gttvkqiycc.html

[F05] 判断文件或目录是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtyyzougdd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtaccpacdi.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtcftxduuc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbbvahlk.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtceggjkpo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gtewgxgiwg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yonumen.top/Article/details/gtqcdknixk.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrgcirij.html

C#:   File.Exists("a.txt")
来源：http://dali.cashguo.top/Article/details/gtiozhhwxw.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtussnvmvf.html

Py:   os.remove("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtbyitnkub.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtppsrfkbw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gthdzqsmgc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtdfqokcep.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hfpthk.cn/Article/details/gthtpbbaje.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjltwykbr.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfauasvia.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtijvddsot.html

[F07] 创建目录（含多级）
来源：http://dali.gaohongyu789.top/Article/details/gtufygkmqv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gtalogbwdh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sysykeji.top/Article/details/gtdolxahyj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gtajucphku.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtqbadeqci.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.quarkkingdee.top/Article/details/gtyhtsfztb.html


<!-- 参考信息 -->