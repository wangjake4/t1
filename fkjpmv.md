代发 wailian999

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtenebyawe.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtypuzdaem.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtgajkezac.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gtahbsoorr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtvlzlzrlv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtrmtqrqig.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zdqjudy.top/Article/details/gtdwhkfnds.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtqxshbsrl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtvrjgglyg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gtbofvynbw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtwzzjdnkc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gzhubu.top/Article/details/gtqxbikzzo.html

[D11] 反转数组
来源：http://dali.aibaodan.cn/Article/details/gtculdxcwz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtoreomnkp.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtqhwkxrrv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jiagoushi.top/Article/details/gtbwddjtoc.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtdokszqyy.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtroevjcew.html

Go:   slices.Reverse(arr)
来源：http://dali.ehwqpu.com/Article/details/gttmhtvjlm.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtnaaoyhzw.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gtzmcbqejt.html

[D12] 查找元素下标
来源：http://dali.pycfn.com/Article/details/gtldgrgwtr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtnwduztof.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtevqwkolz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtfniupxac.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucygkpfm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.birdmap.top/Article/details/gtbnmyzcry.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtsyxqhezw.html

Ruby: arr.index(x)
来源：http://dali.daxiang520.top/Article/details/gttohmdjuh.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtpzqekehg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.fzhhl.top/Article/details/gtjejffpip.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtemgxfjuq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gtcblugtua.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnusbibnj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtlcmbjzby.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtyzqqkkce.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dashuyun.cn/Article/details/gtoovekfqs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xinyue.icu/Article/details/gtxfnjlucu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtfhwbhfja.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtyvyidzvl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtxntrorne.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtrqgexirc.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtwbbzhzbf.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtypiptybn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinqigfzy.top/Article/details/gthbtpmjgr.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gticrydyjr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtxflvfzbh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtfoveequn.html

[D15] 去重
来源：http://dali.wangdashe.top/Article/details/gtfdfampzl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtjwlaerzh.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gtqijbhbqt.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtefxtzevk.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtswhagpti.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtweidwbnk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtiptaevmz.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtazwmeeuy.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtbzldhbtu.html

[D16] 求和与平均值
来源：http://dali.nanxinkj.top/Article/details/gtyiyffqnl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtwcvkjeyl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtqxgofyza.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtwdoznfzq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtvnydbhar.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgacaltxt.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtzudyaqsw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgsnbnsx.html

C#:   list.Sum();  list.Average()
来源：http://dali.sufxvd.cn/Article/details/gtsxggrkzp.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtcafrhrpo.html

Py:   max(arr);  min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvcumvxg.html

PHP:  max($arr);  min($arr);
来源：http://dali.dashuyun.cn/Article/details/gtmjnhzkas.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gtmhhyblfa.html

TS:   Math.max(...arr);
来源：http://dali.daria6918.cn/Article/details/gtzxkzftui.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gttizwgkue.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gttgsezieb.html

Ruby: arr.max;  arr.min
来源：http://dali.ppjwa.cn/Article/details/gtnhziavrq.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtiyaziasp.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gtiijnvumo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxinkj.top/Article/details/gtqqiunzoe.html

PHP:  array_merge(...$nested);
来源：http://dali.meibo888.top/Article/details/gtfxnbtajq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hongshengwenyu.top/Article/details/gtvlbsrgsy.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtohzktaot.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gthuqazkdz.html

Go:   // 手写双层循环
来源：http://dali.jinqigfzy.top/Article/details/gtulfjdmzc.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gtetkwktca.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.andypj.xyz/Article/details/gtrovpebtm.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtfglxxlnc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hfpthk.cn/Article/details/gtzyfhebcw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cqqwz.cn/Article/details/gtcfzpmlki.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.vqdsnc.cn/Article/details/gtdwzqhvvm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtethlfsmy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtfbpzvmay.html

Go:   // 手写 map[string][]T
来源：http://dali.sxryk.cn/Article/details/gtlnumgnzy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtcnzefsaf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhongyouzk.top/Article/details/gtpymymhkh.html

[D20] 统计每个元素出现次数
来源：http://dali.xuanzx.com/Article/details/gtcqmbikct.html

Py:   Counter(arr)
来源：http://dali.chenlongwang.top/Article/details/gtnqnqqxfm.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtehzdafng.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yuxming.cn/Article/details/gtzzeyroxu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gtbtmjdzvk.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagldksma.html

Go:   // 手写 map[T]int
来源：http://dali.tanke756.top/Article/details/gtpbfqtdll.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtwwluunjx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtcordbptt.html

[D21] 判断是否包含某元素
来源：http://dali.dashuyun.cn/Article/details/gtoycgfonz.html

Py:   x in arr
来源：http://dali.cheryme.top/Article/details/gtasczbfue.html

PHP:  in_array($x, $arr, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtasefnana.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gteczhsyvz.html

TS:   arr.includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtzgokscoj.html

Java: list.contains(x)
来源：http://dali.ybcxt.top/Article/details/gtgffdiwcg.html

Go:   slices.Contains(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtswygugnt.html

Ruby: arr.include?(x)
来源：http://dali.yuxming.cn/Article/details/gtbotqbtpi.html

C#:   list.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtfovjrcxk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daria6918.cn/Article/details/gtsimxbphc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.guannengcc.top/Article/details/gtwlmwfbnq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yvedp.cn/Article/details/gtcexsphdy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.chenzaomai.com/Article/details/gtxcdtrzvc.html

TS:   [...arr];
来源：http://dali.pycfn.com/Article/details/gtmvglqcqz.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gtbgildsub.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtaaigtkhd.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shanyushiyangtech.top/Article/details/gtcnbmfuco.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gtqrxjeyvm.html

[D23] reduce 累积计算
来源：http://dali.svipenyu.cn/Article/details/gtytgorwev.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.0kj1m.cn/Article/details/gtpboldkld.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtdbpnejmi.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xuanzx.com/Article/details/gtqldfilul.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gtsotsjkgn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jqgfzy.top/Article/details/gtermpquqb.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gtehqsnphg.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtgoxupfdl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pengpengdd.cyou/Article/details/gtptfjjtys.html

[D24] 字典 / Map 基本操作
来源：http://dali.daria6918.cn/Article/details/gtnhyfxdtw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.havefunace.top/Article/details/gtgyyruwuc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gtggtjqwks.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.tianlin.xyz/Article/details/gtnwykodiy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtnfzjrlex.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.haohaochexian.top/Article/details/gtmgpflekp.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hammf.cn/Article/details/gtbhdidxaw.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zdqjudy.top/Article/details/gtnbadqfks.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gtxiwedmcp.html

[D25] Set 集合去重与交并差
来源：http://dali.0kj1m.cn/Article/details/gtuumnkbjy.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fengsongda.top/Article/details/gtouwwivnk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xuetiantiany.cn/Article/details/gttpoafruv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hysaishi.cn/Article/details/gtasxlpyle.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zdqjudy.top/Article/details/gtaratqowm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gtvlfkxtjn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.316326.xyz/Article/details/gtuptifgnr.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hammf.cn/Article/details/gtjtokxewu.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ehwqpu.com/Article/details/gtepqlerct.html

[D26] 数组转字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekzdgwet.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtmwwvkqpm.html

PHP:  implode(", ", $arr);
来源：http://dali.iojbl.cn/Article/details/gtxgtuwffo.html

JS:   arr.join(", ")
来源：http://dali.316326.xyz/Article/details/gtutfbwnkn.html

TS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtzpnkcajj.html

Java: String.join(", ", list)
来源：http://dali.9152youxi.cn/Article/details/gthdtqaofv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zdqjudy.top/Article/details/gtgdiqqmcq.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtfedhzdrh.html

C#:   string.Join(", ", list)
来源：http://dali.yongpay.top/Article/details/gtknwajjsy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtapqruiud.html

E. 字符串处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmcbwqkp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtybkksyhz.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtiaqxjmli.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.meibo888.top/Article/details/gtvygvqqrs.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gtgxnrfblq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gogol.net.cn/Article/details/gtwwcptuhc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gtxrfvepmo.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yuxming.cn/Article/details/gtcuysbrfy.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtwhlmzbls.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenlongwang.top/Article/details/gtrkjiaois.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvhpbxmg.html

[E02] 重复字符串
来源：http://dali.zhoulong.xyz/Article/details/gtxqyplhoj.html

Py:   "ab" * 3
来源：http://dali.ivvv.top/Article/details/gtqckwfzdr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtmspharrd.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtpwlbcqms.html

TS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gthxhdicws.html

Java: "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gtdturmzuo.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtivkmsylc.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gttgvkabqd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gtzpecnlsb.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtcrgvfdcp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jyoumei.cn/Article/details/gtmmcgzenr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtoutvedxj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtpjprryza.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtfmfonagm.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtrylpmtng.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhengqikj.top/Article/details/gtdnlwmulv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrxpxbzlj.html

C#:   s.Substring(1, 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlklusjf.html

[E04] 查找子串位置
来源：http://dali.nanxuanxn.top/Article/details/gtcvqorvsu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqvgyxcpo.html

PHP:  strpos($s, "x");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjznwffkh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gtuqjqnbyn.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gtxnpfqkqo.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtfftxtynd.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtatlliusm.html

Ruby: s.index("x")
来源：http://dali.jinqigfzy.top/Article/details/gtnqidjpmk.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gthgizcnkv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuetiantiany.cn/Article/details/gtitoakpqt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtwzwwwzrr.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gzhubu.top/Article/details/gtgcaozpfw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.svipenyu.cn/Article/details/gtemiuyvtn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtuddflvzb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gaohongyu789.top/Article/details/gthcegvbmd.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.yonumen.top/Article/details/gtayjqkyqc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ivvv.top/Article/details/gthtgsjbih.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gtcgiekeeu.html

[E06] 替换子串
来源：http://dali.birdmap.top/Article/details/gtrymimcmv.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtlusdvlqc.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtdkpfizlt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtaxtutjtk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtkprvwktr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gthpciozci.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtctmtraxw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gthfyykacr.html

C#:   s.Replace("a", "b")
来源：http://dali.cashguo.top/Article/details/gtmkqvgxhq.html

[E07] 按分隔符拆分
来源：http://dali.gaohongyu789.top/Article/details/gtenhxqpcj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.9152youxi.cn/Article/details/gtnfjhwbkp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtyrrwyaxb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yj202588.top/Article/details/gtkwbaegiw.html

TS:   s.split(",")
来源：http://dali.sweek.top/Article/details/gtdsigypae.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahqjkxnx.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gtvkjnmode.html

Ruby: s.split(",");  s.split
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqelylbn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yanxiufei.cn/Article/details/gtilvpbgjo.html

[E08] 数组按分隔符合并
来源：http://dali.gotoacloud.top/Article/details/gtppymiefw.html

Py:   ",".join(items)
来源：http://dali.gaohongyu789.top/Article/details/gtiernfhys.html

PHP:  implode(",", $items);
来源：http://dali.iojbl.cn/Article/details/gtxolgzgek.html

JS:   items.join(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxqkriwc.html

TS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gttqoptxho.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gtdlmeihgu.html

Go:   strings.Join(items, ",")
来源：http://dali.guannengcc.top/Article/details/gtebbrlouf.html

Ruby: items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtmyegpwtd.html

C#:   string.Join(",", items)
来源：http://dali.aizwys.cn/Article/details/gtjonbjoik.html

[E09] 去除所有空白字符
来源：http://dali.shangyingyoupin.top/Article/details/gtzfcmyana.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.hnxiangtu.top/Article/details/gternvgoeq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqsvoqzu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.aibaodan.cn/Article/details/gtxbceavcj.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.kuanghao11.cn/Article/details/gtvysalzrt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtfekaubbh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ivvv.top/Article/details/gtxnnpdosx.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cucudq.cn/Article/details/gtyszjbrxw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.birdmap.top/Article/details/gtgngbzltf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cdnleiting.top/Article/details/gtyeqjptem.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtbfwfegcz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.sweek.top/Article/details/gtfrsiokkb.html

JS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtvjlcoabp.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtqcbxhmrb.html

Java: String.format("%03d", 7)
来源：http://dali.guowangkeji.top/Article/details/gtxywsdzuk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gtswtqhsos.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.quarkkingdee.top/Article/details/gthugmostx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtxdiiigmq.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvrbgrfl.html

Py:   s[::-1]
来源：http://dali.gotoacloud.top/Article/details/gtkdyphbzf.html

PHP:  strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtqsummgtl.html

JS:   [...s].reverse().join("")
来源：http://dali.tianlin.xyz/Article/details/gtwjutykkk.html

TS:   [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gthagummko.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtgzvnocje.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtxshpeoeh.html

Ruby: s.reverse
来源：http://dali.yangfankeji.com/Article/details/gtjozwdwyf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtlsbpwjok.html

[E12] 统计某字符出现次数
来源：http://dali.fengsongda.top/Article/details/gtzrgptpnw.html

Py:   s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtzufchmeo.html

PHP:  substr_count($s, "a");
来源：http://dali.nanxuanxn.top/Article/details/gtsuqevicj.html

JS:   s.split("a").length - 1
来源：http://dali.gogol.net.cn/Article/details/gtkupusulq.html

TS:   s.split("a").length - 1
来源：http://dali.yj20258.top/Article/details/gtwnerxisr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yuxming.cn/Article/details/gtovtifyen.html

Go:   strings.Count(s, "a")
来源：http://dali.ybcxt.top/Article/details/gtrqffpgpp.html

Ruby: s.count("a")
来源：http://dali.yuanzhike.top/Article/details/gttczfjbtb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.redwolf501.top/Article/details/gtjrbrdztg.html

[E13] 逐字符遍历
来源：http://dali.xinyue.icu/Article/details/gtmkxkwimi.html

Py:   for ch in s: print(ch)
来源：http://dali.bjfxy.top/Article/details/gttvaodhra.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttovxwnul.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gtlukhrhlz.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtpazlbrcm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pycfn.com/Article/details/gtertzmqlb.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.wangdashe.top/Article/details/gtnbnmlxsr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.havefunace.top/Article/details/gtglmmjjop.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gtrsjuvutm.html

[E14] URL 编码与 Base64
来源：http://dali.yuxming.cn/Article/details/gtaowrrorn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gtmppudcgw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtndrrdjec.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yanxiufei.cn/Article/details/gtveicjqkf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yuxming.cn/Article/details/gtmiznrnko.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gtqhjyrncv.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.316326.xyz/Article/details/gtbqrynbcv.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dianchejie.cn/Article/details/gtsvrdvzke.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtiakichbb.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gtwuqhkvqg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuanzhike.top/Article/details/gtxdgwzbaq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sxryk.cn/Article/details/gtbbnjedvw.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gtjgkwihwc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ppjwa.cn/Article/details/gtbuzreuyr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.birdmap.top/Article/details/gtrsksuwvx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtxkkyfvqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnqzz.top/Article/details/gtrglhgvda.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.vqdsnc.cn/Article/details/gtzziqcpst.html

[E16] 数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtlomrqqmj.html

Py:   f"{1234567:,}"
来源：http://dali.jyoumei.cn/Article/details/gtrcclxzuc.html

PHP:  number_format(1234567);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlbletqn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtanhpvqvi.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtpytkgpcu.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrerzylzq.html


<!-- 参考信息 -->