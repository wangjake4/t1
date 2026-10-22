代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gtoylkimir.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yangfankeji.com/Article/details/gtuumtbpri.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtxnykvvel.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ppjwa.cn/Article/details/gtfoaulvnk.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnwiszcb.html

[D24] 字典 / Map 基本操作
来源：http://dali.andypj.xyz/Article/details/gtgnthrwwt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.xuetiantiany.cn/Article/details/gtdeymywbj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yj20258888.top/Article/details/gtsfqlsaql.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.meibo888.top/Article/details/gtaogtrlus.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gthuyzoqid.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.havefunace.top/Article/details/gtcoyhzegy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jlsjyb.cn/Article/details/gtrfgnmofe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xinyue.icu/Article/details/gtomyftkgn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yj202588.top/Article/details/gtfgvmnwre.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtclgmuass.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hnqzz.top/Article/details/gthoapdnwu.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gtgsdhyodm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtoismfcbv.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.gotoacloud.top/Article/details/gtpxnxdpzn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gtqfxleeow.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ybcxt.top/Article/details/gtnorchigw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxinkj.top/Article/details/gthhnctclu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtnpcahmua.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gtxwhfdvvb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtbnpkvjtq.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtcduprryf.html

JS:   arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtbhwpiyjj.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtaywrmzda.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtepxubnic.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtykfyanzu.html

Ruby: arr.join(", ")
来源：http://dali.hammf.cn/Article/details/gtfxdnnocq.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gtmqezogml.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtkltgwjpw.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gtbjfayisn.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtucmvcqnr.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gtlmkdtfsz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhijiandao.cn/Article/details/gtiopugxzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtkyvynbqz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrgddyxs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.smart0.xyz/Article/details/gtamsimkci.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cucudq.cn/Article/details/gthmpqieru.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.dashuyun.cn/Article/details/gtshnynyxa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sxryk.cn/Article/details/gtpdiwtjcw.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtpqdzshsi.html

[E02] 重复字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpknrrfh.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacxmsfij.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtlijogmzx.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtyejmknhc.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtslpiwpkm.html

Java: "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtjkmikrad.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.birdmap.top/Article/details/gtxdjtdxvz.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtfalghspq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtfxmziumv.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtgipsqjyi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtxejthoqd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtohfmlpvd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtzexfafdw.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtbhnzhenm.html

Java: s.substring(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtgbvebccq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtyzahhply.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtgoasxpzy.html

C#:   s.Substring(1, 3)
来源：http://dali.guowangkeji.top/Article/details/gtiaffjvpr.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtroxgomdu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtfvpozzvo.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmddlgbas.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.redwolf501.top/Article/details/gtjqvhsoih.html

TS:   s.indexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtrcovmwsi.html

Java: s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtetpoduhz.html

Go:   strings.Index(s, "x")
来源：http://dali.gotoacloud.top/Article/details/gtrcyyhpbw.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtxqjopnxp.html

C#:   s.IndexOf("x")
来源：http://dali.jinqigufen.top/Article/details/gtslomckql.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gtphwnmldf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jyoumei.cn/Article/details/gtfxlbbzzv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dashuyun.cn/Article/details/gtxzdxqnjo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtvaryfune.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yvedp.cn/Article/details/gtbglwvzvy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtmnnlvrsv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hfpthk.cn/Article/details/gteyifoaub.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtzhvrptga.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhheelik.html

[E06] 替换子串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoldomdus.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gtfzsbewys.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtdwwsogme.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtalzulomd.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqjgywdu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtzkpjfrtw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtkwnmzjhg.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtkejeubsd.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtcduxoubi.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvvoidxh.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.chenjidiqi.icu/Article/details/gtdyyjinau.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.daria6918.cn/Article/details/gtjkamlnui.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shangyingyoupin.top/Article/details/gtrbqglpkg.html

TS:   s.split(",")
来源：http://dali.jianghu66.top/Article/details/gtouvdjcxm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ydzc1.top/Article/details/gtovvpnnvc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnhdtlym.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtzhaydeac.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hfpthk.cn/Article/details/gtqnxdtqdd.html

[E08] 数组按分隔符合并
来源：http://dali.tianlin.xyz/Article/details/gtclbmjccb.html

Py:   ",".join(items)
来源：http://dali.0kj1m.cn/Article/details/gtiudurvqo.html

PHP:  implode(",", $items);
来源：http://dali.ppjwa.cn/Article/details/gtovmhzunb.html

JS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtxlojzbbk.html

TS:   items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtkcmlvshw.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwffkwka.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmakxitoa.html

Ruby: items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtxjulolak.html

C#:   string.Join(",", items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkkvrpzbs.html

[E09] 去除所有空白字符
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvvcstel.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yj20258.top/Article/details/gtskdlsfwk.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.guannengcc.top/Article/details/gtfttxtcmg.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtvwsideyk.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gtouizdxur.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtblfscqoz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jyoumei.cn/Article/details/gtrsirokfs.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhengqikj.top/Article/details/gtonlwgdlj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtfjcdjgec.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinqigufen.top/Article/details/gtylihtpym.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtzeaouwzc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shangyingyoupin.top/Article/details/gtvebfdxuv.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtialuaxxh.html

TS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtngpwyycs.html

Java: String.format("%03d", 7)
来源：http://dali.sysykeji.top/Article/details/gtiwhzmkhx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtmwxapdjt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtzkfxis.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shuidangran.top/Article/details/gtreqqmweb.html

[E11] 反转字符串
来源：http://dali.gzhubu.top/Article/details/gtncccjems.html

Py:   s[::-1]
来源：http://dali.hfpthk.cn/Article/details/gtcvtlnvgv.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtloezirdw.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnbynttu.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtagylzjlo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gturdelvga.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtujxcswpf.html

Ruby: s.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtyowthvtj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtncjnhuxf.html

[E12] 统计某字符出现次数
来源：http://dali.birdmap.top/Article/details/gtszkocltt.html

Py:   s.count("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtciugggdy.html

PHP:  substr_count($s, "a");
来源：http://dali.ybcxt.top/Article/details/gtphjiswpr.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpswnvsz.html

TS:   s.split("a").length - 1
来源：http://dali.xuanzx.com/Article/details/gtzwdansmr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhongyouzk.top/Article/details/gtajbxljkc.html

Go:   strings.Count(s, "a")
来源：http://dali.iojbl.cn/Article/details/gtlnypdbkb.html

Ruby: s.count("a")
来源：http://dali.zycfv.cn/Article/details/gtygnzlyrd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtahxyypmv.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtmddtndsw.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxnmuwtf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yongpay.top/Article/details/gtcwxykzwl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gthqsslzxe.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtlppttjza.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.bjfxy.top/Article/details/gtkdllaqaw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guowangkeji.top/Article/details/gtuzabejwd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jianghu66.top/Article/details/gtnrymwjvc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nwbrower.top/Article/details/gtriintued.html

[E14] URL 编码与 Base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatkqpehg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtwowbwecn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtjjxmegvc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtvotxugij.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xuanzx.com/Article/details/gtqktxdynv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgfzy.top/Article/details/gtomvwusgw.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.tianlin.xyz/Article/details/gtqobhgkjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuanzhike.top/Article/details/gthxqtkdix.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtsbekmuwe.html

[E15] HTML 转义 / 反转义
来源：http://dali.xuetiantiany.cn/Article/details/gtuplrmcle.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.redwolf501.top/Article/details/gtnmqqwlau.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtnjobqtwu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhongyouzk.top/Article/details/gtupvubpgf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtokqlajhj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pycfn.com/Article/details/gthjbevnbc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtawjzreue.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtarjuwfja.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tianlin.xyz/Article/details/gtqlabsctw.html

[E16] 数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtolleybeq.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtaawyhwdq.html

PHP:  number_format(1234567);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayzlzztk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gtlxfnfdfn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnxiangtu.top/Article/details/gtqwhfhtkb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hnxiangtu.top/Article/details/gtmcwgxubw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fengsongda.top/Article/details/gtxmchprcf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.bjfxy.top/Article/details/gtjoeqtpbk.html

C#:   1234567.ToString("N0")
来源：http://dali.hnqzz.top/Article/details/gtwugjoqzi.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtgpicwlvt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtlfubqvsb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hysaishi.cn/Article/details/gtjvlivxld.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtdpsliqxh.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pycfn.com/Article/details/gtqlhjahtd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yanxiufei.cn/Article/details/gtkrpzflwl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtueeegtoi.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtauitgbnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.9152youxi.cn/Article/details/gtkckwqzpp.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gtngoscbjn.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.nanxinkj.top/Article/details/gtclhmthbu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.cheryme.top/Article/details/gtncqcjyfq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zycfv.cn/Article/details/gtcozcvgjx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gtvpnmmqbm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yvedp.cn/Article/details/gtwkbxgbfs.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtwrbfqhme.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gtdztaakah.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gtoeslnftg.html

[E19] 多行文本按行拆分
来源：http://dali.jianghu66.top/Article/details/gtzkpjovnd.html

Py:   s.splitlines()
来源：http://dali.tian-w.cn/Article/details/gtpldaihdr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtwzdiujpt.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gtjskzirgd.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtsenncfpc.html

Java: s.lines().toList()
来源：http://dali.shzxlz.cn/Article/details/gtsitogbmk.html

Go:   strings.Split(s, "\n")
来源：http://dali.kuanghao11.cn/Article/details/gtziaaypsb.html

Ruby: s.lines
来源：http://dali.chenzaomai.com/Article/details/gtsbseusyw.html

C#:   s.Split('\n')
来源：http://dali.ydzc1.top/Article/details/gttrgcjemv.html

[E20] 判断字符串是否为空
来源：http://dali.wangdashe.top/Article/details/gtdilkpgmw.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gttxcqktic.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jiagoushi.top/Article/details/gtuhegykyx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.9152youxi.cn/Article/details/gtlgtmlytj.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gtqwptgeks.html

Java: if (s.isEmpty()) {}
来源：http://dali.dianchejie.cn/Article/details/gtaljcqyjn.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtfbmetjzo.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtoqkzrhpu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtntxrtcnt.html

[E21] 超长截断加省略号
来源：http://dali.9152youxi.cn/Article/details/gtrymiabxg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtzbyccwcs.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtnsgsdneq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtmexnjneq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gtjfpuisif.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gthgrdotwp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtyjztwlwc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtrpjazdaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gthykyvrbf.html

[E22] 字节长度与字符长度
来源：http://dali.0kj1m.cn/Article/details/gtcbpyyzhf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpjpjqlgm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtftoeapgk.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtpegiqgcb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtzboiswjy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtahxrakgi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtjukbejzh.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtbxqmdtdz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.fengsongda.top/Article/details/gtgbpijwfl.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gttzyxwexx.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtatbzyyww.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtpzhvxnjk.html

[F01] 读取整个文件
来源：http://dali.shangyingyoupin.top/Article/details/gtjjbubqrf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.feifeiyinyue.top/Article/details/gtijkqzjip.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hnxiangtu.top/Article/details/gtkbgwcgqm.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhoulong.xyz/Article/details/gtcvelpxfa.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.daria6918.cn/Article/details/gtnueualre.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtpsqjnsje.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jinqigfzy.top/Article/details/gtgqoksrhw.html

Ruby: File.read("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtnrhthumg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtkjzvfkbz.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtsaaprjya.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqlzkvyv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtxrptickr.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtxsgzkgsa.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtwzhdlmtv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtjazgxzqv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.vqdsnc.cn/Article/details/gtkbbenpdj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yuanzhike.top/Article/details/gtgnqpwvjf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.haohaochexian.top/Article/details/gtdeslfzve.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigfzy.top/Article/details/gtmgqylczf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtyvkuyvfa.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtutvflhxr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jlsjyb.cn/Article/details/gtjdtvoccr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxuanxn.top/Article/details/gtdagstdmq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gttvnjxaqr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.fzhhl.top/Article/details/gtnyqfyxbc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.wangshuangyany.cn/Article/details/gtukwdwssk.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xinyue.icu/Article/details/gtlewsupho.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtekdwqhsu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.bjfxy.top/Article/details/gtnbyqoccj.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyljrascw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dianchejie.cn/Article/details/gtyqnliqwm.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gtlcxbiuzz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yueranfly.top/Article/details/gtqpmtcber.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtqngsswhm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zdqjudy.top/Article/details/gtyvisruxd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtbzbjxrnl.html

[F05] 判断文件或目录是否存在
来源：http://dali.fengsongda.top/Article/details/gtvijafxgl.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ydzc1.top/Article/details/gtzwspiztq.html

PHP:  file_exists("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtueingeaq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.wangdashe.top/Article/details/gttjzdzzci.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldnowsue.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtutasxdrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.yuanzhike.top/Article/details/gtydxoimzj.html

Ruby: File.exist?("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtusbrsoje.html

C#:   File.Exists("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gttjzukaax.html

[F06] 删除文件
来源：http://dali.pengpengdd.cyou/Article/details/gtggpdrfie.html

Py:   os.remove("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtsjnpwsvd.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyigbgrlu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtootezvni.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtebipwdwe.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtvyevzyhv.html

Go:   os.Remove("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyefhgpk.html

Ruby: File.delete("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtpvdjivew.html

C#:   File.Delete("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxhwxacoq.html

[F07] 创建目录（含多级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbxsdmny.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtndzvdcwm.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtcbdvraai.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtifmuhcrk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.0kj1m.cn/Article/details/gtvfgellyu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gtikclmumc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.mhx1999.top/Article/details/gtedlepuhi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yuanzhike.top/Article/details/gtfcsweuiz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zdqjudy.top/Article/details/gtayipjyko.html

[F08] 遍历目录
来源：http://dali.316326.xyz/Article/details/gteszynvaf.html


<!-- 参考信息 -->