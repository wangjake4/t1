代发 wailian999

[D23] reduce 累积计算
来源：http://dali.hammf.cn/Article/details/gtkuefovme.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtljqksrlp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yj202588.top/Article/details/gtxyiusokh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtcxmkrrxs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.havefunace.top/Article/details/gtsadjmmal.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtefflurfm.html

Go:   // 手写循环
来源：http://dali.smart0.xyz/Article/details/gtxhvztjvn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.bjfxy.top/Article/details/gtcyfzzwld.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jiagoushi.top/Article/details/gttfeydhbu.html

[D24] 字典 / Map 基本操作
来源：http://dali.shangyingyoupin.top/Article/details/gtonnxunvi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtobzqdaud.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jqgufenzy.top/Article/details/gtphcxypia.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.birdmap.top/Article/details/gtovnndzxl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtjuklbdvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ydzc1.top/Article/details/gtazvfquzp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtavreplbg.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtclituxcn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhengqikj.top/Article/details/gtqnkkivay.html

[D25] Set 集合去重与交并差
来源：http://dali.iojbl.cn/Article/details/gtfeubmnfi.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtdtupfxrf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenzaomai.com/Article/details/gtllnpdoaj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtpljpfyzo.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtrbmdnrqj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.haohaochexian.top/Article/details/gtgnpilpjg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gtxdibkbsa.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gthlkfdder.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hfpthk.cn/Article/details/gtgvbteixr.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gtjroayegf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jinqigufen.top/Article/details/gthxwtpgaw.html

PHP:  implode(", ", $arr);
来源：http://dali.andypj.xyz/Article/details/gtyceykici.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gtgnwzgxds.html

TS:   arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtahbfjrqt.html

Java: String.join(", ", list)
来源：http://dali.guowangkeji.top/Article/details/gtfzkprqyu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuxming.cn/Article/details/gtncliqvip.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtinczzppx.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtlttmllws.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtoylhksjk.html

E. 字符串处理
来源：http://dali.guowangkeji.top/Article/details/gtobwengon.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtbfnwwuuu.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtwxufybtj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.birdmap.top/Article/details/gtwlmezpjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtfrloxlkt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtfdmzgtjd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtznqwchfk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtsfmnkukb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gtplwucgjv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtpzauemez.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtekjpryxp.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gtptwbtppy.html

Py:   "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtatecqszl.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gzhubu.top/Article/details/gtszdgstgi.html

JS:   "ab".repeat(3)
来源：http://dali.yangfankeji.com/Article/details/gtqlvirqui.html

TS:   "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtqpnygubn.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtupktafhb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtgcdestyl.html

Ruby: "ab" * 3
来源：http://dali.chenzaomai.com/Article/details/gtkxovdqno.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cqqwz.cn/Article/details/gtcyzwyvzg.html

[E03] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtibfynboy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yueranfly.top/Article/details/gthkmhgaxk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.vqdsnc.cn/Article/details/gtlshmzhil.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtqymenqed.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtuptqwfad.html

Java: s.substring(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtesgufgfk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cucudq.cn/Article/details/gtbujqrduu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dianchejie.cn/Article/details/gteaspzmxa.html

C#:   s.Substring(1, 3)
来源：http://dali.yanxiufei.cn/Article/details/gtklfclzxh.html

[E04] 查找子串位置
来源：http://dali.hnqzz.top/Article/details/gthsugbajx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cdnleiting.top/Article/details/gtjupmqvcf.html

PHP:  strpos($s, "x");
来源：http://dali.snrcjt.cn/Article/details/gtrmaacapq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtknggbwnx.html

TS:   s.indexOf("x")
来源：http://dali.yongpay.top/Article/details/gtthdvlvbc.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtyrpzsssg.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gtgtttkhhs.html

Ruby: s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtuvbzrgrs.html

C#:   s.IndexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtykyyipcs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtszqmjaoz.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hammf.cn/Article/details/gtrrwazgvk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgufenzy.top/Article/details/gtpjjohfct.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nanxinkj.top/Article/details/gttfirtrut.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.havefunace.top/Article/details/gtxuroqvbu.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtemwqjdvo.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhiwuduotai.top/Article/details/gthbebgdjy.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.haohaochexian.top/Article/details/gtpasbuoow.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fengsongda.top/Article/details/gthekimfaz.html

[E06] 替换子串
来源：http://dali.nanxuanxn.top/Article/details/gtyjavfwao.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jiagoushi.top/Article/details/gtlwxpwtzl.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shzxlz.cn/Article/details/gtrehsnhxx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgibyovge.html

TS:   s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtgonbgzyt.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisamupla.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtnvyddhhn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gteycctvye.html

C#:   s.Replace("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtknhoptdv.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gttbntktxx.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtagxpuynj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtyvosjzth.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hysaishi.cn/Article/details/gtgrtuqnfv.html

TS:   s.split(",")
来源：http://dali.aibaodan.cn/Article/details/gtghczczbp.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.sysykeji.top/Article/details/gtdyymieps.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gtdqayfzuw.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtihlvsnbv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cdnleiting.top/Article/details/gtfbszsavb.html

[E08] 数组按分隔符合并
来源：http://dali.aizwys.cn/Article/details/gttfneptcn.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gtzzfnijir.html

PHP:  implode(",", $items);
来源：http://dali.redwolf501.top/Article/details/gtuqjevlme.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gteqkaxleg.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtzcqgexsz.html

Java: String.join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtzunivitk.html

Go:   strings.Join(items, ",")
来源：http://dali.meibo888.top/Article/details/gtlgknmzaf.html

Ruby: items.join(",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyartyhfm.html

C#:   string.Join(",", items)
来源：http://dali.snrcjt.cn/Article/details/gtxbzoaqrp.html

[E09] 去除所有空白字符
来源：http://dali.ehwqpu.com/Article/details/gtiihmizel.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yuanzhike.top/Article/details/gterqwbqwx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtardgindy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cheryme.top/Article/details/gtxosssdlu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtvpadubvy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmjewtoj.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cdnleiting.top/Article/details/gtpnnccuic.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gtdzyamnjp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtnjmkapct.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shangyingyoupin.top/Article/details/gtfznvczoo.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtlhelmwno.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxuanxn.top/Article/details/gtmxwlydry.html

JS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtqzjdmucr.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtwehkjhrx.html

Java: String.format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtphltjtmn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gthijfkpaa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yueranfly.top/Article/details/gtaqptzlix.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhixingplan.top/Article/details/gtzltanrdh.html

[E11] 反转字符串
来源：http://dali.pycfn.com/Article/details/gtuxpahlpy.html

Py:   s[::-1]
来源：http://dali.andypj.xyz/Article/details/gtumtoiubo.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtznfpukwi.html

JS:   [...s].reverse().join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtvpiabudj.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtezwkttiu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gtdbrrpeii.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.bjfxy.top/Article/details/gtxeilapyf.html

Ruby: s.reverse
来源：http://dali.fzhhl.top/Article/details/gtauhdukky.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtyrhoyumq.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtvydjuinf.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtulcchjbc.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtyzkicbxb.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gttonfnssm.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtapvkrmzd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ehwqpu.com/Article/details/gtehfwgdtn.html

Go:   strings.Count(s, "a")
来源：http://dali.yongpay.top/Article/details/gtqzeetahk.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtmczidluq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangshuangyany.cn/Article/details/gtutcnmkrd.html

[E13] 逐字符遍历
来源：http://dali.wangdashe.top/Article/details/gtlgiaraqs.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gthwkltulq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.iojbl.cn/Article/details/gtdkgvegry.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258888.top/Article/details/gttdllllzq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtgtwlobde.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtqvkosjtp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.mhx1999.top/Article/details/gthgzmpvkt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtkgwykxsz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtlzdqhvsv.html

[E14] URL 编码与 Base64
来源：http://dali.chenjidiqi.icu/Article/details/gtoxfvvkmo.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.316326.xyz/Article/details/gtfbnoxixx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtusowsnfl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuxming.cn/Article/details/gtucijbeoj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtngxoxacm.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtaqnyyjno.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gtwigbcqae.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.ybcxt.top/Article/details/gtxewctrau.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtuhpuwand.html

[E15] HTML 转义 / 反转义
来源：http://dali.cashguo.top/Article/details/gtwdpgfbiv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.9152youxi.cn/Article/details/gtkwejuuui.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gthnvpjhfw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ehwqpu.com/Article/details/gtzxmdikoy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtyevtjses.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtttiaihhd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.svipenyu.cn/Article/details/gttgjmkpll.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.tian-w.cn/Article/details/gtdgevphza.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtfowxoept.html

[E16] 数字千分位
来源：http://dali.9152youxi.cn/Article/details/gthsmvrpci.html

Py:   f"{1234567:,}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxrzmdhj.html

PHP:  number_format(1234567);
来源：http://dali.zhiwuduotai.top/Article/details/gtxfqheiaa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtolvfylos.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtflahwznq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.wangdashe.top/Article/details/gtmokiybim.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtnsjnwccg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtsuhrczgr.html

C#:   1234567.ToString("N0")
来源：http://dali.guannengcc.top/Article/details/gtquasxtup.html

[E17] 首字母大写
来源：http://dali.daxiang520.top/Article/details/gtgxahwhfx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtonmjmhxb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterotrged.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtfczrcbms.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtuqukpalt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhoulong.xyz/Article/details/gtebhhbhls.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cucudq.cn/Article/details/gtmsjxsivb.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gtkprpycuk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ppjwa.cn/Article/details/gtamlttkin.html

[E18] 模板占位符替换
来源：http://dali.tianlin.xyz/Article/details/gtedpphhye.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gtyakbaygs.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkvynigy.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guannengcc.top/Article/details/gtidmesctb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtlhnqbqcv.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtycsbhdmh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtdzriaafk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ybcxt.top/Article/details/gtbspzuimu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pycfn.com/Article/details/gtltrozasb.html

[E19] 多行文本按行拆分
来源：http://dali.daria6918.cn/Article/details/gteqghmerf.html

Py:   s.splitlines()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkgovoax.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.iojbl.cn/Article/details/gtqsqymwdx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtrszshvnx.html

TS:   s.split(/\r?\n/)
来源：http://dali.yanxiufei.cn/Article/details/gtvffeetdu.html

Java: s.lines().toList()
来源：http://dali.zycfv.cn/Article/details/gtozolqfrt.html

Go:   strings.Split(s, "\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpmrtkmwe.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtlyqbgrqt.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gtfireyfhm.html

[E20] 判断字符串是否为空
来源：http://dali.tanke756.top/Article/details/gtifthsvvb.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gtfacopouu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtxawtdaxt.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gtjuhdjqin.html

TS:   if (s === "") {}
来源：http://dali.wangdashe.top/Article/details/gtuqmyyavk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwmzwwtfc.html

Go:   if s == "" {}
来源：http://dali.jlsjyb.cn/Article/details/gtpfvrjjgc.html

Ruby: if s.empty?
来源：http://dali.yj20258.top/Article/details/gtaunelvve.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtkkiatndp.html

[E21] 超长截断加省略号
来源：http://dali.wangdashe.top/Article/details/gtbyffogvk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.316326.xyz/Article/details/gthgytgcyf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtyhaphliz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gtqqasmncg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtkmfqweqt.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtcmsjlswo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hfpthk.cn/Article/details/gtfswuvymv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gtxigbaqip.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtnsqvjjad.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtkdijvufq.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gthprtabne.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gtidqyeend.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhongyouzk.top/Article/details/gtcfnlvfzv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tian-w.cn/Article/details/gtykyaiyah.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sysykeji.top/Article/details/gtxoqhcskm.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cqqwz.cn/Article/details/gtibgquhke.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtajftvawu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtnvkrvgca.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatkmjbgi.html

F. 文件与目录
来源：http://dali.zhijiandao.cn/Article/details/gtnrzxgxft.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtdioimqjc.html

[F01] 读取整个文件
来源：http://dali.redwolf501.top/Article/details/gtgjzternx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ivvv.top/Article/details/gtcfhnuhhw.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqqwsjjhi.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuxming.cn/Article/details/gtjzuysimy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtxjbnxkcy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtfscrccqv.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gtutxepcat.html

Ruby: File.read("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtgdsmebew.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtppiykdqi.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtzgsodpuq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhengqikj.top/Article/details/gtvjnufsbd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqxgyvnxo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtzumplvmg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxufdrje.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.havefunace.top/Article/details/gtrwbrdgaa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.daria6918.cn/Article/details/gtftmfqbhe.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ydzc1.top/Article/details/gtmakspesb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtyzwqsspl.html

[F03] 写入文件（覆盖）
来源：http://dali.jyoumei.cn/Article/details/gtfzixllou.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.redwolf501.top/Article/details/gttxicpazm.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuanzhike.top/Article/details/gttpsokqhg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hongshengwenyu.top/Article/details/gtcqxkrfqg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gtsiieigpy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yonumen.top/Article/details/gtgwdcddom.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gtftvqnoyk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadtopooz.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gttyuyohbz.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgpisfpti.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtvgkfsewt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtgifrehwq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gtlunvygwz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.nwbrower.top/Article/details/gtdvmgtprd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.bjfxy.top/Article/details/gtnkgfvgmc.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.bjfxy.top/Article/details/gttlmmhbit.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jqgfzy.top/Article/details/gtguxpkfhd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.guowangkeji.top/Article/details/gtqerkjezk.html

[F05] 判断文件或目录是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtfwfwnqrd.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.vqdsnc.cn/Article/details/gttzlytdpe.html

PHP:  file_exists("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtksqhdmpe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtmhgieucm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gthjphvtha.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gtxoppvioy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtsokkcmrl.html

Ruby: File.exist?("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtauhczlhs.html

C#:   File.Exists("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gthuegfvdb.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gthmoeopzu.html

Py:   os.remove("a.txt")
来源：http://dali.yj20258.top/Article/details/gtghvbarye.html

PHP:  unlink("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtqvtrrjlx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gttsecossr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdejuzitv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtquhclynt.html

Go:   os.Remove("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcsyobpyu.html

Ruby: File.delete("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtxqbrlezn.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtwmalzlfb.html

[F07] 创建目录（含多级）
来源：http://dali.shangyingyoupin.top/Article/details/gtefokevwq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gtwubyuzgw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gtdcsgwyfq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gzhubu.top/Article/details/gtrpecovzu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.birdmap.top/Article/details/gtezjdclnl.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtqiorbyre.html


<!-- 参考信息 -->