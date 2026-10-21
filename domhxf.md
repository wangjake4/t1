代发 wailian999

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtipibojyw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.sysykeji.top/Article/details/gtmcawgpjc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhengqikj.top/Article/details/gtmbvqbgxr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtftfmylvt.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gtrfynbbco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxbjgrpd.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtmgssmure.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.sxryk.cn/Article/details/gtxadcycsh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj20258.top/Article/details/gtbwilxwtu.html

[D24] 字典 / Map 基本操作
来源：http://dali.cheryme.top/Article/details/gtvfjbqsga.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtxthljskm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnqzz.top/Article/details/gtesfrgdmx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zdqjudy.top/Article/details/gtxvkhdmon.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtziejtyap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gterdiebst.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtanvessns.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gtoecckumq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuanzx.com/Article/details/gtuqaljfxw.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gtvbszfvoj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtrfgvawir.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jqgufenzy.top/Article/details/gtzbzgcgyt.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gtojnfxuta.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.ybcxt.top/Article/details/gtwowmmgou.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.dashuyun.cn/Article/details/gtzotqjkbx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.sysykeji.top/Article/details/gtiafzwtum.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ivvv.top/Article/details/gtnwfhnysp.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ydzc1.top/Article/details/gtvljyolpz.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gtaobljnkh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtkpwstiwd.html

PHP:  implode(", ", $arr);
来源：http://dali.tianlin.xyz/Article/details/gtynfenpsf.html

JS:   arr.join(", ")
来源：http://dali.yueranfly.top/Article/details/gtqonweydk.html

TS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtgpwtgavx.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gtwangavpq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtcpicjvrx.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyjvatmq.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gtylzylzjq.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstyhfaig.html

E. 字符串处理
来源：http://dali.xziqi.cn/Article/details/gtwyixbetl.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtulcdwtiz.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtllguavzj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cdnleiting.top/Article/details/gtfeifcvzv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.haohaochexian.top/Article/details/gtpjqamdjs.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtrebqywzj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.birdmap.top/Article/details/gtmjtoomyy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtrjqcygjc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hfpthk.cn/Article/details/gtoyjqczgk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtrumbnwlp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtcdxpvpnl.html

[E02] 重复字符串
来源：http://dali.yonumen.top/Article/details/gtuyiaeele.html

Py:   "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtyxkegzvt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gtuilqegme.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gtojrpcrxe.html

TS:   "ab".repeat(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtujfckiib.html

Java: "ab".repeat(3)
来源：http://dali.mhx1999.top/Article/details/gtzbbnmoys.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cashguo.top/Article/details/gtfegxxlrl.html

Ruby: "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gturnnxncy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuetiantiany.cn/Article/details/gtyxxmwcrc.html

[E03] 截取子串
来源：http://dali.ydzc1.top/Article/details/gtjnvmdyta.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.snrcjt.cn/Article/details/gtgbiakmtn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtnfrfesnw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtipcgerre.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtirerivpe.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtzjoztege.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258888.top/Article/details/gtzeyexoqt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gtewsncdkj.html

C#:   s.Substring(1, 3)
来源：http://dali.gotoacloud.top/Article/details/gtofwbzowi.html

[E04] 查找子串位置
来源：http://dali.hywenlv.cn/Article/details/gtvifjdbsd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ehwqpu.com/Article/details/gtmaisajlw.html

PHP:  strpos($s, "x");
来源：http://dali.zhoulong.xyz/Article/details/gtlwgaixue.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtvkeslpga.html

TS:   s.indexOf("x")
来源：http://dali.hnqzz.top/Article/details/gtycpmqzbu.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtaycnlbid.html

Go:   strings.Index(s, "x")
来源：http://dali.hfpthk.cn/Article/details/gtsmxtyerm.html

Ruby: s.index("x")
来源：http://dali.yongpay.top/Article/details/gtjcjusdoa.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtizjkpcne.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtpcdekqtd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtorhozjdh.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtwfhuvtkq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtoyfnkohe.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.birdmap.top/Article/details/gtzovmpdce.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.nwbrower.top/Article/details/gtexmvkxxt.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jiagoushi.top/Article/details/gtnozehdtx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.fzhhl.top/Article/details/gticboiqay.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gtryeufzdy.html

[E06] 替换子串
来源：http://dali.ybcxt.top/Article/details/gtqhdeoipa.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtzdwclwyb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gtbzsaehsl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtyiyuvnjr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gtybvmdhcp.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.birdmap.top/Article/details/gthixhvijw.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqgpqloez.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gttxjzyoan.html

C#:   s.Replace("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtajehpfdt.html

[E07] 按分隔符拆分
来源：http://dali.jianghu66.top/Article/details/gtwqxxqkmr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtwbvcvwsi.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtgqykndem.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.chenzaomai.com/Article/details/gttzdukhto.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtkokvyray.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ybcxt.top/Article/details/gtfjezgelp.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yueranfly.top/Article/details/gtaxwsntyt.html

Ruby: s.split(",");  s.split
来源：http://dali.dianchejie.cn/Article/details/gtlutoyebo.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtsyypcurb.html

[E08] 数组按分隔符合并
来源：http://dali.daria6918.cn/Article/details/gtakanowua.html

Py:   ",".join(items)
来源：http://dali.ehwqpu.com/Article/details/gtjabysjdt.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtiqubhbhc.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtrpghozej.html

TS:   items.join(",")
来源：http://dali.andypj.xyz/Article/details/gtmawsldbg.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtyatfemhx.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtfeldbgfk.html

Ruby: items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtuabftlif.html

C#:   string.Join(",", items)
来源：http://dali.hnxiangtu.top/Article/details/gthxtabvia.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gttnvoycnj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ydzc1.top/Article/details/gttbdjsetz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hysaishi.cn/Article/details/gtdhbidnyz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtcpykkzgn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gteqbhxbqd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yongpay.top/Article/details/gtvlsnxgir.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gteqsvbjym.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.kuanghao11.cn/Article/details/gtgwbnrrvv.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocauimxh.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtxaqjxwsg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtlsakhbco.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fengsongda.top/Article/details/gtmsxoeeiz.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmgpexio.html

TS:   "7".padStart(3, "0")
来源：http://dali.hongshengwenyu.top/Article/details/gtjdzyzbgh.html

Java: String.format("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtosbhdkax.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtclkiaeyy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gtiwfujcjl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtkklbaxui.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtyyfvmywk.html

Py:   s[::-1]
来源：http://dali.nwbrower.top/Article/details/gtoipdlduf.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzdkuooch.html

JS:   [...s].reverse().join("")
来源：http://dali.daxiang520.top/Article/details/gtpozcghso.html

TS:   [...s].reverse().join("")
来源：http://dali.zhiwuduotai.top/Article/details/gtoyoflglg.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtolbypzvr.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtagsefzlc.html

Ruby: s.reverse
来源：http://dali.dashuyun.cn/Article/details/gtddvsnmyk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.smart0.xyz/Article/details/gtcfyjiuly.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtcmunteqn.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtwnfyalhg.html

PHP:  substr_count($s, "a");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemgjwvfo.html

JS:   s.split("a").length - 1
来源：http://dali.nanxuanxn.top/Article/details/gtrcpirfub.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtckktwjju.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnqzz.top/Article/details/gtrvmnxmdg.html

Go:   strings.Count(s, "a")
来源：http://dali.jinqigfzy.top/Article/details/gtumcbxxay.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtysaszrnz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gaohongyu789.top/Article/details/gtxrvbkkdg.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtkgydrovg.html

Py:   for ch in s: print(ch)
来源：http://dali.dashuyun.cn/Article/details/gtjqtpjjuj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yuxming.cn/Article/details/gtdrjszomh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtzuqthcye.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gttjlymidy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gtvpyjxdwk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtfgsnkqte.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.svipenyu.cn/Article/details/gtlrzdbtys.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtnjpjzqnv.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtiqvmtpvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxuanxn.top/Article/details/gtjqbswfol.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tianlin.xyz/Article/details/gtoqwzdjyd.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.smart0.xyz/Article/details/gturtchldc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.andypj.xyz/Article/details/gtaamukwai.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.smart0.xyz/Article/details/gtcqgxyxpg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gtmpdolnei.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtbgpyiiye.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.snrcjt.cn/Article/details/gtrzdcipgo.html

[E15] HTML 转义 / 反转义
来源：http://dali.nanxuanxn.top/Article/details/gtiebylgjn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhongyouzk.top/Article/details/gtgljqcmqk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtvukdgobm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.tianlin.xyz/Article/details/gtccipdpqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.daria6918.cn/Article/details/gtftmzoiqa.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gtqfvrcinl.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yonumen.top/Article/details/gtfjecdois.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtuodrbhqb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.mhx1999.top/Article/details/gtdwvggesc.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gtwajntgsr.html

Py:   f"{1234567:,}"
来源：http://dali.pycfn.com/Article/details/gtfmuwnjpq.html

PHP:  number_format(1234567);
来源：http://dali.sufxvd.cn/Article/details/gtgdphmjpd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtnpkfblbs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.0kj1m.cn/Article/details/gtmyqtbapu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtjcgzkyrc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.feifeiyinyue.top/Article/details/gtkkwxmofr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.havefunace.top/Article/details/gtwaelmlsn.html

C#:   1234567.ToString("N0")
来源：http://dali.haohaochexian.top/Article/details/gtvtyeermu.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gtfwgudkhh.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yonumen.top/Article/details/gtqbvalrmv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.snrcjt.cn/Article/details/gtwbrpqzdl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtidbmdwli.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.snrcjt.cn/Article/details/gtnkmrfzoe.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.9152youxi.cn/Article/details/gtbabmbyvn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cdnleiting.top/Article/details/gtmdlsnawn.html

Ruby: s.capitalize
来源：http://dali.hongshengwenyu.top/Article/details/gtfseqnexu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.xziqi.cn/Article/details/gtczovuify.html

[E18] 模板占位符替换
来源：http://dali.zhijiandao.cn/Article/details/gtvyckhuxr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtzwhveoam.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xziqi.cn/Article/details/gtoesaqqds.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtstkbfifk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shangyingyoupin.top/Article/details/gtjnqwuxpt.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtnpvbalsa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtoshokior.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gtuzaxkipr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xylfe.cn/Article/details/gtmsodpkel.html

[E19] 多行文本按行拆分
来源：http://dali.xziqi.cn/Article/details/gtwhiatffy.html

Py:   s.splitlines()
来源：http://dali.iojbl.cn/Article/details/gtenhmlchy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shzxlz.cn/Article/details/gtkhnrnmwe.html

JS:   s.split(/\r?\n/)
来源：http://dali.pycfn.com/Article/details/gtcczxbdvi.html

TS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyhvqatm.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxwagusg.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gtzhrtpvlb.html

Ruby: s.lines
来源：http://dali.mhx1999.top/Article/details/gtzkjtoayg.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gtzgcojfpe.html

[E20] 判断字符串是否为空
来源：http://dali.c1oappe.top/Article/details/gtlszmjugz.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gtotdlqlxh.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtvrvvxzvb.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenlongwang.top/Article/details/gtbhgjasyr.html

TS:   if (s === "") {}
来源：http://dali.vqdsnc.cn/Article/details/gtefjjqezu.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtwporunma.html

Go:   if s == "" {}
来源：http://dali.cqqwz.cn/Article/details/gtyrgreggn.html

Ruby: if s.empty?
来源：http://dali.jiagoushi.top/Article/details/gtspivvhgo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.kuanghao11.cn/Article/details/gtudrbvllr.html

[E21] 超长截断加省略号
来源：http://dali.meibo888.top/Article/details/gtsvspikrm.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.iojbl.cn/Article/details/gttvpgvaze.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtwycqmfiz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtntjwaylv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cqqwz.cn/Article/details/gtasuwnvql.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtqdzwtqxa.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhoulong.xyz/Article/details/gtpudhdvzn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ybcxt.top/Article/details/gtjkqswpcf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtoqmglths.html

[E22] 字节长度与字符长度
来源：http://dali.mhx1999.top/Article/details/gtgkwosmvt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jinqigufen.top/Article/details/gthtqrlkxe.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtgkcvgwgn.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gturlaylxc.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gtoptbkfgc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.mhx1999.top/Article/details/gtvaxwuqbi.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gtauuolgwa.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtgqgcfske.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.redwolf501.top/Article/details/gtfchyexij.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtmbbwsqoo.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtzhzlipdm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtcqmgacll.html

[F01] 读取整个文件
来源：http://dali.tanke756.top/Article/details/gtylwxuiqg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.bjfxy.top/Article/details/gtcxmvodan.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj202588.top/Article/details/gtbjdmojjb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yonumen.top/Article/details/gtvgcgcatz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tanke756.top/Article/details/gtumslshyc.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gteyjjqins.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.dianchejie.cn/Article/details/gtckyjdjrz.html

Ruby: File.read("a.txt")
来源：http://dali.cashguo.top/Article/details/gtrqsdcgow.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtkixopyti.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gtqyeyjkzu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.quarkkingdee.top/Article/details/gtalubnrsq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.dashuyun.cn/Article/details/gtoavadutz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigfzy.top/Article/details/gthfgdwmtm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtbzxqwhge.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngecovsf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtypcmwcst.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.iojbl.cn/Article/details/gtjieljfav.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtzsgvprnb.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtydygeppn.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gtcufsetcu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gogol.net.cn/Article/details/gtveynjjop.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258888.top/Article/details/gtzunejwqj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hfpthk.cn/Article/details/gtcnyyxnna.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnqzz.top/Article/details/gtfdrvhvho.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gtbblpqzqx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhiwuduotai.top/Article/details/gtzrmvrxjy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gtqhbcbxmf.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gtqsitvycl.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.316326.xyz/Article/details/gtltacnken.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gtapnuynka.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtpulgszdl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtyryasitt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yj202588.top/Article/details/gtejbdpoig.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hfpthk.cn/Article/details/gtuvbtfdxo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.bjfxy.top/Article/details/gtmwmcsaiz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.xinyue.icu/Article/details/gtoccmaatl.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gteuaezsqo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hnqzz.top/Article/details/gtgetagkyv.html

PHP:  file_exists("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtbyhweboa.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzjjgodw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtgppiamgy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.kuanghao11.cn/Article/details/gtudoycuap.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gteigbuxau.html

Ruby: File.exist?("a.txt")
来源：http://dali.tanke756.top/Article/details/gtrblelpul.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtklfrgddh.html

[F06] 删除文件
来源：http://dali.cdnleiting.top/Article/details/gtofyhyuwq.html

Py:   os.remove("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtgtllgpko.html

PHP:  unlink("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtswhfiaym.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtnyhdbjsi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtekiwztcw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtxtbtaxkb.html

Go:   os.Remove("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtgnsvavkm.html

Ruby: File.delete("a.txt")
来源：http://dali.redwolf501.top/Article/details/gttisreewo.html

C#:   File.Delete("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtqasrqulf.html

[F07] 创建目录（含多级）
来源：http://dali.chenlongwang.top/Article/details/gtjbxxrzvh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjvcqkyx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.andypj.xyz/Article/details/gtapjetgxu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.meibo888.top/Article/details/gtkubzvyzw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtwzvrrtwn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jyoumei.cn/Article/details/gthswalwsg.html


<!-- 参考信息 -->