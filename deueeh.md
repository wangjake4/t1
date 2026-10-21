代发 wailian999

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtoovqaypq.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtunpvbujc.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtampojchf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gttlgvqwrh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtwpqckyya.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtngexvuqa.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jiagoushi.top/Article/details/gtcyuzhmcw.html

Go:   // 手写循环累加
来源：http://dali.fzhhl.top/Article/details/gthrvwbvij.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gtsqmmzyrw.html

C#:   list.Sum();  list.Average()
来源：http://dali.chenzaomai.com/Article/details/gtnzrbxcjg.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gtuvklbcwi.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtoxuylehc.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgfzy.top/Article/details/gtqjarambl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfvztudtm.html

TS:   Math.max(...arr);
来源：http://dali.chenzaomai.com/Article/details/gtknwpzyvr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gtxlbkiimd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ehwqpu.com/Article/details/gtietxbqln.html

Ruby: arr.max;  arr.min
来源：http://dali.316326.xyz/Article/details/gtmoioxlyp.html

C#:   list.Max();  list.Min()
来源：http://dali.c1oappe.top/Article/details/gtciuaquap.html

[D18] 扁平化嵌套数组
来源：http://dali.tanke756.top/Article/details/gtfgbeethv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.havefunace.top/Article/details/gtxtrdbpui.html

PHP:  array_merge(...$nested);
来源：http://dali.yueranfly.top/Article/details/gtguhltgfn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tian-w.cn/Article/details/gtjpcssdue.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtqnfipjys.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinqigufen.top/Article/details/gtvdkyvvhb.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gtivcxqvqy.html

Ruby: nested.flatten
来源：http://dali.pengpengdd.cyou/Article/details/gtnxgaaeuk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuxming.cn/Article/details/gtzsyminjz.html

[D19] 按字段分组
来源：http://dali.snrcjt.cn/Article/details/gtztdfgjqw.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrjeffbq.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guannengcc.top/Article/details/gtecyqwfeo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtiuqasopb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj20258.top/Article/details/gtcxagtkpa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jqgfzy.top/Article/details/gtwwuzffde.html

Go:   // 手写 map[string][]T
来源：http://dali.smart0.xyz/Article/details/gtvscyubsu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gtimpbpsye.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtjvewqrcf.html

[D20] 统计每个元素出现次数
来源：http://dali.hysaishi.cn/Article/details/gtxhzwtzli.html

Py:   Counter(arr)
来源：http://dali.dashuyun.cn/Article/details/gtnxzgiaie.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtcdpfngvs.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtotrfnosy.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gtclpnybdt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj202588.top/Article/details/gtkfzsheeo.html

Go:   // 手写 map[T]int
来源：http://dali.pycfn.com/Article/details/gtbsapekci.html

Ruby: arr.tally
来源：http://dali.yangfankeji.com/Article/details/gtwpxlscmx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtpywlztrz.html

[D21] 判断是否包含某元素
来源：http://dali.redwolf501.top/Article/details/gtunefhulw.html

Py:   x in arr
来源：http://dali.mhx1999.top/Article/details/gtxgvpnnmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.tian-w.cn/Article/details/gtfvizrncz.html

JS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtqsvbtspe.html

TS:   arr.includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvvkhonwb.html

Java: list.contains(x)
来源：http://dali.xuanzx.com/Article/details/gteoujpgca.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtwjpazxps.html

Ruby: arr.include?(x)
来源：http://dali.sysykeji.top/Article/details/gtnexzazjm.html

C#:   list.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtdlbmnduk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.snrcjt.cn/Article/details/gtqehlgyhq.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ivvv.top/Article/details/gtpsnglncv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.pycfn.com/Article/details/gtsjejfapx.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yj20258888.top/Article/details/gtpnnqhcuv.html

TS:   [...arr];
来源：http://dali.jianghu66.top/Article/details/gtpdnxvupf.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtktfbfzkc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtyacfximt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hongshengwenyu.top/Article/details/gtkqrfxqch.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtfihpxajt.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtkrxmiuyx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guannengcc.top/Article/details/gtwxvpvagv.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gteuhcupti.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gtmcgruufk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.aizwys.cn/Article/details/gtshkxsxjf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.redwolf501.top/Article/details/gtngdpiaqa.html

Go:   // 手写循环
来源：http://dali.xinyue.icu/Article/details/gtbebdlzdu.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenlongwang.top/Article/details/gttfonipap.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tanke756.top/Article/details/gtvrzadnpk.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gtaqbuepeg.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.wangdashe.top/Article/details/gtwfsdvyut.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.cucudq.cn/Article/details/gtvlyfrjyy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sufxvd.cn/Article/details/gtjgazekog.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtrrmmlcnp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.birdmap.top/Article/details/gtatejbmte.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhoulong.xyz/Article/details/gtfmedacah.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyylkdam.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yuxming.cn/Article/details/gtfudqacze.html

[D25] Set 集合去重与交并差
来源：http://dali.shuidangran.top/Article/details/gtbcspmfvh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.0kj1m.cn/Article/details/gtolwypshr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gtknvviioz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.c1oappe.top/Article/details/gtynhcykuf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hammf.cn/Article/details/gthxyxunjt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.birdmap.top/Article/details/gtnctquigp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gtmwnosucx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.snrcjt.cn/Article/details/gtysfaywab.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenjidiqi.icu/Article/details/gttazjetel.html

[D26] 数组转字符串
来源：http://dali.sufxvd.cn/Article/details/gtymxvsucn.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtnwkylmkf.html

PHP:  implode(", ", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzftdtyq.html

JS:   arr.join(", ")
来源：http://dali.sxryk.cn/Article/details/gtfrrqxzos.html

TS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtawplxmnn.html

Java: String.join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghzvzazw.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gtapthcihc.html

Ruby: arr.join(", ")
来源：http://dali.ydzc1.top/Article/details/gtewpzczoh.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gttgydjuvw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiscbxyjo.html

E. 字符串处理
来源：http://dali.chenlongwang.top/Article/details/gtqitodjfq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtveodzdmk.html

[E01] 拼接字符串
来源：http://dali.jqgfzy.top/Article/details/gttqfvdpvd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yanxiufei.cn/Article/details/gtblbxxjgh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cashguo.top/Article/details/gtkvqmohbo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gtnsvqnaxh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gtcazaebmn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhongyouzk.top/Article/details/gtxnfhvpjw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.kuanghao11.cn/Article/details/gtubtjbufu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcslsnwf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtzrqscxsq.html

[E02] 重复字符串
来源：http://dali.hnxiangtu.top/Article/details/gtdsfpguqw.html

Py:   "ab" * 3
来源：http://dali.hnxiangtu.top/Article/details/gtanxcudmp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shuidangran.top/Article/details/gtqpseechc.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtzakatqii.html

TS:   "ab".repeat(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysqbknok.html

Java: "ab".repeat(3)
来源：http://dali.sweek.top/Article/details/gtdtssfqyf.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxnqleajy.html

Ruby: "ab" * 3
来源：http://dali.andypj.xyz/Article/details/gtoqygzyub.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtlgaevzxp.html

[E03] 截取子串
来源：http://dali.pengpengdd.cyou/Article/details/gtluwvvhxs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gtbmhwaboi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtbbsjscjj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtjxgthzjq.html

TS:   s.slice(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gtilaziqrm.html

Java: s.substring(1, 4)
来源：http://dali.jyoumei.cn/Article/details/gtskiszxeq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtrrbuceil.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtvoykeerf.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtwnhdzakn.html

[E04] 查找子串位置
来源：http://dali.zycfv.cn/Article/details/gtngjzvsns.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtajnddscz.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gtlrquxvvl.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jiagoushi.top/Article/details/gticrxsape.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gtywcuiazn.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtvjbethiy.html

Go:   strings.Index(s, "x")
来源：http://dali.haohaochexian.top/Article/details/gtwudazijy.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtmzevzlxo.html

C#:   s.IndexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtxhwmnlrc.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dashuyun.cn/Article/details/gtxzckylpp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.sysykeji.top/Article/details/gtgtpswmub.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.hysaishi.cn/Article/details/gtncmjheyh.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtzyanrbps.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhixingplan.top/Article/details/gtdynzcqez.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.haohaochexian.top/Article/details/gtkoywgsne.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hysaishi.cn/Article/details/gtdfunzyxm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtacbdfgct.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jqgfzy.top/Article/details/gtqumhommi.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gthgvursmo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.redwolf501.top/Article/details/gtjhudduny.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.bjfxy.top/Article/details/gtdyyvynnu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gtdvqpszgt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gtxjpyxsiz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtpxhgqlps.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gteteodgqq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cucudq.cn/Article/details/gthgvylfbg.html

C#:   s.Replace("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtiitlzney.html

[E07] 按分隔符拆分
来源：http://dali.hysaishi.cn/Article/details/gtqxxbwhpw.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jyoumei.cn/Article/details/gtmgvarror.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfyhkaxz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gtbfqjiury.html

TS:   s.split(",")
来源：http://dali.bjfxy.top/Article/details/gtioiloehv.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangdashe.top/Article/details/gtmobujrqe.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jianghu66.top/Article/details/gtlpxirxhu.html

Ruby: s.split(",");  s.split
来源：http://dali.xinyue.icu/Article/details/gtvdgaleij.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.quarkkingdee.top/Article/details/gtubqcprfl.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtrmbrcjdd.html

Py:   ",".join(items)
来源：http://dali.jqgufenzy.top/Article/details/gtmmyzkmkp.html

PHP:  implode(",", $items);
来源：http://dali.cdnleiting.top/Article/details/gtvawvcyec.html

JS:   items.join(",")
来源：http://dali.ppjwa.cn/Article/details/gtqqbyqqte.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtakjbpszl.html

Java: String.join(",", items)
来源：http://dali.xuanzx.com/Article/details/gtjnhalxjz.html

Go:   strings.Join(items, ",")
来源：http://dali.daria6918.cn/Article/details/gtkdduckth.html

Ruby: items.join(",")
来源：http://dali.ybcxt.top/Article/details/gtmybkamxa.html

C#:   string.Join(",", items)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzmkgldz.html

[E09] 去除所有空白字符
来源：http://dali.guowangkeji.top/Article/details/gtnlonnktn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.ehwqpu.com/Article/details/gtlskkiqlu.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sysykeji.top/Article/details/gtimqmxqkc.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gotoacloud.top/Article/details/gthhuewcrd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yonumen.top/Article/details/gtywnicynj.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sysykeji.top/Article/details/gtodqvcmuu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtkrczprqm.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gtcxvueskk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.shangyingyoupin.top/Article/details/gtwfunadyq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hnqzz.top/Article/details/gtdvtkwyiv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtafoadgiu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhongyouzk.top/Article/details/gtvuhlbnxq.html

JS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtruhukvdm.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtrsrgbkmg.html

Java: String.format("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtmwqrnwos.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtmkopxgsq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtoivvpufe.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuxming.cn/Article/details/gtkojxwbxy.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtappuwqtx.html

Py:   s[::-1]
来源：http://dali.tanke756.top/Article/details/gteypjffrd.html

PHP:  strrev($s);
来源：http://dali.xuanzx.com/Article/details/gtznzahztq.html

JS:   [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtjeretfua.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtlfjletmd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hammf.cn/Article/details/gtrhwkbodh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtihdoerwj.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtdnqjilkp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.shzxlz.cn/Article/details/gtzukdlcbq.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gthjspmylr.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtbadvadjb.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtpfrmjmfj.html

JS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gtxjvpgxmd.html

TS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtuxbygjjt.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtthppwqkb.html

Go:   strings.Count(s, "a")
来源：http://dali.sweek.top/Article/details/gtqjgyctri.html

Ruby: s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtpiyetxti.html

C#:   s.Count(c => c == 'a')
来源：http://dali.fengsongda.top/Article/details/gtlvvjjisg.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtdtnamnuy.html

Py:   for ch in s: print(ch)
来源：http://dali.quarkkingdee.top/Article/details/gtashqlozu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.havefunace.top/Article/details/gtsxqnzmdw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtjfzolxbj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hnqzz.top/Article/details/gtzlgyotgc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtoceihhgv.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtydwrxncm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ppjwa.cn/Article/details/gtwvigkqdj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinqigufen.top/Article/details/gtysyklfeo.html

[E14] URL 编码与 Base64
来源：http://dali.hfpthk.cn/Article/details/gtkfqdevuk.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtgjbnykcv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtpwxwjpvv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlqkmfck.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gtmsabadfz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hnqzz.top/Article/details/gtusdvimxa.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhiwuduotai.top/Article/details/gtgjhplckc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258888.top/Article/details/gtghzepxbg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtsephnhht.html

[E15] HTML 转义 / 反转义
来源：http://dali.jianghu66.top/Article/details/gtpeqcejwn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hammf.cn/Article/details/gtqohlxyrg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.snrcjt.cn/Article/details/gtxwhdtbzw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhoulong.xyz/Article/details/gtxgtyzvqp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigfzy.top/Article/details/gtzbttvsmr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgufenzy.top/Article/details/gtybftgume.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gtdufvdltr.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.guowangkeji.top/Article/details/gtecqagtjk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthjwcgghy.html

[E16] 数字千分位
来源：http://dali.quarkkingdee.top/Article/details/gtwbesvqvb.html

Py:   f"{1234567:,}"
来源：http://dali.jqgfzy.top/Article/details/gtlviymwvu.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtgaksegyf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtcotwuvah.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ydzc1.top/Article/details/gtbaedjoce.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtwzvostdn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sysykeji.top/Article/details/gtffaeivhv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sweek.top/Article/details/gtvatujdjp.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gtvwambsdg.html

[E17] 首字母大写
来源：http://dali.zhiwuduotai.top/Article/details/gtsshtszwa.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtuwgwtbgi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ehwqpu.com/Article/details/gtfyvbypzj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtesrbgvnz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqryazkeu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqugvpkhw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tian-w.cn/Article/details/gtsxygrxjh.html

Ruby: s.capitalize
来源：http://dali.sweek.top/Article/details/gtlibmttrb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guowangkeji.top/Article/details/gtdhqwvrnh.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtimkxtfnk.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yonumen.top/Article/details/gtiplueikp.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.quarkkingdee.top/Article/details/gtevzmzjna.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtovwksggh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtlohijkkg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngrrqkzm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtgwceergv.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtnnftmxxw.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cdnleiting.top/Article/details/gtbxwkcptx.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gthquscnbw.html

Py:   s.splitlines()
来源：http://dali.yongpay.top/Article/details/gtkyaymekn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtaihhsuhc.html

JS:   s.split(/\r?\n/)
来源：http://dali.tanke756.top/Article/details/gtmmphlbub.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhongyouzk.top/Article/details/gtmkmranap.html

Java: s.lines().toList()
来源：http://dali.shuidangran.top/Article/details/gtvnaxxjip.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gtbxfoahui.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtdlwkymny.html

C#:   s.Split('\n')
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwlocnsv.html

[E20] 判断字符串是否为空
来源：http://dali.sweek.top/Article/details/gtddsjnggo.html

Py:   if not s:
来源：http://dali.hongshengwenyu.top/Article/details/gtpqmoghqs.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gtflluemof.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gtjrxehsst.html

TS:   if (s === "") {}
来源：http://dali.9152youxi.cn/Article/details/gtbdfjqaeh.html

Java: if (s.isEmpty()) {}
来源：http://dali.yj20258.top/Article/details/gtlfdrivfa.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtmprgamwt.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtusgrtiun.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtcqdspvyd.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtlbvxxuls.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.guowangkeji.top/Article/details/gtoelxgvxc.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.andypj.xyz/Article/details/gtzotlxbht.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gtdkoqwwbn.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gthxswdior.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtaezfuoiw.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shuidangran.top/Article/details/gtvlqpaolm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdmuwgky.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gtkbtpenai.html

[E22] 字节长度与字符长度
来源：http://dali.cashguo.top/Article/details/gtoweqysfi.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.snrcjt.cn/Article/details/gtvbueawcm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtjtebevnt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.9152youxi.cn/Article/details/gtivueyjwg.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gthmytizia.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.birdmap.top/Article/details/gtlhfwreeq.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.gzhubu.top/Article/details/gttmlitxpk.html

Ruby: s.bytesize;  s.length
来源：http://dali.xylfe.cn/Article/details/gtdvqtxbsn.html


<!-- 参考信息 -->