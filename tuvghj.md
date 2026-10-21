代发 wailian999

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.vqdsnc.cn/Article/details/gtkiyairla.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtzdhocgmr.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtmiwlujij.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtukhiblhd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gtmulpuudi.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtdzilqbpp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gzhubu.top/Article/details/gtdhffafkf.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gtraqcohiz.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gtinmcuepk.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.daria6918.cn/Article/details/gtdycspuow.html

[D21] 判断是否包含某元素
来源：http://dali.sysykeji.top/Article/details/gthibrokvn.html

Py:   x in arr
来源：http://dali.shzxlz.cn/Article/details/gtsyuoveki.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xziqi.cn/Article/details/gtdgeiewnj.html

JS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpcyhbff.html

TS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxrksepy.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtnytbvqkx.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnxiangtu.top/Article/details/gtdbckdtvi.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gtmwrkfuoj.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtosdgstgx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhoulong.xyz/Article/details/gtsmukkmzo.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrubqfaeu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hysaishi.cn/Article/details/gtuarurgsu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.fengsongda.top/Article/details/gtrqpxluco.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtblykbbpa.html

Java: new ArrayList<>(list);
来源：http://dali.shuidangran.top/Article/details/gtvnzmjgwb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxuowprqg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yanxiufei.cn/Article/details/gtyyxluejf.html

C#:   new List<int>(list);
来源：http://dali.guowangkeji.top/Article/details/gtlugjoprr.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtqhhdravk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbsljzpvf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtckiyzalr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.andypj.xyz/Article/details/gtwhibexja.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hammf.cn/Article/details/gtepsdsrby.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cheryme.top/Article/details/gtrgeahdma.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtlvzhzzbf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgfzy.top/Article/details/gtiucllvzg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtunizpjqw.html

[D24] 字典 / Map 基本操作
来源：http://dali.gaohongyu789.top/Article/details/gtgzrjaxnf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.kuanghao11.cn/Article/details/gtxcvktbap.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtfwruplln.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yangfankeji.com/Article/details/gtecmyrkii.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtvlpxewfa.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fengsongda.top/Article/details/gtxjaiwyjx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gtqruokpiw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtbxvncxos.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ybcxt.top/Article/details/gtzcdfuzyg.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtpmqqixpd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ybcxt.top/Article/details/gtlvxcyqed.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbohscigd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfknzral.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tian-w.cn/Article/details/gtxtvhoerq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yangfankeji.com/Article/details/gtyppujuzn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.shanyushiyangtech.top/Article/details/gtymyhnawt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cashguo.top/Article/details/gtdzkpjyjb.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daxiang520.top/Article/details/gtqhkbfaoh.html

[D26] 数组转字符串
来源：http://dali.gotoacloud.top/Article/details/gtowqzvxcs.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gtfgmuoega.html

PHP:  implode(", ", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtmjdmavlq.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtyfzwuxvs.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtxqdbgcrk.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtmhqyondn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.wangdashe.top/Article/details/gtqrcaiadq.html

Ruby: arr.join(", ")
来源：http://dali.xuanzx.com/Article/details/gtwwivdnsw.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtibjpnvzd.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngchudtq.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtpjbiecjf.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpwilpplb.html

[E01] 拼接字符串
来源：http://dali.bjfxy.top/Article/details/gtqmirbqcb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtxpyjlxyx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yueranfly.top/Article/details/gtmbrwlzhc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhzoxouc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yuxming.cn/Article/details/gtfnsjapeo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cashguo.top/Article/details/gtlffrooyh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gtbwhjprvp.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gtfilzeeoa.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gticxqegxi.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtbmuwgvdd.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gtziaascwm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhoulong.xyz/Article/details/gtdggkmsiq.html

JS:   "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtyyewdsvc.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtisuldpcq.html

Java: "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gtzxqljvst.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.316326.xyz/Article/details/gtjqstpxuk.html

Ruby: "ab" * 3
来源：http://dali.jyoumei.cn/Article/details/gtfkgowzjj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinqigfzy.top/Article/details/gtwwalochk.html

[E03] 截取子串
来源：http://dali.snrcjt.cn/Article/details/gtzskuzfam.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.iojbl.cn/Article/details/gtzhjhwsmp.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sxryk.cn/Article/details/gtnynwvmjj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gtkmywboix.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtgeaashjb.html

Java: s.substring(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtrcdbgcmu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.haohaochexian.top/Article/details/gtctspdqex.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gttxssvatp.html

C#:   s.Substring(1, 3)
来源：http://dali.yuanzhike.top/Article/details/gtvcnklkcp.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtjkebrhej.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtyzbuyknp.html

PHP:  strpos($s, "x");
来源：http://dali.nanxinkj.top/Article/details/gthziatwju.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gtzlefihrj.html

TS:   s.indexOf("x")
来源：http://dali.haohaochexian.top/Article/details/gtxgnyaefw.html

Java: s.indexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtdhcfnsae.html

Go:   strings.Index(s, "x")
来源：http://dali.aizwys.cn/Article/details/gttyjmdgls.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtiznadivx.html

C#:   s.IndexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gthlcueudu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shuidangran.top/Article/details/gtbdnakodo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtwqebiojb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gtwhstddhp.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gtuqeapczm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jiagoushi.top/Article/details/gtrueoffxt.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtpcpevdpr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangshuangyany.cn/Article/details/gtredmohkp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.316326.xyz/Article/details/gtaaivdwjn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gthaoklqun.html

[E06] 替换子串
来源：http://dali.quarkkingdee.top/Article/details/gtswkmywft.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllmebxog.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtjspqkpec.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtrmyzhcum.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtrvcspcmo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtomsexqcy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gtofgvbycz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtctqutgvf.html

C#:   s.Replace("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtebmdqspc.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtdzjzvnmt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtkmdqyrnk.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.meibo888.top/Article/details/gtsqqepvnl.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ivvv.top/Article/details/gtwwomwelb.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtnxisohur.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.bjfxy.top/Article/details/gtunykmqpl.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jlsjyb.cn/Article/details/gtokomojdb.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gtogbftdxe.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtuhzjfauz.html

[E08] 数组按分隔符合并
来源：http://dali.andypj.xyz/Article/details/gtqmkoamjr.html

Py:   ",".join(items)
来源：http://dali.meibo888.top/Article/details/gtgdmolrll.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauesqsbe.html

JS:   items.join(",")
来源：http://dali.jianghu66.top/Article/details/gtxnemzizf.html

TS:   items.join(",")
来源：http://dali.shuidangran.top/Article/details/gttuqvmmgs.html

Java: String.join(",", items)
来源：http://dali.hywenlv.cn/Article/details/gtqlipthql.html

Go:   strings.Join(items, ",")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlyxycin.html

Ruby: items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmuohisb.html

C#:   string.Join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtdycpiwbi.html

[E09] 去除所有空白字符
来源：http://dali.sysykeji.top/Article/details/gtilyjqvcl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hywenlv.cn/Article/details/gtnxpppkqu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yuanzhike.top/Article/details/gthfwkqvzf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtkgloyuwz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhiwuduotai.top/Article/details/gtmnqcjslm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gtlwmqtmbw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gtolqussur.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenjidiqi.icu/Article/details/gtqowpgwzu.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.iojbl.cn/Article/details/gtbvqdtbkg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.sweek.top/Article/details/gtosbabddp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtrtrmzlve.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhoulong.xyz/Article/details/gtvcfxbeci.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakocokzj.html

TS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtmcahwfgl.html

Java: String.format("%03d", 7)
来源：http://dali.pengpengdd.cyou/Article/details/gtldoixdxf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gthfuipxxr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shuidangran.top/Article/details/gtvqjheixd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aibaodan.cn/Article/details/gtkvupjfia.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkernncs.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtvhrzsemn.html

PHP:  strrev($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtjqnmachv.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtjnfhuwae.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtkjfcrirs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.fzhhl.top/Article/details/gtiujlyoyp.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jqgufenzy.top/Article/details/gtnvxpbleg.html

Ruby: s.reverse
来源：http://dali.meibo888.top/Article/details/gtjwwigwie.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtlpjyqynd.html

[E12] 统计某字符出现次数
来源：http://dali.daria6918.cn/Article/details/gtybvxuehq.html

Py:   s.count("a")
来源：http://dali.gotoacloud.top/Article/details/gtgulhtwqt.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgfzy.top/Article/details/gtfnrqjerc.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtgbrwzfjh.html

TS:   s.split("a").length - 1
来源：http://dali.ppjwa.cn/Article/details/gtsngjwtge.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.9152youxi.cn/Article/details/gtdmwrmdes.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gtywwdxeya.html

Ruby: s.count("a")
来源：http://dali.yangfankeji.com/Article/details/gtmczosdzu.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtdmidbqkn.html

[E13] 逐字符遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkillhtil.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtcrxskqit.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.daxiang520.top/Article/details/gtowdmbqqy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yj20258.top/Article/details/gtsxvnwuur.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gtqgkmiofj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hongshengwenyu.top/Article/details/gtfedvqnhn.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.birdmap.top/Article/details/gttzmbmucu.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.nanxuanxn.top/Article/details/gtihxrvzul.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmdyrrydr.html

[E14] URL 编码与 Base64
来源：http://dali.kuanghao11.cn/Article/details/gtjoahxglt.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cdnleiting.top/Article/details/gtksfslfik.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhongyouzk.top/Article/details/gtghkggwnv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtowevswrw.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhijiandao.cn/Article/details/gtrvdndhwu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtpnozzuin.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.havefunace.top/Article/details/gtzicawjpx.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtelvtriys.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtqofypeqy.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtmrnffcqs.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtyzhcnlgm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhengqikj.top/Article/details/gtujeidxdi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.ydzc1.top/Article/details/gtfkjutlpl.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtbllhrgcc.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shzxlz.cn/Article/details/gtoynympvt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyydphqjb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shzxlz.cn/Article/details/gtjbwnhjli.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtpuhdtbcj.html

[E16] 数字千分位
来源：http://dali.chenzaomai.com/Article/details/gtlncdwqei.html

Py:   f"{1234567:,}"
来源：http://dali.hysaishi.cn/Article/details/gtybfajddo.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gtqklgoqtw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hywenlv.cn/Article/details/gtlodywyio.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtvvaqxjyk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtsnpaypaz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nanxinkj.top/Article/details/gtvljygfkr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtrdqnjkqo.html

C#:   1234567.ToString("N0")
来源：http://dali.bjfxy.top/Article/details/gtvipjwbmb.html

[E17] 首字母大写
来源：http://dali.yj202588.top/Article/details/gtljqdbotv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtrwzxzica.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcawouzpu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtqhvlrqhf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtzicdjcda.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.svipenyu.cn/Article/details/gtyveiqlrd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgfsbarn.html

Ruby: s.capitalize
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhikamys.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtunebcikk.html

[E18] 模板占位符替换
来源：http://dali.chenjidiqi.icu/Article/details/gtrlaukiqa.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtvnjyxwdg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.meibo888.top/Article/details/gttatgutsn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cashguo.top/Article/details/gtyybymdtq.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.dianchejie.cn/Article/details/gtatjccdbx.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtawjjnwrj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.wangdashe.top/Article/details/gtsrkrewun.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cqqwz.cn/Article/details/gtxjfrsoig.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gtujmcughm.html

[E19] 多行文本按行拆分
来源：http://dali.shuidangran.top/Article/details/gtbyjphdjx.html

Py:   s.splitlines()
来源：http://dali.guowangkeji.top/Article/details/gtioexxaqf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gtbpthheoi.html

JS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gtgodvuifx.html

TS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gtkfqsaqum.html

Java: s.lines().toList()
来源：http://dali.yj20258888.top/Article/details/gtrnmforvv.html

Go:   strings.Split(s, "\n")
来源：http://dali.zdqjudy.top/Article/details/gtwuaxtiln.html

Ruby: s.lines
来源：http://dali.zhengqikj.top/Article/details/gtliplxmrq.html

C#:   s.Split('\n')
来源：http://dali.havefunace.top/Article/details/gtmdtvwneo.html

[E20] 判断字符串是否为空
来源：http://dali.zhongyouzk.top/Article/details/gtteoeukad.html

Py:   if not s:
来源：http://dali.yj202588.top/Article/details/gtbhysmpck.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shzxlz.cn/Article/details/gtdjounddk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ehwqpu.com/Article/details/gtzqjnjmmw.html

TS:   if (s === "") {}
来源：http://dali.ppjwa.cn/Article/details/gtapfkrppl.html

Java: if (s.isEmpty()) {}
来源：http://dali.dashuyun.cn/Article/details/gtwuawsewh.html

Go:   if s == "" {}
来源：http://dali.daxiang520.top/Article/details/gtfvwadeyp.html

Ruby: if s.empty?
来源：http://dali.hongshengwenyu.top/Article/details/gttearhzbc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yongpay.top/Article/details/gtsuvrruav.html

[E21] 超长截断加省略号
来源：http://dali.jqgufenzy.top/Article/details/gtulupfrzw.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ydzc1.top/Article/details/gtqwftkgfw.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfauxjagf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtpspauykp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbbzfizk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gtzfrrkvhr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcvmdhvc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtbblrfesj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtdoufgroa.html

[E22] 字节长度与字符长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyenpvpas.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yueranfly.top/Article/details/gtpkpfomal.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtgiztidlt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.snrcjt.cn/Article/details/gtpvzpcloa.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtqrvkatpq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.fzhhl.top/Article/details/gteyelscle.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jyoumei.cn/Article/details/gtxwbqhhfd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jinqigfzy.top/Article/details/gtduvcbqfv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtewaerhpq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtypkrjhmr.html

F. 文件与目录
来源：http://dali.zdqjudy.top/Article/details/gtduqgeuwo.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdpttrufm.html

[F01] 读取整个文件
来源：http://dali.shzxlz.cn/Article/details/gtoocuhsod.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtzcyvgtoe.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gtshwabjag.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.snrcjt.cn/Article/details/gthumboyyt.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gteqfhasae.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtijiqilye.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guannengcc.top/Article/details/gtpaekbzot.html

Ruby: File.read("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtvgsxmwpx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtuhvbuyad.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gtkscudtlw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.snrcjt.cn/Article/details/gteljdkero.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhongyouzk.top/Article/details/gtylydwdvt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yonumen.top/Article/details/gtmqnpfrww.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gtazcammus.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.birdmap.top/Article/details/gtqjzvhtqn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.feifeiyinyue.top/Article/details/gtkrompjwz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstkwmsbm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtdbxijnfv.html

[F03] 写入文件（覆盖）
来源：http://dali.snrcjt.cn/Article/details/gtbrneoema.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtekwglpdk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gtiagsiiva.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jqgfzy.top/Article/details/gtdvxyvxja.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gteiozaexb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.9152youxi.cn/Article/details/gtpjulejze.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtrjjgemze.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hywenlv.cn/Article/details/gtmfpxhxgd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.mhx1999.top/Article/details/gtvqnubjlb.html

[F04] 追加写入文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvgxffcu.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.nwbrower.top/Article/details/gtjpueirdu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtehlxkcar.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtmurwikfn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtwjzepvaw.html


<!-- 参考信息 -->