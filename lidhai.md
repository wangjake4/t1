代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.fengsongda.top/Article/details/gtfavqzqke.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtvgocurbn.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.birdmap.top/Article/details/gtpcagnbek.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xuanzx.com/Article/details/gtdyjpvheq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtizqhlbjr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtwigasgnl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgufenzy.top/Article/details/gtsoooxiyt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtxqttnbrc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ybcxt.top/Article/details/gtnsvjanbr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dashuyun.cn/Article/details/gtxpjkicfy.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gtuteotohg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.quarkkingdee.top/Article/details/gtkygvkxze.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtpmqbbiaw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gttpuubamj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gthgcnthpa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtdhdpicer.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.dashuyun.cn/Article/details/gtfovboifo.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtnkrabsuv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtjdtuqmgl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxvasepmz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtrehzpbcr.html

PHP:  implode(", ", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtyibnkbtl.html

JS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtfzoldhgp.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtmllazmcl.html

Java: String.join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtftotmnqn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtdepccnbs.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gtfdonlkkb.html

C#:   string.Join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gthwwyirkk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtrudnhbol.html

E. 字符串处理
来源：http://dali.hfpthk.cn/Article/details/gtkctrnazn.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwtjzozqs.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtgkolzafn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yongpay.top/Article/details/gtcxabhnzs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtbbzacmij.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtgetqugev.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.feifeiyinyue.top/Article/details/gtjzfiwxxj.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtxdixcnmu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gtjdjbcdwn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ehwqpu.com/Article/details/gtidztolwa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtqqpsbmls.html

[E02] 重复字符串
来源：http://dali.hammf.cn/Article/details/gtqtdcbrbm.html

Py:   "ab" * 3
来源：http://dali.gogol.net.cn/Article/details/gtycicnzqb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xylfe.cn/Article/details/gtsttloado.html

JS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtxzfslwmt.html

TS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtezuljwox.html

Java: "ab".repeat(3)
来源：http://dali.jqgufenzy.top/Article/details/gtfkswbvfl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.bjfxy.top/Article/details/gtuzyeaerp.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsakcdqlz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtjjmicztx.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gtrcjdaepl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtqdsdicqf.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtxzxrqajd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yueranfly.top/Article/details/gtnodrtadh.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtktdyjajr.html

Java: s.substring(1, 4)
来源：http://dali.jiagoushi.top/Article/details/gtqjxujvnv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtbhqielyg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.wangdashe.top/Article/details/gtafzjupdj.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtxpyjqtsw.html

[E04] 查找子串位置
来源：http://dali.zhixingplan.top/Article/details/gtupyiwnay.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtemjnpknv.html

PHP:  strpos($s, "x");
来源：http://dali.gogol.net.cn/Article/details/gtetxeuuti.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gotoacloud.top/Article/details/gtyjvlfstx.html

TS:   s.indexOf("x")
来源：http://dali.sufxvd.cn/Article/details/gtmdvcxrhc.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtiamjcjaa.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtjtfyycan.html

Ruby: s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtpkeyamds.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtwycllhos.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jiagoushi.top/Article/details/gtifjwwqyn.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cashguo.top/Article/details/gtvkkjvrbc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnqzz.top/Article/details/gtavwnmvjc.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gthskfybcy.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.nwbrower.top/Article/details/gtorndvnut.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtftwfzmbx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.tianlin.xyz/Article/details/gtbgmcpxzn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuxming.cn/Article/details/gtsfuqckqv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtjmqptdwb.html

[E06] 替换子串
来源：http://dali.yj20258.top/Article/details/gtbslsoghh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtjwtayega.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtsarmwnpu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtohegjbcw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtnkzmkagf.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuixpgikt.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtrhxadeyj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnleqghq.html

C#:   s.Replace("a", "b")
来源：http://dali.tanke756.top/Article/details/gtkmxycbmp.html

[E07] 按分隔符拆分
来源：http://dali.zdqjudy.top/Article/details/gtpbrpbyoj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.0kj1m.cn/Article/details/gtafmmlmyn.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtdiqmcfnr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.meibo888.top/Article/details/gtaeidsyhl.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtrwlkoepd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xuanzx.com/Article/details/gtvncjnrxg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yuanzhike.top/Article/details/gtmhvswlrp.html

Ruby: s.split(",");  s.split
来源：http://dali.cdnleiting.top/Article/details/gtphrdzcnj.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jyoumei.cn/Article/details/gtlddletqu.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldynryyu.html

Py:   ",".join(items)
来源：http://dali.zhongyouzk.top/Article/details/gtctfekfcw.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtsxizvyzz.html

JS:   items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gtpyaumtou.html

TS:   items.join(",")
来源：http://dali.zhoulong.xyz/Article/details/gtpjrmbhaj.html

Java: String.join(",", items)
来源：http://dali.ydzc1.top/Article/details/gtzfbnsnrq.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtereyrisp.html

Ruby: items.join(",")
来源：http://dali.hywenlv.cn/Article/details/gtclsaqndq.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtvtdomhnt.html

[E09] 去除所有空白字符
来源：http://dali.yj20258.top/Article/details/gteoqacwzj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hysaishi.cn/Article/details/gtuyihvymg.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgykpbamo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.pycfn.com/Article/details/gttfkrsmcb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtitkvsohv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.guowangkeji.top/Article/details/gtbkawcdrg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtlhqhchxy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sysykeji.top/Article/details/gtzdiswqoj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.bjfxy.top/Article/details/gthykxfylv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnxiangtu.top/Article/details/gtvhnubmoc.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gtjkoeirpv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gtggnhbvkh.html

JS:   "7".padStart(3, "0")
来源：http://dali.kuanghao11.cn/Article/details/gtdviwmngn.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtdiaatyva.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtjsogyrht.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.aibaodan.cn/Article/details/gtgzntmhqi.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtvrzxayzs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtmulcjigm.html

[E11] 反转字符串
来源：http://dali.wangdashe.top/Article/details/gtoeelclii.html

Py:   s[::-1]
来源：http://dali.snrcjt.cn/Article/details/gtfimaehop.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtdymxpegt.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtweyvxter.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gthvdiwgij.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zycfv.cn/Article/details/gtqwjkxudx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtewglwtbx.html

Ruby: s.reverse
来源：http://dali.cqqwz.cn/Article/details/gtnybcjthp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtsnwftdxj.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gthbpaeved.html

Py:   s.count("a")
来源：http://dali.shuidangran.top/Article/details/gtgfembipj.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtlnjzuzvr.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtawhlxviq.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtbdchkrzc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtvelohtto.html

Go:   strings.Count(s, "a")
来源：http://dali.jianghu66.top/Article/details/gtlaeqsszg.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtuurhpvun.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtzvnmanpx.html

[E13] 逐字符遍历
来源：http://dali.zhixingplan.top/Article/details/gtyoyumyqk.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtnytpysoj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gtkfdlkpel.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtctxtuizc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gtobwuawjg.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtvaoggatg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.guannengcc.top/Article/details/gtfilrnqov.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gtugrxkdzk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fzhhl.top/Article/details/gtibzbekbi.html

[E14] URL 编码与 Base64
来源：http://dali.birdmap.top/Article/details/gtykxvrwdy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gtlcujtpqd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guowangkeji.top/Article/details/gtzxblugje.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gtpmzybsrs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zdqjudy.top/Article/details/gtxxgrzbec.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sweek.top/Article/details/gthrljudhh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtoxyclhgc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtkpuvrlfe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtiowcrxvw.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtghankytn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.svipenyu.cn/Article/details/gtehlmgqbh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtdabaezvk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cashguo.top/Article/details/gtrsbfgmhk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtgqfkcomx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtrvsmvmnr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yangfankeji.com/Article/details/gtrxzhbfjd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.nwbrower.top/Article/details/gtyjyswadf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jyoumei.cn/Article/details/gtvyjkbxck.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtoclxqhce.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtqrkirysw.html

PHP:  number_format(1234567);
来源：http://dali.wangshuangyany.cn/Article/details/gtimqnawxh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllrlkoep.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtfieuxvae.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtzefknrci.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhiwuduotai.top/Article/details/gtndihmvmk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yj20258888.top/Article/details/gtatdoctno.html

C#:   1234567.ToString("N0")
来源：http://dali.zhongyouzk.top/Article/details/gtrsuspgps.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtlqsejsbv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtvehcxqlv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sweek.top/Article/details/gtndqztmaz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxinkj.top/Article/details/gtonvntvqe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtwlqahdxt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ivvv.top/Article/details/gtuuwdndqe.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gthfbqfxys.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtvczduxdu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtkwgirtag.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtjmoetooa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gtlsrgdyyi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuanzhike.top/Article/details/gthgbupbof.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtralkdclf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtobzeooix.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gttellchjt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtijwfzmlg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gotoacloud.top/Article/details/gtkasoajbi.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.chenzaomai.com/Article/details/gtlsyfqati.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gttfhfcuou.html

Py:   s.splitlines()
来源：http://dali.c1oappe.top/Article/details/gtganifvba.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtzddvrges.html

JS:   s.split(/\r?\n/)
来源：http://dali.cucudq.cn/Article/details/gtdthhonwf.html

TS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gtciljvpgx.html

Java: s.lines().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtdbqojrxj.html

Go:   strings.Split(s, "\n")
来源：http://dali.hywenlv.cn/Article/details/gtsuczjmzy.html

Ruby: s.lines
来源：http://dali.gaohongyu789.top/Article/details/gtvbtohtlk.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtilspbvhp.html

[E20] 判断字符串是否为空
来源：http://dali.sxryk.cn/Article/details/gtdssgpjup.html

Py:   if not s:
来源：http://dali.xinyue.icu/Article/details/gtuafaeqvf.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlewoghg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.bjfxy.top/Article/details/gtooaupwqg.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtdadhtcdm.html

Java: if (s.isEmpty()) {}
来源：http://dali.tian-w.cn/Article/details/gtvcxkemzf.html

Go:   if s == "" {}
来源：http://dali.tanke756.top/Article/details/gtjzepczkz.html

Ruby: if s.empty?
来源：http://dali.yj202588.top/Article/details/gtkeaabcnk.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fzhhl.top/Article/details/gtnrycnanb.html

[E21] 超长截断加省略号
来源：http://dali.yangfankeji.com/Article/details/gtlojmcpom.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnqzz.top/Article/details/gtaeiynnot.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenjidiqi.icu/Article/details/gtnyjtyive.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtqbhoaorm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtdljnwgpw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gtsdrinddr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gtckzbmsjz.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtuepwrukg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtemzihqgp.html

[E22] 字节长度与字符长度
来源：http://dali.shangyingyoupin.top/Article/details/gtgqyklcep.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtnzfespva.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtwejtmica.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtsbvuwkyd.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gtyypbsirm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigfzy.top/Article/details/gtsuywavho.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gtlbknihpw.html

Ruby: s.bytesize;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtfsbrkzmg.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtchmkasnt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcdfkvzai.html

F. 文件与目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhhbtrta.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtevnvgoqz.html

[F01] 读取整个文件
来源：http://dali.316326.xyz/Article/details/gtfcaqrgxl.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.birdmap.top/Article/details/gtsefwrnwr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtdnwyusar.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shzxlz.cn/Article/details/gtittiesjr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtntvqalal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hammf.cn/Article/details/gtdaetzwrh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtwiuzliwy.html

Ruby: File.read("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtxewefrlg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtqxbynvwe.html

[F02] 逐行读取文件
来源：http://dali.ppjwa.cn/Article/details/gtgtndizwf.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtouifokir.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gtxgrcmedk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gtfxgfznvm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtuanzkzny.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.gaohongyu789.top/Article/details/gtpclsgzst.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tanke756.top/Article/details/gtjvajnltb.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.daxiang520.top/Article/details/gtanxcdltk.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yuxming.cn/Article/details/gtokppbxci.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtisodqytc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gzhubu.top/Article/details/gtoljlwhnr.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtphpopzje.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtmkzpeaiq.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtjzmmcpsg.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtnvzcstrz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.sufxvd.cn/Article/details/gtvbblvght.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yangfankeji.com/Article/details/gtgqchpxvu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtohdibrek.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gtnqzgjvwl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gthtveusin.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gtnwmyvixy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xinyue.icu/Article/details/gtexvjciqx.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtwhpqokua.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.iojbl.cn/Article/details/gtxorvdrjb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmnzlzim.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtsvqnakvp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhongyouzk.top/Article/details/gtbnhufwcp.html

[F05] 判断文件或目录是否存在
来源：http://dali.redwolf501.top/Article/details/gtkpcyznds.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtqfpjhegg.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtksavucac.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtgpxacnjz.html

TS:   fs.existsSync("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtrkgatwyj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtojijppyr.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.meibo888.top/Article/details/gtlctbqpip.html

Ruby: File.exist?("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtuhjurdox.html

C#:   File.Exists("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtheprsqqm.html

[F06] 删除文件
来源：http://dali.quarkkingdee.top/Article/details/gtvzwzkrnl.html

Py:   os.remove("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtsjbmfxhn.html

PHP:  unlink("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gtaibvfepa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gteatspayi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfihwrkri.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsxfhaiw.html

Go:   os.Remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtokbanzxi.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtypeqnsfe.html

C#:   File.Delete("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtlcrqyceg.html

[F07] 创建目录（含多级）
来源：http://dali.wangdashe.top/Article/details/gtyxvdsgsq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtvihtxuym.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.birdmap.top/Article/details/gtuwdvxqmt.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cucudq.cn/Article/details/gtwgtnqlgf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtaalrmpmm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ppjwa.cn/Article/details/gtfgrxmlbw.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtsdqgxkbr.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.svipenyu.cn/Article/details/gtfydfnmsd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gttfrcwuza.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtcyexzope.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gtbkykanwz.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtcwlmudgs.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtpmzhmzyx.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtupkwodso.html


<!-- 参考信息 -->