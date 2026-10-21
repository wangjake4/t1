代发 wailian999

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ivvv.top/Article/details/gtqoxuvrom.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuxming.cn/Article/details/gtadrlujhj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jianghu66.top/Article/details/gtgjdclrtr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gtxrzydacc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtibobgdwe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.haohaochexian.top/Article/details/gtbjvkhkyd.html

JS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtltqidjid.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtsfpdzuqy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtlbnvrykl.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtxhwkrlmj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtystpskoy.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ivvv.top/Article/details/gtjrehbjxx.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtbtubbxir.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtawddrufm.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtkzlujday.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtltcrivox.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtpphmhzhw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gthqoprudq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gttnoezqsr.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtjsuvxgtw.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtzdphxshs.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtgoiipqub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sweek.top/Article/details/gtqxutzowg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtifmjkvoo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtwxachnja.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgufenzy.top/Article/details/gttlixxnij.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtbzomaaal.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtdbvjdyxr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jiagoushi.top/Article/details/gtyxjqefak.html

C#:   list.Sum();  list.Average()
来源：http://dali.yonumen.top/Article/details/gtlymsurjw.html

[D17] 最大值与最小值
来源：http://dali.shangyingyoupin.top/Article/details/gtujlslgbw.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gtrdupqrcu.html

PHP:  max($arr);  min($arr);
来源：http://dali.yangfankeji.com/Article/details/gtwijahnok.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtyrdhylrl.html

TS:   Math.max(...arr);
来源：http://dali.smart0.xyz/Article/details/gthwcekjll.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtoyooewxh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.svipenyu.cn/Article/details/gtijuruadg.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtezfnbice.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtpelgknhu.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtauxefjgx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtdiffenup.html

PHP:  array_merge(...$nested);
来源：http://dali.daria6918.cn/Article/details/gtwkmwazth.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gteayubrdy.html

TS:   nested.flat();
来源：http://dali.jinghuilouyu.cn/Article/details/gtflqsmzyv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtxdgtipyj.html

Go:   // 手写双层循环
来源：http://dali.xinyue.icu/Article/details/gtrrlmfclf.html

Ruby: nested.flatten
来源：http://dali.shuidangran.top/Article/details/gtntrbkyxe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtmmfrvlbb.html

[D19] 按字段分组
来源：http://dali.nwbrower.top/Article/details/gteawitvvw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shzxlz.cn/Article/details/gtlchoaibj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtehlwlrnl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtaveujgxb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.9152youxi.cn/Article/details/gttzgnowod.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.nanxuanxn.top/Article/details/gtenmlprjh.html

Go:   // 手写 map[string][]T
来源：http://dali.yueranfly.top/Article/details/gtchhtagze.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gtnjluuwij.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gtanwkxdbp.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjshorgc.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtrkvmbgxx.html

PHP:  array_count_values($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtdexpooqj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtuqkgjbgx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtjsegnzfx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yanxiufei.cn/Article/details/gtquywcsmb.html

Go:   // 手写 map[T]int
来源：http://dali.jqgufenzy.top/Article/details/gtkmkmcpsj.html

Ruby: arr.tally
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmmikhua.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtpzctjbsl.html

[D21] 判断是否包含某元素
来源：http://dali.gotoacloud.top/Article/details/gtgkqeleqj.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtgifywqmy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigufen.top/Article/details/gtqzgsktfa.html

JS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtfngmeaqa.html

TS:   arr.includes(x)
来源：http://dali.shuidangran.top/Article/details/gtjcfrcbay.html

Java: list.contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrsjclplr.html

Go:   slices.Contains(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtpkvvhhlp.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtzjfdbjnm.html

C#:   list.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtjxcncmeh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnxiangtu.top/Article/details/gtyujqvqkb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cheryme.top/Article/details/gtsgkehcsk.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.gotoacloud.top/Article/details/gtxovzxtsp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.pycfn.com/Article/details/gthxfhupoc.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtfzuutjlk.html

Java: new ArrayList<>(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtljbkxjeg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.0kj1m.cn/Article/details/gtydpxcuyg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtdyqyvdzc.html

C#:   new List<int>(list);
来源：http://dali.nanxinkj.top/Article/details/gtbsoofioc.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtoapvwczs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yongpay.top/Article/details/gtvfklfpvn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.redwolf501.top/Article/details/gthrzrueaf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gtgmmiebao.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gtarcabkne.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtwjcjtqpg.html

Go:   // 手写循环
来源：http://dali.sxryk.cn/Article/details/gttbrvgdrl.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtkplcsyha.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gtpiovnbqu.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtmaurlbqg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cqqwz.cn/Article/details/gtkbmvazov.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtmkvmcwrd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxinkj.top/Article/details/gtjblzktql.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtlqkpnkih.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.nanxuanxn.top/Article/details/gtssbdljjd.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xylfe.cn/Article/details/gtdqpzdend.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuanzhike.top/Article/details/gtjaocaakk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gtnljdffws.html

[D25] Set 集合去重与交并差
来源：http://dali.smart0.xyz/Article/details/gtmmuiiiwj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyriifwwn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gtsfimeeer.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtnmcfpdlk.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.daria6918.cn/Article/details/gtnjbsyded.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yueranfly.top/Article/details/gtmmgckgpl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxuanxn.top/Article/details/gthdtaxawr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xinyue.icu/Article/details/gtijejbmgj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtiyzifxyn.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gttvgqlqwd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtlzqqgsqb.html

PHP:  implode(", ", $arr);
来源：http://dali.yuxming.cn/Article/details/gtqxtdhzun.html

JS:   arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtkkvwvvlp.html

TS:   arr.join(", ")
来源：http://dali.xuetiantiany.cn/Article/details/gttrrzvyig.html

Java: String.join(", ", list)
来源：http://dali.sufxvd.cn/Article/details/gttouzvmsv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cdnleiting.top/Article/details/gtkcaskxfa.html

Ruby: arr.join(", ")
来源：http://dali.yvedp.cn/Article/details/gtfuicfjmp.html

C#:   string.Join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtjvagiimy.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtntexmata.html

E. 字符串处理
来源：http://dali.xinyue.icu/Article/details/gtfofatwvx.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtcibcekwa.html

[E01] 拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthxdmjmsg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.jinqigfzy.top/Article/details/gtlvdjqrgm.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhixingplan.top/Article/details/gtcblazrth.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtopcheksm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtldfxaxhn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gtpwqjdxsm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.tanke756.top/Article/details/gtkeujjmwc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sysykeji.top/Article/details/gthhnakmeg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gtolbfuetd.html

[E02] 重复字符串
来源：http://dali.yj202588.top/Article/details/gtqjgoqocc.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthdpqorw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.quarkkingdee.top/Article/details/gtkfryyuvw.html

JS:   "ab".repeat(3)
来源：http://dali.zycfv.cn/Article/details/gthwkcykef.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtiisyyaps.html

Java: "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gthejxquyl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoopyluyb.html

Ruby: "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtlwfvejgm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gtpxixorgx.html

[E03] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gtlatikyaw.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.0kj1m.cn/Article/details/gtdkpmwsef.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.daxiang520.top/Article/details/gtmglzbtvg.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.316326.xyz/Article/details/gtcefvgbow.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtlvcciuxa.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtbiyhhoaj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtwqdvmstj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtxiqzgpfk.html

C#:   s.Substring(1, 3)
来源：http://dali.havefunace.top/Article/details/gtpqocsprh.html

[E04] 查找子串位置
来源：http://dali.hfpthk.cn/Article/details/gtqmihlreh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gtbvcxothy.html

PHP:  strpos($s, "x");
来源：http://dali.wangshuangyany.cn/Article/details/gtwcomffvh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.vqdsnc.cn/Article/details/gtemzkwvuk.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtstemthdi.html

Java: s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtumyjodjn.html

Go:   strings.Index(s, "x")
来源：http://dali.sxryk.cn/Article/details/gtqnzpycsr.html

Ruby: s.index("x")
来源：http://dali.snrcjt.cn/Article/details/gtydhchnwj.html

C#:   s.IndexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtximiotaz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yuxming.cn/Article/details/gttxeznpqi.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.quarkkingdee.top/Article/details/gtgxlsiunu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gaohongyu789.top/Article/details/gtictfjkof.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtuwhljtso.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtdhkalshb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtpqbfdkmc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtxpyrykvp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yonumen.top/Article/details/gtxakuyfhm.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtdbsykqon.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtzivjifcc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtkiglezih.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinqigufen.top/Article/details/gtftlmhftm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtkutsqzhg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtpdtqrhfj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yonumen.top/Article/details/gtrbnqrskr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtvxmguwfu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtxrxsesha.html

C#:   s.Replace("a", "b")
来源：http://dali.fengsongda.top/Article/details/gttflpbram.html

[E07] 按分隔符拆分
来源：http://dali.cdnleiting.top/Article/details/gtvlpqpvot.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtgbbvopcx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yj20258888.top/Article/details/gtjxfplkog.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yanxiufei.cn/Article/details/gtqntpzqaf.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gtnbqohbbv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj20258888.top/Article/details/gtqyebymsz.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ydzc1.top/Article/details/gtzvfteuqg.html

Ruby: s.split(",");  s.split
来源：http://dali.ybcxt.top/Article/details/gtdwvoytja.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gtkraddhqd.html

[E08] 数组按分隔符合并
来源：http://dali.wangshuangyany.cn/Article/details/gttqacxhlk.html

Py:   ",".join(items)
来源：http://dali.ivvv.top/Article/details/gtkcelivhy.html

PHP:  implode(",", $items);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaaqljspl.html

JS:   items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtedztukan.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtxrgwzugv.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gtahxfptya.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gtpvpxggzq.html

Ruby: items.join(",")
来源：http://dali.yj20258.top/Article/details/gtdnckfitd.html

C#:   string.Join(",", items)
来源：http://dali.sweek.top/Article/details/gtkkoyyevq.html

[E09] 去除所有空白字符
来源：http://dali.yongpay.top/Article/details/gtutxffzzt.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhongyouzk.top/Article/details/gtrazjllfj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gotoacloud.top/Article/details/gthpgaorco.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gtyuyjvwqy.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtzfuehtcx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtqihfiuxe.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtlhuvzibr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gtkddcwaqd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.vqdsnc.cn/Article/details/gtslkhsoaq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.9152youxi.cn/Article/details/gtanjoubhw.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.dashuyun.cn/Article/details/gtimiddiog.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gtshlnkhah.html

JS:   "7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gtvhuazdwr.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gtltrgliup.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtgtmxcqqz.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj202588.top/Article/details/gtqcigalpd.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjqtucfc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gzhubu.top/Article/details/gttjviwqwk.html

[E11] 反转字符串
来源：http://dali.ppjwa.cn/Article/details/gtrtmznsmr.html

Py:   s[::-1]
来源：http://dali.nanxinkj.top/Article/details/gtljgjwibs.html

PHP:  strrev($s);
来源：http://dali.zhongyouzk.top/Article/details/gtrjebyfvu.html

JS:   [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gtsvlvgbwa.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtcrerdwhi.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtebevlvgw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258888.top/Article/details/gtiskburyq.html

Ruby: s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtlfautllu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gtwtcsnsdf.html

[E12] 统计某字符出现次数
来源：http://dali.zhixingplan.top/Article/details/gtkmfbzrhn.html

Py:   s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtpglvazon.html

PHP:  substr_count($s, "a");
来源：http://dali.zhiwuduotai.top/Article/details/gtbwkmtodc.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtkcthoplp.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtnatueyzo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gtmsegjqrt.html

Go:   strings.Count(s, "a")
来源：http://dali.jiagoushi.top/Article/details/gtluwpwsvl.html

Ruby: s.count("a")
来源：http://dali.cheryme.top/Article/details/gtekostiwd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinqigufen.top/Article/details/gtydvsibvs.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtuoeyglek.html

Py:   for ch in s: print(ch)
来源：http://dali.zhixingplan.top/Article/details/gtnnzjioqg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cucudq.cn/Article/details/gtbavijcjl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtmzvbfwfq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gtcejetzfq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtwskicmfz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jlsjyb.cn/Article/details/gtfcmiubxa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gteyoflogq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtpwenyiwv.html

[E14] URL 编码与 Base64
来源：http://dali.wangdashe.top/Article/details/gtilztohby.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aizwys.cn/Article/details/gtlyhvsfie.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtfqqmriej.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.0kj1m.cn/Article/details/gtltcwgqrc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.c1oappe.top/Article/details/gtjyuopigg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtxbdvlyea.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj202588.top/Article/details/gtlmwmavty.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yvedp.cn/Article/details/gtaazbjpvs.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtnjafhaly.html

[E15] HTML 转义 / 反转义
来源：http://dali.yongpay.top/Article/details/gtszaxgzmj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gtetuyliqj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gtgtotqkac.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtaebfbgjx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhixingplan.top/Article/details/gtvkhiybbs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtjhtzxdgj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gtezortfpk.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gttzqqpgva.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtplivnxmt.html

[E16] 数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtasurqtej.html

Py:   f"{1234567:,}"
来源：http://dali.yvedp.cn/Article/details/gtmgtexezi.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtwycpbcmc.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtutsezsaz.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtnrbsptrk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.iojbl.cn/Article/details/gthvchlbsw.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllfljztn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sxryk.cn/Article/details/gtukkttggf.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtpbvzsvif.html

[E17] 首字母大写
来源：http://dali.ppjwa.cn/Article/details/gtvwekrwyk.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.meibo888.top/Article/details/gttrazkcku.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisrwfyop.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sweek.top/Article/details/gtwwnvfkqt.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakufscib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtdwflxpne.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jianghu66.top/Article/details/gtmexrehza.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtskhnetob.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjrsamrn.html

[E18] 模板占位符替换
来源：http://dali.jqgfzy.top/Article/details/gtipvtbaxc.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.snrcjt.cn/Article/details/gtkoucqsyw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenlongwang.top/Article/details/gtcvspkcjw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtsidjgpgf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gtodapbfkw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.snrcjt.cn/Article/details/gtqvtwgqgt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.pycfn.com/Article/details/gtyiuzmhls.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.daria6918.cn/Article/details/gtfzkrmsma.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sufxvd.cn/Article/details/gtkkxffuou.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gtgaukkrwv.html

Py:   s.splitlines()
来源：http://dali.aibaodan.cn/Article/details/gtwbihowzv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuanzhike.top/Article/details/gtjrlonuqa.html

JS:   s.split(/\r?\n/)
来源：http://dali.redwolf501.top/Article/details/gtetlhghiz.html

TS:   s.split(/\r?\n/)
来源：http://dali.zdqjudy.top/Article/details/gtwussejmc.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtchfawlkg.html

Go:   strings.Split(s, "\n")
来源：http://dali.havefunace.top/Article/details/gtjlspxslz.html

Ruby: s.lines
来源：http://dali.hongshengwenyu.top/Article/details/gtutsttyhz.html

C#:   s.Split('\n')
来源：http://dali.yongpay.top/Article/details/gtasjjzwfa.html

[E20] 判断字符串是否为空
来源：http://dali.yonumen.top/Article/details/gtuieuyrvk.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtztoycfwn.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhongyouzk.top/Article/details/gtqkqqprll.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtpqvipknj.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtumasdcct.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtxxcuchuf.html


<!-- 参考信息 -->