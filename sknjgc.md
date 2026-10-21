代发 wailian999

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.kuanghao11.cn/Article/details/gtnuzjebla.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shangyingyoupin.top/Article/details/gttcmoabca.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtkrpnasii.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gtefavovsq.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cqqwz.cn/Article/details/gtdbxkkeyg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.tian-w.cn/Article/details/gtqygzkozk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sysykeji.top/Article/details/gthepebljl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zycfv.cn/Article/details/gtcjaklxfh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gtcejsdhdy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.aizwys.cn/Article/details/gtjbltkpwl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zdqjudy.top/Article/details/gtuyflhnol.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtelvhjifa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtrlqbkgbu.html

PHP:  implode(", ", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gthsfsptoc.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtxexjrdtu.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhstywqp.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwldgrht.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtiaiofxrb.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtuaxeonls.html

C#:   string.Join(", ", list)
来源：http://dali.tianlin.xyz/Article/details/gtkfocyece.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtprvluqnb.html

E. 字符串处理
来源：http://dali.yueranfly.top/Article/details/gtvamqbnyb.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtdcrmygcs.html

[E01] 拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtwkkstoxb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.feifeiyinyue.top/Article/details/gtywkkzokx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gaohongyu789.top/Article/details/gttrgujexw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yangfankeji.com/Article/details/gtocrmxffy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtobkbcdit.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gogol.net.cn/Article/details/gtwnfkjred.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jiagoushi.top/Article/details/gthqazaahb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtpwzgerbx.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqjmtgot.html

[E02] 重复字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkddbulr.html

Py:   "ab" * 3
来源：http://dali.xinyue.icu/Article/details/gtcqvupowe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigufen.top/Article/details/gtjuybhvsj.html

JS:   "ab".repeat(3)
来源：http://dali.gaohongyu789.top/Article/details/gthqokddzf.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gteesfyocl.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtifleiyuj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtppymgsqg.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkpqmcvg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ehwqpu.com/Article/details/gtmudzwvju.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtjetijkwr.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.xuanzx.com/Article/details/gtlonzmjsc.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gtilhtjvsc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtxehokjqx.html

TS:   s.slice(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtgxrjbyua.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtrguoswdb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shuidangran.top/Article/details/gtmiqodahb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zdqjudy.top/Article/details/gthgsvoknw.html

C#:   s.Substring(1, 3)
来源：http://dali.ydzc1.top/Article/details/gtxsmgtxut.html

[E04] 查找子串位置
来源：http://dali.yj20258.top/Article/details/gtmqcazbfm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhixingplan.top/Article/details/gtsywayqcc.html

PHP:  strpos($s, "x");
来源：http://dali.aizwys.cn/Article/details/gttbkqjppy.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtxlhferag.html

TS:   s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtwjjovzzw.html

Java: s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtuytcvwfe.html

Go:   strings.Index(s, "x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkctdwtaj.html

Ruby: s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtuyjlwqnj.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtlcwyyuai.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.guannengcc.top/Article/details/gtttqxvwov.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ydzc1.top/Article/details/gtrlhwuasn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.birdmap.top/Article/details/gttvaaeltr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangdashe.top/Article/details/gtikoqzabr.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tanke756.top/Article/details/gtoazpkwwj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtkmbxfsdd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinqigufen.top/Article/details/gtyibhlupi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhengqikj.top/Article/details/gtxvnksowf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtusgqfqfm.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtguegigzt.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtwygkpabm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gteobcmwls.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtkrjxpvmp.html

TS:   s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtmbcjkthu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtxspncshh.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtbcppamjp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtzmphdqmv.html

C#:   s.Replace("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtozvfdlyb.html

[E07] 按分隔符拆分
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjzydrzt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.vqdsnc.cn/Article/details/gtqerklfrx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtwmpszwhc.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkvxkdob.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtlkewaykw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.mhx1999.top/Article/details/gtqjominap.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtsmlpufrp.html

Ruby: s.split(",");  s.split
来源：http://dali.wangdashe.top/Article/details/gtbncjgaax.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtzsugrahr.html

[E08] 数组按分隔符合并
来源：http://dali.guowangkeji.top/Article/details/gtqbfphrbo.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtdzwbnmhj.html

PHP:  implode(",", $items);
来源：http://dali.jiagoushi.top/Article/details/gtosuhiqgs.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtmntisyun.html

TS:   items.join(",")
来源：http://dali.ivvv.top/Article/details/gtjwybcwme.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtgceolwir.html

Go:   strings.Join(items, ",")
来源：http://dali.jianghu66.top/Article/details/gtqfgynjls.html

Ruby: items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gtchktizng.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtjhltyxym.html

[E09] 去除所有空白字符
来源：http://dali.andypj.xyz/Article/details/gttcnvjbbl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yueranfly.top/Article/details/gtaxsomafq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gtdmpgqffm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gttiigefyy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtugambayw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nwbrower.top/Article/details/gtxtxtejkk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.jiagoushi.top/Article/details/gtlzupbxxd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gttzblwmvd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shuidangran.top/Article/details/gtnflbgeke.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hysaishi.cn/Article/details/gtbkobdgug.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gttqqehczz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hnxiangtu.top/Article/details/gtgmtcngxd.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtaiuwdozj.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtcspwkimf.html

Java: String.format("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtkderlgbg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtmvxibzml.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtrfiwmrkl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gtiqruxlnl.html

[E11] 反转字符串
来源：http://dali.aibaodan.cn/Article/details/gtpiylfbnd.html

Py:   s[::-1]
来源：http://dali.gzhubu.top/Article/details/gtkzewhtgz.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtxivwkirp.html

JS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtopjmxvkl.html

TS:   [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtddtjakkp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtfvfegh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hongshengwenyu.top/Article/details/gthenkfmzm.html

Ruby: s.reverse
来源：http://dali.daxiang520.top/Article/details/gtrznjbibv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ydzc1.top/Article/details/gtkrmcbeqf.html

[E12] 统计某字符出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbpjkkxn.html

Py:   s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtcccgjcud.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gtuasubvfr.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtnypypvav.html

TS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gttetiqcjh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigfzy.top/Article/details/gtmhteswau.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gthjzluuby.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gtbcjlgfpm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtuktommez.html

[E13] 逐字符遍历
来源：http://dali.cqqwz.cn/Article/details/gtxbcqdkzm.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtocjmlywk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtztvnzrwf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.fengsongda.top/Article/details/gtvjmhegpc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gtfcrsvgom.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.sysykeji.top/Article/details/gtbwyqtgyt.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gtuhzzeevx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.mhx1999.top/Article/details/gtiquvvoax.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtiqbtluhh.html

[E14] URL 编码与 Base64
来源：http://dali.dashuyun.cn/Article/details/gtyzwoadra.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ivvv.top/Article/details/gthnwbbubn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ehwqpu.com/Article/details/gtbltnylop.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gtfrrcxbpo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hnxiangtu.top/Article/details/gtfeiimtiv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gtxeedjrap.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtoegzgrmi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhongyouzk.top/Article/details/gtvdrbixvz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.daria6918.cn/Article/details/gtzwqdciht.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gtkskbsgsm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jlsjyb.cn/Article/details/gtsveahvvx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gtvgsajbmg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gtojdeshpy.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtgpqioqgm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtspvnzvmq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtoddtflcj.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtkbyfwbfg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtkxouhswl.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtelwulcjv.html

Py:   f"{1234567:,}"
来源：http://dali.nanxinkj.top/Article/details/gtxaojbigg.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gtrhajzlwa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtzmnumwtf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtjwwyyulx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtdzsydfqa.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gttdttblfx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258.top/Article/details/gtijxyqdyy.html

C#:   1234567.ToString("N0")
来源：http://dali.gaohongyu789.top/Article/details/gtfoptrwjx.html

[E17] 首字母大写
来源：http://dali.yueranfly.top/Article/details/gtppwbnxhe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cdnleiting.top/Article/details/gtnlawsuwb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.redwolf501.top/Article/details/gtyxquwszx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gteljwfbnp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtulvowaxo.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtffprtygm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yangfankeji.com/Article/details/gtptkchrgd.html

Ruby: s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gtnbpesvye.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkzdvjca.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtcxhglegr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ehwqpu.com/Article/details/gtozuugeyh.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xuanzx.com/Article/details/gtpewwtvvl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtcozjhqkf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.meibo888.top/Article/details/gtuxuxeupl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgigkppfm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gttiemnfoq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.quarkkingdee.top/Article/details/gtajiiymxt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtcuygkbkv.html

[E19] 多行文本按行拆分
来源：http://dali.chenzaomai.com/Article/details/gtqjopwsue.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gthexxjkim.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtrwaqnbdt.html

JS:   s.split(/\r?\n/)
来源：http://dali.smart0.xyz/Article/details/gtcpxxkoli.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gthativxcj.html

Java: s.lines().toList()
来源：http://dali.iojbl.cn/Article/details/gtekkxuthe.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhijiandao.cn/Article/details/gtpalibgru.html

Ruby: s.lines
来源：http://dali.shanyushiyangtech.top/Article/details/gtudziszed.html

C#:   s.Split('\n')
来源：http://dali.sweek.top/Article/details/gtevoexxcp.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtinibakix.html

Py:   if not s:
来源：http://dali.sxryk.cn/Article/details/gtatnhbirb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.havefunace.top/Article/details/gtbrbvlcqg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.snrcjt.cn/Article/details/gtbvxrbhot.html

TS:   if (s === "") {}
来源：http://dali.kuanghao11.cn/Article/details/gtdmsuarvf.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtyxsoaehf.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtiicacita.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gtrhilkffw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.redwolf501.top/Article/details/gtozsjoeeu.html

[E21] 超长截断加省略号
来源：http://dali.bjfxy.top/Article/details/gtwhgatvua.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jianghu66.top/Article/details/gtdssvxdoi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yonumen.top/Article/details/gtaoocateo.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtxzcujjhl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtqfzqhtsv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtviegpwag.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcurzvvs.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtepxxoiga.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxinkj.top/Article/details/gtcmlqvmjc.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtdeeciffg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtleqxanzu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtznzombyx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtepezcgag.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guowangkeji.top/Article/details/gtytflbgac.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fengsongda.top/Article/details/gtwajdiulj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ppjwa.cn/Article/details/gtbjwbhdfa.html

Ruby: s.bytesize;  s.length
来源：http://dali.nwbrower.top/Article/details/gtmndsmntv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenlongwang.top/Article/details/gthepcxdkk.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtygaauukw.html

F. 文件与目录
来源：http://dali.tianlin.xyz/Article/details/gtedkobzxo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfrvgzsyd.html

[F01] 读取整个文件
来源：http://dali.chenzaomai.com/Article/details/gtmjeilwgz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hfpthk.cn/Article/details/gtuvpobdcf.html

PHP:  file_get_contents("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtebseavqg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.fzhhl.top/Article/details/gtgtuwlcnr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqfqlddi.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtsccfapzf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gtbmgipjpy.html

Ruby: File.read("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtugyfobnl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtfkygdmjt.html

[F02] 逐行读取文件
来源：http://dali.zdqjudy.top/Article/details/gtoyboelve.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.9152youxi.cn/Article/details/gtgbengqmq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlquukgbp.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgoybrvmh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqnzevry.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gtimrmuean.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hammf.cn/Article/details/gtpsjqeomw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gtwpqwmybn.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.0kj1m.cn/Article/details/gtnkrnqrzz.html

[F03] 写入文件（覆盖）
来源：http://dali.yueranfly.top/Article/details/gtqkgmyazn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hammf.cn/Article/details/gtefaqxyba.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.wangdashe.top/Article/details/gttilqhyku.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtvujzlzxi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gtdnmkabph.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtoiregjka.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hywenlv.cn/Article/details/gtldfarrro.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtxyxwbfti.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtzlsenteo.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtutdmoaaa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhengqikj.top/Article/details/gtnsqwxdji.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yangfankeji.com/Article/details/gtghodbzfx.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtvtceyeyf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.meibo888.top/Article/details/gtpkcdlbpg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.haohaochexian.top/Article/details/gtzuqltwou.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xylfe.cn/Article/details/gtptarlewb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ppjwa.cn/Article/details/gtdvkvyvrr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxmbzhou.html

[F05] 判断文件或目录是否存在
来源：http://dali.cheryme.top/Article/details/gteuhfkosh.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgufenzy.top/Article/details/gtkamcoobq.html

PHP:  file_exists("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtqmcmqpuw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtctzcqpqo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjrnhrhax.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtvxbaecgy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jyoumei.cn/Article/details/gtpharfyis.html

Ruby: File.exist?("a.txt")
来源：http://dali.birdmap.top/Article/details/gtefseuwtx.html

C#:   File.Exists("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtmmkutvkk.html

[F06] 删除文件
来源：http://dali.nwbrower.top/Article/details/gtirrkfquv.html

Py:   os.remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkamoosdz.html

PHP:  unlink("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtdlrklfeb.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtoerqetah.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gthyglrtdx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlowsmph.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlmtedmvz.html

Ruby: File.delete("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtydnnzbvr.html

C#:   File.Delete("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtfgqxhggk.html

[F07] 创建目录（含多级）
来源：http://dali.jyoumei.cn/Article/details/gtqzrdstpm.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtklqecety.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtraejoodc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtxkkaspyq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtwtwjfend.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtoorxoqjv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gtptjkbgjp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hysaishi.cn/Article/details/gtlcbubqys.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtxmttdsbx.html

[F08] 遍历目录
来源：http://dali.shzxlz.cn/Article/details/gtlsgufwwf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ppjwa.cn/Article/details/gtjwmpoqdl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fengsongda.top/Article/details/gtitjqawtx.html

JS:   fs.readdirSync("dir")
来源：http://dali.hfpthk.cn/Article/details/gtqpgubtat.html

TS:   fs.readdirSync("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtteljxujb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtjpfwjnoo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gthukprgfq.html

Ruby: Dir.children("dir")
来源：http://dali.guannengcc.top/Article/details/gtbvugfocz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.fzhhl.top/Article/details/gthrrzbofg.html

[F09] 获取文件大小
来源：http://dali.shangyingyoupin.top/Article/details/gtobpgjvju.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtsmbsyeag.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkzfenrad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnqzz.top/Article/details/gtweqylkhc.html


<!-- 参考信息 -->