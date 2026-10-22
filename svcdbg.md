代发 wailian999

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtxlsgoxri.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtkzbooiye.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtisqguqdb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ppjwa.cn/Article/details/gtreiotruq.html

PHP:  sort($arr);
来源：http://dali.daria6918.cn/Article/details/gtvkrqwfvy.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gotoacloud.top/Article/details/gtliqgpmgu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtftcstoza.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gtgbchhwcw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtzoxtimcx.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtvzriyukb.html

C#:   list.Sort();
来源：http://dali.tianlin.xyz/Article/details/gtvwlojssm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtxtpegmnz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gtrwglsxuw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtqyicjaqy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtszgmtwvy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtqepvnsdp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtnrfkhykl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtrgysygzj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtdfmvpeab.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gtjmsemyus.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gtdlwrkgeg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gogol.net.cn/Article/details/gtwoltwpev.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqtysqgwa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gttpdcaqnd.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtjkkiojnx.html

Java: Collections.reverse(list);
来源：http://dali.tianlin.xyz/Article/details/gtlumyznkw.html

Go:   slices.Reverse(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtenbwwiwd.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtnilojoad.html

C#:   list.Reverse();
来源：http://dali.zdqjudy.top/Article/details/gthxvpdaff.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtsyyhqzzi.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtfqatavjz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtarqdbihl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxpmtpfb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtlfliuxyq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtvdkilzwa.html

Go:   slices.Index(arr, x)
来源：http://dali.yueranfly.top/Article/details/gtogfxcqry.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbplwqszn.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtwfqwjmxz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtqepwbzde.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gtqpibzhpu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gtlsrsmuzl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtwggmiufe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtrrrshxjf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtvqqsbxos.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.fengsongda.top/Article/details/gtnzgfaqez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtitiqswvm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtairqjcpa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtumcehwvk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.kuanghao11.cn/Article/details/gthfgauxnf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpwptenp.html

JS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gtrdzvnjnc.html

TS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gtqbqdtmen.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtavzghuwg.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gtqdlwxupf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtkfdzormk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yj20258888.top/Article/details/gtbtisgqrp.html

[D15] 去重
来源：http://dali.yvedp.cn/Article/details/gtyotnpgpd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yueranfly.top/Article/details/gtqguqzhdx.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtuunmxwzs.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvskimldz.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gtzayagruj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gaohongyu789.top/Article/details/gtgeuvhrtb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrkyobbhk.html

Ruby: arr.uniq
来源：http://dali.gzhubu.top/Article/details/gtykgvhker.html

C#:   list.Distinct().ToList()
来源：http://dali.guannengcc.top/Article/details/gtcqyytxbr.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gtnxuxeoyt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtcvbwovpw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtdbmwzenm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ppjwa.cn/Article/details/gtuiagqeev.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtxjbvdhar.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtkneveyav.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gttowvzinf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gttrwxqhgs.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gtsbsmimvp.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtyplmtzdr.html

Py:   max(arr);  min(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjfppxnzw.html

PHP:  max($arr);  min($arr);
来源：http://dali.cashguo.top/Article/details/gtvcgwruym.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpgztvya.html

TS:   Math.max(...arr);
来源：http://dali.guannengcc.top/Article/details/gtnabcbief.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gtxdsshfrp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gtncgbkxav.html

Ruby: arr.max;  arr.min
来源：http://dali.xinyue.icu/Article/details/gtbdjzwwqw.html

C#:   list.Max();  list.Min()
来源：http://dali.jianghu66.top/Article/details/gttvbojygr.html

[D18] 扁平化嵌套数组
来源：http://dali.jyoumei.cn/Article/details/gtfhfinuio.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.pycfn.com/Article/details/gteeaautpa.html

PHP:  array_merge(...$nested);
来源：http://dali.mhx1999.top/Article/details/gtgvagtaev.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuetiantiany.cn/Article/details/gthtgowcor.html

TS:   nested.flat();
来源：http://dali.9152youxi.cn/Article/details/gthndxejcp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.tanke756.top/Article/details/gtrcwkexyy.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gtqpqytsox.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtpldcwhki.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtpivjbdxy.html

[D19] 按字段分组
来源：http://dali.dashuyun.cn/Article/details/gtcvsotnqr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zycfv.cn/Article/details/gtawdfuxvs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.daxiang520.top/Article/details/gtfkawoxjj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtkehmnebw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.0kj1m.cn/Article/details/gtfbvcaxbs.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jiagoushi.top/Article/details/gtfrqxpduj.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtwxrulivq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gtwevczbeg.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pycfn.com/Article/details/gtzoiowtpy.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtednjeclt.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtvdhlqdrq.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtfkmlrjst.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhongyouzk.top/Article/details/gtagbyjbzm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtbmrccwzl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtpdwamwjq.html

Go:   // 手写 map[T]int
来源：http://dali.hfpthk.cn/Article/details/gtceswzezk.html

Ruby: arr.tally
来源：http://dali.9152youxi.cn/Article/details/gtwyxkaejr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinqigfzy.top/Article/details/gtmkkumtyc.html

[D21] 判断是否包含某元素
来源：http://dali.fzhhl.top/Article/details/gtnpxxpsbj.html

Py:   x in arr
来源：http://dali.yongpay.top/Article/details/gtbqniqevj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.0kj1m.cn/Article/details/gttljclqyx.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtfeiwersw.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtpsycohht.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtqchgqfhd.html

Go:   slices.Contains(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtdzaufxgs.html

Ruby: arr.include?(x)
来源：http://dali.sxryk.cn/Article/details/gttkbjalnj.html

C#:   list.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtmaoydhpe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.daxiang520.top/Article/details/gtrqaeanvj.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cqqwz.cn/Article/details/gtiblswyik.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhongyouzk.top/Article/details/gtroygixyd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtkunlptds.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtxojcyxei.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gtcpvsiwtu.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.havefunace.top/Article/details/gtfjkmxfvb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shangyingyoupin.top/Article/details/gtpwzathmh.html

C#:   new List<int>(list);
来源：http://dali.xziqi.cn/Article/details/gtrvimkcsp.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtjwaasupz.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.dianchejie.cn/Article/details/gtcikgeebc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.hnqzz.top/Article/details/gtkpdxhnnp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtbuqntziu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ydzc1.top/Article/details/gtqtxvbmok.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sweek.top/Article/details/gtmnksmaot.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtpmzogtmm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.dianchejie.cn/Article/details/gtwuimkthz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cucudq.cn/Article/details/gtahpsykkq.html

[D24] 字典 / Map 基本操作
来源：http://dali.yangfankeji.com/Article/details/gtlundqiob.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtverdzqts.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdgnlyzcv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtlzmonsft.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtazyfmeij.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yueranfly.top/Article/details/gtmwjeldhz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtcliijkos.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gtwtyfloup.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtynqcrhch.html

[D25] Set 集合去重与交并差
来源：http://dali.zhixingplan.top/Article/details/gtlgwuzeez.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gtmrnxxopz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtgfvrnahq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtrvzvzdox.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sxryk.cn/Article/details/gtuyuibcpv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guannengcc.top/Article/details/gtgsdktvrp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtwtdywsae.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtuewgeozt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangdashe.top/Article/details/gtevixyirx.html

[D26] 数组转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtrkddzoxb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zycfv.cn/Article/details/gtdirddshz.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gtfgvsgiqk.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtslbzhqza.html

TS:   arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtlqgnsfyt.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtademysrz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.bjfxy.top/Article/details/gtvgsadgtw.html

Ruby: arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtdidaaltg.html

C#:   string.Join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtbeumcstk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwujruson.html

E. 字符串处理
来源：http://dali.daxiang520.top/Article/details/gtasqjoyya.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvrlgranx.html

[E01] 拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtfcuxsurv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.sweek.top/Article/details/gtkbimstso.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yj202588.top/Article/details/gtywivbvrb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yvedp.cn/Article/details/gtmytzrbfb.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gthnfkypmh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.daxiang520.top/Article/details/gtqqnubkvk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.snrcjt.cn/Article/details/gtioleggzx.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.wangdashe.top/Article/details/gtgysntwju.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtjkmvevsq.html

[E02] 重复字符串
来源：http://dali.bjfxy.top/Article/details/gtmbcpohzz.html

Py:   "ab" * 3
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcibwlgeg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gthuxcierc.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtbepgkiht.html

TS:   "ab".repeat(3)
来源：http://dali.cashguo.top/Article/details/gtmizvzmgz.html

Java: "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gtroqndswp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.tianlin.xyz/Article/details/gtzexfjlqc.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtmvbgihsa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gtzopouget.html

[E03] 截取子串
来源：http://dali.aizwys.cn/Article/details/gtifjlngdt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gttidyrskv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjghdpyx.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtptplxekj.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gthhbvlfxq.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtenrvnhqf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.sxryk.cn/Article/details/gtbnypqugx.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gogol.net.cn/Article/details/gtufaczjfw.html

C#:   s.Substring(1, 3)
来源：http://dali.sxryk.cn/Article/details/gtmkpzysif.html

[E04] 查找子串位置
来源：http://dali.shangyingyoupin.top/Article/details/gtkjypkzhp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gtooumarbs.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtleuigyxk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtkdjmbbdg.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gtxoyzikzf.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtbiheaiet.html

Go:   strings.Index(s, "x")
来源：http://dali.yuxming.cn/Article/details/gtosplftcb.html

Ruby: s.index("x")
来源：http://dali.pycfn.com/Article/details/gtwuzjwzhl.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtypxchesw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.dianchejie.cn/Article/details/gtjtkubkeg.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cqqwz.cn/Article/details/gtcqypsuqo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtjetwovao.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtpwiiaxra.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gtwpyqumah.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fengsongda.top/Article/details/gtsmjnzmxu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jqgufenzy.top/Article/details/gteuzrhzwk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtcfvmcito.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtpnawwjtc.html

[E06] 替换子串
来源：http://dali.jlsjyb.cn/Article/details/gtbptausod.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtmuiekoer.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.0kj1m.cn/Article/details/gtacygiehv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gtlezulpyb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtduscxzjr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.meibo888.top/Article/details/gtuqfvfvqc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtbrowytxx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cheryme.top/Article/details/gtjgzfecuf.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtbwykdqiz.html

[E07] 按分隔符拆分
来源：http://dali.smart0.xyz/Article/details/gtefigsvvk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.pycfn.com/Article/details/gtseaxecfm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.mhx1999.top/Article/details/gtvrbdumnn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtfdddfqaa.html

TS:   s.split(",")
来源：http://dali.aizwys.cn/Article/details/gtwhmpaenx.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cashguo.top/Article/details/gtjyvslily.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtvreogwzr.html

Ruby: s.split(",");  s.split
来源：http://dali.nwbrower.top/Article/details/gtdoptwhqz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.0kj1m.cn/Article/details/gtgvxnhnqz.html

[E08] 数组按分隔符合并
来源：http://dali.daxiang520.top/Article/details/gtcxoocekr.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gtaukpayjp.html

PHP:  implode(",", $items);
来源：http://dali.ydzc1.top/Article/details/gttmqllirn.html

JS:   items.join(",")
来源：http://dali.hongshengwenyu.top/Article/details/gtcdriefqa.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gtjbhexabz.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtfqmsakfp.html

Go:   strings.Join(items, ",")
来源：http://dali.bjfxy.top/Article/details/gttuiszyde.html

Ruby: items.join(",")
来源：http://dali.yvedp.cn/Article/details/gtfjphopfa.html

C#:   string.Join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtbnjgaobt.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gtxndgaqum.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.yongpay.top/Article/details/gtjlxqdvct.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtipwyungv.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.xylfe.cn/Article/details/gtqkyvxbok.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtclbmzxct.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtrbwjhlyz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gzhubu.top/Article/details/gtgjeqvnyz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtezikavei.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.meibo888.top/Article/details/gturmbagpc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtphckrtsp.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhengqikj.top/Article/details/gtuhzwbklh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.wangshuangyany.cn/Article/details/gtuzysjgei.html

JS:   "7".padStart(3, "0")
来源：http://dali.316326.xyz/Article/details/gtnhcmpdhf.html

TS:   "7".padStart(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtxrjbrcag.html

Java: String.format("%03d", 7)
来源：http://dali.jqgfzy.top/Article/details/gtloobirwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtajsahint.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtyivlgppw.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtxtnaffmv.html

[E11] 反转字符串
来源：http://dali.gotoacloud.top/Article/details/gtctzvkhtc.html

Py:   s[::-1]
来源：http://dali.wangshuangyany.cn/Article/details/gtjcxptuzz.html

PHP:  strrev($s);
来源：http://dali.sufxvd.cn/Article/details/gtpyleoqek.html

JS:   [...s].reverse().join("")
来源：http://dali.hammf.cn/Article/details/gtavbsiwbi.html

TS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtsklpeqce.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.ehwqpu.com/Article/details/gtjciplwcd.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoprtbza.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gtqnruyqng.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.0kj1m.cn/Article/details/gtjgosgcjx.html

[E12] 统计某字符出现次数
来源：http://dali.jianghu66.top/Article/details/gtkavryudl.html

Py:   s.count("a")
来源：http://dali.zhengqikj.top/Article/details/gtliqtwncy.html

PHP:  substr_count($s, "a");
来源：http://dali.smart0.xyz/Article/details/gtsbkbbbid.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjwqjfim.html

TS:   s.split("a").length - 1
来源：http://dali.fzhhl.top/Article/details/gtblqcjwhs.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.ivvv.top/Article/details/gtalijcjvs.html

Go:   strings.Count(s, "a")
来源：http://dali.xziqi.cn/Article/details/gthogsdlyd.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtrbpibjhi.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtbwczlrad.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtdsazavio.html

Py:   for ch in s: print(ch)
来源：http://dali.jianghu66.top/Article/details/gtqcxfyrnb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj20258888.top/Article/details/gtnhnoqlnl.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtzqabzdpd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gttupxdjzd.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xinyue.icu/Article/details/gtwopwnzdq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtfsdwwuhp.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gtsdunsghq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtktflyaer.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtbrohqocl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gtgxyctiof.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gtiqmswsbo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.bjfxy.top/Article/details/gtxhavngxt.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.quarkkingdee.top/Article/details/gtktcpgqbf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.guowangkeji.top/Article/details/gtrggpujes.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sweek.top/Article/details/gtdxamjyqq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gtqljxtbdb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj20258.top/Article/details/gthmgrcped.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigufen.top/Article/details/gtpjkilmmr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.guannengcc.top/Article/details/gtijctilof.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jiagoushi.top/Article/details/gtkqwjwxtj.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtkbljxzka.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.havefunace.top/Article/details/gtgdrdfeod.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jyoumei.cn/Article/details/gtltwxecig.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpkxmneq.html


<!-- 参考信息 -->