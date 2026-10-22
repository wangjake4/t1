代发 wailian999

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtbrevhskw.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtvudazooj.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gthealkcur.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtqfcuzfif.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtubrsediq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gtwcedzycr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtfohidylx.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtayisqham.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtscqwbwke.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtdqcxsgpe.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtylalgbie.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtztlsemxd.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtxvoypppl.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gttjwacdve.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtjfzlidmb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gtzybxlrhi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtmlbjjqjf.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfedqcqm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtcugeyrgt.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gtjyzkohgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtswxppnos.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtfxjqqzhy.html

[D09] 排序（升序）
来源：http://dali.feifeiyinyue.top/Article/details/gtqkqnzwrd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yueranfly.top/Article/details/gtofrpuyty.html

PHP:  sort($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdcqdaozb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtyfjtwqmw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gthimbwiyn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gtvoycuptv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gtelkswdoy.html

Ruby: arr.sort
来源：http://dali.aizwys.cn/Article/details/gtjxhpvupz.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtdjheewwm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkverzzaa.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtncxmhuhz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtiyziyeel.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtaxydhpzb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtdswqwkyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gtcebfleym.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gtdpbmdpho.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkvdkcxw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtayzqrzkb.html

[D11] 反转数组
来源：http://dali.yongpay.top/Article/details/gtjzpdmyar.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdigjfswq.html

PHP:  array_reverse($arr);
来源：http://dali.jiagoushi.top/Article/details/gtncvpfdds.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtgwwtqlzc.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtiinlruqj.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtppjhqzuh.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtpfurvbvr.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gtfsymzkbs.html

C#:   list.Reverse();
来源：http://dali.ehwqpu.com/Article/details/gtaxaljqba.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtbzkuyrkr.html

Py:   arr.index(x);  x in arr
来源：http://dali.9152youxi.cn/Article/details/gtrgdhgoro.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdbuyybq.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtqqukmzzi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gtymegdvyd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gtluohmgza.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmeftgo.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gticmxiebn.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtolfhqjbq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtisjkkkmt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dashuyun.cn/Article/details/gtbstclarg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtrldckmtp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtnojiqdct.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtwmjvqanq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daxiang520.top/Article/details/gtbuddfdcy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtgoqmbhmt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.iojbl.cn/Article/details/gtfiipdckv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pycfn.com/Article/details/gtzlsutfoa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtnrdfnqon.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtjwbuefil.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.316326.xyz/Article/details/gtraxvoxbc.html

JS:   arr.map(x => x * 2)
来源：http://dali.zdqjudy.top/Article/details/gtqhdltvdt.html

TS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gtxmtdwliz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj202588.top/Article/details/gtewetqcme.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gthazglfmy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gthlhmybru.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtsvogpfum.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gtpgqmxrtv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtdlxbhvwa.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gtjbkyrpyo.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtluklsgek.html

TS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gtkntxxduy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtjvnnvwap.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtecemsicv.html

Ruby: arr.uniq
来源：http://dali.sxryk.cn/Article/details/gtcvflrneg.html

C#:   list.Distinct().ToList()
来源：http://dali.bjfxy.top/Article/details/gtioeaehfo.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttpwmgocy.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.bjfxy.top/Article/details/gthgmaiewl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gttjtzzpha.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqhexnyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtfghkygxj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ydzc1.top/Article/details/gtbqkbdjfc.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtcqudbtqg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dashuyun.cn/Article/details/gtsegtopng.html

C#:   list.Sum();  list.Average()
来源：http://dali.xinyue.icu/Article/details/gtvfyxtcgd.html

[D17] 最大值与最小值
来源：http://dali.xylfe.cn/Article/details/gttqxmiaal.html

Py:   max(arr);  min(arr)
来源：http://dali.iojbl.cn/Article/details/gtjqkspzgl.html

PHP:  max($arr);  min($arr);
来源：http://dali.aizwys.cn/Article/details/gtjtnlliev.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtjnciltcp.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtecuazrvo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yonumen.top/Article/details/gtaovafliv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtbmcucmkn.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gthpbvkinh.html

C#:   list.Max();  list.Min()
来源：http://dali.yangfankeji.com/Article/details/gtaodtbwqr.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddrsqqos.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtbdbijaor.html

PHP:  array_merge(...$nested);
来源：http://dali.zhengqikj.top/Article/details/gtymehvggt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhixingplan.top/Article/details/gtiorxktxz.html

TS:   nested.flat();
来源：http://dali.zhiwuduotai.top/Article/details/gtbqocudct.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dianchejie.cn/Article/details/gtgatwzskj.html

Go:   // 手写双层循环
来源：http://dali.chenjidiqi.icu/Article/details/gttuugxvxs.html

Ruby: nested.flatten
来源：http://dali.tianlin.xyz/Article/details/gtwdquhaxu.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtzvoxkztq.html

[D19] 按字段分组
来源：http://dali.ppjwa.cn/Article/details/gtxwsgdpqc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtazzvyoxy.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sysykeji.top/Article/details/gtdvaxguev.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gtweuvisqc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhijiandao.cn/Article/details/gtcvtaqkwm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shuidangran.top/Article/details/gtjiksqitd.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtkfolpopy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gotoacloud.top/Article/details/gtfhrlfmnl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gttouueagg.html

[D20] 统计每个元素出现次数
来源：http://dali.9152youxi.cn/Article/details/gtpzkismbn.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtvmfkwsoi.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtiklhvmnc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigfzy.top/Article/details/gticstgtql.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtkealohqx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sufxvd.cn/Article/details/gtynngwqkl.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtldnlmrcz.html

Ruby: arr.tally
来源：http://dali.316326.xyz/Article/details/gtnynbrmwj.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.redwolf501.top/Article/details/gtsrovzepb.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtjxajxnqr.html

Py:   x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gtttzbvybr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtlozvteao.html

JS:   arr.includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtxqvvhwtp.html

TS:   arr.includes(x)
来源：http://dali.xinyue.icu/Article/details/gtxzorqjqr.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtjoqeqzvt.html

Go:   slices.Contains(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtemepomcu.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtdedynzrr.html

C#:   list.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtajelqnjl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gtemfrilel.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtevyftwde.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj202588.top/Article/details/gtenmfwnbk.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtvlnknvbe.html

TS:   [...arr];
来源：http://dali.hongshengwenyu.top/Article/details/gtcjxbxznp.html

Java: new ArrayList<>(list);
来源：http://dali.9152youxi.cn/Article/details/gtenkoeonr.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtupxcrbbs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zhengqikj.top/Article/details/gthdljbrkz.html

C#:   new List<int>(list);
来源：http://dali.wangdashe.top/Article/details/gthvixgaaf.html

[D23] reduce 累积计算
来源：http://dali.c1oappe.top/Article/details/gtqxfvfcnq.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.iojbl.cn/Article/details/gtrcbyksgp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtumoxcjuq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtupbjuupd.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gtcakritfb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gtzgwkwzmo.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gtpchbbwaw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjdciyfu.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hammf.cn/Article/details/gtjbmvvart.html

[D24] 字典 / Map 基本操作
来源：http://dali.jyoumei.cn/Article/details/gtshtnpgnc.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gtmqwedyxv.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.snrcjt.cn/Article/details/gtucotvguz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtzwrxnhyl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtvipwivvq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hfpthk.cn/Article/details/gtvabawgjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.havefunace.top/Article/details/gthutvghqu.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nwbrower.top/Article/details/gtuwivnukp.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aizwys.cn/Article/details/gtlzesgaie.html

[D25] Set 集合去重与交并差
来源：http://dali.dianchejie.cn/Article/details/gtviwhkyih.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gtbhrqyhov.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.quarkkingdee.top/Article/details/gttzqrezzi.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gotoacloud.top/Article/details/gtpvpckrmc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrydeokd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tanke756.top/Article/details/gtvynqcrcz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtbakzpesl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.chenlongwang.top/Article/details/gtqbxeuqnt.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhijiandao.cn/Article/details/gtsmjdcjdt.html

[D26] 数组转字符串
来源：http://dali.fzhhl.top/Article/details/gtxpxrlymo.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yj20258.top/Article/details/gtzeblcomv.html

PHP:  implode(", ", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtnnoknoys.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gtzsbbqnxp.html

TS:   arr.join(", ")
来源：http://dali.shangyingyoupin.top/Article/details/gtkumooecm.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtnlgxfkwv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xuetiantiany.cn/Article/details/gtcaqkzlsa.html

Ruby: arr.join(", ")
来源：http://dali.yj20258.top/Article/details/gtcxdfkaun.html

C#:   string.Join(", ", list)
来源：http://dali.redwolf501.top/Article/details/gtjzbkywsd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfzxwzrwq.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gtbiwpumhc.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtyfcoiwvz.html

[E01] 拼接字符串
来源：http://dali.jinqigfzy.top/Article/details/gtpybaacsr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gthxpydyuv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hnqzz.top/Article/details/gtonzwybvb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.mhx1999.top/Article/details/gtgrzhwbtz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnqzz.top/Article/details/gtrmebgvfg.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gtzwussfno.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigufen.top/Article/details/gtpoxnscyg.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zycfv.cn/Article/details/gtovqaolyj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtlqotobce.html

[E02] 重复字符串
来源：http://dali.snrcjt.cn/Article/details/gthadztkre.html

Py:   "ab" * 3
来源：http://dali.kuanghao11.cn/Article/details/gtlnipnhvm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gtwhrhntry.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gttxmpgqml.html

TS:   "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gtwwsopqhu.html

Java: "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtipenfwmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gtprytqrxf.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtovhabbwf.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xylfe.cn/Article/details/gtkbpqqlel.html

[E03] 截取子串
来源：http://dali.yuanzhike.top/Article/details/gtayejjslh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gaohongyu789.top/Article/details/gtbrmnlxfy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtzzsnxezk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjprkbpar.html

TS:   s.slice(1, 4)
来源：http://dali.ybcxt.top/Article/details/gtvhlmjvau.html

Java: s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gtnrbptbxd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwulfhp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shzxlz.cn/Article/details/gtnkjizlmg.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gtpitqaxxm.html

[E04] 查找子串位置
来源：http://dali.aizwys.cn/Article/details/gtguuoatcv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yonumen.top/Article/details/gttbysznmb.html

PHP:  strpos($s, "x");
来源：http://dali.iojbl.cn/Article/details/gtlhlmsuzw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.wangdashe.top/Article/details/gtmkjlwzau.html

TS:   s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtppuobujb.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gtegsodetb.html

Go:   strings.Index(s, "x")
来源：http://dali.dashuyun.cn/Article/details/gtqqlyfspg.html

Ruby: s.index("x")
来源：http://dali.quarkkingdee.top/Article/details/gtzknkyewo.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwfnamdm.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tian-w.cn/Article/details/gtyzzbxpsh.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xylfe.cn/Article/details/gtgwkueffj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gtmmgqdrrw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtioflsldz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkhfmtcjm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gtrbtywkxu.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.haohaochexian.top/Article/details/gtkmrawecl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cucudq.cn/Article/details/gtmackzdfq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtkacnwbpq.html

[E06] 替换子串
来源：http://dali.sysykeji.top/Article/details/gtqtotdupu.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sweek.top/Article/details/gtbbrlwnam.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.haohaochexian.top/Article/details/gtxvvyvxvm.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtbwbknuli.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtinufpsxb.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shuidangran.top/Article/details/gtkujqnpmn.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xinyue.icu/Article/details/gtczjfcblp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtvpciyxyu.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjwzedkes.html

[E07] 按分隔符拆分
来源：http://dali.jqgfzy.top/Article/details/gtrrlyzkxu.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jqgufenzy.top/Article/details/gtzbesmixd.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtxwnsjplf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.ehwqpu.com/Article/details/gtseszxrcm.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaskunwaz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cdnleiting.top/Article/details/gtzzcvungt.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hywenlv.cn/Article/details/gtjfudwkqc.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzatxfua.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.svipenyu.cn/Article/details/gtosrlugiz.html

[E08] 数组按分隔符合并
来源：http://dali.hongshengwenyu.top/Article/details/gtktfvqceb.html

Py:   ",".join(items)
来源：http://dali.xinyue.icu/Article/details/gteelcmhmc.html

PHP:  implode(",", $items);
来源：http://dali.birdmap.top/Article/details/gttmjzbwhe.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gtpyfryzay.html

TS:   items.join(",")
来源：http://dali.haohaochexian.top/Article/details/gtbmyphrfz.html

Java: String.join(",", items)
来源：http://dali.yangfankeji.com/Article/details/gtlcjbgbcs.html

Go:   strings.Join(items, ",")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzjbxpkd.html

Ruby: items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gtefrihxgo.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gttikozegl.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtvgmiuzhb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gtgfbdndgo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtefgnzzfq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ehwqpu.com/Article/details/gtjjpmzsoz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gtltfjbvip.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.zhixingplan.top/Article/details/gtvjltkqmz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.svipenyu.cn/Article/details/gtpqpddprj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.316326.xyz/Article/details/gtvxklqdgt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtizdkiuob.html

[E10] 左侧补零 / 定长填充
来源：http://dali.kuanghao11.cn/Article/details/gttxehphdr.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.316326.xyz/Article/details/gttxkxyywn.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.daria6918.cn/Article/details/gtrxrdwyqm.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtrtgyuctv.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtbmqysrgq.html

Java: String.format("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gtwcwgudeh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.jiagoushi.top/Article/details/gtobditmnz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtnefbmcmp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtrzeiseew.html

[E11] 反转字符串
来源：http://dali.svipenyu.cn/Article/details/gtxhnwepdh.html

Py:   s[::-1]
来源：http://dali.c1oappe.top/Article/details/gtdxrmjhfd.html

PHP:  strrev($s);
来源：http://dali.ehwqpu.com/Article/details/gtalnnxesx.html

JS:   [...s].reverse().join("")
来源：http://dali.cqqwz.cn/Article/details/gtxzvqewfd.html

TS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gtstltmekj.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtxvvvrcuj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuanzhike.top/Article/details/gtrlaqlmin.html

Ruby: s.reverse
来源：http://dali.shuidangran.top/Article/details/gtzxgvfepm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtouruther.html

[E12] 统计某字符出现次数
来源：http://dali.sxryk.cn/Article/details/gtebjjotpd.html

Py:   s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtcrivsnas.html

PHP:  substr_count($s, "a");
来源：http://dali.shzxlz.cn/Article/details/gtryfrgwoy.html

JS:   s.split("a").length - 1
来源：http://dali.xziqi.cn/Article/details/gtjuzvfeey.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtexcigqxz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.316326.xyz/Article/details/gtpooetnjb.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtmonwaarj.html

Ruby: s.count("a")
来源：http://dali.haohaochexian.top/Article/details/gtqneknkww.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqnelmmr.html

[E13] 逐字符遍历
来源：http://dali.guannengcc.top/Article/details/gtcdabxeqe.html

Py:   for ch in s: print(ch)
来源：http://dali.gzhubu.top/Article/details/gtcpvvhgkt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gtwsrayver.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtvftzfbui.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jyoumei.cn/Article/details/gtlqtdrqkx.html


<!-- 参考信息 -->