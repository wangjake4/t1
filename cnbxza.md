代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtxnqyvvmh.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtxyuxgdxt.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtptduxmoe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jiagoushi.top/Article/details/gtfemmhglr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gthaynanuo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhiwuduotai.top/Article/details/gtosdvfhaz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtdquyytfg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ppjwa.cn/Article/details/gtglahzsni.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtufuaavmd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtryntbhia.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258.top/Article/details/gtgtgjfodd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtdzfpugqa.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tanke756.top/Article/details/gtifaqaksi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtejxakdqg.html

[D25] Set 集合去重与交并差
来源：http://dali.bjfxy.top/Article/details/gtfnbwnzjq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gtfionwkel.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnqzz.top/Article/details/gtcnxyrwwu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ehwqpu.com/Article/details/gthnugappe.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.andypj.xyz/Article/details/gtdwkvwsfv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hammf.cn/Article/details/gttqcbsnnv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtnnvyaxbm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.birdmap.top/Article/details/gtqakpbkxu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgfzy.top/Article/details/gtynwqgmge.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtucziioek.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtmfuugcpl.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtroindusx.html

JS:   arr.join(", ")
来源：http://dali.havefunace.top/Article/details/gtshzvphcc.html

TS:   arr.join(", ")
来源：http://dali.shzxlz.cn/Article/details/gtrqjzfyrk.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbtixcaz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gthjgyzodu.html

Ruby: arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gtbvgglrpb.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtcdbpgbzj.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtekrpzubf.html

E. 字符串处理
来源：http://dali.chenzaomai.com/Article/details/gtfeyksvbk.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjuaxfylz.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtzenywfwo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.gaohongyu789.top/Article/details/gteqhydufa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gthprjawfw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.quarkkingdee.top/Article/details/gthgzamczg.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtgeaaaxde.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtujsvvcfq.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ivvv.top/Article/details/gtjljqnuxr.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtjeztdtpp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.andypj.xyz/Article/details/gteppwvuhz.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtjabcmccd.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtxymlzrgn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.pycfn.com/Article/details/gtytikpryb.html

JS:   "ab".repeat(3)
来源：http://dali.nwbrower.top/Article/details/gtbbvfylnx.html

TS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gtlbsiklxu.html

Java: "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtwrnqgvhy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtbsxnyrvp.html

Ruby: "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtjwlcipwt.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnqzz.top/Article/details/gtesgsrkav.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtkqhaimco.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtdifcvjoz.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daria6918.cn/Article/details/gtggxpmlmy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nanxuanxn.top/Article/details/gteajgwxiv.html

TS:   s.slice(1, 4)
来源：http://dali.hammf.cn/Article/details/gtdvihjufy.html

Java: s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtkeplkmne.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtkobbjbmc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jiagoushi.top/Article/details/gtgczmzxen.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gtdftkqfwl.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtczfsrurr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gtnmgzsqdu.html

PHP:  strpos($s, "x");
来源：http://dali.yanxiufei.cn/Article/details/gtgerindjc.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzgxkeovn.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtbflkrkjd.html

Java: s.indexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gtbxxnegwz.html

Go:   strings.Index(s, "x")
来源：http://dali.iojbl.cn/Article/details/gtlkylpxeq.html

Ruby: s.index("x")
来源：http://dali.ybcxt.top/Article/details/gthgceebib.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuijexvn.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.aizwys.cn/Article/details/gtxylaukif.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtszhkmbgn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hnxiangtu.top/Article/details/gtphbcgszd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtdtksirfg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtpmkvyelh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtziwiqxuj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guannengcc.top/Article/details/gtxxqybzaq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtegsbpjgj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.aizwys.cn/Article/details/gtyreomgkf.html

[E06] 替换子串
来源：http://dali.jqgufenzy.top/Article/details/gtljouoxlr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtxbwoxmot.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtsxqozbsv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sufxvd.cn/Article/details/gtiqhzckcs.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqyqwqytx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtlwufmeqc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.andypj.xyz/Article/details/gtwgtypxnn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtmnmukvxt.html

C#:   s.Replace("a", "b")
来源：http://dali.ppjwa.cn/Article/details/gtafnsovnd.html

[E07] 按分隔符拆分
来源：http://dali.yuanzhike.top/Article/details/gtwtonautk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cashguo.top/Article/details/gttgjhwvwa.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gttqpaxaku.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtrfhjuvmk.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gteefavcot.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gogol.net.cn/Article/details/gtpuksgscx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ivvv.top/Article/details/gtbvqwknhx.html

Ruby: s.split(",");  s.split
来源：http://dali.redwolf501.top/Article/details/gtfxaipmuv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xylfe.cn/Article/details/gtikvjsgmu.html

[E08] 数组按分隔符合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gttnrqvwsn.html

Py:   ",".join(items)
来源：http://dali.tanke756.top/Article/details/gtpdbxgfin.html

PHP:  implode(",", $items);
来源：http://dali.zhengqikj.top/Article/details/gtubcaafxg.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtdzzsjpbl.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtyhzcpggz.html

Java: String.join(",", items)
来源：http://dali.tianlin.xyz/Article/details/gtlrumaspz.html

Go:   strings.Join(items, ",")
来源：http://dali.zhengqikj.top/Article/details/gtjmsbxllt.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtrpkimmxk.html

C#:   string.Join(",", items)
来源：http://dali.havefunace.top/Article/details/gttkypwxmb.html

[E09] 去除所有空白字符
来源：http://dali.zhengqikj.top/Article/details/gtetwjaslp.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.dashuyun.cn/Article/details/gtloljrmak.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtunjxbaia.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.guannengcc.top/Article/details/gtrevhrosn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtpztivlie.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gzhubu.top/Article/details/gtcwagvsbi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cqqwz.cn/Article/details/gtcjfousiy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtnomfpzes.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cheryme.top/Article/details/gtmlyxinjj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtzfoqpqba.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtazjsjlom.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hywenlv.cn/Article/details/gtfiaervps.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtuhoayxjl.html

TS:   "7".padStart(3, "0")
来源：http://dali.bjfxy.top/Article/details/gtqiuqrugd.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtdodrwmhy.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtslwvgwap.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtmvqezxap.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hnqzz.top/Article/details/gtdvhbmdos.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqbrgkwy.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gthtzscqmw.html

PHP:  strrev($s);
来源：http://dali.ydzc1.top/Article/details/gthasenpcv.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gteyhzpbjz.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtdhrxwmlu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.iojbl.cn/Article/details/gtzbxiejbv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtlqtvlufu.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtzrierjmg.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gtdjvdtkwx.html

[E12] 统计某字符出现次数
来源：http://dali.guowangkeji.top/Article/details/gtectpfmny.html

Py:   s.count("a")
来源：http://dali.yueranfly.top/Article/details/gtxhuguxhh.html

PHP:  substr_count($s, "a");
来源：http://dali.dashuyun.cn/Article/details/gtzaoqfemp.html

JS:   s.split("a").length - 1
来源：http://dali.zdqjudy.top/Article/details/gtywqygepd.html

TS:   s.split("a").length - 1
来源：http://dali.dianchejie.cn/Article/details/gtbbgegfgm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hywenlv.cn/Article/details/gtsxezjkst.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gthkljudze.html

Ruby: s.count("a")
来源：http://dali.shangyingyoupin.top/Article/details/gtqtjiotpj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tanke756.top/Article/details/gtvkvflksk.html

[E13] 逐字符遍历
来源：http://dali.ehwqpu.com/Article/details/gtipiokxhm.html

Py:   for ch in s: print(ch)
来源：http://dali.gaohongyu789.top/Article/details/gtmkmlzdnx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jlsjyb.cn/Article/details/gtgzsklnwj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yangfankeji.com/Article/details/gtmunmrttx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hammf.cn/Article/details/gtjnmulxzx.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xuanzx.com/Article/details/gtvqalwcgp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtlhjouvzl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.redwolf501.top/Article/details/gtvpcdtdgx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtmajosuvi.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtlvlnezcg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtzaobembf.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jyoumei.cn/Article/details/gtfvkdzgzj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.birdmap.top/Article/details/gtknsrddwk.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphecxwkd.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.gaohongyu789.top/Article/details/gtlzedjozk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gteaicskjn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtgjsdwkfq.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtcetupcuw.html

[E15] HTML 转义 / 反转义
来源：http://dali.daria6918.cn/Article/details/gtsnpttpkx.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tian-w.cn/Article/details/gtpnfvcjnx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtmgcjdlks.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gtpcdrgdfp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.meibo888.top/Article/details/gtpyametxa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yanxiufei.cn/Article/details/gtqmbnguer.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtfksbxygb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.chenlongwang.top/Article/details/gtzntrytzd.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gtkpnfgvni.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gtcgtvoslz.html

Py:   f"{1234567:,}"
来源：http://dali.guowangkeji.top/Article/details/gtmqzmniid.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbthhwpyv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtxwzxcyqk.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cheryme.top/Article/details/gtekjlxrbp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigfzy.top/Article/details/gtqamszpbt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gogol.net.cn/Article/details/gtdubebwyb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtdfihhtmf.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gtqlopxegg.html

[E17] 首字母大写
来源：http://dali.chenjidiqi.icu/Article/details/gtusvihvzn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtlzyfizxg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shuidangran.top/Article/details/gtvnptosir.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.0kj1m.cn/Article/details/gtbgkrbxob.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gttawcwtfr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtucntmbfl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtmyqmfazh.html

Ruby: s.capitalize
来源：http://dali.cheryme.top/Article/details/gtwyaqyxuq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxinkj.top/Article/details/gtrwewviwp.html

[E18] 模板占位符替换
来源：http://dali.9152youxi.cn/Article/details/gtawfaaxlr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtdhpeaajx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.mhx1999.top/Article/details/gtnpxkrqme.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtqusfnaom.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gtlyocjjdm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxaklikq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtzpfsktth.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jlsjyb.cn/Article/details/gtccqcbbaf.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gtimtvuzyt.html

[E19] 多行文本按行拆分
来源：http://dali.yuanzhike.top/Article/details/gtjnfjghms.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtexhnolub.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gtoqllzusw.html

JS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtvgiwssno.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtlxbadirr.html

Java: s.lines().toList()
来源：http://dali.sysykeji.top/Article/details/gtbmdgivxd.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbmnuvnd.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gtgpcxzvrj.html

C#:   s.Split('\n')
来源：http://dali.0kj1m.cn/Article/details/gtpqihwmpz.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gttrneiyxt.html

Py:   if not s:
来源：http://dali.316326.xyz/Article/details/gtynvrlzdk.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtyuaqfrsi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cucudq.cn/Article/details/gtlpgthkrv.html

TS:   if (s === "") {}
来源：http://dali.birdmap.top/Article/details/gtfwtrftkx.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gtmlldlnji.html

Go:   if s == "" {}
来源：http://dali.yj20258.top/Article/details/gtqbuqmfrw.html

Ruby: if s.empty?
来源：http://dali.wangshuangyany.cn/Article/details/gtagbhrpqd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sxryk.cn/Article/details/gtoasnymxz.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gtsluaonmf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guannengcc.top/Article/details/gthvzkszly.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtrycsafvk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtopzqjlwx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtlrmkeort.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtifanvzdx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ybcxt.top/Article/details/gtrrynwnlt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtwcpfwxbm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtjletmmqf.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfatmsrgn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtmiwokplv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtubierywc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtpwllfwrf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtiantdkwz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.sxryk.cn/Article/details/gtueikuirg.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xuetiantiany.cn/Article/details/gtapphgkpq.html

Ruby: s.bytesize;  s.length
来源：http://dali.yangfankeji.com/Article/details/gtwhmwtvoa.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.nanxuanxn.top/Article/details/gtjndrgars.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmsatuouq.html

F. 文件与目录
来源：http://dali.hfpthk.cn/Article/details/gtizugwyiq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtoxgrtqol.html

[F01] 读取整个文件
来源：http://dali.shuidangran.top/Article/details/gtjfrhacbn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yongpay.top/Article/details/gtsfhyxsis.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtbpzgbuzt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yj20258.top/Article/details/gtjgawhxjn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtpxhywslw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtbbeyyism.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yj20258888.top/Article/details/gtzmuxolvl.html

Ruby: File.read("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gteisqbmpv.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gtwaznytja.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtxexsevxh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xziqi.cn/Article/details/gticcozzwi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtrbzclsrm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gthautpwwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtwcwcletc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.mhx1999.top/Article/details/gtuiszzpvp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gtonmekgro.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ppjwa.cn/Article/details/gtcjorislz.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtituuwjde.html

[F03] 写入文件（覆盖）
来源：http://dali.daxiang520.top/Article/details/gtqkakjvnu.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gtlkdpimoy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.svipenyu.cn/Article/details/gtbaeyjiew.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xinyue.icu/Article/details/gtgkxtbkhp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtgqcphqzy.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.316326.xyz/Article/details/gtsoozgdwz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xylfe.cn/Article/details/gtnxyntvag.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtsicsryvr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gtnfamqkom.html

[F04] 追加写入文件
来源：http://dali.wangdashe.top/Article/details/gtdagzeduz.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.wangdashe.top/Article/details/gtvladczcd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtqhitidjb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hammf.cn/Article/details/gthmucrwbb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.snrcjt.cn/Article/details/gtiqqnzvtz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xuanzx.com/Article/details/gttxxocfby.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtlstykryb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtocxkhruc.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gtkpnnsqqb.html

[F05] 判断文件或目录是否存在
来源：http://dali.iojbl.cn/Article/details/gtqczowccw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zycfv.cn/Article/details/gtvpslnygo.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtkjwveext.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtxvdmukez.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyaamerqf.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gteqnsvhef.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtrvkehuda.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gttapikiri.html

C#:   File.Exists("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtsccuxqzh.html

[F06] 删除文件
来源：http://dali.cheryme.top/Article/details/gtlhnjqkzc.html

Py:   os.remove("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtzrdvwwbt.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gtwqyqrptl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtjwnrwhdt.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtuloszzze.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yueranfly.top/Article/details/gtlkwugmmi.html

Go:   os.Remove("a.txt")
来源：http://dali.xziqi.cn/Article/details/gthcpubmgv.html

Ruby: File.delete("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtluhfcupl.html

C#:   File.Delete("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtopfotdgg.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtarbtdmij.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gotoacloud.top/Article/details/gtaljncavy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cashguo.top/Article/details/gttxnytvhr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cqqwz.cn/Article/details/gthoczskms.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtslfdcigv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gtgcjtmmzc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtzkhngyzq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gttakfoooa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xinyue.icu/Article/details/gtzatwaklk.html

[F08] 遍历目录
来源：http://dali.fzhhl.top/Article/details/gtgwwxbhaa.html


<!-- 参考信息 -->