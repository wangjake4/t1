代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnqzz.top/Article/details/gtcircwezh.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gtvqxukass.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.ehwqpu.com/Article/details/gtrltoagfx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.dianchejie.cn/Article/details/gthhasbyos.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtophfutiq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtpmihrzjf.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtcvdmxdog.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtznuxnsjm.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtudcmfxnb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cucudq.cn/Article/details/gtarmrjrnm.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gtqhjkwwop.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gttoonojlt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gaohongyu789.top/Article/details/gttikvojuf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.wangdashe.top/Article/details/gtlffhnlcs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtiaylhrni.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtceazzmsd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtlhczfrjk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.mhx1999.top/Article/details/gtjfwhjchh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.iojbl.cn/Article/details/gtawsshmbc.html

[D26] 数组转字符串
来源：http://dali.hnxiangtu.top/Article/details/gtnxlklftv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtpiahbima.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtonihbkcb.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtsmllmuak.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtekqjdaqf.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gthxjcoxvu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.316326.xyz/Article/details/gtibbbxuoa.html

Ruby: arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gtkqmrvaxe.html

C#:   string.Join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gtxyzowmle.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrytzwqod.html

E. 字符串处理
来源：http://dali.havefunace.top/Article/details/gtlrmwyvvk.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzwrtserg.html

[E01] 拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttscdobhl.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtwtyuuhne.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cqqwz.cn/Article/details/gtoasjjvvs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtaaxphxvb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtouzsmrad.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hammf.cn/Article/details/gthgeyaeaw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xylfe.cn/Article/details/gtaiyeepit.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shuidangran.top/Article/details/gtkapygmmy.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgszzqksn.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gtgeawvebq.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtimdjgplz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gtqthuttsb.html

JS:   "ab".repeat(3)
来源：http://dali.sufxvd.cn/Article/details/gtwroighpl.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtyduvzrpq.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtrgjjhont.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtfrzpfznf.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtjlforevl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhongyouzk.top/Article/details/gtbusnxjjm.html

[E03] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtqswndjsx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gtxyavtiwo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.hywenlv.cn/Article/details/gtuaffuhtd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gthqdowswu.html

TS:   s.slice(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtlixgitav.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwildaaim.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtmgmybrkj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yuxming.cn/Article/details/gtkkmznwkc.html

C#:   s.Substring(1, 3)
来源：http://dali.aizwys.cn/Article/details/gtcmqlukun.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtfrxvwxyn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yvedp.cn/Article/details/gtcglgturx.html

PHP:  strpos($s, "x");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigovhcop.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.daria6918.cn/Article/details/gturdzoekn.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gteepnwchn.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gtavzjkoqs.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtgvdcgdiq.html

Ruby: s.index("x")
来源：http://dali.aizwys.cn/Article/details/gtywumeqbu.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtmoqnujau.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gtahqngyxw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.haohaochexian.top/Article/details/gtxeksgvhv.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ydzc1.top/Article/details/gtnjrzelxr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtadtiuqyk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gzhubu.top/Article/details/gtmbpcargv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtqclqnmlq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gtkjcwhglq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtcbnzvhfk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtanccghdf.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtayncveuk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.cashguo.top/Article/details/gtfgygqwam.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmwwbhjsf.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtsdojjcdb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtnvclkqaa.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtqwvebxsn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtipzfkddh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtupikyseq.html

C#:   s.Replace("a", "b")
来源：http://dali.yuxming.cn/Article/details/gthptsxodj.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtysdzvzgg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtmqhiaksw.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.birdmap.top/Article/details/gtzyeetwim.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtqkvmtbuw.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtosdmlvpf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtasalleub.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.cucudq.cn/Article/details/gtzmwsjjry.html

Ruby: s.split(",");  s.split
来源：http://dali.hfpthk.cn/Article/details/gturxadrtb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtxrdjqiml.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtnbfiehmu.html

Py:   ",".join(items)
来源：http://dali.yuxming.cn/Article/details/gteqqixklg.html

PHP:  implode(",", $items);
来源：http://dali.jinqigufen.top/Article/details/gtnemczwyc.html

JS:   items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtjsekoawt.html

TS:   items.join(",")
来源：http://dali.yuxming.cn/Article/details/gtpvcllwpd.html

Java: String.join(",", items)
来源：http://dali.smart0.xyz/Article/details/gtzckdezpe.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtrvuqkvdw.html

Ruby: items.join(",")
来源：http://dali.havefunace.top/Article/details/gtemrvqzfh.html

C#:   string.Join(",", items)
来源：http://dali.gzhubu.top/Article/details/gtodsgxtla.html

[E09] 去除所有空白字符
来源：http://dali.xinyue.icu/Article/details/gtiumfrsjm.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.guowangkeji.top/Article/details/gtmbcfgenn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.chenlongwang.top/Article/details/gthqyzjpkx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangshuangyany.cn/Article/details/gtswtalyfj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtegvcuftc.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtpicorhxi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtwjgruwba.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtoqybyxue.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtfvxhfqfx.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nanxinkj.top/Article/details/gtzrkzkcqq.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtpgvszlmm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gtdatumyrj.html

JS:   "7".padStart(3, "0")
来源：http://dali.yangfankeji.com/Article/details/gtusssrcht.html

TS:   "7".padStart(3, "0")
来源：http://dali.svipenyu.cn/Article/details/gtdshqvzcc.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtgysptojm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtidzpazfz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtveeefsdk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtxiopnpxs.html

[E11] 反转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzclsycfr.html

Py:   s[::-1]
来源：http://dali.yj20258.top/Article/details/gtvxdndvrz.html

PHP:  strrev($s);
来源：http://dali.bjfxy.top/Article/details/gtczgdwylc.html

JS:   [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtjwfhiffa.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gtmbedrbjo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258.top/Article/details/gtucnbefrg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guowangkeji.top/Article/details/gtrbxqphjc.html

Ruby: s.reverse
来源：http://dali.yj20258.top/Article/details/gtitwyzzsp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cqqwz.cn/Article/details/gtgaskvwjn.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtsmiumcpt.html

Py:   s.count("a")
来源：http://dali.shzxlz.cn/Article/details/gttzqxfidv.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtkmesftps.html

JS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gtahgffguh.html

TS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtvjdzdwpk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtedehftod.html

Go:   strings.Count(s, "a")
来源：http://dali.haohaochexian.top/Article/details/gtpcoulgpx.html

Ruby: s.count("a")
来源：http://dali.hnxiangtu.top/Article/details/gtztcssywu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtgxatsmoq.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtjwlocgia.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtmrkgstpt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sxryk.cn/Article/details/gtcsjemqwx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zdqjudy.top/Article/details/gtosyelffz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gtabmxapsw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ppjwa.cn/Article/details/gttkoirffo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cashguo.top/Article/details/gtqurtwtcc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xinyue.icu/Article/details/gtchfrrpia.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aizwys.cn/Article/details/gtpnnjpsfv.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtqlgduhyv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ppjwa.cn/Article/details/gtjjwinxqr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zycfv.cn/Article/details/gtsdjdcvro.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenlongwang.top/Article/details/gtpcikyvsw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozelnevv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtiaytqnac.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtiylaghhm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhengqikj.top/Article/details/gtyegatogy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nwbrower.top/Article/details/gtqbggdkgp.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtknkfytpr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkswsxwze.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtxksysfnq.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtvxloubgk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtqkhpxjsz.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cashguo.top/Article/details/gtvgxldcnv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.kuanghao11.cn/Article/details/gtbmpfoyai.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gotoacloud.top/Article/details/gtpgeiysri.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtjvkhexmv.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxncmcsx.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtiwfkhvpz.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtamiyqphp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gtbezmedrk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gtrdnsdkpy.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cashguo.top/Article/details/gtarpsljoy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gthmkfaxue.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtywkkyttw.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtlssfauxl.html

[E17] 首字母大写
来源：http://dali.redwolf501.top/Article/details/gtdkzdvbym.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkafqekj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jinqigufen.top/Article/details/gtllrvwwya.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gthubhfioq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtivcweabi.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.316326.xyz/Article/details/gtywrxexvq.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fengsongda.top/Article/details/gtaabxmadq.html

Ruby: s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gthruhoqfw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cqqwz.cn/Article/details/gtdgudgpnm.html

[E18] 模板占位符替换
来源：http://dali.cdnleiting.top/Article/details/gtswvrxciq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yuanzhike.top/Article/details/gtfveeitho.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gtcoatayys.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtionxllrq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtxihspmsk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtamczcexy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtsnpzhwfy.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.birdmap.top/Article/details/gtkamkpazo.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtnvzwdnxv.html

[E19] 多行文本按行拆分
来源：http://dali.yongpay.top/Article/details/gthheksukk.html

Py:   s.splitlines()
来源：http://dali.yueranfly.top/Article/details/gtpekqttrn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shuidangran.top/Article/details/gtyglolgot.html

JS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtfmlkpegj.html

TS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtfyonnzpn.html

Java: s.lines().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtasaiznuz.html

Go:   strings.Split(s, "\n")
来源：http://dali.xziqi.cn/Article/details/gtpkvwfsdz.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtlcxldatg.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gtjrdowvtj.html

[E20] 判断字符串是否为空
来源：http://dali.daxiang520.top/Article/details/gtjynincyf.html

Py:   if not s:
来源：http://dali.shanyushiyangkeji.top/Article/details/gthutjoopg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtwjiyqokp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258888.top/Article/details/gtwfraszjd.html

TS:   if (s === "") {}
来源：http://dali.wangshuangyany.cn/Article/details/gthlxcdabt.html

Java: if (s.isEmpty()) {}
来源：http://dali.hysaishi.cn/Article/details/gtgbmzuhyl.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtymmdcsrq.html

Ruby: if s.empty?
来源：http://dali.fengsongda.top/Article/details/gteutsdbnk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuanzhike.top/Article/details/gtxeuawurf.html

[E21] 超长截断加省略号
来源：http://dali.zdqjudy.top/Article/details/gtmucymkfz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yongpay.top/Article/details/gtgwfazbrl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tanke756.top/Article/details/gtxvkzfhrh.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtwmowekyg.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtmzjkjmrg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtdejjolti.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.daxiang520.top/Article/details/gtygrvacph.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtedzgwgjp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gtopawxxgq.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gtruylcrwu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohbqijog.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtznrinygn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtswlpflpy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gthdsbgnoe.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtksbmiday.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.tianlin.xyz/Article/details/gtlgewmhrz.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnwzftimg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pengpengdd.cyou/Article/details/gtljmktfub.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gthmnfizne.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtpyimpejs.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqykuqyhn.html

[F01] 读取整个文件
来源：http://dali.haohaochexian.top/Article/details/gtppehgczi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ehwqpu.com/Article/details/gtuajjbhtt.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtamwssfbu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gteirsjxrp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.316326.xyz/Article/details/gtgrcgeivd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtbxlwxgsd.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtsebymmug.html

Ruby: File.read("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtqxhwgcaw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtbnnhiptf.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtvuaokiiq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtfygkyxfu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.guannengcc.top/Article/details/gtaisijzhu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gteyrjlgkt.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cashguo.top/Article/details/gtdxphqnpv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtokectpfz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gttbwnwvtv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jlsjyb.cn/Article/details/gtzsgmrqfz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhixingplan.top/Article/details/gtydfjjrst.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtcfrzdkiw.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtcdexntwe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtoidgalmy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtlgicdjcx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtgsifsitt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtnukkyjzy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gtgmlbvubp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hysaishi.cn/Article/details/gtbcosedmy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenjidiqi.icu/Article/details/gtxjublcty.html

[F04] 追加写入文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfztirtvn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtahyxzncm.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.wangshuangyany.cn/Article/details/gtqmiavnrg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtfphqrbrg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtpmikkhre.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.hammf.cn/Article/details/gthphaawmw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtwyekmpdu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258888.top/Article/details/gttqkyofrl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gteqpszknz.html

[F05] 判断文件或目录是否存在
来源：http://dali.yj20258.top/Article/details/gtepihydzf.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.quarkkingdee.top/Article/details/gtjktxktyh.html

PHP:  file_exists("a.txt");
来源：http://dali.havefunace.top/Article/details/gtmbmzacuv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yongpay.top/Article/details/gtgzgdxujy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtcbemqurw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.chenzaomai.com/Article/details/gtfiszkqsl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hammf.cn/Article/details/gtuvrkqtcs.html

Ruby: File.exist?("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gthkimaapb.html

C#:   File.Exists("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtaptgkgli.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtzxgmxnpb.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtfgdgnzhi.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258.top/Article/details/gtsacluseg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtymbdkybs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gttpvakiym.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtxlialwpi.html

Go:   os.Remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtmuyceurv.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtpdxzlhkh.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgufenzy.top/Article/details/gtvoedahti.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gtkvnxpfyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gtssnscpxq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.zhongyouzk.top/Article/details/gtefspilyq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yanxiufei.cn/Article/details/gtxhukmlte.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtkogzmzgy.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtjhqefdsc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhiwuduotai.top/Article/details/gtivkjtliv.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.pengpengdd.cyou/Article/details/gtlznyspqm.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.wangshuangyany.cn/Article/details/gtqjnwwsqq.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gtrcdkkbhl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cqqwz.cn/Article/details/gttxaojypc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqhxicqlr.html

JS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtvxjhofye.html

TS:   fs.readdirSync("dir")
来源：http://dali.sxryk.cn/Article/details/gtuttvrdvd.html


<!-- 参考信息 -->