代发 wailian999

Py:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gttycdbwmo.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtdrsqslgg.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtfrjffyqb.html

TS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtmjwfcvfb.html

Java: list.size();
来源：http://dali.xuetiantiany.cn/Article/details/gttlyyszoe.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtmsjwgwgm.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gteizppgpo.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtcdmnkkdu.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gtrwddnprl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gthbgypoki.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtygargmlz.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtgtdmhynz.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtlgscgtux.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gthggvozbk.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gthietbndh.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gthteowikm.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gttqemsjmy.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtmrljhdop.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtuflfpcug.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqqioobn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gtfxbcabaa.html

TS:   [...a, ...b];
来源：http://dali.gzhubu.top/Article/details/gtstbxkbyf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pycfn.com/Article/details/gtuuxlvukc.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtevyaewly.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gtiberpmjm.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gttqtpzsos.html

[D09] 排序（升序）
来源：http://dali.cdnleiting.top/Article/details/gtjmvaiprx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gthjuimeyp.html

PHP:  sort($arr);
来源：http://dali.ppjwa.cn/Article/details/gtmbyppsce.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtxwmukdpw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtgnldotza.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuanzx.com/Article/details/gtqigxzdlh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtvmhpxpso.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbvhucrc.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtbuhbhdbg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.nanxuanxn.top/Article/details/gtgxjvtclq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtcjqomxvo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtsloryuvy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtkkokfclu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtxbbrqvev.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gzhubu.top/Article/details/gtupvlykkg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gtoequvmgn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gtwjdzdhtv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtezmecoes.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtsnvhvsxk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj202588.top/Article/details/gtftpdodzg.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtjyeqnxku.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tian-w.cn/Article/details/gtahcsiakx.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gterhiltfv.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gtqmpcvhtx.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gtlbssnjjo.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gtospwrblw.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtlzyptuat.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtehdufnus.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtqcmgygrw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgfzy.top/Article/details/gttaxvcdxc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gtoaieurjv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtnvomsqro.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hysaishi.cn/Article/details/gtoydabrhc.html

Go:   slices.Index(arr, x)
来源：http://dali.gotoacloud.top/Article/details/gtqepgtuvc.html

Ruby: arr.index(x)
来源：http://dali.yanxiufei.cn/Article/details/gtobcyanjj.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvgtzhxq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cashguo.top/Article/details/gtmkhhqzyr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sxryk.cn/Article/details/gtbcmlrmxx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.birdmap.top/Article/details/gthmdgqfub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gtrymcgube.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtnohaywfm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtnnzxuprc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtjcpczsmr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj202588.top/Article/details/gtgvmfdazw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtachpadmj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtwblcczyj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gthahssrwe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.meibo888.top/Article/details/gtmhtcwrll.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjlzxhaw.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtktxagrug.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ybcxt.top/Article/details/gtahzixxrq.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gtmebyyzoy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gtugjwnvtz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtyuvvimiu.html

[D15] 去重
来源：http://dali.9152youxi.cn/Article/details/gteskldulg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtuecjpqca.html

PHP:  array_unique($arr);
来源：http://dali.hysaishi.cn/Article/details/gtauggivxw.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtzhdnaoym.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtrmcvfkhv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gotoacloud.top/Article/details/gtnaoguqap.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.daria6918.cn/Article/details/gtyeygqaiz.html

Ruby: arr.uniq
来源：http://dali.cqqwz.cn/Article/details/gttenzoctp.html

C#:   list.Distinct().ToList()
来源：http://dali.0kj1m.cn/Article/details/gtwkoanzsm.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gtjlnkkypg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfihkkan.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtmgvacjwy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtukehuwfc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtxwrgabss.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zycfv.cn/Article/details/gtezaiwidq.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtmeoowvmb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenzaomai.com/Article/details/gtqvucmsjy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtkxhzrkge.html

[D17] 最大值与最小值
来源：http://dali.sysykeji.top/Article/details/gttwmkaure.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtslncontj.html

PHP:  max($arr);  min($arr);
来源：http://dali.havefunace.top/Article/details/gttiwbakdm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtjygzjwyk.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gtxalpmctr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpgmrwgn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrzpsoyl.html

Ruby: arr.max;  arr.min
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbfvchnop.html

C#:   list.Max();  list.Min()
来源：http://dali.snrcjt.cn/Article/details/gtlojwiuib.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gteqtenowi.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gtjeatlivf.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gtkzyudvmy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xylfe.cn/Article/details/gtryvoerlc.html

TS:   nested.flat();
来源：http://dali.sweek.top/Article/details/gtzgezoyem.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzfdfkhp.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaueohdho.html

Ruby: nested.flatten
来源：http://dali.gzhubu.top/Article/details/gtdwcvdouk.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.hnqzz.top/Article/details/gtcmldhgph.html

[D19] 按字段分组
来源：http://dali.hysaishi.cn/Article/details/gtfivqdhgi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtyatmnuph.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yanxiufei.cn/Article/details/gtcmhpyovq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtuptrnlky.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmgcncwtv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.dashuyun.cn/Article/details/gtnrlcutul.html

Go:   // 手写 map[string][]T
来源：http://dali.jlsjyb.cn/Article/details/gtpxqkgybv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tanke756.top/Article/details/gtwgyrphnm.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtmkeglwpm.html

[D20] 统计每个元素出现次数
来源：http://dali.zhongyouzk.top/Article/details/gtpliqpqth.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtfzkdtdfi.html

PHP:  array_count_values($arr);
来源：http://dali.xylfe.cn/Article/details/gtuqgxgqld.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.vqdsnc.cn/Article/details/gtctmexsly.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sysykeji.top/Article/details/gtetmiaxbg.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjmfmlqki.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtdajopllz.html

Ruby: arr.tally
来源：http://dali.bjfxy.top/Article/details/gttnnruzbs.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shuidangran.top/Article/details/gtdqhfelfj.html

[D21] 判断是否包含某元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttokcvjfm.html

Py:   x in arr
来源：http://dali.wangdashe.top/Article/details/gtiittmiwh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtogfbjepd.html

JS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gtzserzyjp.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtzmevitvs.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtnnwirjnj.html

Go:   slices.Contains(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtlsncdviz.html

Ruby: arr.include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtbkreasnj.html

C#:   list.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gttazejhnx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nwbrower.top/Article/details/gtudrddoda.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yongpay.top/Article/details/gttqqwvnaw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gtezlkmgzf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yueranfly.top/Article/details/gthznsszlm.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtzybmgddk.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gtpqgwrswe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjyreqmok.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ehwqpu.com/Article/details/gtmjlpxfrd.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxsgslpl.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtgpetmxkb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gtnozspjna.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtviowhnyx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jyoumei.cn/Article/details/gtjfattmog.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtxllypbhd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.smart0.xyz/Article/details/gtpetfiyyx.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtkggxmuif.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gtasivvjoz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gtswwlmpuv.html

[D24] 字典 / Map 基本操作
来源：http://dali.dashuyun.cn/Article/details/gttlctojrs.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.316326.xyz/Article/details/gtifvwdcyz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gtwsgqzkxq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jianghu66.top/Article/details/gthwtvbcio.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtorosnqxw.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj20258888.top/Article/details/gtoeahumwa.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gtomtfrhon.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtfatmvfdh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hnxiangtu.top/Article/details/gtuvnmdrtv.html

[D25] Set 集合去重与交并差
来源：http://dali.andypj.xyz/Article/details/gtahrsyfzz.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nanxinkj.top/Article/details/gtzmlxbvmb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.aizwys.cn/Article/details/gthaqbwimw.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jianghu66.top/Article/details/gtfxnzahku.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yvedp.cn/Article/details/gtomzcihzs.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.tianlin.xyz/Article/details/gtuemdrqdx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.9152youxi.cn/Article/details/gtqfhghgys.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ybcxt.top/Article/details/gtlpolvhhs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtobgukbtp.html

[D26] 数组转字符串
来源：http://dali.ehwqpu.com/Article/details/gtiuaznqdt.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnqzz.top/Article/details/gtmuoyxvkj.html

PHP:  implode(", ", $arr);
来源：http://dali.tanke756.top/Article/details/gtfwebeeed.html

JS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnbkdavd.html

TS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtpjrffxyr.html

Java: String.join(", ", list)
来源：http://dali.zhoulong.xyz/Article/details/gtktmcpeqh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sweek.top/Article/details/gtxpllzxts.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gtxypozwvy.html

C#:   string.Join(", ", list)
来源：http://dali.aizwys.cn/Article/details/gtgtmtjjja.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbuilmegq.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gtkywvmivd.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwgxxuymx.html

[E01] 拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtnskfvjbj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gtkjawdxeg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtcajnlvxm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtgxcvbpzn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gtyocxyuhr.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtjijlawbu.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtsarpbhhq.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjonrgou.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pycfn.com/Article/details/gtyadgxesb.html

[E02] 重复字符串
来源：http://dali.jinqigfzy.top/Article/details/gttitfbivt.html

Py:   "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gtwgcvmgro.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sxryk.cn/Article/details/gtacaykyuo.html

JS:   "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtwvjlvtnq.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqzkbaxx.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtiwccsjqp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gzhubu.top/Article/details/gtjlvdyhgc.html

Ruby: "ab" * 3
来源：http://dali.jqgufenzy.top/Article/details/gtlqrxguju.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cheryme.top/Article/details/gtyqaynrvw.html

[E03] 截取子串
来源：http://dali.hywenlv.cn/Article/details/gtojvfggyj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yj20258.top/Article/details/gtisyktpql.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtiwecxtpi.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.9152youxi.cn/Article/details/gtwrdetxtn.html

TS:   s.slice(1, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtascvxmlu.html

Java: s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gtviaoardo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.andypj.xyz/Article/details/gtzalenzct.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.gotoacloud.top/Article/details/gtvoakuoms.html

C#:   s.Substring(1, 3)
来源：http://dali.shuidangran.top/Article/details/gtpfkwllfl.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gtpovhzqqm.html

Py:   s.find("x");  s.index("x")
来源：http://dali.wangdashe.top/Article/details/gthmjyebss.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtnjghprlf.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhoulong.xyz/Article/details/gtlunijtoo.html

TS:   s.indexOf("x")
来源：http://dali.hfpthk.cn/Article/details/gtetrsvgqp.html

Java: s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtuadehlnd.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gtmuhuqbli.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxyvirnwt.html

C#:   s.IndexOf("x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojfeclmb.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.quarkkingdee.top/Article/details/gtxbhjiawt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.kuanghao11.cn/Article/details/gthllnzodt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gtrsevlkxq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtkshsbzzb.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yj20258.top/Article/details/gtueuwdjil.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gtjfwtyjvj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtergfoooq.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqdhjlrl.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtubakzbph.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtvzkbehbm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.quarkkingdee.top/Article/details/gthudahfzm.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gaohongyu789.top/Article/details/gtayzosbdz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtarilduvt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtslxstnnr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.havefunace.top/Article/details/gtpbqeqsjo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtfxmflcrr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtxrdchouy.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtransjvvq.html

[E07] 按分隔符拆分
来源：http://dali.hywenlv.cn/Article/details/gtayeaxymi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.dashuyun.cn/Article/details/gtcgyqkous.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxuanxn.top/Article/details/gtancanghu.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtazacelam.html

TS:   s.split(",")
来源：http://dali.ybcxt.top/Article/details/gtghxjzbus.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.wangshuangyany.cn/Article/details/gtvnsnkuhd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jyoumei.cn/Article/details/gthrytpzex.html

Ruby: s.split(",");  s.split
来源：http://dali.jiagoushi.top/Article/details/gtjuooehdx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.hnxiangtu.top/Article/details/gteomoufkv.html

[E08] 数组按分隔符合并
来源：http://dali.yanxiufei.cn/Article/details/gtdarsufut.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtakjcxmut.html

PHP:  implode(",", $items);
来源：http://dali.yj20258888.top/Article/details/gtxwokqjla.html

JS:   items.join(",")
来源：http://dali.jqgufenzy.top/Article/details/gtbzwqejoe.html

TS:   items.join(",")
来源：http://dali.nanxinkj.top/Article/details/gtfbyvfrut.html

Java: String.join(",", items)
来源：http://dali.jinqigufen.top/Article/details/gtxkixijyc.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtgtaxxwfm.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gtrrimgzfy.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gtvcmwfkrq.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtcekaklnu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tanke756.top/Article/details/gtwnlvrodx.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tianlin.xyz/Article/details/gtzkwexnbj.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yuxming.cn/Article/details/gtwhbqhyai.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cucudq.cn/Article/details/gthypcqske.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.ybcxt.top/Article/details/gtxutzftaw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.yj20258888.top/Article/details/gtqcundhwr.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenzaomai.com/Article/details/gtzhcwhuso.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtxlybgupc.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zhoulong.xyz/Article/details/gtndutmvok.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gtxrbbfcnr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.fzhhl.top/Article/details/gthshiakuw.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtnhgmdqjc.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtykkjfftb.html

Java: String.format("%03d", 7)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqhmyasm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gtmtjwplsx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtftajucsz.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sxryk.cn/Article/details/gtjglkgspn.html

[E11] 反转字符串
来源：http://dali.316326.xyz/Article/details/gtthgvbhkh.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvfzvqft.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtyvlulkax.html

JS:   [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gthcxpyoxd.html

TS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtpljykmov.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtcsgmmmeu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gtgkdjftqp.html

Ruby: s.reverse
来源：http://dali.aizwys.cn/Article/details/gtmskyulac.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.mhx1999.top/Article/details/gtvdeuiwxr.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtdihrkkhq.html

Py:   s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtypztjuqp.html

PHP:  substr_count($s, "a");
来源：http://dali.pycfn.com/Article/details/gtcvssbvyv.html

JS:   s.split("a").length - 1
来源：http://dali.meibo888.top/Article/details/gtbedfmmbj.html

TS:   s.split("a").length - 1
来源：http://dali.xuetiantiany.cn/Article/details/gtbnplnzbw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfemebep.html

Go:   strings.Count(s, "a")
来源：http://dali.feifeiyinyue.top/Article/details/gteylgcczx.html

Ruby: s.count("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwabbwjq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jlsjyb.cn/Article/details/gtvdeaipdh.html

[E13] 逐字符遍历
来源：http://dali.sufxvd.cn/Article/details/gtrdnofbtv.html


<!-- 参考信息 -->