代发 wailian999

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtvqcjqegc.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtxpppyawu.html

Go:   arr[1:4]
来源：http://dali.shuidangran.top/Article/details/gttxpdtrli.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtyztfrcuz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtrdmnvi.html

[D08] 合并两个数组
来源：http://dali.guannengcc.top/Article/details/gtegkjsigw.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtcmvpzrhh.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwqemdmq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtdpbrmrun.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtrjvautdf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtnfjxwbzx.html

Go:   append(a, b...)
来源：http://dali.gzhubu.top/Article/details/gttbdaugnd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtmiyeprwy.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtugjncveg.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gtualfdkxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtjlkviwbp.html

PHP:  sort($arr);
来源：http://dali.9152youxi.cn/Article/details/gtfmxoycqj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtqbjgbnxg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtentwhgzw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtucjhrkgv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtyygimjec.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gthgecslkz.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtuuozdpum.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zycfv.cn/Article/details/gtgqhfsren.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmmhdipz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gthfsrtixv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtrcgtxusx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtibxdaotz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtwkgeqiss.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.andypj.xyz/Article/details/gtwvhegjyw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hywenlv.cn/Article/details/gtszrczohf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.haohaochexian.top/Article/details/gtiqbyzeap.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtkjjovxaf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gtczqmhvvp.html

PHP:  array_reverse($arr);
来源：http://dali.sysykeji.top/Article/details/gtjlblafha.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtxffekjeh.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtvvmtvbov.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gthhfasasn.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtslolteqw.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gtxwwuzbpp.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtkzgvnwuj.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmftxouik.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gtalxncmid.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtmwonnjvf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtwloopczy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gthukjiioz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258888.top/Article/details/gtvushifdq.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqpvymki.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtrpquldqe.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtwqitmtsj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gtfuyowqgu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gtvwbotyoo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtrxsnobfo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtnosbcleb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gthdrgzrth.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gtbhzfjgwn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtjfgictsf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cdnleiting.top/Article/details/gtgpwmngwj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtkimklhdt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.9152youxi.cn/Article/details/gtzlfnygoa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.andypj.xyz/Article/details/gtvoghvfps.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtgfeegujm.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtlfzbvhbs.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gtjdjlmyum.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtemenskcm.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtootjrcmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtpmqfyxms.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gttfajzmut.html

[D15] 去重
来源：http://dali.snrcjt.cn/Article/details/gtptwrcnvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtdyoyltmq.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtmrisrano.html

JS:   [...new Set(arr)]
来源：http://dali.jinghuilouyu.cn/Article/details/gteagjzide.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtjdzydpig.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigufen.top/Article/details/gtnpibczzt.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwplmfdbs.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gtjhdcsgiq.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtuhacukqk.html

[D16] 求和与平均值
来源：http://dali.gzhubu.top/Article/details/gtfqygavzj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtyxwjrtxv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtwcabycbc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtwaefxulk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtxldqdefl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cqqwz.cn/Article/details/gtymbghxyx.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsuswsly.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gtncmefuyz.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gttkfmzgdr.html

[D17] 最大值与最小值
来源：http://dali.gaohongyu789.top/Article/details/gtshsdxbyw.html

Py:   max(arr);  min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjkrbflaw.html

PHP:  max($arr);  min($arr);
来源：http://dali.birdmap.top/Article/details/gtdxkmileu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtgqboukxp.html

TS:   Math.max(...arr);
来源：http://dali.guowangkeji.top/Article/details/gtcogppghs.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtuxlqgztl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbnreevrp.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtcupwuvny.html

C#:   list.Max();  list.Min()
来源：http://dali.jyoumei.cn/Article/details/gtsbtlhcnq.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gtkjbsnmtr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gttzafluet.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqouegfx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gtoahwsqrm.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtmzqfgtdf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gtpbfcagcs.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtyizhsgoi.html

Ruby: nested.flatten
来源：http://dali.zhiwuduotai.top/Article/details/gtibfnandx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gtkploefyh.html

[D19] 按字段分组
来源：http://dali.guannengcc.top/Article/details/gtmtubeafb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtmkyfhkwy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gthfudmztz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtlmmneoby.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnbinemh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtmraixmen.html

Go:   // 手写 map[string][]T
来源：http://dali.nanxinkj.top/Article/details/gtekzxkeda.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dianchejie.cn/Article/details/gtaecolvey.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gtvlvvegqk.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtjyqfbxcb.html

Py:   Counter(arr)
来源：http://dali.ydzc1.top/Article/details/gtgdwdbxkc.html

PHP:  array_count_values($arr);
来源：http://dali.daria6918.cn/Article/details/gtmexnzztu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yanxiufei.cn/Article/details/gtlkxrjbaw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtjbsshiac.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.bjfxy.top/Article/details/gtztkzfuka.html

Go:   // 手写 map[T]int
来源：http://dali.fengsongda.top/Article/details/gttuoreiud.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gtoecunrsi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj202588.top/Article/details/gthgjihqfd.html

[D21] 判断是否包含某元素
来源：http://dali.daxiang520.top/Article/details/gtxagokbff.html

Py:   x in arr
来源：http://dali.dianchejie.cn/Article/details/gtgtculsua.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cheryme.top/Article/details/gtrlmduvbt.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtkmuzagpx.html

TS:   arr.includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtikxobdhf.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtyefiscrx.html

Go:   slices.Contains(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaonubkgg.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtresghkvq.html

C#:   list.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtofnylaey.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gtsrganwww.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtdxquoxkd.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtieodqpwg.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfxrlfpey.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gtwgghfwym.html

Java: new ArrayList<>(list);
来源：http://dali.nwbrower.top/Article/details/gtsbothuud.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.ivvv.top/Article/details/gtjyqcszex.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtjjgpnfhi.html

C#:   new List<int>(list);
来源：http://dali.shuidangran.top/Article/details/gtervkkifn.html

[D23] reduce 累积计算
来源：http://dali.zhiwuduotai.top/Article/details/gtesszunme.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.wangdashe.top/Article/details/gtdablucmq.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.316326.xyz/Article/details/gtjwvmbixl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ivvv.top/Article/details/gtumicdkwd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtkltwufqp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.shuidangran.top/Article/details/gtsppchohp.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtrymmjrji.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gaohongyu789.top/Article/details/gtmthwspkx.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhijiandao.cn/Article/details/gtcwptqgkp.html

[D24] 字典 / Map 基本操作
来源：http://dali.fzhhl.top/Article/details/gtddernmzw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtwdbydqoe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ydzc1.top/Article/details/gttfrsziwa.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.aibaodan.cn/Article/details/gtfgimczlj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtfkqpzoyy.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hnqzz.top/Article/details/gtzfzjtzhx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.nanxinkj.top/Article/details/gteihefsni.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fzhhl.top/Article/details/gtslspubkb.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.havefunace.top/Article/details/gtcjegertq.html

[D25] Set 集合去重与交并差
来源：http://dali.xylfe.cn/Article/details/gtcdesvwrd.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gtrpxglmxj.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.pycfn.com/Article/details/gtplibfteb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jyoumei.cn/Article/details/gtmcellvfc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yuxming.cn/Article/details/gtranotnjc.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.guowangkeji.top/Article/details/gtdsdtgylh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jlsjyb.cn/Article/details/gtcqemeoip.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gtdigjdhxw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.gzhubu.top/Article/details/gtbnnacgfb.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtpebtyknb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtrgoeekum.html

PHP:  implode(", ", $arr);
来源：http://dali.yonumen.top/Article/details/gtjalhqiad.html

JS:   arr.join(", ")
来源：http://dali.jinqigufen.top/Article/details/gtiwdreupt.html

TS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtyfnfhajq.html

Java: String.join(", ", list)
来源：http://dali.chenjidiqi.icu/Article/details/gtbdgviled.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxpijxbqr.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gtwrzfcvam.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfyyoijmf.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtjxwlmruc.html

E. 字符串处理
来源：http://dali.jinqigufen.top/Article/details/gtrtlaqdmy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpflyral.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtfqsyfwfu.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.guannengcc.top/Article/details/gtnfkjhwsg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gtkdrmtbom.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj202588.top/Article/details/gtemfywcli.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.sxryk.cn/Article/details/gtvbzbgime.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.gotoacloud.top/Article/details/gtshfdgsuk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnasonhwm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ydzc1.top/Article/details/gtxflvhdgz.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtygjvbrgg.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtfqxfxqro.html

Py:   "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtqeiekxwu.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtihsflwps.html

JS:   "ab".repeat(3)
来源：http://dali.xylfe.cn/Article/details/gtnbwgjgez.html

TS:   "ab".repeat(3)
来源：http://dali.hysaishi.cn/Article/details/gtnxgcbxza.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gttylmmnmr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yj20258.top/Article/details/gtjsdixzfe.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gttbzejqbf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtocwjkgov.html

[E03] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtxvhzxric.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtdcaugtks.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gtuelaagjt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtecizsuju.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gthvkwyjhp.html

Java: s.substring(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtcrlugpwg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtdwmzyyvd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhoulong.xyz/Article/details/gtbtgiiffe.html

C#:   s.Substring(1, 3)
来源：http://dali.xinyue.icu/Article/details/gtmncsnylc.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtdlekdqtg.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtptbrxqdw.html

PHP:  strpos($s, "x");
来源：http://dali.shangyingyoupin.top/Article/details/gtuquqbttr.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gttmiwftic.html

TS:   s.indexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtbldrtcpa.html

Java: s.indexOf("x")
来源：http://dali.quarkkingdee.top/Article/details/gtqimkgsfa.html

Go:   strings.Index(s, "x")
来源：http://dali.nwbrower.top/Article/details/gtcazsskgo.html

Ruby: s.index("x")
来源：http://dali.yuxming.cn/Article/details/gteqpthzsh.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gthtgwtjys.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gtuxgqxexs.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guannengcc.top/Article/details/gthyriqxvl.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.nanxinkj.top/Article/details/gtcwaalsmy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtwwtsgfbk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.snrcjt.cn/Article/details/gtrpmtoxwb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuanzx.com/Article/details/gttldztxfn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cashguo.top/Article/details/gtcmablftm.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.c1oappe.top/Article/details/gtigjvjgnu.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gttemlawth.html

[E06] 替换子串
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwqgtjjr.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yuanzhike.top/Article/details/gtzkahamuk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fengsongda.top/Article/details/gthdzycwyc.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtvwhcrobf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtvbjqxnuj.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.nanxinkj.top/Article/details/gtigcxbrsc.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.nanxinkj.top/Article/details/gtzjoinruy.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbrdpmti.html

C#:   s.Replace("a", "b")
来源：http://dali.havefunace.top/Article/details/gtoeqpqnns.html

[E07] 按分隔符拆分
来源：http://dali.vqdsnc.cn/Article/details/gtemlbszhq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.cheryme.top/Article/details/gtbtawwmcp.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtdpakxunj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jinqigfzy.top/Article/details/gtpraeppxl.html

TS:   s.split(",")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmnqisee.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jinqigfzy.top/Article/details/gtqgxtivjb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtqfwraxuv.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gtzwtuxgiv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj20258.top/Article/details/gtpaaqhhkd.html

[E08] 数组按分隔符合并
来源：http://dali.fengsongda.top/Article/details/gtwdcswdoi.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtizabawwd.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtvycdugma.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtphpedmrj.html

TS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gteafacqer.html

Java: String.join(",", items)
来源：http://dali.yj20258888.top/Article/details/gtlvxrpgpn.html

Go:   strings.Join(items, ",")
来源：http://dali.9152youxi.cn/Article/details/gtupjnrnhq.html

Ruby: items.join(",")
来源：http://dali.xuetiantiany.cn/Article/details/gtpetfajax.html

C#:   string.Join(",", items)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgpxzylf.html

[E09] 去除所有空白字符
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzgzgreh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhengqikj.top/Article/details/gteligmmeo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ivvv.top/Article/details/gtgjycibkl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gttcxfdori.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.guowangkeji.top/Article/details/gtkovfdhjm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtzvfbdnyg.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtbycibkwz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.zhoulong.xyz/Article/details/gtkclqyzmx.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.smart0.xyz/Article/details/gtjdfnqdqd.html

[E10] 左侧补零 / 定长填充
来源：http://dali.iojbl.cn/Article/details/gtqyqpwuge.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gthnnvozno.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.andypj.xyz/Article/details/gtjrrpliis.html

JS:   "7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtokqmurvd.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtckgpbhfw.html

Java: String.format("%03d", 7)
来源：http://dali.0kj1m.cn/Article/details/gtcdnhvrva.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhongyouzk.top/Article/details/gtjiogclan.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhiwuduotai.top/Article/details/gtgmgxkrns.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenjidiqi.icu/Article/details/gtmxttgtey.html

[E11] 反转字符串
来源：http://dali.havefunace.top/Article/details/gtmaolturj.html

Py:   s[::-1]
来源：http://dali.0kj1m.cn/Article/details/gtytcfbuas.html

PHP:  strrev($s);
来源：http://dali.ybcxt.top/Article/details/gtufkenqik.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtkxdncoes.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtehmjsbre.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.dashuyun.cn/Article/details/gtesqxtgnx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gttcodygqs.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gtfyvnaepm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.cheryme.top/Article/details/gtosoqfqof.html

[E12] 统计某字符出现次数
来源：http://dali.smart0.xyz/Article/details/gtckifgjfs.html

Py:   s.count("a")
来源：http://dali.yongpay.top/Article/details/gtezlmvyhn.html

PHP:  substr_count($s, "a");
来源：http://dali.havefunace.top/Article/details/gtzqgagphu.html

JS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gtaheqwabj.html

TS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtupnjcwny.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fzhhl.top/Article/details/gtvhzxfzqw.html

Go:   strings.Count(s, "a")
来源：http://dali.yvedp.cn/Article/details/gthzrpcxgu.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtgstfptdd.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtjymycwws.html

[E13] 逐字符遍历
来源：http://dali.jlsjyb.cn/Article/details/gteiakhtiv.html

Py:   for ch in s: print(ch)
来源：http://dali.xylfe.cn/Article/details/gtrotwmcey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gtgyvxjiay.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzubtnhhj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangshuangyany.cn/Article/details/gthxmmmend.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zycfv.cn/Article/details/gtudgujyht.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gttmffpweg.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gtqfyjaxlw.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtygplbmfc.html

[E14] URL 编码与 Base64
来源：http://dali.yongpay.top/Article/details/gtbpbtmuav.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtbeikxkuy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cucudq.cn/Article/details/gtwykmhpwe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.aizwys.cn/Article/details/gtxtajobgv.html


<!-- 参考信息 -->