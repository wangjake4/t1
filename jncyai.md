代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cdnleiting.top/Article/details/gtyytbfcfn.html

[D24] 字典 / Map 基本操作
来源：http://dali.zycfv.cn/Article/details/gtksssensd.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.nanxuanxn.top/Article/details/gtswibyvvk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtkheqrbqb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtsulxquhm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtweegqaeq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gtohxopznu.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yuanzhike.top/Article/details/gtmhfipfbx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.iojbl.cn/Article/details/gtcvhwtzhz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaybfwpbb.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtrmzpseqk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxuanxn.top/Article/details/gtsrsznhfb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtcigtiswm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.bjfxy.top/Article/details/gtqlyfkgqp.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnqzz.top/Article/details/gtmhgfmqyc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.aibaodan.cn/Article/details/gtjbjwarjt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xuetiantiany.cn/Article/details/gtotouxsbl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yj202588.top/Article/details/gtxtyixrkd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yj20258888.top/Article/details/gtvmcpqrpg.html

[D26] 数组转字符串
来源：http://dali.hysaishi.cn/Article/details/gtmpsbckyk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gtjgpptmqw.html

PHP:  implode(", ", $arr);
来源：http://dali.sxryk.cn/Article/details/gtolzqjiwo.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtzmbqfoot.html

TS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gtbfksnnlh.html

Java: String.join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gtcqjyrihz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gtnodbhtvf.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtolbsoexq.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtusyfezan.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtspxgfpwq.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtoavlcshk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtffftqwee.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gttwhpemaq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ehwqpu.com/Article/details/gtemqslnoi.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.wangshuangyany.cn/Article/details/gtnqdsquqs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gtiyqqckrz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jlsjyb.cn/Article/details/gtsbavjoxc.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sxryk.cn/Article/details/gtzugomyju.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cheryme.top/Article/details/gtjehpfepe.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.kuanghao11.cn/Article/details/gtldimbfop.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtngpbbmhb.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtjfmgvakb.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtokdambwp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guowangkeji.top/Article/details/gtktfoivyh.html

JS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtarafunpm.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtcavivoel.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtgrjqiqnh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.svipenyu.cn/Article/details/gtyiazxovb.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gtnadhaxjm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gttrljtkhy.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtmnwctgsq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtheezhbac.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtorozwdfd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtviyaypho.html

TS:   s.slice(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrguevydv.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtydueujua.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjexgnwlu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sufxvd.cn/Article/details/gtbpnsrdhs.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtuhmlurko.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gtwmqfzjqq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtxefgxvuv.html

PHP:  strpos($s, "x");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiktglgj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gtoqbjpntw.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtxnkzrhwc.html

Java: s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gthnzxtucb.html

Go:   strings.Index(s, "x")
来源：http://dali.cucudq.cn/Article/details/gtiboonbrp.html

Ruby: s.index("x")
来源：http://dali.yj20258.top/Article/details/gtymksbyxl.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtufijulvl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtoourykrk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtoogvyylz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtlsyozixh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dashuyun.cn/Article/details/gtkkcigsyt.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.quarkkingdee.top/Article/details/gtvxstexqj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daria6918.cn/Article/details/gtakwyasqk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtbavoidkb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.birdmap.top/Article/details/gtorraonwb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.feifeiyinyue.top/Article/details/gtkyfnglnm.html

[E06] 替换子串
来源：http://dali.yuxming.cn/Article/details/gtupynjuqo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.dashuyun.cn/Article/details/gtdkqzbrxn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.zhijiandao.cn/Article/details/gtcdetdrwi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtrmjqjtcv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zdqjudy.top/Article/details/gtbzojvyew.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtqjnuakat.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xylfe.cn/Article/details/gtuhfkssta.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtxoujmanh.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtoaxlxlxk.html

[E07] 按分隔符拆分
来源：http://dali.xuetiantiany.cn/Article/details/gtodjetgrn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hongshengwenyu.top/Article/details/gtapyvdkay.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.iojbl.cn/Article/details/gttnviqhsv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtsodkkfmt.html

TS:   s.split(",")
来源：http://dali.sxryk.cn/Article/details/gtslzvshqd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtqszqqqac.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xziqi.cn/Article/details/gtmqeasozs.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258.top/Article/details/gtridimxhf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sufxvd.cn/Article/details/gtcoxlvwsf.html

[E08] 数组按分隔符合并
来源：http://dali.redwolf501.top/Article/details/gtddroihgc.html

Py:   ",".join(items)
来源：http://dali.yangfankeji.com/Article/details/gtritojimy.html

PHP:  implode(",", $items);
来源：http://dali.yj20258.top/Article/details/gtmtysiclp.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtxtitlukc.html

TS:   items.join(",")
来源：http://dali.9152youxi.cn/Article/details/gtlvooqjon.html

Java: String.join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclsdwock.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtcqeqfvbp.html

Ruby: items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtgqfmqmyo.html

C#:   string.Join(",", items)
来源：http://dali.hammf.cn/Article/details/gtrwrkocvw.html

[E09] 去除所有空白字符
来源：http://dali.sweek.top/Article/details/gtrugsklmy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.iojbl.cn/Article/details/gthrfxsytt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtufokweib.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtensratfg.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.sysykeji.top/Article/details/gtsljfjvjx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtiephyinl.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xziqi.cn/Article/details/gtkftysczg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.birdmap.top/Article/details/gtkcyauupr.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gthgimpivh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtayxidqyi.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gthacigyqr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gogol.net.cn/Article/details/gthaajkskd.html

JS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtmdvapmki.html

TS:   "7".padStart(3, "0")
来源：http://dali.jyoumei.cn/Article/details/gtkdkiuekv.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtvcnqcphi.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yangfankeji.com/Article/details/gtiwjzwfqa.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gtzquhpsnx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gaohongyu789.top/Article/details/gtllssjwcm.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gtkrbyoedw.html

Py:   s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gtjusqmpgw.html

PHP:  strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtswncneuq.html

JS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtpzpvahan.html

TS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtbymxpwia.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fengsongda.top/Article/details/gtzuqkboak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.ppjwa.cn/Article/details/gtnaqeuybr.html

Ruby: s.reverse
来源：http://dali.wangshuangyany.cn/Article/details/gtoxtgeyyl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gtnkbmyslq.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gthbhqltnu.html

Py:   s.count("a")
来源：http://dali.cheryme.top/Article/details/gtcgondiqn.html

PHP:  substr_count($s, "a");
来源：http://dali.tanke756.top/Article/details/gtumlcmlfa.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gtpgjcdzgs.html

TS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gttbruimuh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtouwcxjlc.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtpjruvaji.html

Ruby: s.count("a")
来源：http://dali.sysykeji.top/Article/details/gtvbjduluo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.bjfxy.top/Article/details/gtmtdsvvwt.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtiizisqne.html

Py:   for ch in s: print(ch)
来源：http://dali.nanxuanxn.top/Article/details/gtnlwlgmxf.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cashguo.top/Article/details/gtfruqhxai.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtvqkjnrph.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gthcphqwnv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shangyingyoupin.top/Article/details/gtowuxrmjf.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gotoacloud.top/Article/details/gtvbovioln.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.pycfn.com/Article/details/gtiahiikrc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtbyueirqi.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtmtiimxve.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.smart0.xyz/Article/details/gtraesfvtv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.mhx1999.top/Article/details/gtygwjqcvm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gteydhinvl.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ivvv.top/Article/details/gtfmchhvaj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtfjtculhe.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.meibo888.top/Article/details/gtbxdbaisa.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenzaomai.com/Article/details/gtopclmyfs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtrvyrbkhi.html

[E15] HTML 转义 / 反转义
来源：http://dali.yuanzhike.top/Article/details/gtwikjqunc.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtitzrjdxk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtclpzczgs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.svipenyu.cn/Article/details/gtpkpdzgdj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.iojbl.cn/Article/details/gtjbocahrr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.havefunace.top/Article/details/gtvirixzhw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcwgnzsl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtpkgecylq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.snrcjt.cn/Article/details/gtoxjmvnuj.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gtyedtivhk.html

Py:   f"{1234567:,}"
来源：http://dali.9152youxi.cn/Article/details/gtqdvtvxud.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtknndwffd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fzhhl.top/Article/details/gtxyaugmag.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gtzifminfm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtxyvoqljx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yj202588.top/Article/details/gtcfmhhaia.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jlsjyb.cn/Article/details/gtrfxqmzkx.html

C#:   1234567.ToString("N0")
来源：http://dali.hfpthk.cn/Article/details/gtofnhxfjq.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtcmphrsfm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj202588.top/Article/details/gtjmoehjxt.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtoqxobmgb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gteaqenpqx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gtwbssqzeo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.nanxuanxn.top/Article/details/gtzyjlquel.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrmlaiwgf.html

Ruby: s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtswhvguws.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtlvayexpb.html

[E18] 模板占位符替换
来源：http://dali.shangyingyoupin.top/Article/details/gtkltxoagj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gtxumowjrt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258888.top/Article/details/gtatvxamyq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.ybcxt.top/Article/details/gtdnneschm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gtybggbzna.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfqntdbx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gteklwffao.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.aibaodan.cn/Article/details/gteeduwthr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhiwuduotai.top/Article/details/gtnpfajskw.html

[E19] 多行文本按行拆分
来源：http://dali.ppjwa.cn/Article/details/gtiwheepmb.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtuzpjcfmc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtjffsvvqm.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gthdpqymsz.html

TS:   s.split(/\r?\n/)
来源：http://dali.cashguo.top/Article/details/gthzrorqme.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gtdgfpixbo.html

Go:   strings.Split(s, "\n")
来源：http://dali.xinyue.icu/Article/details/gtxksgaogb.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtkjciitik.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gteyfodiuz.html

[E20] 判断字符串是否为空
来源：http://dali.yj202588.top/Article/details/gtfyrusdxk.html

Py:   if not s:
来源：http://dali.jlsjyb.cn/Article/details/gtixbuxsam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yuxming.cn/Article/details/gttlngeckx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtscstqzjd.html

TS:   if (s === "") {}
来源：http://dali.yueranfly.top/Article/details/gtyhovgplv.html

Java: if (s.isEmpty()) {}
来源：http://dali.xylfe.cn/Article/details/gthbfjgbjj.html

Go:   if s == "" {}
来源：http://dali.ydzc1.top/Article/details/gttfmcwjmp.html

Ruby: if s.empty?
来源：http://dali.wangdashe.top/Article/details/gtckddtxyt.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shzxlz.cn/Article/details/gtexqcpnes.html

[E21] 超长截断加省略号
来源：http://dali.yonumen.top/Article/details/gtxnbhqbun.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtarzawpnf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtpqusdcyy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxvcdljj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtpijallvu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxtycxtj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jiagoushi.top/Article/details/gtyelifbeu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtwbquxqpv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtjextbkry.html

[E22] 字节长度与字符长度
来源：http://dali.tianlin.xyz/Article/details/gtmpudhwlx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shzxlz.cn/Article/details/gtghocieqm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ppjwa.cn/Article/details/gtccbmgfbp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtkymiryyc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtlrhsjbrg.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.shuidangran.top/Article/details/gtvxjcvprj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtpddwzfiw.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtugqyszjz.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyqcvdfis.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvapltgxw.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtudktpvkk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkqtmxyi.html

[F01] 读取整个文件
来源：http://dali.yangfankeji.com/Article/details/gtpqfvnzwv.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.havefunace.top/Article/details/gtwarfnbra.html

PHP:  file_get_contents("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtivsejoof.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.svipenyu.cn/Article/details/gtonuphtiu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.bjfxy.top/Article/details/gthsxzldva.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtwubmgcxf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.havefunace.top/Article/details/gtnwznmqoq.html

Ruby: File.read("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtaztqsoiu.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtfjlvumwo.html

[F02] 逐行读取文件
来源：http://dali.bjfxy.top/Article/details/gtzxesvojo.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gtnzbbuwle.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gtvtietypa.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gtdhqoftyn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gtfbgehyxx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnrpyzwc.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gtjfwaodyt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtkcibxfue.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbiefdrt.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gtocleidnt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtuhypqhgb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtknjdadxx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtxsqthlyc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtldzuginv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtiszwunmw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ybcxt.top/Article/details/gtqqibtfsr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yonumen.top/Article/details/gtzpvxyzna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gtupwkrohm.html

[F04] 追加写入文件
来源：http://dali.sufxvd.cn/Article/details/gtxsdixjsi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtooyuacvi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygvikvua.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jianghu66.top/Article/details/gtwxobrkqu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gzhubu.top/Article/details/gtkersazez.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvviqdvvt.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sysykeji.top/Article/details/gtijhfczhr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cashguo.top/Article/details/gtmorblzdb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tianlin.xyz/Article/details/gtxgqkriwi.html

[F05] 判断文件或目录是否存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmxlxyoge.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.snrcjt.cn/Article/details/gtubykqalj.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtxkxodevz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.fzhhl.top/Article/details/gtaaqdyyfh.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtfqhyvujr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtjfirriju.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.smart0.xyz/Article/details/gthcqvvmkc.html

Ruby: File.exist?("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbunuywgr.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gtyflxaszn.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtwcmyhneo.html

Py:   os.remove("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtnggqsrcn.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtucaueqbi.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtjlwzbjur.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.tanke756.top/Article/details/gtztczkkfm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtvadvhmim.html

Go:   os.Remove("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtazwwhzud.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtcnvptffu.html

C#:   File.Delete("a.txt");
来源：http://dali.c1oappe.top/Article/details/gtvtmxelut.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gtcbhxuxwv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtwbksmxrl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gticjtqahm.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtsghhrics.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtnvahrwsj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtpqbdaqrz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zycfv.cn/Article/details/gtnvpmtxuj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jqgufenzy.top/Article/details/gtdqkwuvhl.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.iojbl.cn/Article/details/gtcqouupyh.html

[F08] 遍历目录
来源：http://dali.0kj1m.cn/Article/details/gtmztewqdq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenzaomai.com/Article/details/gtxuuyvacm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtythspdty.html

JS:   fs.readdirSync("dir")
来源：http://dali.hnqzz.top/Article/details/gtdicfulbx.html

TS:   fs.readdirSync("dir")
来源：http://dali.dashuyun.cn/Article/details/gtevjqpcgn.html


<!-- 参考信息 -->