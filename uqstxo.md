代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.nanxinkj.top/Article/details/gtegxghucu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.mhx1999.top/Article/details/gtmxrwlorq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.cashguo.top/Article/details/gtslcqfqnz.html

Go:   // 手写 map[T]int
来源：http://dali.dianchejie.cn/Article/details/gthsfeuzhr.html

Ruby: arr.tally
来源：http://dali.guannengcc.top/Article/details/gtvzlihmei.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hysaishi.cn/Article/details/gtczulbdqr.html

[D21] 判断是否包含某元素
来源：http://dali.ybcxt.top/Article/details/gtepahamqz.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gttcshmovy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhiwuduotai.top/Article/details/gtnwikpfje.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtuwuzmslu.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtoxuvnhkk.html

Java: list.contains(x)
来源：http://dali.yueranfly.top/Article/details/gtiihsydai.html

Go:   slices.Contains(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gteyluzjbc.html

Ruby: arr.include?(x)
来源：http://dali.xinyue.icu/Article/details/gtqypfwkcz.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtambvonwj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtfxvebnsu.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtutlnazak.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtiqitwfcq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.iojbl.cn/Article/details/gtmjdmnqwr.html

TS:   [...arr];
来源：http://dali.snrcjt.cn/Article/details/gtrothcfzi.html

Java: new ArrayList<>(list);
来源：http://dali.ppjwa.cn/Article/details/gtjiihhymj.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zycfv.cn/Article/details/gtqnihcnxh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.jqgfzy.top/Article/details/gtbjeawank.html

C#:   new List<int>(list);
来源：http://dali.kuanghao11.cn/Article/details/gtzhcekjwa.html

[D23] reduce 累积计算
来源：http://dali.9152youxi.cn/Article/details/gttqxnghca.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtroanxrqy.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtgowpkwgg.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtnjyqoanl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtuppppwnj.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gtoahwxsml.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtpqethdbk.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.ybcxt.top/Article/details/gtilkcqzyc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gtrvwfhbvs.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gtbzcswgor.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jyoumei.cn/Article/details/gtuwphxyqt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hywenlv.cn/Article/details/gtynsrmaxh.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtdsqyuzcd.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtiwtzseko.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yongpay.top/Article/details/gtxaaftfav.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtdapbotlt.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.xziqi.cn/Article/details/gtipqjdswa.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtozotykpf.html

[D25] Set 集合去重与交并差
来源：http://dali.fengsongda.top/Article/details/gtprsbdpxc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrdvdahz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhixingplan.top/Article/details/gthllmkyhq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtrzsfjspa.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nanxuanxn.top/Article/details/gtinfqefag.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xuanzx.com/Article/details/gtbpwclefg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gtidahxadt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gogol.net.cn/Article/details/gtqbywurbr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtoikktfub.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlnxdjmdd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtfjtowojt.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtxcyihzfi.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gttskngzjl.html

TS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gtintqvhpg.html

Java: String.join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gtopcniscb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shuidangran.top/Article/details/gtofdpyass.html

Ruby: arr.join(", ")
来源：http://dali.zhongyouzk.top/Article/details/gtiubmctee.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbsmwtqp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtpbrzpqan.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gttdvpkcis.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgcbzvdsn.html

[E01] 拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuoxaapn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zdqjudy.top/Article/details/gtaxxwlubh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sxryk.cn/Article/details/gtfascbssp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.redwolf501.top/Article/details/gtrulkwwhf.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenjidiqi.icu/Article/details/gtscjcvgna.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.0kj1m.cn/Article/details/gtzrtitjyl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gtbrmlljxw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gthtfmodwa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gtaherdamj.html

[E02] 重复字符串
来源：http://dali.svipenyu.cn/Article/details/gtnilrgpir.html

Py:   "ab" * 3
来源：http://dali.redwolf501.top/Article/details/gtnvspdyul.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtwkfbwuyj.html

JS:   "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyufqxxme.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtxohmelxr.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtjfytfxqh.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtkvademjt.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtdhtebhia.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangdashe.top/Article/details/gtngwedgof.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtrbyjukfv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gtbzwrryxy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhixingplan.top/Article/details/gtjyfpufac.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtcdbildkr.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gthperkokg.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtzpxwyjya.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlzmreko.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gttscehtzq.html

C#:   s.Substring(1, 3)
来源：http://dali.cashguo.top/Article/details/gtkkvmkvrf.html

[E04] 查找子串位置
来源：http://dali.tianlin.xyz/Article/details/gteqcfatqi.html

Py:   s.find("x");  s.index("x")
来源：http://dali.kuanghao11.cn/Article/details/gtlgdiledm.html

PHP:  strpos($s, "x");
来源：http://dali.cdnleiting.top/Article/details/gtrldhqvxo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtfzpneyyf.html

TS:   s.indexOf("x")
来源：http://dali.zhixingplan.top/Article/details/gtqxrcvcko.html

Java: s.indexOf("x")
来源：http://dali.nanxuanxn.top/Article/details/gteqjtjnfh.html

Go:   strings.Index(s, "x")
来源：http://dali.zhengqikj.top/Article/details/gtxnzwhkri.html

Ruby: s.index("x")
来源：http://dali.zhijiandao.cn/Article/details/gtqsgdkfpo.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtncbuznpo.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtfvzqjtyj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.316326.xyz/Article/details/gtnvzqezyy.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtdkoecbmb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtsnqnwhbc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnqzz.top/Article/details/gtvswuttcb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtkwrjpqjp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.meibo888.top/Article/details/gtrjqgpesl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcppjqskn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtodtlmvqx.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtecbfuhlr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqdfuxgtb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cheryme.top/Article/details/gtenlxrgng.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.smart0.xyz/Article/details/gtqmsjznee.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtkxagukmn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtpxtushuo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cheryme.top/Article/details/gtnihohtin.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yongpay.top/Article/details/gtxpjbaksw.html

C#:   s.Replace("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtdrmecrwa.html

[E07] 按分隔符拆分
来源：http://dali.hnqzz.top/Article/details/gtnyhixdww.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hnxiangtu.top/Article/details/gtpizetncb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtbdhgdyom.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.birdmap.top/Article/details/gtcmofykou.html

TS:   s.split(",")
来源：http://dali.jqgufenzy.top/Article/details/gtxjofddsv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtcoaninvz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtogwwigyx.html

Ruby: s.split(",");  s.split
来源：http://dali.iojbl.cn/Article/details/gtcvmgelac.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.sxryk.cn/Article/details/gtdvrlxvrb.html

[E08] 数组按分隔符合并
来源：http://dali.mhx1999.top/Article/details/gtidrmnmpq.html

Py:   ",".join(items)
来源：http://dali.ybcxt.top/Article/details/gtlflfyech.html

PHP:  implode(",", $items);
来源：http://dali.xinyue.icu/Article/details/gteauuldfa.html

JS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtkmzwxzkg.html

TS:   items.join(",")
来源：http://dali.wangdashe.top/Article/details/gtzsfonryd.html

Java: String.join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtnsojuvzs.html

Go:   strings.Join(items, ",")
来源：http://dali.hnqzz.top/Article/details/gtigwuhgbp.html

Ruby: items.join(",")
来源：http://dali.316326.xyz/Article/details/gtwdqekdaa.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gtilewqjxh.html

[E09] 去除所有空白字符
来源：http://dali.nanxinkj.top/Article/details/gtgscvtqwa.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.meibo888.top/Article/details/gtslponhvd.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jlsjyb.cn/Article/details/gtpojbdcim.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daxiang520.top/Article/details/gtwbbtihil.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aizwys.cn/Article/details/gtzwizssev.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jqgufenzy.top/Article/details/gtoxsqrtuk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtsgvvcrqi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pycfn.com/Article/details/gtpxmouydj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtlgbvguhp.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhongyouzk.top/Article/details/gtjsywbfgp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zdqjudy.top/Article/details/gtbqliwikm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.0kj1m.cn/Article/details/gtztfynobx.html

JS:   "7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gtjxgdsnli.html

TS:   "7".padStart(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gtywkreycg.html

Java: String.format("%03d", 7)
来源：http://dali.aizwys.cn/Article/details/gtivycolsc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtlcbzikho.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtkfogmdlb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.birdmap.top/Article/details/gtbpfbqqco.html

[E11] 反转字符串
来源：http://dali.xziqi.cn/Article/details/gtivmaeabg.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gtsimnfeiy.html

PHP:  strrev($s);
来源：http://dali.birdmap.top/Article/details/gtjdtbksvy.html

JS:   [...s].reverse().join("")
来源：http://dali.hnxiangtu.top/Article/details/gtyykdpfvl.html

TS:   [...s].reverse().join("")
来源：http://dali.chenzaomai.com/Article/details/gtoupsrjit.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gtcjlcbbtn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gotoacloud.top/Article/details/gtrqmshnuu.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtkeymwcyl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gtnfbpjsbj.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtviilpiwx.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtpotjrikq.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtqqheoeox.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtdepzvpza.html

TS:   s.split("a").length - 1
来源：http://dali.cucudq.cn/Article/details/gtiinnxiil.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yongpay.top/Article/details/gtjxyyitor.html

Go:   strings.Count(s, "a")
来源：http://dali.bjfxy.top/Article/details/gtjtvftdbn.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtkdlsfypz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtovqjneap.html

[E13] 逐字符遍历
来源：http://dali.yanxiufei.cn/Article/details/gtodcrzqpg.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtyakyafbj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtftqcogmp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtnbdabrxc.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gtqeukmemy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtctlwzzlm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ybcxt.top/Article/details/gtvptlwnkq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.sufxvd.cn/Article/details/gtkzzhyhiz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.sysykeji.top/Article/details/gtwflhrgyu.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtffwntvte.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtuohsqced.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.andypj.xyz/Article/details/gtnajgifhc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ivvv.top/Article/details/gtoomivfxe.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtkklfricz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtzzladdcb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.chenzaomai.com/Article/details/gtflyhdgjv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.kuanghao11.cn/Article/details/gtsshqjssb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtejlvwzkc.html

[E15] HTML 转义 / 反转义
来源：http://dali.sxryk.cn/Article/details/gtcepgatwt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gtyzvrqchf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cdnleiting.top/Article/details/gtwsbaiisf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.snrcjt.cn/Article/details/gtjkxnzwio.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gtczwxlujo.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfwrmjlt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtgmunuesb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtbrgrwsyn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtahyhqqdw.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtexauckgu.html

Py:   f"{1234567:,}"
来源：http://dali.hywenlv.cn/Article/details/gthatlqzrb.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtekojqfjd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtpfhzftuo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtabgfffnj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zycfv.cn/Article/details/gtoycrkgir.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtlrgiromz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.fengsongda.top/Article/details/gtewqztzee.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtfmwqtpsw.html

[E17] 首字母大写
来源：http://dali.shzxlz.cn/Article/details/gtxoyfubko.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtfmhheqgc.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gtwrbwnjxf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtwaxwkypl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gtxadtlmjg.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtdtpbfjqr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtpeokiuoz.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtmvpvxajn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhengqikj.top/Article/details/gtxypfniwm.html

[E18] 模板占位符替换
来源：http://dali.zhixingplan.top/Article/details/gtpefztbnz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhengqikj.top/Article/details/gtohfdtlhn.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nwbrower.top/Article/details/gtfcykhebd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gtycyokkgm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jqgufenzy.top/Article/details/gtbtclvapz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gtxiawncsu.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtfrljilug.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yj20258.top/Article/details/gtbdhsanca.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrasgnoz.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtuvggvbmx.html

Py:   s.splitlines()
来源：http://dali.meibo888.top/Article/details/gtjqfspjyz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.daria6918.cn/Article/details/gtxmknctcg.html

JS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gtyymnltau.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtuaboptjr.html

Java: s.lines().toList()
来源：http://dali.svipenyu.cn/Article/details/gtfsrhemww.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhoulong.xyz/Article/details/gtjhfpdsbg.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtrxiawlxu.html

C#:   s.Split('\n')
来源：http://dali.redwolf501.top/Article/details/gtxlfznbgw.html

[E20] 判断字符串是否为空
来源：http://dali.ybcxt.top/Article/details/gtyznveejj.html

Py:   if not s:
来源：http://dali.c1oappe.top/Article/details/gtukbaliza.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dianchejie.cn/Article/details/gtimsslhup.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtbbhugfku.html

TS:   if (s === "") {}
来源：http://dali.hnxiangtu.top/Article/details/gtclifqows.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfiixhzvb.html

Go:   if s == "" {}
来源：http://dali.sweek.top/Article/details/gtzdhlzfti.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gtjdsvupdg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.9152youxi.cn/Article/details/gtilbdvcqz.html

[E21] 超长截断加省略号
来源：http://dali.hammf.cn/Article/details/gtsdfxmdcu.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.tanke756.top/Article/details/gtogwuawjy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtsdjcjxlu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gtmtakomzb.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gtmcjywymr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtyqtryavp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ivvv.top/Article/details/gtjxrzsspo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtiukgjfcj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtdiottpcd.html

[E22] 字节长度与字符长度
来源：http://dali.jqgfzy.top/Article/details/gtcnimvvwn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtwpwgjozm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtsxddlozx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gthnjoqckr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gtowjhudqs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtamfvkfmf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqsnxjrr.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtdvoulpal.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.haohaochexian.top/Article/details/gtofnfjndf.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjrrmrlar.html

F. 文件与目录
来源：http://dali.hnxiangtu.top/Article/details/gtkeckxqab.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrwfvevox.html

[F01] 读取整个文件
来源：http://dali.cucudq.cn/Article/details/gtxajtmopq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shuidangran.top/Article/details/gtbajkoqkx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtbjpjpiii.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.dashuyun.cn/Article/details/gtcwncqnbi.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtvmgdtifs.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtwskykxzs.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jianghu66.top/Article/details/gtvmpqmgxt.html

Ruby: File.read("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtueykahqz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.meibo888.top/Article/details/gtziggitfj.html

[F02] 逐行读取文件
来源：http://dali.cheryme.top/Article/details/gtgyqgaais.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hnxiangtu.top/Article/details/gtnxcylawh.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yueranfly.top/Article/details/gtyudlttxu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtywuiobgv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtbgbtiydl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guowangkeji.top/Article/details/gtwjysuaeq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yonumen.top/Article/details/gtiqmnhras.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtordiivjm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtlumsamar.html

[F03] 写入文件（覆盖）
来源：http://dali.jlsjyb.cn/Article/details/gtnrdlngbb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.meibo888.top/Article/details/gtojzcnxyu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yangfankeji.com/Article/details/gtekgvhgtr.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtvayolmne.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.cheryme.top/Article/details/gtoidbhtxf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gtcaadysuo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jlsjyb.cn/Article/details/gtohyerxnf.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gtatszcitf.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gteobnobtk.html

[F04] 追加写入文件
来源：http://dali.haohaochexian.top/Article/details/gtbhdriumr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sweek.top/Article/details/gtoqbpkbbu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtwakvejjz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cucudq.cn/Article/details/gtihmxltsp.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvlxsiobd.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtlgoijxpw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hysaishi.cn/Article/details/gtialcprzo.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hammf.cn/Article/details/gttxaeerxu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.svipenyu.cn/Article/details/gtenrdmdsp.html


<!-- 参考信息 -->