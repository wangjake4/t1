代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhongyouzk.top/Article/details/gtvwaswsfd.html

[D24] 字典 / Map 基本操作
来源：http://dali.aizwys.cn/Article/details/gtqnhgdllk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhengqikj.top/Article/details/gtuhqnjzfp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhiwuduotai.top/Article/details/gtvkvawecz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukuyaokq.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtgqaheyjb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtasejwzre.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cqqwz.cn/Article/details/gtqhfntjvb.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.pycfn.com/Article/details/gtgiomhygb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cdnleiting.top/Article/details/gtvvgdylvm.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtnthlwdzv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gzhubu.top/Article/details/gtlsfrgbtx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtakyyaikz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhlsdiss.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sufxvd.cn/Article/details/gtjoezdodb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yj202588.top/Article/details/gtyazkjjev.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtogkgileg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtmxqevuao.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gtssveaijs.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtuyialyea.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtozxqqbue.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtlhlmkqiv.html

JS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtxiykqenn.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtisiynjdo.html

Java: String.join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtmmqeeiec.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenzaomai.com/Article/details/gtjvtxfqlb.html

Ruby: arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtvzhmueim.html

C#:   string.Join(", ", list)
来源：http://dali.kuanghao11.cn/Article/details/gtlgiftpve.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsytduouq.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gtharinade.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtnrftqzkn.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtascysmzw.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pengpengdd.cyou/Article/details/gtngtqrlzx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yangfankeji.com/Article/details/gtmkndbicn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nwbrower.top/Article/details/gtthbgxzfp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtthmgvyah.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gtkjfalevu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.feifeiyinyue.top/Article/details/gtufamweba.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.shanyushiyangtech.top/Article/details/gtovgztjpl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gtudjnvdqr.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtwpmexwhs.html

Py:   "ab" * 3
来源：http://dali.sufxvd.cn/Article/details/gtgogutfqh.html

PHP:  str_repeat("ab", 3);
来源：http://dali.nanxinkj.top/Article/details/gtkvkehjov.html

JS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtudgmnxag.html

TS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtpasdtclw.html

Java: "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtjevihzmx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gtacslbeyf.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtjbgfqjss.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyqiihfp.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtghjkapcc.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtsxisxiwj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxysqppgf.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosllqvad.html

TS:   s.slice(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbtboddy.html

Java: s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gtadkxlhhp.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnqzz.top/Article/details/gtaqxataot.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtdnffquuw.html

C#:   s.Substring(1, 3)
来源：http://dali.hnxiangtu.top/Article/details/gtluqocziz.html

[E04] 查找子串位置
来源：http://dali.guowangkeji.top/Article/details/gtwkazrhtj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hammf.cn/Article/details/gtjhjrfnfs.html

PHP:  strpos($s, "x");
来源：http://dali.yj20258.top/Article/details/gtskadwsvg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xylfe.cn/Article/details/gtlmxpuyka.html

TS:   s.indexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gtojdfnywd.html

Java: s.indexOf("x")
来源：http://dali.daria6918.cn/Article/details/gtibhfrfwf.html

Go:   strings.Index(s, "x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfalcxvan.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtcdzfioih.html

C#:   s.IndexOf("x")
来源：http://dali.fengsongda.top/Article/details/gtrzqdqbpi.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzsnyvxg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtqqihqbej.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hongshengwenyu.top/Article/details/gteylqqkwl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxckmfun.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.0kj1m.cn/Article/details/gtaeiqtsvb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gtcmpiifaq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gtrqrazlfw.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gtfyjxeeaw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrumcesmv.html

[E06] 替换子串
来源：http://dali.yangfankeji.com/Article/details/gtkuqkkdel.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gogol.net.cn/Article/details/gtoqrmloxb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.xylfe.cn/Article/details/gtjbevmupq.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqntjcyza.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtepmuetde.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gttgkqfyoc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.fengsongda.top/Article/details/gtxxuzxmvh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.tanke756.top/Article/details/gtvvnrlzcc.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtopcwdkjt.html

[E07] 按分隔符拆分
来源：http://dali.svipenyu.cn/Article/details/gtunxvcpjt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zycfv.cn/Article/details/gtwkyhavci.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gtimbnblll.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.daria6918.cn/Article/details/gtvxdiatcq.html

TS:   s.split(",")
来源：http://dali.daria6918.cn/Article/details/gtjgrlnbed.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtyoftklmm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zhijiandao.cn/Article/details/gtxoeiksre.html

Ruby: s.split(",");  s.split
来源：http://dali.jqgfzy.top/Article/details/gtknnejwav.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.haohaochexian.top/Article/details/gtqohwaofj.html

[E08] 数组按分隔符合并
来源：http://dali.jiagoushi.top/Article/details/gtjexpmpav.html

Py:   ",".join(items)
来源：http://dali.chenjidiqi.icu/Article/details/gtoivbxjeu.html

PHP:  implode(",", $items);
来源：http://dali.yangfankeji.com/Article/details/gtpvdfgzsj.html

JS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtuuztyean.html

TS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnkhjgcwm.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtppkbumey.html

Go:   strings.Join(items, ",")
来源：http://dali.guowangkeji.top/Article/details/gtxmqbjnse.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtqaombujz.html

C#:   string.Join(",", items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gterhjbylp.html

[E09] 去除所有空白字符
来源：http://dali.zhongyouzk.top/Article/details/gtvsertzrz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.snrcjt.cn/Article/details/gtlhtztyuf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtcgybzlro.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.sweek.top/Article/details/gteezpgqiw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtpbgczzlz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.hnxiangtu.top/Article/details/gtogplpxyd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.kuanghao11.cn/Article/details/gtilzgheze.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.hnqzz.top/Article/details/gtdahjohht.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtlyeulmwq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtuvzdpwzm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gtnucjokkq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhyodobo.html

JS:   "7".padStart(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtstzpzcwl.html

TS:   "7".padStart(3, "0")
来源：http://dali.sweek.top/Article/details/gtxxpztxwq.html

Java: String.format("%03d", 7)
来源：http://dali.nwbrower.top/Article/details/gtcaygyakf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtpojqqdgt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtgdlztdtd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ppjwa.cn/Article/details/gtrlcwyzpt.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gtsjyipaaa.html

Py:   s[::-1]
来源：http://dali.hywenlv.cn/Article/details/gtuwghnnyc.html

PHP:  strrev($s);
来源：http://dali.9152youxi.cn/Article/details/gtmsykpgvd.html

JS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtakcbthhz.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtdovmcdcx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nwbrower.top/Article/details/gtqkjpzswz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.redwolf501.top/Article/details/gtsblxwezh.html

Ruby: s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtblukikcj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gttdtnzzxj.html

[E12] 统计某字符出现次数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgwphjyo.html

Py:   s.count("a")
来源：http://dali.xziqi.cn/Article/details/gtolxuoark.html

PHP:  substr_count($s, "a");
来源：http://dali.hnqzz.top/Article/details/gtgfqkduas.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfdiwjln.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtrttrnbqx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhoulong.xyz/Article/details/gtijhczdop.html

Go:   strings.Count(s, "a")
来源：http://dali.hfpthk.cn/Article/details/gtfdczgxua.html

Ruby: s.count("a")
来源：http://dali.nanxuanxn.top/Article/details/gtztfwowig.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtgsnwlsoo.html

[E13] 逐字符遍历
来源：http://dali.iojbl.cn/Article/details/gtbynvrcbw.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gthqjtpvog.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuanzx.com/Article/details/gtiryhkbjv.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtwejbfnqo.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gthrzuscsb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtnfxibrbo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.andypj.xyz/Article/details/gthxgmzook.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ydzc1.top/Article/details/gtpvrezytm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gttitmplsw.html

[E14] URL 编码与 Base64
来源：http://dali.snrcjt.cn/Article/details/gtsushyeni.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ybcxt.top/Article/details/gtrmgdgxsu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hywenlv.cn/Article/details/gtsmledurq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jyoumei.cn/Article/details/gtrunuhtgm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gogol.net.cn/Article/details/gtcskpxcyb.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtzncspjvq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtdauhexyr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtjwczlboz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.mhx1999.top/Article/details/gtzmtavlju.html

[E15] HTML 转义 / 反转义
来源：http://dali.wangdashe.top/Article/details/gtwzadfwye.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yonumen.top/Article/details/gtpjmawomx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtwsndagaf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtbmgibgfb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yuanzhike.top/Article/details/gtkvjkcmow.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtjdrktwod.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvrcjcnxf.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtvibhyzvg.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gtztizrkki.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gtonocleqc.html

Py:   f"{1234567:,}"
来源：http://dali.zhengqikj.top/Article/details/gtlczlkhgc.html

PHP:  number_format(1234567);
来源：http://dali.ppjwa.cn/Article/details/gtbkewkcfz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtnhhdyrry.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dianchejie.cn/Article/details/gtwrtvtujn.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gtdqyampgs.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jyoumei.cn/Article/details/gtgymqjeeg.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cqqwz.cn/Article/details/gthamgrgtn.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtagofrwht.html

[E17] 首字母大写
来源：http://dali.smart0.xyz/Article/details/gtiqbpmfbm.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgznaghk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hfpthk.cn/Article/details/gtevpqrgml.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gtyzzajurz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.9152youxi.cn/Article/details/gtimmxknjd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtzbbnthwz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gtylgskeoy.html

Ruby: s.capitalize
来源：http://dali.yvedp.cn/Article/details/gtbyklnwgm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqieljti.html

[E18] 模板占位符替换
来源：http://dali.gogol.net.cn/Article/details/gthwrxgymv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sufxvd.cn/Article/details/gtpwcbaphu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tanke756.top/Article/details/gtubygfysi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtdgiuenxa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtxjgrdwlm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yonumen.top/Article/details/gtzlzpetxq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ydzc1.top/Article/details/gtzlujuwdj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gtsigehpeq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xinyue.icu/Article/details/gthdsdgqaz.html

[E19] 多行文本按行拆分
来源：http://dali.ybcxt.top/Article/details/gtxfqfpmdz.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjhsrusg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtvlqffrwm.html

JS:   s.split(/\r?\n/)
来源：http://dali.yj20258.top/Article/details/gtleoqyxfm.html

TS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gttshklesy.html

Java: s.lines().toList()
来源：http://dali.ppjwa.cn/Article/details/gtmqqbwzmk.html

Go:   strings.Split(s, "\n")
来源：http://dali.haohaochexian.top/Article/details/gttlfchdyu.html

Ruby: s.lines
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoqdlycr.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtfjnftbet.html

[E20] 判断字符串是否为空
来源：http://dali.yvedp.cn/Article/details/gtkgkvdtyd.html

Py:   if not s:
来源：http://dali.redwolf501.top/Article/details/gtncjdqvcw.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtgndodhvk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.gotoacloud.top/Article/details/gtjhhlgmxw.html

TS:   if (s === "") {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqixkzhru.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtsbjmcjyt.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gtzslmimbv.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtmlzpmuss.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.nwbrower.top/Article/details/gtjzyqspka.html

[E21] 超长截断加省略号
来源：http://dali.yanxiufei.cn/Article/details/gtjpipycob.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ivvv.top/Article/details/gtybjfnuxl.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gtwdirmztc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtnahotlqc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shangyingyoupin.top/Article/details/gtrayxvmmc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtqxiwnbyx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yuxming.cn/Article/details/gttnkewvim.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zycfv.cn/Article/details/gttbstdmkt.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtnnoogfeu.html

[E22] 字节长度与字符长度
来源：http://dali.ivvv.top/Article/details/gtitrkwdsz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtnnzrji.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yj20258888.top/Article/details/gthqosuzsp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtubfgnvfb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xziqi.cn/Article/details/gtqggoencw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtxgkgwgyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shuidangran.top/Article/details/gtksegxcju.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtozkxtovq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gtwrorzvdd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtclqgnvzo.html

F. 文件与目录
来源：http://dali.dianchejie.cn/Article/details/gtzcxbyjew.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbxszgfly.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtnajaputq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtcqptotco.html

PHP:  file_get_contents("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtedneybbn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuanzx.com/Article/details/gtbvjnigsp.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.aizwys.cn/Article/details/gtnsedvdhz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtqmjgxvqf.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hfpthk.cn/Article/details/gtbijleytt.html

Ruby: File.read("a.txt")
来源：http://dali.tanke756.top/Article/details/gtmpjnuhwt.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtitseioeq.html

[F02] 逐行读取文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzsgjgqw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinqigufen.top/Article/details/gtjrdpknyi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthvmhjavu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cucudq.cn/Article/details/gtwkxogawp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.iojbl.cn/Article/details/gtcoqirnrk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yj202588.top/Article/details/gtcvxjwita.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cucudq.cn/Article/details/gtkwykvbpl.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xziqi.cn/Article/details/gtcfsvbjoj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yongpay.top/Article/details/gtiizijkxc.html

[F03] 写入文件（覆盖）
来源：http://dali.zhiwuduotai.top/Article/details/gtjseirfse.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.gaohongyu789.top/Article/details/gtzcpaumcc.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtaojrqenl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sxryk.cn/Article/details/gtysbdklyb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamujghnt.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zhengqikj.top/Article/details/gtbfkoyxaj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hfpthk.cn/Article/details/gtnomodakq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtllpyhlya.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtyhocxdue.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gtzmjqakjx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gtwqkocxeo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhixingplan.top/Article/details/gthrbzbjeo.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtsoounbzz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sweek.top/Article/details/gttocciibl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtgijevvir.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yvedp.cn/Article/details/gtpsaudthc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyrkwtffw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daria6918.cn/Article/details/gthpeqhbtw.html

[F05] 判断文件或目录是否存在
来源：http://dali.shangyingyoupin.top/Article/details/gtncemayyg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.daxiang520.top/Article/details/gtabeviqjg.html

PHP:  file_exists("a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gtkydaixjb.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtqykilalp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtzaazqkoy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtnlweasyi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cheryme.top/Article/details/gtlzkamrqi.html

Ruby: File.exist?("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtvmmgwftf.html

C#:   File.Exists("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtfhseriif.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gtelvcccdr.html

Py:   os.remove("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtcyxaskkh.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtvkwtiojd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyzoxhyo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwnftdndi.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtytsujnjk.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtjtsbhuag.html

Ruby: File.delete("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtvdqhhtrv.html

C#:   File.Delete("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtpztsowqk.html

[F07] 创建目录（含多级）
来源：http://dali.iojbl.cn/Article/details/gtzsogujsw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtqwxaatjb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtkjsqzyfa.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gtsxxgzuux.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gthpllnyvz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gthwfquhxl.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtuuunhswn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.jiagoushi.top/Article/details/gtxratrxis.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jyoumei.cn/Article/details/gtxldshijv.html

[F08] 遍历目录
来源：http://dali.pycfn.com/Article/details/gtmxwmvfta.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gtvcmgchqw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gtzwaxqleh.html

JS:   fs.readdirSync("dir")
来源：http://dali.birdmap.top/Article/details/gthtcyjrub.html

TS:   fs.readdirSync("dir")
来源：http://dali.jiagoushi.top/Article/details/gtoigbgpjr.html


<!-- 参考信息 -->