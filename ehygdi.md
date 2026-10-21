代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtkxahzwhd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.aizwys.cn/Article/details/gtjjvpaapa.html

Go:   // 手写循环
来源：http://dali.zhoulong.xyz/Article/details/gtblxpfivj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.pycfn.com/Article/details/gtodampbcb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtdatkciyh.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtvtneqlzq.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtgadgxqda.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jiagoushi.top/Article/details/gtpieovwmu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shuidangran.top/Article/details/gttdhbrkjw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtqtwqawjj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gtwfollydo.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtzgcgsmka.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aizwys.cn/Article/details/gtvrjmmbsg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gtwkbdhvww.html

[D25] Set 集合去重与交并差
来源：http://dali.jiagoushi.top/Article/details/gtumqeejkp.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.birdmap.top/Article/details/gtrgdfuvnr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhongyouzk.top/Article/details/gtghntrnrm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtpumsrtyr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xuanzx.com/Article/details/gtpgyfbowt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnxiangtu.top/Article/details/gttzqrfwim.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yonumen.top/Article/details/gthsfvpfhm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.9152youxi.cn/Article/details/gtgrttfgjv.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtxwxodyxo.html

[D26] 数组转字符串
来源：http://dali.fengsongda.top/Article/details/gtmaffldok.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtlkyzfyby.html

PHP:  implode(", ", $arr);
来源：http://dali.ehwqpu.com/Article/details/gtkmhdprtm.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtzfcoyqya.html

TS:   arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtgcxgdsha.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhycezuu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinqigfzy.top/Article/details/gtylzmxobu.html

Ruby: arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gthmvqqrra.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtvkicernx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtdtsxqaxi.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtrevwwyxu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtflkgtjur.html

[E01] 拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtrzcvatgk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxinkj.top/Article/details/gtnzxyoznt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yanxiufei.cn/Article/details/gtfvllxrts.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hywenlv.cn/Article/details/gtistactfk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zdqjudy.top/Article/details/gthijojtoe.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jiagoushi.top/Article/details/gtxmohssok.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guowangkeji.top/Article/details/gtsqachlgg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gtgafmkojl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblxlnbch.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtjfsvbwkw.html

Py:   "ab" * 3
来源：http://dali.hysaishi.cn/Article/details/gtvoaxqgsa.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jlsjyb.cn/Article/details/gtcunakzfq.html

JS:   "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtxppggwjg.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtbzoetsvb.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtgnolyvcb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtxoluscpt.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtqwxttcvl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gtebvnwubi.html

[E03] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtqnvoogjo.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hywenlv.cn/Article/details/gtijgmpbvr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtvalurgda.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.meibo888.top/Article/details/gtugytkgdo.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtifeswojw.html

Java: s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtgwretkuy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtoyabbwbs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtauejvwgg.html

C#:   s.Substring(1, 3)
来源：http://dali.nwbrower.top/Article/details/gthrdgdyic.html

[E04] 查找子串位置
来源：http://dali.sweek.top/Article/details/gtnqzeaxgl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhoulong.xyz/Article/details/gtiogjdakc.html

PHP:  strpos($s, "x");
来源：http://dali.jlsjyb.cn/Article/details/gtbcegphtp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtodxokfwo.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gtfrtgrzxy.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtutljjulz.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtsmxfmsse.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtumxxvubq.html

C#:   s.IndexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtzyrdrjgp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixobihdh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258.top/Article/details/gtvdvjhusd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gttwycwhjx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtlthmkmhh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258888.top/Article/details/gtfegffemf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtjbplctlu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.smart0.xyz/Article/details/gtokvvxtzq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.andypj.xyz/Article/details/gtayhwraqw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gtnquctnsd.html

[E06] 替换子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtleddpyru.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtdapiaffp.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtmddrnure.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.cucudq.cn/Article/details/gtjlfwegfu.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtyksrgqud.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gthwujfzbw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gtjlpdjcib.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtwjjtzarw.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtdmerfzco.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtftkbjcqg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.c1oappe.top/Article/details/gtgktlehex.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.chenzaomai.com/Article/details/gttymeoqqg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yonumen.top/Article/details/gtmsxoeryw.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtwtavsoxt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtptplulgi.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gtzrekdysg.html

Ruby: s.split(",");  s.split
来源：http://dali.zhengqikj.top/Article/details/gtzxcsnail.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.cqqwz.cn/Article/details/gtxihtwgnz.html

[E08] 数组按分隔符合并
来源：http://dali.tanke756.top/Article/details/gtgthopqhl.html

Py:   ",".join(items)
来源：http://dali.yj202588.top/Article/details/gtfvypddvb.html

PHP:  implode(",", $items);
来源：http://dali.pycfn.com/Article/details/gtmieldlct.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtbyblzqyr.html

TS:   items.join(",")
来源：http://dali.gogol.net.cn/Article/details/gthqiojlnf.html

Java: String.join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gthcknrtji.html

Go:   strings.Join(items, ",")
来源：http://dali.quarkkingdee.top/Article/details/gtxwhqhkcw.html

Ruby: items.join(",")
来源：http://dali.gzhubu.top/Article/details/gtiiyhppee.html

C#:   string.Join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gtxohjlhsg.html

[E09] 去除所有空白字符
来源：http://dali.tian-w.cn/Article/details/gtopdvrdfi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.nanxinkj.top/Article/details/gtdrcqmwoy.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtuzzfvnhx.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtxzsuhgjb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gttxgufkgo.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.bjfxy.top/Article/details/gtaxbqykng.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.cucudq.cn/Article/details/gtmujmgacp.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtqkrddfqv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtnlmcdell.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtpqbklvmz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtcnpokuyw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdtczpaa.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtwykkomnd.html

TS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gthaoytpom.html

Java: String.format("%03d", 7)
来源：http://dali.hnxiangtu.top/Article/details/gtmcondwdu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gtxzncckad.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzmbfgcn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.svipenyu.cn/Article/details/gtxmugukks.html

[E11] 反转字符串
来源：http://dali.zycfv.cn/Article/details/gtgciustly.html

Py:   s[::-1]
来源：http://dali.vqdsnc.cn/Article/details/gtmqwpbyjq.html

PHP:  strrev($s);
来源：http://dali.daria6918.cn/Article/details/gtujmlwsrb.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtrdaucfxd.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtyiwcwgoa.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtxsvniuxs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tianlin.xyz/Article/details/gtaumjrgyk.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gtoehfrcru.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtbcxkyhfi.html

[E12] 统计某字符出现次数
来源：http://dali.zhiwuduotai.top/Article/details/gtgxkoefcr.html

Py:   s.count("a")
来源：http://dali.jinqigfzy.top/Article/details/gtndisahzs.html

PHP:  substr_count($s, "a");
来源：http://dali.gaohongyu789.top/Article/details/gtvoykatwx.html

JS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtdgekbwol.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtswzupxqo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ybcxt.top/Article/details/gtuwbnbyjs.html

Go:   strings.Count(s, "a")
来源：http://dali.chenzaomai.com/Article/details/gtennztjqq.html

Ruby: s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gtwfeyzwgj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gtbucqrmzp.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtpfvyslgc.html

Py:   for ch in s: print(ch)
来源：http://dali.svipenyu.cn/Article/details/gtlvccyspw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xuetiantiany.cn/Article/details/gtygexaaed.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtbxzldloi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtisvjsvxh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guannengcc.top/Article/details/gtvvlmjies.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtlqrdnfeu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhiwuduotai.top/Article/details/gthylxxarb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hammf.cn/Article/details/gtxvrflmdk.html

[E14] URL 编码与 Base64
来源：http://dali.guowangkeji.top/Article/details/gtdbemrdqu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gtfnmurhcd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqekgtuvh.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gthvbwkgmu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.fengsongda.top/Article/details/gtfxllalty.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangshuangyany.cn/Article/details/gteiewuanq.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guowangkeji.top/Article/details/gtqwmvdjxw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtfvhtibbt.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jyoumei.cn/Article/details/gtwwcjohwt.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gtixxmumez.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.tanke756.top/Article/details/gtzjglisfh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtkbyvzcqc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtppderaxx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtkitsgisw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhixingplan.top/Article/details/gtcfympinc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.cucudq.cn/Article/details/gtngtkbmuw.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtiechwtqv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhpggsfm.html

[E16] 数字千分位
来源：http://dali.hongshengwenyu.top/Article/details/gthnnpqpfa.html

Py:   f"{1234567:,}"
来源：http://dali.cashguo.top/Article/details/gtepebkbyj.html

PHP:  number_format(1234567);
来源：http://dali.cashguo.top/Article/details/gtroyntibv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuanzx.com/Article/details/gtdvfezdzm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtzrziotwq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuanzhike.top/Article/details/gtpkgqalrh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.smart0.xyz/Article/details/gtcfywsyue.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gtnogkyxjw.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtxoyymhmb.html

[E17] 首字母大写
来源：http://dali.cdnleiting.top/Article/details/gtopgmtadc.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.nwbrower.top/Article/details/gtvjprdfvf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zdqjudy.top/Article/details/gtizwvhjsl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnqzz.top/Article/details/gtqugodxmq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtpdzakhvf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtqouohtvt.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gthpipotmx.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gthcghsfqt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.quarkkingdee.top/Article/details/gtepwgexzi.html

[E18] 模板占位符替换
来源：http://dali.aibaodan.cn/Article/details/gtxgtbpowc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.9152youxi.cn/Article/details/gtbqwltacq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.9152youxi.cn/Article/details/gtdtnfksge.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtgeflqarb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj202588.top/Article/details/gtjzjpojly.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.tanke756.top/Article/details/gtbsmginkf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtrsztulnf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtervihawq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtstbxykij.html

[E19] 多行文本按行拆分
来源：http://dali.nanxinkj.top/Article/details/gtecufwriv.html

Py:   s.splitlines()
来源：http://dali.hywenlv.cn/Article/details/gtxymihjcm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gttqlcxtgb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gtznoqqmoh.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtxxbedshj.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gtjxclgmre.html

Go:   strings.Split(s, "\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtxsddvyex.html

Ruby: s.lines
来源：http://dali.feifeiyinyue.top/Article/details/gtcokzbfrk.html

C#:   s.Split('\n')
来源：http://dali.cucudq.cn/Article/details/gtiakobnml.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gtbvqkeawo.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gtzubzjnqt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.daxiang520.top/Article/details/gtdozlbkss.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtfazrhfod.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gttzcnabwx.html

Java: if (s.isEmpty()) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtefkzfgjc.html

Go:   if s == "" {}
来源：http://dali.sufxvd.cn/Article/details/gtuhfwexru.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtdqzdwjaq.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gthmopnodt.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gtzovyohuo.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhiwuduotai.top/Article/details/gtiwlpwhbp.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gtmzywkint.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtwkoupgrv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtqtfpzjcs.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gttgiclzpy.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtzuczvohr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtkjqygrdq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfjxzehn.html

[E22] 字节长度与字符长度
来源：http://dali.aizwys.cn/Article/details/gtdjmxkxvl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gttdzwddqi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gttxeajcpi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtbdbweuqv.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtuoalkcpv.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ehwqpu.com/Article/details/gtowealguw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtzteigngp.html

Ruby: s.bytesize;  s.length
来源：http://dali.gogol.net.cn/Article/details/gtrhutgfuq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.guowangkeji.top/Article/details/gtcbzqojfw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqbqcwbfe.html

F. 文件与目录
来源：http://dali.gzhubu.top/Article/details/gtntjwcdgz.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtysikmpos.html

[F01] 读取整个文件
来源：http://dali.wangshuangyany.cn/Article/details/gtqfksrgau.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtojpzaqsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtxzmfemam.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.kuanghao11.cn/Article/details/gtkfzxstzz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gtqollbznw.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtqkoeldzq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yuxming.cn/Article/details/gtsfybaoro.html

Ruby: File.read("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtejmzlioy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.havefunace.top/Article/details/gtumomcqkp.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtpvrhxgzk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tian-w.cn/Article/details/gtxqhiwyys.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jqgfzy.top/Article/details/gtxicpqokm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ybcxt.top/Article/details/gtvkwjkydd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gtlstjbiwa.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.svipenyu.cn/Article/details/gtyrxuldvl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gtswdnsmec.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shzxlz.cn/Article/details/gtnvobwbgl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.vqdsnc.cn/Article/details/gtcmkavixv.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtdyselrin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.dianchejie.cn/Article/details/gtvrlnwmiu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtqlervzht.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.birdmap.top/Article/details/gtvrbgjnsh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jyoumei.cn/Article/details/gtlagfrtqp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtauovegyb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapwrfdwd.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtbmeuggqh.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtxhexdrns.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxvbdwxj.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrxfwlhnp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gthkhrzpvg.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gtoynrmzyc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gtyowlcykv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cucudq.cn/Article/details/gtfdogpktp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtrfpjhshc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gtcmcqlhhz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yonumen.top/Article/details/gtkyqgnhkm.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangshuangyany.cn/Article/details/gtggmmtziz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cheryme.top/Article/details/gtddqogejj.html

PHP:  file_exists("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtwqphcrsn.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtrwvmjius.html

TS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtozqxjbua.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zhoulong.xyz/Article/details/gtjcpejbmd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.havefunace.top/Article/details/gtsidckvht.html

Ruby: File.exist?("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtvehxjopn.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtbmfudouv.html

[F06] 删除文件
来源：http://dali.shuidangran.top/Article/details/gthotxdxfy.html

Py:   os.remove("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtulqenszm.html

PHP:  unlink("a.txt");
来源：http://dali.mhx1999.top/Article/details/gtyswilica.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtrvlijejs.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gtygxblwdh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ivvv.top/Article/details/gttvqaaanw.html

Go:   os.Remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtlmltxtjl.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtotjdqetg.html

C#:   File.Delete("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtflqaicip.html

[F07] 创建目录（含多级）
来源：http://dali.shzxlz.cn/Article/details/gtcitvwawx.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gtzrcpsnbw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cucudq.cn/Article/details/gtljuzhnnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hysaishi.cn/Article/details/gtadnqlikg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jlsjyb.cn/Article/details/gtjlxyrgkj.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.cqqwz.cn/Article/details/gtxvsqsdbg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.smart0.xyz/Article/details/gttjfsqivm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.bjfxy.top/Article/details/gtozpjeena.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaltfoms.html

[F08] 遍历目录
来源：http://dali.meibo888.top/Article/details/gtggnvudti.html


<!-- 参考信息 -->