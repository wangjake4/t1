代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.andypj.xyz/Article/details/gtmmgtuubq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.wangdashe.top/Article/details/gtsdmzgoxo.html

Ruby: arr.dup;  arr.clone
来源：http://dali.svipenyu.cn/Article/details/gtqwmtzxec.html

C#:   new List<int>(list);
来源：http://dali.fzhhl.top/Article/details/gtbpmaxyeh.html

[D23] reduce 累积计算
来源：http://dali.smart0.xyz/Article/details/gttkpekbrm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hammf.cn/Article/details/gtyitchbau.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtdayyzxow.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dashuyun.cn/Article/details/gtrjfagssh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtwacxxfbb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jianghu66.top/Article/details/gtuhqmyhzr.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtnjgfpzyh.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gttoblfxqv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.0kj1m.cn/Article/details/gtkucljqrc.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtugazoyor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yongpay.top/Article/details/gtaybnddyo.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.andypj.xyz/Article/details/gtbzyxnzpv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.shzxlz.cn/Article/details/gtfdaffaer.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gtswmenwlu.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.tanke756.top/Article/details/gtlovtetek.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gtzhnedguf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtvadqrxly.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.sufxvd.cn/Article/details/gtbyzgsazw.html

[D25] Set 集合去重与交并差
来源：http://dali.yuxming.cn/Article/details/gtqtukjwbq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gtfbukynev.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.0kj1m.cn/Article/details/gtbxjowzad.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtiavtchei.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hywenlv.cn/Article/details/gtfkoeangd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehejkywg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yangfankeji.com/Article/details/gtynupatvc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtdsdgccmk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuxming.cn/Article/details/gtgmhkdzpl.html

[D26] 数组转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtleayoaro.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gtjhaicmgt.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gtxzkrxkaf.html

JS:   arr.join(", ")
来源：http://dali.nanxuanxn.top/Article/details/gtczprdnjv.html

TS:   arr.join(", ")
来源：http://dali.hywenlv.cn/Article/details/gtkmpafojv.html

Java: String.join(", ", list)
来源：http://dali.gotoacloud.top/Article/details/gtohlpques.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yvedp.cn/Article/details/gtiwpnarnv.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttynyldtt.html

C#:   string.Join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gtdiycarta.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtonnxtztv.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtojckqylr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjlczytwp.html

[E01] 拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gttqtsvywk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtivnljpqm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ppjwa.cn/Article/details/gtygsdvwhg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtytlbxgpk.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gtyorvxsff.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtclsdcrvy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.vqdsnc.cn/Article/details/gtmrlebzmv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.iojbl.cn/Article/details/gtynwfmxdz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xylfe.cn/Article/details/gtggfndnnp.html

[E02] 重复字符串
来源：http://dali.yvedp.cn/Article/details/gtguzghxfj.html

Py:   "ab" * 3
来源：http://dali.yuxming.cn/Article/details/gtwsqssest.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtbmvieiza.html

JS:   "ab".repeat(3)
来源：http://dali.gzhubu.top/Article/details/gtkivkpato.html

TS:   "ab".repeat(3)
来源：http://dali.kuanghao11.cn/Article/details/gthccnafsu.html

Java: "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtamijdhqv.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dashuyun.cn/Article/details/gtjgjjczcq.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtebwjfujw.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258.top/Article/details/gthowudpkx.html

[E03] 截取子串
来源：http://dali.sufxvd.cn/Article/details/gtutaauvhm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jiagoushi.top/Article/details/gtbreqoerp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtvhyxhqua.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gtikaheiwo.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtukayszrh.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtxjfhfkru.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuxming.cn/Article/details/gtsyynlabh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gtycoprsmu.html

C#:   s.Substring(1, 3)
来源：http://dali.tianlin.xyz/Article/details/gtuhzkrwya.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gtmyluaugt.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gtiwrwdrdn.html

PHP:  strpos($s, "x");
来源：http://dali.shuidangran.top/Article/details/gtruaeimqm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gtjhkadhtu.html

TS:   s.indexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gtbopiubht.html

Java: s.indexOf("x")
来源：http://dali.aizwys.cn/Article/details/gtfqceysoy.html

Go:   strings.Index(s, "x")
来源：http://dali.xuetiantiany.cn/Article/details/gtwrsdumgf.html

Ruby: s.index("x")
来源：http://dali.daxiang520.top/Article/details/gtfijqgzqr.html

C#:   s.IndexOf("x")
来源：http://dali.cheryme.top/Article/details/gtoiwgfehc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ydzc1.top/Article/details/gtgexznlge.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtlapvjank.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tian-w.cn/Article/details/gtktzrznyh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtwpenorny.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpbuxqwe.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtijbtktyj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuetiantiany.cn/Article/details/gthednpeiq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.0kj1m.cn/Article/details/gtanakfffz.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtjcnlhklz.html

[E06] 替换子串
来源：http://dali.gaohongyu789.top/Article/details/gtvnizpahl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtvezhyyjx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigfzy.top/Article/details/gtpzizttdz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtnctcznqi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtzxkzbpar.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmoyczheo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.chenlongwang.top/Article/details/gtfmodmnre.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtvvndrpbw.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtziakjsxr.html

[E07] 按分隔符拆分
来源：http://dali.snrcjt.cn/Article/details/gtbrawkhsj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gaohongyu789.top/Article/details/gtcngaklor.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hammf.cn/Article/details/gtkgsreqti.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhijiandao.cn/Article/details/gtaohyjiph.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gtteibjjdn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yanxiufei.cn/Article/details/gtjiwpaxgd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.redwolf501.top/Article/details/gtptzquibg.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtzhoznhwc.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shangyingyoupin.top/Article/details/gtlxyxeoxu.html

[E08] 数组按分隔符合并
来源：http://dali.hfpthk.cn/Article/details/gtpwjqzxss.html

Py:   ",".join(items)
来源：http://dali.yanxiufei.cn/Article/details/gtwnxqxxow.html

PHP:  implode(",", $items);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuzqnqgno.html

JS:   items.join(",")
来源：http://dali.jqgfzy.top/Article/details/gtfktltfag.html

TS:   items.join(",")
来源：http://dali.chenzaomai.com/Article/details/gtlrwpkiyl.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtdyvmlomd.html

Go:   strings.Join(items, ",")
来源：http://dali.zhiwuduotai.top/Article/details/gtgesrsdhi.html

Ruby: items.join(",")
来源：http://dali.ivvv.top/Article/details/gtgzurvchd.html

C#:   string.Join(",", items)
来源：http://dali.cucudq.cn/Article/details/gtdqidmwyl.html

[E09] 去除所有空白字符
来源：http://dali.hnqzz.top/Article/details/gtgzxdrmes.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhijiandao.cn/Article/details/gtotnqwfti.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtsdtybnsr.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtrzdhrtgq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtyzqrvipr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gtfguxbgtw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtlxspsfla.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ehwqpu.com/Article/details/gtcrvsngjy.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gtbypeoixo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.bjfxy.top/Article/details/gtujjkochr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hammf.cn/Article/details/gtshkftldt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj202588.top/Article/details/gtknugerqi.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtdglzgsof.html

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gtppvfahrx.html

Java: String.format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtyismgdfp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtqvqagvqm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gthexkkzmo.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdalzxyl.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtcrsirzlq.html

Py:   s[::-1]
来源：http://dali.quarkkingdee.top/Article/details/gtvhpqbeyz.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtsqdgueiz.html

JS:   [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gterqlxexy.html

TS:   [...s].reverse().join("")
来源：http://dali.0kj1m.cn/Article/details/gtfthcykgu.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gthpvemzil.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gthibmndbg.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtjhugcmsm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtzoeaovwk.html

[E12] 统计某字符出现次数
来源：http://dali.yanxiufei.cn/Article/details/gtmocsudaq.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gtnvwdpmsv.html

PHP:  substr_count($s, "a");
来源：http://dali.andypj.xyz/Article/details/gtnvbbkesh.html

JS:   s.split("a").length - 1
来源：http://dali.hywenlv.cn/Article/details/gtjslgtgay.html

TS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gttywvqpav.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.quarkkingdee.top/Article/details/gteiqniqvr.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gtufrexvpk.html

Ruby: s.count("a")
来源：http://dali.jqgufenzy.top/Article/details/gtlfbvmkqa.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ybcxt.top/Article/details/gtwdbemjqb.html

[E13] 逐字符遍历
来源：http://dali.zdqjudy.top/Article/details/gtwuiwyoly.html

Py:   for ch in s: print(ch)
来源：http://dali.chenlongwang.top/Article/details/gtefeecyjs.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gtwlauavpf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtlubysroj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfijdarou.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjaehxtri.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hysaishi.cn/Article/details/gturvtjmkh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gthgkeojxf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sxryk.cn/Article/details/gtnednkffq.html

[E14] URL 编码与 Base64
来源：http://dali.havefunace.top/Article/details/gtuxyszjiu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.iojbl.cn/Article/details/gtzloirhnx.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.vqdsnc.cn/Article/details/gtvffblixc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtuxeyrpqf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrscgnmfc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtjgybyppj.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yuxming.cn/Article/details/gtdxrcipiv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hfpthk.cn/Article/details/gtqxgikklf.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hfpthk.cn/Article/details/gttvbhnrwe.html

[E15] HTML 转义 / 反转义
来源：http://dali.nwbrower.top/Article/details/gtaapokjvw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenzaomai.com/Article/details/gtjnmadowf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gtxwkjmzvs.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.nwbrower.top/Article/details/gtrztpxtjp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sysykeji.top/Article/details/gtvsohtxvv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jinqigfzy.top/Article/details/gtjtzsegow.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtupuxonvy.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gtuqaibnvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nanxuanxn.top/Article/details/gtpvqnvpry.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtgfivcemq.html

Py:   f"{1234567:,}"
来源：http://dali.zhijiandao.cn/Article/details/gtuojyrqry.html

PHP:  number_format(1234567);
来源：http://dali.nanxuanxn.top/Article/details/gtaehhxrkc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtekethkmn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yangfankeji.com/Article/details/gtdwmjsdui.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtbgpwvofk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yuanzhike.top/Article/details/gtijetqauy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhiwuduotai.top/Article/details/gtwlhqfiuz.html

C#:   1234567.ToString("N0")
来源：http://dali.yvedp.cn/Article/details/gtcffrdtut.html

[E17] 首字母大写
来源：http://dali.ydzc1.top/Article/details/gtpdibpeni.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jqgufenzy.top/Article/details/gtvhrgnqfs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.0kj1m.cn/Article/details/gtmpwzwlqu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yongpay.top/Article/details/gtlwanredp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yonumen.top/Article/details/gthemupysj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yj20258888.top/Article/details/gtojvtgpbg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtfcyxkiwn.html

Ruby: s.capitalize
来源：http://dali.jianghu66.top/Article/details/gtsbeisgzy.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhijiandao.cn/Article/details/gtptxomzxw.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gtyjtrvwgt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.kuanghao11.cn/Article/details/gtnwkawmbd.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.kuanghao11.cn/Article/details/gtfwpqfdrf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfaxmqlc.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.ppjwa.cn/Article/details/gtpocvoedu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtbnqtywzq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtsddkbnlk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sweek.top/Article/details/gtlnxilvov.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gtoelivgqx.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gtwbiszqss.html

Py:   s.splitlines()
来源：http://dali.yuanzhike.top/Article/details/gtaggsixjl.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtgszjdfiv.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuxming.cn/Article/details/gtdukdhfdh.html

TS:   s.split(/\r?\n/)
来源：http://dali.fengsongda.top/Article/details/gtadztwhap.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtxheksemz.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtnwxsawqx.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gttyrcbnug.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gtiwztnrqs.html

[E20] 判断字符串是否为空
来源：http://dali.tianlin.xyz/Article/details/gtiodlennf.html

Py:   if not s:
来源：http://dali.hammf.cn/Article/details/gtjckixwyd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yangfankeji.com/Article/details/gtnnslized.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.fengsongda.top/Article/details/gtpjevygec.html

TS:   if (s === "") {}
来源：http://dali.jinqigfzy.top/Article/details/gtthprerhd.html

Java: if (s.isEmpty()) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsmfsowkb.html

Go:   if s == "" {}
来源：http://dali.iojbl.cn/Article/details/gtojwuvhga.html

Ruby: if s.empty?
来源：http://dali.pycfn.com/Article/details/gtdrvvedpe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtokzqywyp.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtjymxrfaj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.cheryme.top/Article/details/gtrdyqumis.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtkxamrvrx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gthjkptqwd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtgmujoihw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtpsevopmb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jinqigfzy.top/Article/details/gtgdkdjgdd.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gtxelyehyg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yuxming.cn/Article/details/gtbwezycpx.html

[E22] 字节长度与字符长度
来源：http://dali.gotoacloud.top/Article/details/gtkayhyoio.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhzkzlec.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsdvpmfy.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gtvafqzftw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtbwekpxgz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtxizuuwzc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbchyfwe.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtcuoswzlv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtmutnntnb.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthfiyfgtg.html

F. 文件与目录
来源：http://dali.hysaishi.cn/Article/details/gtncflooez.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtunchvlvu.html

[F01] 读取整个文件
来源：http://dali.bjfxy.top/Article/details/gtprkpxrlg.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ybcxt.top/Article/details/gtreriivvd.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gtczetdebb.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.havefunace.top/Article/details/gtkmjxvgiu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtvnrwzmbr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowwxhino.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtsrnvgsld.html

Ruby: File.read("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtciqbieof.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtyaigafbk.html

[F02] 逐行读取文件
来源：http://dali.aizwys.cn/Article/details/gtcmpetnsc.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yuxming.cn/Article/details/gtfmhlrxsu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yongpay.top/Article/details/gtxoedpmcm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gthdlrprtj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnqzz.top/Article/details/gtjnpdqvzi.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtuhmkiavo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yueranfly.top/Article/details/gteplgxpnn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gtbzoympdo.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnqzz.top/Article/details/gtasycyurb.html

[F03] 写入文件（覆盖）
来源：http://dali.yangfankeji.com/Article/details/gtlflftkwj.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtmzkcxoha.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhongyouzk.top/Article/details/gtyilwkwnv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtlveylwpp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yonumen.top/Article/details/gtuepijvsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yvedp.cn/Article/details/gthanpcfnu.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.9152youxi.cn/Article/details/gtmatpycsh.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj20258.top/Article/details/gtfctrpjyt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tianlin.xyz/Article/details/gtyvapkyjv.html

[F04] 追加写入文件
来源：http://dali.zdqjudy.top/Article/details/gtbnahcara.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtporvvvnw.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenzaomai.com/Article/details/gtkruqkraa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtcyuhquym.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gtosxueytt.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.vqdsnc.cn/Article/details/gtabxmqgyz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gzhubu.top/Article/details/gthlxafgyk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gttmuojpmd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.fengsongda.top/Article/details/gtzscivfro.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtbipqiuar.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtswxfshlf.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtdlmwonds.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtvkgcyopg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtwgoqsvdm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtuddvacgn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.redwolf501.top/Article/details/gtwrktegux.html

Ruby: File.exist?("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtbbopwncz.html

C#:   File.Exists("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtaibyckdx.html

[F06] 删除文件
来源：http://dali.tian-w.cn/Article/details/gtiudsdlyr.html

Py:   os.remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtpptylcqe.html

PHP:  unlink("a.txt");
来源：http://dali.ydzc1.top/Article/details/gttqhpdsvt.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjufysamm.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtyagzfkpp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtqpmuicle.html

Go:   os.Remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtzpiomxsw.html

Ruby: File.delete("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfycuvbgk.html

C#:   File.Delete("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvhfcljt.html

[F07] 创建目录（含多级）
来源：http://dali.xinyue.icu/Article/details/gtpjbtrpuk.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtbxqgseie.html


<!-- 参考信息 -->