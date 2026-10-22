代发 wailian999

[D11] 反转数组
来源：http://dali.nanxinkj.top/Article/details/gtebomuvsx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtdmgzipqi.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtxjnxxtcj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gteotdxcfj.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gtsyymlhug.html

Java: Collections.reverse(list);
来源：http://dali.guannengcc.top/Article/details/gtpqctersi.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gtuqcbvvye.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gtftljhdzq.html

C#:   list.Reverse();
来源：http://dali.sxryk.cn/Article/details/gtlzxzqcfe.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gtnxiwbwne.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gtlyivizei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtnbfxczbl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gteqdzruge.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtiemqkgrl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gteslweupn.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtfkbadocj.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtffriyniv.html

C#:   list.IndexOf(x);
来源：http://dali.sxryk.cn/Article/details/gtpjakglcl.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhixingplan.top/Article/details/gtyevqufic.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtphkvvsjv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gtpmmywjmx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcksusgxj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gtmjhhnlsh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fengsongda.top/Article/details/gtcdnfgvcn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gtuwmlfxng.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtxzlwvykt.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtehrqxrkq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cqqwz.cn/Article/details/gtvyyatwgl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnqzz.top/Article/details/gtzcdyminq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhixingplan.top/Article/details/gtizzcatke.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtvurnvgmn.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtzcuqbzrl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtbvhxvlja.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtyowjipxz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtemzpizjp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtpstgvjxp.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gtxltbkkqz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zycfv.cn/Article/details/gtdnvqqzih.html

PHP:  array_unique($arr);
来源：http://dali.9152youxi.cn/Article/details/gttqcbgjro.html

JS:   [...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtougvaoab.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtffweszeg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtzsowholw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gtsaedcmrj.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtsbbalnzi.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtmueirave.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gtnafppylw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xziqi.cn/Article/details/gtxyvuwzyo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.c1oappe.top/Article/details/gtrznaowdf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtbxxekgyq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtxqgrxqes.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtmlrmchbf.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtzugltsbp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.wangdashe.top/Article/details/gtqmvkyykq.html

C#:   list.Sum();  list.Average()
来源：http://dali.gotoacloud.top/Article/details/gtcnlpuups.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtkvnfasca.html

Py:   max(arr);  min(arr)
来源：http://dali.yangfankeji.com/Article/details/gtevpctgfl.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gthgelisjx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.chenzaomai.com/Article/details/gtawevegya.html

TS:   Math.max(...arr);
来源：http://dali.haohaochexian.top/Article/details/gtfopewbaw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtpeljlcbl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtnpaceqyj.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtvwfbzrir.html

C#:   list.Max();  list.Min()
来源：http://dali.gogol.net.cn/Article/details/gtsbtjgwqv.html

[D18] 扁平化嵌套数组
来源：http://dali.9152youxi.cn/Article/details/gtiqaztbdd.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yvedp.cn/Article/details/gtossuhvbi.html

PHP:  array_merge(...$nested);
来源：http://dali.fengsongda.top/Article/details/gtcbxhjcwu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zdqjudy.top/Article/details/gtdryypqus.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gtvfrcybij.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtfnlfsuyv.html

Go:   // 手写双层循环
来源：http://dali.cqqwz.cn/Article/details/gtjmyhzsee.html

Ruby: nested.flatten
来源：http://dali.smart0.xyz/Article/details/gtkxzjeswb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.havefunace.top/Article/details/gtoeicotte.html

[D19] 按字段分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhinubjp.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gthzdxxfqz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtxgyqvcqs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sysykeji.top/Article/details/gtfzyuvsdh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfzbtexs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.svipenyu.cn/Article/details/gtmaaxymsa.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtivgwgaaf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gtpwbsbnnv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtrtmmqqqr.html

[D20] 统计每个元素出现次数
来源：http://dali.kuanghao11.cn/Article/details/gtudvxhdte.html

Py:   Counter(arr)
来源：http://dali.xziqi.cn/Article/details/gtifhzbepi.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtgvxcvptu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gtpyzlipla.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtyjsuilry.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenjidiqi.icu/Article/details/gtyawkurvo.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtokqlfdry.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gtmtfenslw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtwcrvjzir.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gtznwwmvjk.html

Py:   x in arr
来源：http://dali.gotoacloud.top/Article/details/gtghvgbxkt.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dianchejie.cn/Article/details/gthmpxvagx.html

JS:   arr.includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtosekcvqk.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtbclnvpsu.html

Java: list.contains(x)
来源：http://dali.guannengcc.top/Article/details/gtlazmfxva.html

Go:   slices.Contains(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtejevyyqv.html

Ruby: arr.include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtrpyzlykl.html

C#:   list.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbljfugph.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenzaomai.com/Article/details/gthtcicyso.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xinyue.icu/Article/details/gtgzqnejkl.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtncpruuze.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sweek.top/Article/details/gtaopsrvib.html

TS:   [...arr];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnijfzidf.html

Java: new ArrayList<>(list);
来源：http://dali.svipenyu.cn/Article/details/gtjcppxunu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yangfankeji.com/Article/details/gtoyfrusua.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hysaishi.cn/Article/details/gtkyszkjgv.html

C#:   new List<int>(list);
来源：http://dali.zdqjudy.top/Article/details/gtlmpyjuey.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gtjesulryx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.c1oappe.top/Article/details/gtthkseqkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.daria6918.cn/Article/details/gtqjyisjcf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ybcxt.top/Article/details/gtsplifugo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shzxlz.cn/Article/details/gtmrorvfox.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtrmgpultr.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtqkizohos.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtuiqflxhx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gtrtnpxpyg.html

[D24] 字典 / Map 基本操作
来源：http://dali.jqgufenzy.top/Article/details/gtyevkbpsw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cheryme.top/Article/details/gtkmekghsu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.fzhhl.top/Article/details/gtqluhevrz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhoulong.xyz/Article/details/gtodccjgux.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtkztfpitj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtmamdegig.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtjyxmpfar.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.gogol.net.cn/Article/details/gtcbhthpsp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.chenjidiqi.icu/Article/details/gtpvhtdltp.html

[D25] Set 集合去重与交并差
来源：http://dali.feifeiyinyue.top/Article/details/gtxqkkibcu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuanzhike.top/Article/details/gtvisgvolr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtdxicasys.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.aibaodan.cn/Article/details/gtvgiehxtb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gtltmvquwk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.gogol.net.cn/Article/details/gtqiiiangt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.svipenyu.cn/Article/details/gtzmjroyxr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cheryme.top/Article/details/gtportrjwq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ybcxt.top/Article/details/gtcpkxhnjz.html

[D26] 数组转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtwgwkobzt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrucmbmkt.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtymhcyrym.html

JS:   arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gthomnssme.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtwnhoihdo.html

Java: String.join(", ", list)
来源：http://dali.hammf.cn/Article/details/gtlkvavuls.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yuanzhike.top/Article/details/gtfrjdhmrs.html

Ruby: arr.join(", ")
来源：http://dali.zhiwuduotai.top/Article/details/gtwirixzqm.html

C#:   string.Join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtuiykqqkl.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtwtxuilhv.html

E. 字符串处理
来源：http://dali.bjfxy.top/Article/details/gtweardxuv.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtkkflpfpj.html

[E01] 拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtiqagsdha.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuetiantiany.cn/Article/details/gthyfjgqck.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.bjfxy.top/Article/details/gtpwsbmccn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtgpupfokt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtvofzdqov.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.ppjwa.cn/Article/details/gtsummvcml.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtnocviilb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangshuangyany.cn/Article/details/gtztkglqna.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtyfgffloa.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gthyyinjjo.html

Py:   "ab" * 3
来源：http://dali.guannengcc.top/Article/details/gtjwplofrz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.svipenyu.cn/Article/details/gtpijnsimt.html

JS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtqucdsgls.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gtbgipvdsu.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjkaulmm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtcslbipcy.html

Ruby: "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtvhfafjrl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hfpthk.cn/Article/details/gtjuigzwjy.html

[E03] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtvapokdoa.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtjdyfhrjg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangshuangyany.cn/Article/details/gtweyonych.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtogzvxqqu.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtbyidnuwa.html

Java: s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gtfkrrbmdy.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigufen.top/Article/details/gtjfflmrjc.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gtwbzzhntk.html

C#:   s.Substring(1, 3)
来源：http://dali.hammf.cn/Article/details/gtwqoshiiq.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtmosibaxe.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xziqi.cn/Article/details/gtymevfyug.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtuvqiyyej.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shzxlz.cn/Article/details/gtcszdwjph.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtrqtfwigh.html

Java: s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtzfrgpjym.html

Go:   strings.Index(s, "x")
来源：http://dali.chenzaomai.com/Article/details/gtrwlpcqvh.html

Ruby: s.index("x")
来源：http://dali.meibo888.top/Article/details/gtvkgirvzn.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtkcqazmpv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hnqzz.top/Article/details/gtuylssqjt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtqtyzrxqw.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xylfe.cn/Article/details/gtequfhiar.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jiagoushi.top/Article/details/gtvsilyiry.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.jinqigufen.top/Article/details/gtedqnkmqj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gtebhxrswj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtswgrvetx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yj20258.top/Article/details/gtqzjimvhl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gtryxreghp.html

[E06] 替换子串
来源：http://dali.zhengqikj.top/Article/details/gtkkdvdhiy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guowangkeji.top/Article/details/gtchxygtyz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yangfankeji.com/Article/details/gtyaqjiecu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ybcxt.top/Article/details/gtqvfsaies.html

TS:   s.replaceAll("a", "b")
来源：http://dali.wangdashe.top/Article/details/gttojwhoqz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258888.top/Article/details/gtmokyzkde.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtabjjvpcs.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtjbgsybci.html

C#:   s.Replace("a", "b")
来源：http://dali.pycfn.com/Article/details/gtenstrojd.html

[E07] 按分隔符拆分
来源：http://dali.havefunace.top/Article/details/gtkzcaaweq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gtewluusam.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtffdicvtf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.tian-w.cn/Article/details/gtpwmfvuhg.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtqillymqi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.haohaochexian.top/Article/details/gtmwcyrptn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.mhx1999.top/Article/details/gtbqgoedyr.html

Ruby: s.split(",");  s.split
来源：http://dali.yanxiufei.cn/Article/details/gtjeuairue.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.kuanghao11.cn/Article/details/gthzmuzlme.html

[E08] 数组按分隔符合并
来源：http://dali.0kj1m.cn/Article/details/gttwyjxdta.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtmyiatmao.html

PHP:  implode(",", $items);
来源：http://dali.shangyingyoupin.top/Article/details/gtxwbyrcbu.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtdjwugqop.html

TS:   items.join(",")
来源：http://dali.jyoumei.cn/Article/details/gtibkwsuza.html

Java: String.join(",", items)
来源：http://dali.cheryme.top/Article/details/gtrexkvqer.html

Go:   strings.Join(items, ",")
来源：http://dali.zhijiandao.cn/Article/details/gtzedqamgd.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtflgceynl.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtxrphxbho.html

[E09] 去除所有空白字符
来源：http://dali.cashguo.top/Article/details/gtyurwsjih.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gteeeofeqm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnoqbevi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtiahjssuu.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shzxlz.cn/Article/details/gtvcyeajbv.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tanke756.top/Article/details/gtkbvazsrt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guannengcc.top/Article/details/gtbnphfrjx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtguqzezrd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gtqousffrc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.havefunace.top/Article/details/gtmimzyuta.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtukllnija.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtipjzwsxn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtolpmtxti.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtpuqcaxrg.html

Java: String.format("%03d", 7)
来源：http://dali.yonumen.top/Article/details/gtizvmrdah.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtlgzmjckj.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gtuffmvbkd.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.316326.xyz/Article/details/gtvmwpsomw.html

[E11] 反转字符串
来源：http://dali.hnqzz.top/Article/details/gtesooxabm.html

Py:   s[::-1]
来源：http://dali.yueranfly.top/Article/details/gthzrvaruw.html

PHP:  strrev($s);
来源：http://dali.cashguo.top/Article/details/gtepdbklts.html

JS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtwvyocfcz.html

TS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gtfxomtjsf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daria6918.cn/Article/details/gtpbnbqnxs.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gtfhvcidjd.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtxksvdzzx.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gthosxvgrh.html

[E12] 统计某字符出现次数
来源：http://dali.vqdsnc.cn/Article/details/gtlbhrjmiz.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtuwpefqkq.html

PHP:  substr_count($s, "a");
来源：http://dali.yvedp.cn/Article/details/gtrdvuvsok.html

JS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtjwdglcsb.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtcvzizatb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cheryme.top/Article/details/gtmyksxdcn.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtdxvianoa.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtobviovxp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yanxiufei.cn/Article/details/gtsjxgiuqn.html

[E13] 逐字符遍历
来源：http://dali.jinqigufen.top/Article/details/gtzugbvaja.html

Py:   for ch in s: print(ch)
来源：http://dali.hysaishi.cn/Article/details/gtqdcxgyxp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.sweek.top/Article/details/gtxhrtdhdc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cheryme.top/Article/details/gtiovowjsh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtftnmosdj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtkpgiusif.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gaohongyu789.top/Article/details/gtnvqusuxq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuetiantiany.cn/Article/details/gtmiwvqxsx.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajaaymun.html

[E14] URL 编码与 Base64
来源：http://dali.daria6918.cn/Article/details/gtvugmpchc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuxming.cn/Article/details/gtslyruwsy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.guannengcc.top/Article/details/gtznmmziey.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtoqdtpawq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtrngznkjf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.dianchejie.cn/Article/details/gtlxdoxota.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hywenlv.cn/Article/details/gtmegrelrg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.wangdashe.top/Article/details/gthxmowadh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtcqftudav.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtohnxtsek.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gogol.net.cn/Article/details/gtmjpjsjaw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.havefunace.top/Article/details/gtgrlaobzg.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fengsongda.top/Article/details/gtcabzwwgc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.andypj.xyz/Article/details/gtvpxqspyg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.shangyingyoupin.top/Article/details/gtxzvouyaq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj202588.top/Article/details/gtoedsbxcx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtosfzykiz.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hywenlv.cn/Article/details/gtrzjasjyf.html

[E16] 数字千分位
来源：http://dali.shanyushiyangtech.top/Article/details/gtlftqwbuw.html

Py:   f"{1234567:,}"
来源：http://dali.quarkkingdee.top/Article/details/gtjaodxhqi.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtlsomrqqw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtlvxqesbh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgdqhhenl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtidqlckrg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jlsjyb.cn/Article/details/gtuqlqbmiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shzxlz.cn/Article/details/gterrklfcc.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtuqtiqfep.html

[E17] 首字母大写
来源：http://dali.xinyue.icu/Article/details/gtjnjbslzv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtkdunynfd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dianchejie.cn/Article/details/gthozymtmz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenzaomai.com/Article/details/gtmfovutfe.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gaohongyu789.top/Article/details/gtlqocgbbf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtobcumhzw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gtcfswwngf.html

Ruby: s.capitalize
来源：http://dali.hfpthk.cn/Article/details/gtnpbxkzzr.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gtbfbcmcze.html


<!-- 参考信息 -->