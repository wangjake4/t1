代发 wailian999

[D23] reduce 累积计算
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaeyexdl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.redwolf501.top/Article/details/gtazmilhxf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.gzhubu.top/Article/details/gtarbwovrd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gtohhllkqg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gteekhetdk.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zdqjudy.top/Article/details/gtumprnipq.html

Go:   // 手写循环
来源：http://dali.chenlongwang.top/Article/details/gtxuhamxvv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.daria6918.cn/Article/details/gtzrcssfps.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xziqi.cn/Article/details/gtkxjuxebm.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenzaomai.com/Article/details/gtequfllqu.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fengsongda.top/Article/details/gttvgcctut.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cashguo.top/Article/details/gtghcaonoh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tian-w.cn/Article/details/gtswghumuu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yonumen.top/Article/details/gtlotfuiar.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sufxvd.cn/Article/details/gttzsevrvm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.svipenyu.cn/Article/details/gtfmvekreq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jqgufenzy.top/Article/details/gtcransrtp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenlongwang.top/Article/details/gtipysoqzz.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gtztehteol.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yueranfly.top/Article/details/gtpeyeuusn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gtgkvwpmwl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.smart0.xyz/Article/details/gtpysnlfuh.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.redwolf501.top/Article/details/gttmitxrfy.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gtneaneogq.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sweek.top/Article/details/gtlzdsgqgk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstsengzi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtlszerqfo.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gtibaiacui.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jqgfzy.top/Article/details/gtzvccfvve.html

PHP:  implode(", ", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtflobxmgu.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlnjgarkh.html

TS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmmgxqvw.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gttqkffqcl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtvuxnfhis.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtycnhtony.html

C#:   string.Join(", ", list)
来源：http://dali.zhijiandao.cn/Article/details/gtbdfbobgv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcadsjvhy.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtrfbussgz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnihaajoe.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtaakxmkho.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwtaqyay.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtqhbmndsg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gtlafxeyjt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtvwfqiyex.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.wangshuangyany.cn/Article/details/gtsduxaluk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtvwsnjpoa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtubddfbrc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtpzovyxuw.html

[E02] 重复字符串
来源：http://dali.zhengqikj.top/Article/details/gtoedjchtt.html

Py:   "ab" * 3
来源：http://dali.jlsjyb.cn/Article/details/gtwrfsvdhr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.birdmap.top/Article/details/gtvgwtmvxb.html

JS:   "ab".repeat(3)
来源：http://dali.jianghu66.top/Article/details/gtjknbvnik.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gtvtpoipjm.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtqbrrcbui.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenlongwang.top/Article/details/gtczenjzsg.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gtnbkogvqc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtzlnuiqka.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtxbujnyce.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhixingplan.top/Article/details/gttqfjhdzf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gtaubzeagr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtsxwejmnt.html

TS:   s.slice(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtpdvjwins.html

Java: s.substring(1, 4)
来源：http://dali.cucudq.cn/Article/details/gtfcaqtjja.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtpgygcmpd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.9152youxi.cn/Article/details/gtokqffzjr.html

C#:   s.Substring(1, 3)
来源：http://dali.yj20258.top/Article/details/gtzzynzqhn.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gtzobasxsi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtemtuasde.html

PHP:  strpos($s, "x");
来源：http://dali.jiagoushi.top/Article/details/gtenmguapy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtawsropob.html

TS:   s.indexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtlldtagow.html

Java: s.indexOf("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtobpsoqjk.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gthzzaymqh.html

Ruby: s.index("x")
来源：http://dali.zycfv.cn/Article/details/gtimqkakxf.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gthjheendt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.svipenyu.cn/Article/details/gtvvqbshxh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtcrnqqiqp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtmvrfrcfr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtjiffwzyq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhoulong.xyz/Article/details/gteugiarxb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtarfpqtoa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtizzxgwpd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gtieygtjsa.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.fzhhl.top/Article/details/gtiskhafah.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtkgcxmbad.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yj20258888.top/Article/details/gtpnyffkla.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtdfchxyvd.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtaufruepc.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtyvgrhyng.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtgdannppo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gtoberxfzt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzzcqqigj.html

C#:   s.Replace("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgykcbedp.html

[E07] 按分隔符拆分
来源：http://dali.birdmap.top/Article/details/gtaonbfbqo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ybcxt.top/Article/details/gtokfecrwv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zycfv.cn/Article/details/gtlequrvdl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjrbdvkl.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gtbmfahjba.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yonumen.top/Article/details/gtoahulntm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hfpthk.cn/Article/details/gtsrxuifzi.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gtpzmwypbq.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dashuyun.cn/Article/details/gtojglxsav.html

[E08] 数组按分隔符合并
来源：http://dali.guannengcc.top/Article/details/gtezpfhbsc.html

Py:   ",".join(items)
来源：http://dali.guowangkeji.top/Article/details/gthclyxnvs.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtupymeajj.html

JS:   items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtqnjkjsnf.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtpajwnywj.html

Java: String.join(",", items)
来源：http://dali.jqgufenzy.top/Article/details/gtwomvkseh.html

Go:   strings.Join(items, ",")
来源：http://dali.jqgufenzy.top/Article/details/gtcrkujara.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtnlebztes.html

C#:   string.Join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtbvvdhbuk.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtajlkvmqs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtxzswangi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrajvelr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xinyue.icu/Article/details/gtlonehfwo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtfwllzeis.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xinyue.icu/Article/details/gthkrjdluu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsbugpkkj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guowangkeji.top/Article/details/gtbtwzxgqe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gtkoptjvrz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jiagoushi.top/Article/details/gtqzbetxeu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gtjswzmyeb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.pengpengdd.cyou/Article/details/gtmlrlbjgl.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyhqdwps.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtsjhsdvvl.html

Java: String.format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtuhedatih.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gtkexudcms.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtcnpcvjot.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gtvalujkyg.html

[E11] 反转字符串
来源：http://dali.fzhhl.top/Article/details/gteuocdhrg.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtdnzhzkzx.html

PHP:  strrev($s);
来源：http://dali.tianlin.xyz/Article/details/gtycfhdgje.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtkwgdccbz.html

TS:   [...s].reverse().join("")
来源：http://dali.ehwqpu.com/Article/details/gtegqbtzad.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqqwpkrcl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtfcdbbirm.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtbifqegaw.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtvqotqboh.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtbhuptxrw.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtyvzwfahi.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gthjgdndbr.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gtxlmdzwsu.html

TS:   s.split("a").length - 1
来源：http://dali.zhongyouzk.top/Article/details/gtnoppfyuc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtyblpkwvr.html

Go:   strings.Count(s, "a")
来源：http://dali.cheryme.top/Article/details/gtzfndslyq.html

Ruby: s.count("a")
来源：http://dali.yongpay.top/Article/details/gtjytedreb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cdnleiting.top/Article/details/gtryftsywi.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gteifzwzgj.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtwnebhylw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuanzhike.top/Article/details/gtfbfohbyp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcgtuhdi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtknhqphqq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gttmpptbhg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yongpay.top/Article/details/gtilomczlg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gtbovanxrx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.xziqi.cn/Article/details/gtoydlakid.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gthvlsrcbj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtxeleigma.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudivawrf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sysykeji.top/Article/details/gtpkjmhzaq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtohxktdva.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolberzhy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenlongwang.top/Article/details/gtencgebkh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.316326.xyz/Article/details/gtpfufflat.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtgcrlxxux.html

[E15] HTML 转义 / 反转义
来源：http://dali.mhx1999.top/Article/details/gtoyzgmgpv.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shuidangran.top/Article/details/gtmszzlavn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtqmlmvwei.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ybcxt.top/Article/details/gtzuiwikhx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yj20258888.top/Article/details/gtpsghzyff.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhiwuduotai.top/Article/details/gtmwncsbge.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtmiyhbrpk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aibaodan.cn/Article/details/gtxnprajhx.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zdqjudy.top/Article/details/gtjypwtidc.html

[E16] 数字千分位
来源：http://dali.c1oappe.top/Article/details/gtsgmbolnq.html

Py:   f"{1234567:,}"
来源：http://dali.daria6918.cn/Article/details/gtcgpoloww.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gtajalxnqj.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gtyxnyjyhk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhijiandao.cn/Article/details/gtbjilbkag.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gtaxvmyqgf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gtgokfzjki.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.ppjwa.cn/Article/details/gtwxjutnwy.html

C#:   1234567.ToString("N0")
来源：http://dali.hysaishi.cn/Article/details/gtustupzso.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gttfserdqc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sufxvd.cn/Article/details/gtkgwdxuqc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.svipenyu.cn/Article/details/gtxqlngusp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtvtafvvdg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtvqjusuee.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtqhxzmbth.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gogol.net.cn/Article/details/gtnykdmnvv.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gteyegqnme.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgmggnrwt.html

[E18] 模板占位符替换
来源：http://dali.fzhhl.top/Article/details/gtiwvpihxt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtrfsxqtkn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gtgrtlgywn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtvcbkhqul.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtemwiffaw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtqknltbij.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.tanke756.top/Article/details/gtjgkloylb.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtxfuvaunk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtqetvwoxm.html

[E19] 多行文本按行拆分
来源：http://dali.zhijiandao.cn/Article/details/gtdbhavbek.html

Py:   s.splitlines()
来源：http://dali.feifeiyinyue.top/Article/details/gtwkjzraux.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aizwys.cn/Article/details/gtnbtozrqh.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtevipuzms.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhskawbr.html

Java: s.lines().toList()
来源：http://dali.jiagoushi.top/Article/details/gtcaydujlz.html

Go:   strings.Split(s, "\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtquwezgql.html

Ruby: s.lines
来源：http://dali.zhixingplan.top/Article/details/gthyvmkewm.html

C#:   s.Split('\n')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsqixvtl.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gtiyuowrve.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtpfhgtefl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.gotoacloud.top/Article/details/gtohymweml.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.aibaodan.cn/Article/details/gtefseimvu.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gtwhiryezj.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gtxqfdxief.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtquiudqns.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtmzwyntpu.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtlzuobfix.html

[E21] 超长截断加省略号
来源：http://dali.nanxuanxn.top/Article/details/gtbptcwtex.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.fengsongda.top/Article/details/gtgfswfxqy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtjhbypppg.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtvpgmcroi.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtsjghupuc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtaygggsxi.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.cucudq.cn/Article/details/gtcfotfcnt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhoulong.xyz/Article/details/gtquxrjbaa.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hammf.cn/Article/details/gthhvicyfn.html

[E22] 字节长度与字符长度
来源：http://dali.gzhubu.top/Article/details/gtzizifkoj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebnembyy.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtedvwikya.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zycfv.cn/Article/details/gtyckoqvyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yonumen.top/Article/details/gttfwappcl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zdqjudy.top/Article/details/gtwozpsxxt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtfienqeoc.html

Ruby: s.bytesize;  s.length
来源：http://dali.xinyue.icu/Article/details/gtckugxhem.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtvyobmwow.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtbxjbllhe.html

F. 文件与目录
来源：http://dali.wangshuangyany.cn/Article/details/gtovpgjoko.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtaieievns.html

[F01] 读取整个文件
来源：http://dali.xinyue.icu/Article/details/gtybknzadc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jqgufenzy.top/Article/details/gtajxxxrwn.html

PHP:  file_get_contents("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwenimnpr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtzngqsxac.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezbthkta.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtacpvvexu.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hongshengwenyu.top/Article/details/gtwgplegrz.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtsozieemk.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gteggdikpa.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtjkqrelbs.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.cucudq.cn/Article/details/gtrjrcdxem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.snrcjt.cn/Article/details/gtvpmdjpfg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvvdzclxg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtyvnaqcrv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gtlrgndpwi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fengsongda.top/Article/details/gtttvtilxq.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jiagoushi.top/Article/details/gthwwzhllp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cheryme.top/Article/details/gtbvdyyabh.html

[F03] 写入文件（覆盖）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjehzouhi.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtlehealpl.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxajmcis.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gturwjflpn.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtzuysdbfp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.meibo888.top/Article/details/gtsjawfiym.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtcwbidmos.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xylfe.cn/Article/details/gtdysxkzqy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xuanzx.com/Article/details/gtafahlaoz.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtzsuqhngz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtlojdigeq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gtfjjxczwe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yuxming.cn/Article/details/gtxpfeuovz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtgvbqupmq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yonumen.top/Article/details/gtpfkegsix.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.fengsongda.top/Article/details/gtiidwgdpx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangshuangyany.cn/Article/details/gthvtmsfvs.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.meibo888.top/Article/details/gtpfhhazqa.html

[F05] 判断文件或目录是否存在
来源：http://dali.yueranfly.top/Article/details/gtgzvutxta.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.pycfn.com/Article/details/gtnejxnpal.html

PHP:  file_exists("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgbudgsc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtpfzbwwil.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtjqhxujea.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.redwolf501.top/Article/details/gtpnkrmjjc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnqzz.top/Article/details/gtwrdhnplj.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtniyjqkrt.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258.top/Article/details/gtewweompr.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gtcomwijgl.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gtxhhaksdq.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikpzxrbf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtcjjmcnzo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gttosrldjy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtofwjpzxp.html

Go:   os.Remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtxfsfrxki.html

Ruby: File.delete("a.txt")
来源：http://dali.pycfn.com/Article/details/gtbpgundbf.html

C#:   File.Delete("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtbdaausxm.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtbfpmufbh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtwubpruoz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yuxming.cn/Article/details/gtidybsird.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gthdxvrtzl.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkootvvll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.haohaochexian.top/Article/details/gtawdsbtco.html


<!-- 参考信息 -->