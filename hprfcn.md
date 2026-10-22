代发 wailian999

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gttpwnvfnb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtkqheekag.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gtimubkumr.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtnsgvwvxz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtndbezhgq.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtinlecvns.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gthyegbwoe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gtwccvwyyz.html

PHP:  sort($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtjvwnuppk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgufenzy.top/Article/details/gttbpdxsef.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtynbozznx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hysaishi.cn/Article/details/gtglvllfql.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtclwiltsz.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gtfhpcdihp.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrxmgbcb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gtdkijgemg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gtlluawzrl.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtiryzuvbp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtwiebppqw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtqyidlpya.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtbtsoggnd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xziqi.cn/Article/details/gtehsemqtv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.haohaochexian.top/Article/details/gtdhaysvyi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtnpdjvrvj.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtgjoamonp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtdqaqwjjx.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtnhslchuv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtsxduoogj.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtmvyfhrqx.html

Java: Collections.reverse(list);
来源：http://dali.hongshengwenyu.top/Article/details/gtmqqqixmd.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtqysacgvh.html

Ruby: arr.reverse
来源：http://dali.sysykeji.top/Article/details/gtbmuiqjhm.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtccasjaub.html

[D12] 查找元素下标
来源：http://dali.iojbl.cn/Article/details/gtrxjeazbw.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtvgudtiod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtzsyzcbrr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtgiontxgt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtlrqhpoyo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtdnbblgwr.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gtghebrklg.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gtdnwmdjky.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gtokbkexrq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gthvzgcruy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.svipenyu.cn/Article/details/gtispkgqyz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtbymxecom.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtranjmyct.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxejfvgq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.dianchejie.cn/Article/details/gtepopzoko.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.mhx1999.top/Article/details/gtbfmewtcy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gtwacxmbti.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aizwys.cn/Article/details/gtsfgrduxj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcoggacg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtxaglfdbz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthqftgdxh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtkftilxwq.html

TS:   arr.map(x => x * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmuwgksol.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtltmwifdj.html

Go:   // 手写循环
来源：http://dali.dianchejie.cn/Article/details/gtrpovrylc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gtlxiprysq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtcyjiynuj.html

[D15] 去重
来源：http://dali.sxryk.cn/Article/details/gtaskzkwxy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtfbddzscy.html

PHP:  array_unique($arr);
来源：http://dali.zdqjudy.top/Article/details/gtwerugpnd.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gtxvwrvhyh.html

TS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtduwzybzx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenzaomai.com/Article/details/gtoddhjmzc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoznbkvim.html

Ruby: arr.uniq
来源：http://dali.cashguo.top/Article/details/gtdfmydgtv.html

C#:   list.Distinct().ToList()
来源：http://dali.fzhhl.top/Article/details/gtshsndlrr.html

[D16] 求和与平均值
来源：http://dali.fengsongda.top/Article/details/gtswovutvo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tian-w.cn/Article/details/gtzkfzwing.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hfpthk.cn/Article/details/gthojxymve.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtmhapshkz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtrtliewfd.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtuukowsxw.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtxxfnthzr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hfpthk.cn/Article/details/gtkflzpqql.html

C#:   list.Sum();  list.Average()
来源：http://dali.bjfxy.top/Article/details/gtsglqjdsw.html

[D17] 最大值与最小值
来源：http://dali.ppjwa.cn/Article/details/gtvrmmxzvl.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gtqsuoaket.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtlaphmfjc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aibaodan.cn/Article/details/gtmzfaemad.html

TS:   Math.max(...arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfoshtbje.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.quarkkingdee.top/Article/details/gtxzjvzqlm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtphcaomzw.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtffmmyeof.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gtvwyacbwu.html

[D18] 扁平化嵌套数组
来源：http://dali.316326.xyz/Article/details/gtmlwewjct.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkxnkrmod.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtquzgqnzu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ybcxt.top/Article/details/gttvytmdeh.html

TS:   nested.flat();
来源：http://dali.tanke756.top/Article/details/gtrlxqoumq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zdqjudy.top/Article/details/gtmvxrlkcr.html

Go:   // 手写双层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchasbhov.html

Ruby: nested.flatten
来源：http://dali.tian-w.cn/Article/details/gtwwhsytgg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtjlnyueuf.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtyvxkbezj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xziqi.cn/Article/details/gtwdlitqon.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtjshtyanb.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtnxbtiruy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtssmezyil.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtficcaxzi.html

Go:   // 手写 map[string][]T
来源：http://dali.wangdashe.top/Article/details/gthuskgdvd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtmuobwoxh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtebtmbarw.html

[D20] 统计每个元素出现次数
来源：http://dali.jlsjyb.cn/Article/details/gtgtpzqmze.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtszphpbrr.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrwgdtlci.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gttibqlnam.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhfukooo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yangfankeji.com/Article/details/gtuohgbatx.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtqwzmfmzg.html

Ruby: arr.tally
来源：http://dali.shangyingyoupin.top/Article/details/gtfthvgkel.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtkxrodpjz.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdascylki.html

Py:   x in arr
来源：http://dali.jianghu66.top/Article/details/gtgjejmfsz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jqgfzy.top/Article/details/gtykszxgfh.html

JS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtkcrcnqjk.html

TS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gthvyucmjb.html

Java: list.contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtnnuqmmqo.html

Go:   slices.Contains(arr, x)
来源：http://dali.ivvv.top/Article/details/gtlzybhtkr.html

Ruby: arr.include?(x)
来源：http://dali.ybcxt.top/Article/details/gtaqorcrho.html

C#:   list.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtmmfvxkai.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hnqzz.top/Article/details/gtepijclxz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.sufxvd.cn/Article/details/gtzrfzkkke.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxuanxn.top/Article/details/gtzenontst.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbsjohyge.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtzfpvqvcw.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gtluktkxft.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sysykeji.top/Article/details/gtxhaorkoy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shzxlz.cn/Article/details/gtcpazerud.html

C#:   new List<int>(list);
来源：http://dali.svipenyu.cn/Article/details/gtrsdxzfhh.html

[D23] reduce 累积计算
来源：http://dali.bjfxy.top/Article/details/gtirsjzthh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.9152youxi.cn/Article/details/gtayqvmefx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.svipenyu.cn/Article/details/gtbikancih.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258888.top/Article/details/gtwdacxyss.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtewomnzij.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yj20258888.top/Article/details/gtipkcwrgk.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gtsadwswqx.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.9152youxi.cn/Article/details/gtxdtamxdr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zdqjudy.top/Article/details/gturhlrtlp.html

[D24] 字典 / Map 基本操作
来源：http://dali.nanxuanxn.top/Article/details/gtlveufxal.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtroohtypm.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhengqikj.top/Article/details/gtolhoavdv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtyukqcfmn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gtosmuklhg.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.quarkkingdee.top/Article/details/gtvamrrirj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gtesmjedix.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cashguo.top/Article/details/gtaefqzokd.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnqzz.top/Article/details/gtznzwnhuu.html

[D25] Set 集合去重与交并差
来源：http://dali.svipenyu.cn/Article/details/gtqjhahrzt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cdnleiting.top/Article/details/gtrcvhimbt.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ivvv.top/Article/details/gtzzoscvpg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.guowangkeji.top/Article/details/gtdchlpurc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yueranfly.top/Article/details/gtshnkpmsu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtvfidervn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gtaoleleva.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonggirwt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtdibaoina.html

[D26] 数组转字符串
来源：http://dali.tanke756.top/Article/details/gtktnkrtvv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gtimczvxpr.html

PHP:  implode(", ", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtqftmtxaj.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtrvllakjh.html

TS:   arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gtfunlgvqw.html

Java: String.join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtnijerecg.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxinkj.top/Article/details/gtmhjvptkg.html

Ruby: arr.join(", ")
来源：http://dali.ivvv.top/Article/details/gtpmntppdw.html

C#:   string.Join(", ", list)
来源：http://dali.quarkkingdee.top/Article/details/gtlacpexib.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtpqnmrccm.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gtvajjsqfz.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtcebzutvk.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gthnxjftis.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangdashe.top/Article/details/gtbdgqakxp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yonumen.top/Article/details/gtekfquwky.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ivvv.top/Article/details/gtdwlcfwhu.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtericzhml.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hywenlv.cn/Article/details/gtxzbhghbx.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdrybuag.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtnafeojkl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtjnsaqxvc.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gtzeyqpjld.html

Py:   "ab" * 3
来源：http://dali.haohaochexian.top/Article/details/gtxmugkuni.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sufxvd.cn/Article/details/gtximuyojj.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtyxpnyoie.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gtnukkaoxn.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtnhqlglop.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenzaomai.com/Article/details/gtfkhstjna.html

Ruby: "ab" * 3
来源：http://dali.snrcjt.cn/Article/details/gtcsmfcwdc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xziqi.cn/Article/details/gtlhtlmoeh.html

[E03] 截取子串
来源：http://dali.haohaochexian.top/Article/details/gtiqipyoti.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhongyouzk.top/Article/details/gtguamhuzt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtlfrcgutw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gtvbxhfsfr.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplcakjvp.html

Java: s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gttukawlcw.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtxlihlohx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtvckdthxh.html

C#:   s.Substring(1, 3)
来源：http://dali.andypj.xyz/Article/details/gtttcndljh.html

[E04] 查找子串位置
来源：http://dali.hongshengwenyu.top/Article/details/gtdnamlykh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ppjwa.cn/Article/details/gtotpsdzuo.html

PHP:  strpos($s, "x");
来源：http://dali.chenzaomai.com/Article/details/gtbvldfvbt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zdqjudy.top/Article/details/gtpsfktprx.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gthzuoarzj.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtjtetqbgy.html

Go:   strings.Index(s, "x")
来源：http://dali.havefunace.top/Article/details/gtopmxfzzr.html

Ruby: s.index("x")
来源：http://dali.wangshuangyany.cn/Article/details/gtwqfeqghv.html

C#:   s.IndexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtwohjvojl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtnldiknno.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yj20258888.top/Article/details/gtwwoyhkgs.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gtdepmauws.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sysykeji.top/Article/details/gtfzjgewnv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtuhvxnbzy.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xinyue.icu/Article/details/gtlovceogr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtzdqsvknu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinqigfzy.top/Article/details/gtyinkgdbb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxsnqdvd.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtwelacwdc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtpkndossc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cucudq.cn/Article/details/gtsripeuol.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gthbgxohav.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtaqypknqe.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtfnmssgna.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tianlin.xyz/Article/details/gtgrsuaquf.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cashguo.top/Article/details/gtbrekxgrh.html

C#:   s.Replace("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtryajvzbw.html

[E07] 按分隔符拆分
来源：http://dali.yj202588.top/Article/details/gtdwicamze.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtdcvrykbo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtipepzcbx.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jqgufenzy.top/Article/details/gthshsfdok.html

TS:   s.split(",")
来源：http://dali.zhijiandao.cn/Article/details/gthjpuhbhf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.snrcjt.cn/Article/details/gtgqfjoouv.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxuanxn.top/Article/details/gtgvytrbac.html

Ruby: s.split(",");  s.split
来源：http://dali.guannengcc.top/Article/details/gtofllivtm.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.dianchejie.cn/Article/details/gtkthqalyo.html

[E08] 数组按分隔符合并
来源：http://dali.nanxuanxn.top/Article/details/gtwdfncgze.html

Py:   ",".join(items)
来源：http://dali.dianchejie.cn/Article/details/gtmeciuedt.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gtefxaqlci.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtlwhslihd.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtfctqntap.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtldzuppvs.html

Go:   strings.Join(items, ",")
来源：http://dali.sufxvd.cn/Article/details/gtdkknmlnc.html

Ruby: items.join(",")
来源：http://dali.zhixingplan.top/Article/details/gtmtqcmfdb.html

C#:   string.Join(",", items)
来源：http://dali.yueranfly.top/Article/details/gtijekjseu.html

[E09] 去除所有空白字符
来源：http://dali.quarkkingdee.top/Article/details/gtpomsygch.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtwosxdpcf.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hfpthk.cn/Article/details/gtzlqfyfkl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jlsjyb.cn/Article/details/gtvmvgvvqf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yvedp.cn/Article/details/gtmaspgian.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ydzc1.top/Article/details/gtmcfpdksd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gtwflpqbgy.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigufen.top/Article/details/gtoxwwdmrj.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gtfsuiouwg.html

[E10] 左侧补零 / 定长填充
来源：http://dali.chenzaomai.com/Article/details/gtyxsnohla.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtvjagqklq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtjpvxuquf.html

JS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtryvmefkh.html

TS:   "7".padStart(3, "0")
来源：http://dali.aizwys.cn/Article/details/gtxbjtgtyh.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gthrnxflky.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gaohongyu789.top/Article/details/gtozfnkuun.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobbwtmjf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbzdpbxr.html

[E11] 反转字符串
来源：http://dali.yueranfly.top/Article/details/gtkqpqbvrp.html

Py:   s[::-1]
来源：http://dali.havefunace.top/Article/details/gtjpiwdmqb.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtcmsmgmxr.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtrgiqubzs.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtoxkloics.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.9152youxi.cn/Article/details/gtgkleupbg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gtbyumwiey.html

Ruby: s.reverse
来源：http://dali.yanxiufei.cn/Article/details/gtovsccqmh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gtnzeutqkn.html

[E12] 统计某字符出现次数
来源：http://dali.bjfxy.top/Article/details/gtqdrvoziw.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtugvhaibs.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtrjkgpuuo.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtgipvrcyj.html

TS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtzwsykacy.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zycfv.cn/Article/details/gtppstixru.html

Go:   strings.Count(s, "a")
来源：http://dali.snrcjt.cn/Article/details/gtzzmhefvm.html

Ruby: s.count("a")
来源：http://dali.0kj1m.cn/Article/details/gtfqunrmre.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jinghuilouyu.cn/Article/details/gttgdemiqx.html

[E13] 逐字符遍历
来源：http://dali.hywenlv.cn/Article/details/gtmlfowwwf.html

Py:   for ch in s: print(ch)
来源：http://dali.hfpthk.cn/Article/details/gtyhczoiyg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkesaqono.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqzhwlli.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtztzzhhsv.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtapkdflph.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cdnleiting.top/Article/details/gtcmsuhjny.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gtylakmhii.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtxdqsydek.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gteamgqntc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgfzy.top/Article/details/gtxkygrjed.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cheryme.top/Article/details/gthhladkef.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hongshengwenyu.top/Article/details/gtxadkjbqx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvhrslee.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtrdsfwmtg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtposhgaco.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtxuawgyts.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhoulong.xyz/Article/details/gtvsskcufs.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtunnbqxsj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gtfwjoccjp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jlsjyb.cn/Article/details/gtaloybcjj.html


<!-- 参考信息 -->