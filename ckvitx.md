代发 wailian999

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtpfyxvlca.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtzzlpkjfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gtrjjlqqdv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdccvfcnu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gtacoehuhj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtsfmjuikl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtbnefjdit.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtqhuivxil.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtvsnaqfne.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gthylmuaib.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtlcnwbltb.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtqeelawal.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtvwxvvrlz.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtukalfpwc.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gtjsjtihby.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gtnmalgxbp.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtesfvmcqu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwnbwwsq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtxjjriajh.html

JS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtpsjdwarj.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gttjlkmkzz.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtfymkdiaw.html

Go:   arr[1:4]
来源：http://dali.nwbrower.top/Article/details/gtmlnzvwqu.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtdahkclum.html

C#:   list.GetRange(1, 3);
来源：http://dali.316326.xyz/Article/details/gtlpoitlvd.html

[D08] 合并两个数组
来源：http://dali.jiagoushi.top/Article/details/gtgxouopcr.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gtqiqvnmbh.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtlrcoqypq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtblnvjglt.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtszjnxwas.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nwbrower.top/Article/details/gtktzlbngt.html

Go:   append(a, b...)
来源：http://dali.cashguo.top/Article/details/gtqlgpsypo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jiagoushi.top/Article/details/gtxzfminoo.html

C#:   a.Concat(b).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtojcsgwod.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gtfgopanbd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzsstcyhr.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtvylwfpow.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jlsjyb.cn/Article/details/gtzphwbqaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtmozbwryj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jlsjyb.cn/Article/details/gttlbuiwqk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aibaodan.cn/Article/details/gtytwqymms.html

Ruby: arr.sort
来源：http://dali.zycfv.cn/Article/details/gtilnuvwwc.html

C#:   list.Sort();
来源：http://dali.chenzaomai.com/Article/details/gtlfgjabsm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gtsmgdssye.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gtnedaptah.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtmkvhepfm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gtxtiykrul.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtvbrriosp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtoixnfnap.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtzokmrkln.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtwbrlqbrr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtjfjtxnwp.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gtxhyrwidr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtqjzwxmfu.html

PHP:  array_reverse($arr);
来源：http://dali.yongpay.top/Article/details/gtmyvxqevt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtpgjjjrsh.html

TS:   [...arr].reverse();
来源：http://dali.snrcjt.cn/Article/details/gtqhntgmfr.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtkikmjmgw.html

Go:   slices.Reverse(arr)
来源：http://dali.sweek.top/Article/details/gtvhaqbzml.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gtqgmfvjyy.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtuultaqlu.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtgdfeynfh.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdtihxkt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtfxpuauxa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gtzufqmvcf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gtkycizzhk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.kuanghao11.cn/Article/details/gtbluuseel.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gttqkiixkt.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtcqvazjgk.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gtvahriraf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtpzxtpwhl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.9152youxi.cn/Article/details/gtlosqlmik.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtcmakblwp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gthwowmfnf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtwmrlvdka.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gthaznmfmg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuanzhike.top/Article/details/gtgnrnrhvk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtrmicshyu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtdfvxdmwr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aibaodan.cn/Article/details/gtqvtqvnwi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtkjzyxucf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ydzc1.top/Article/details/gtuxwucdrj.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtylhixpdf.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiufyesy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.9152youxi.cn/Article/details/gtzhupywqp.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtqpcqlwqw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtqjafrvaq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtqcqasjxs.html

[D15] 去重
来源：http://dali.nanxuanxn.top/Article/details/gtcugmzuoh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dashuyun.cn/Article/details/gtssvvcrhp.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtfomfofnm.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtblxveesn.html

TS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtiuxypgwi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtmnlbzzgk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtkediqzot.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtnggbaorv.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gteomuqlci.html

[D16] 求和与平均值
来源：http://dali.hongshengwenyu.top/Article/details/gtaicnyzdk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gthrwaeggf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gthpgmwixc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gtmjrpetrq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtivualawt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jqgufenzy.top/Article/details/gtcirntgoh.html

Go:   // 手写循环累加
来源：http://dali.hfpthk.cn/Article/details/gtbnhdamam.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtpopuglyw.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtkxbpklbp.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtudwktrhj.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtaphenwne.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbqhdesso.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.smart0.xyz/Article/details/gtbgmyerxu.html

TS:   Math.max(...arr);
来源：http://dali.fengsongda.top/Article/details/gtbefbdvru.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shuidangran.top/Article/details/gtfjrmopga.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhqqlgms.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtlgbspfpy.html

C#:   list.Max();  list.Min()
来源：http://dali.xziqi.cn/Article/details/gtszlqkdna.html

[D18] 扁平化嵌套数组
来源：http://dali.yj202588.top/Article/details/gtuszyblvs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cdnleiting.top/Article/details/gtpmcashzw.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtvzbthuid.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevjsbprk.html

TS:   nested.flat();
来源：http://dali.0kj1m.cn/Article/details/gtowpvxkkz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtljsxfniv.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtjtlyicts.html

Ruby: nested.flatten
来源：http://dali.hnqzz.top/Article/details/gtjpttogms.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtyvfxifiw.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gtfgdxvhwm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnmqgqql.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shangyingyoupin.top/Article/details/gtdzhnedix.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtxfpwjxat.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jqgufenzy.top/Article/details/gtuffryvqb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gtpydslnbu.html

Go:   // 手写 map[string][]T
来源：http://dali.pycfn.com/Article/details/gtbazycpdd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gtfrcxgpky.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cqqwz.cn/Article/details/gtybybqsmj.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtxmanbcyu.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtslybvakg.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gtnqxxydtx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dianchejie.cn/Article/details/gtbtqkbsdh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfpaftqh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.wangshuangyany.cn/Article/details/gtigxzucqc.html

Go:   // 手写 map[T]int
来源：http://dali.chenzaomai.com/Article/details/gtvsthhzly.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtpgrzgnhi.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.wangshuangyany.cn/Article/details/gtyqnxuoix.html

[D21] 判断是否包含某元素
来源：http://dali.xuetiantiany.cn/Article/details/gtztfrzovq.html

Py:   x in arr
来源：http://dali.tian-w.cn/Article/details/gtrqqzxbmw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj20258888.top/Article/details/gtqkticgct.html

JS:   arr.includes(x)
来源：http://dali.yj202588.top/Article/details/gtiypfjjrw.html

TS:   arr.includes(x)
来源：http://dali.yj20258888.top/Article/details/gtegypnnsn.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gthknyvsnv.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtquufereu.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsataxwcc.html

C#:   list.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtijtxmcqd.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xziqi.cn/Article/details/gtfladwfar.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj202588.top/Article/details/gtgusktbkf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.bjfxy.top/Article/details/gtquhghlsw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvehazfa.html

TS:   [...arr];
来源：http://dali.xinyue.icu/Article/details/gtgmjgihlg.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxpnqkgg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtnezmmgdy.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hywenlv.cn/Article/details/gtegcivgok.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gtecqwvqkl.html

[D23] reduce 累积计算
来源：http://dali.fzhhl.top/Article/details/gtnjnyfgsg.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hywenlv.cn/Article/details/gtdxrayhzg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtfdqchykm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tian-w.cn/Article/details/gtetecahks.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gteoswuycd.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.c1oappe.top/Article/details/gtntboziiw.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gtcsckibjw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gtwyuomrnr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthybmpidk.html

[D24] 字典 / Map 基本操作
来源：http://dali.gotoacloud.top/Article/details/gtzivyokem.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pengpengdd.cyou/Article/details/gtkoymtxag.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtsduuluzb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yanxiufei.cn/Article/details/gtrsktdmjj.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtnbafiutk.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.smart0.xyz/Article/details/gtxbyuonto.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtdqrmxwyi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.nanxuanxn.top/Article/details/gtdstgepgl.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gtcxnaoedm.html

[D25] Set 集合去重与交并差
来源：http://dali.hnqzz.top/Article/details/gtiorvynku.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.yuxming.cn/Article/details/gtqomxhvod.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gtzuxanmap.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gtzbkcnoez.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqxiqjalv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hywenlv.cn/Article/details/gtsnuungzy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.tianlin.xyz/Article/details/gtcznqzjdl.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.havefunace.top/Article/details/gtmobvwlbf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jlsjyb.cn/Article/details/gthjxulwwd.html

[D26] 数组转字符串
来源：http://dali.chenzaomai.com/Article/details/gtfsneicai.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sxryk.cn/Article/details/gterjgdsyl.html

PHP:  implode(", ", $arr);
来源：http://dali.dashuyun.cn/Article/details/gtwsuhptwe.html

JS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtzcsawtjc.html

TS:   arr.join(", ")
来源：http://dali.sweek.top/Article/details/gtxzuayius.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtsoudmozl.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gtlbyogkns.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiaxrrxmt.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gthwiyxbyv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtofsqzgcg.html

E. 字符串处理
来源：http://dali.c1oappe.top/Article/details/gthueovmkc.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlxxjkpkl.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gtetxnepij.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tanke756.top/Article/details/gtudhohmkh.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.0kj1m.cn/Article/details/gticejheuq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.kuanghao11.cn/Article/details/gthbxlsdaq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gtibaacvzw.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtzrkowcxe.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.cdnleiting.top/Article/details/gtvzfwxtcu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.andypj.xyz/Article/details/gtzacnvsan.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtqgsjllys.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtenkuyzjz.html

Py:   "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gtguufxufq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtsaibitgc.html

JS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtoemizv.html

TS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtrgkrtkfd.html

Java: "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gtjzyxdkza.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cheryme.top/Article/details/gtlqlmovio.html

Ruby: "ab" * 3
来源：http://dali.meibo888.top/Article/details/gtbpiojmxc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.havefunace.top/Article/details/gtvsfwifih.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtzfjbaxbx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.andypj.xyz/Article/details/gtwrtzgrat.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xinyue.icu/Article/details/gttpzrgfqd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtickjkbyd.html

TS:   s.slice(1, 4)
来源：http://dali.nwbrower.top/Article/details/gttjholwho.html

Java: s.substring(1, 4)
来源：http://dali.chenzaomai.com/Article/details/gtcinbtoqs.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtlegzoaph.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gtmcxekdhf.html

C#:   s.Substring(1, 3)
来源：http://dali.hfpthk.cn/Article/details/gtqlimcyso.html

[E04] 查找子串位置
来源：http://dali.jqgfzy.top/Article/details/gtturogqgh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtfcnydmyp.html

PHP:  strpos($s, "x");
来源：http://dali.zhixingplan.top/Article/details/gtnegwubjo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtkqctykoq.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtmurnukat.html

Java: s.indexOf("x")
来源：http://dali.sweek.top/Article/details/gtvupdenpy.html

Go:   strings.Index(s, "x")
来源：http://dali.shangyingyoupin.top/Article/details/gthkrcnzxc.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gtpbhyyvvm.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtkoarskwu.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenjidiqi.icu/Article/details/gtdolsoofc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxuanxn.top/Article/details/gtqqafzuhj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cdnleiting.top/Article/details/gtenllotlu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.birdmap.top/Article/details/gtoxavhmdv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.vqdsnc.cn/Article/details/gtysbifwgm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtqfmikeig.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.mhx1999.top/Article/details/gtccxfpvoj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.chenzaomai.com/Article/details/gtyfuvjjou.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtnscasxui.html

[E06] 替换子串
来源：http://dali.chenlongwang.top/Article/details/gtnbryseim.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtyqmqdxeb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.meibo888.top/Article/details/gtfzkuqqap.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtszbzkzbe.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtrzwgjiqv.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yongpay.top/Article/details/gtbpbzqdxi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.feifeiyinyue.top/Article/details/gthzoadxpm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.ivvv.top/Article/details/gtxoxyjjtj.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtupcujqzs.html

[E07] 按分隔符拆分
来源：http://dali.cqqwz.cn/Article/details/gtmakeuhze.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xylfe.cn/Article/details/gtjygzujen.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gtanvbnonn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.nwbrower.top/Article/details/gtldqfcejw.html

TS:   s.split(",")
来源：http://dali.cdnleiting.top/Article/details/gtthxdjwqq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.316326.xyz/Article/details/gttoryzodb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpnthxdr.html

Ruby: s.split(",");  s.split
来源：http://dali.havefunace.top/Article/details/gtqrqjpbzd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.wangdashe.top/Article/details/gtdefopgnu.html

[E08] 数组按分隔符合并
来源：http://dali.yj202588.top/Article/details/gtwrmjnwgm.html

Py:   ",".join(items)
来源：http://dali.hammf.cn/Article/details/gtdbjvxfmm.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gtdjhtqfwl.html

JS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtkrfdieds.html

TS:   items.join(",")
来源：http://dali.iojbl.cn/Article/details/gtpduxrjxh.html

Java: String.join(",", items)
来源：http://dali.haohaochexian.top/Article/details/gtudshqrrs.html

Go:   strings.Join(items, ",")
来源：http://dali.fengsongda.top/Article/details/gtfnjgrcoa.html

Ruby: items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gttcldelto.html

C#:   string.Join(",", items)
来源：http://dali.sysykeji.top/Article/details/gtbkjpuntd.html

[E09] 去除所有空白字符
来源：http://dali.yj202588.top/Article/details/gtcwhsxwav.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gtncuybvwz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.hammf.cn/Article/details/gtubxgdpfw.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jyoumei.cn/Article/details/gtcbjkzrcp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtwxcmeutq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fengsongda.top/Article/details/gtftmlecih.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhiwuduotai.top/Article/details/gtfealgync.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ppjwa.cn/Article/details/gtxpcaavsl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtopcqomfk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zycfv.cn/Article/details/gtckwnchuu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gtouawzvxz.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shuidangran.top/Article/details/gtdzdythob.html

JS:   "7".padStart(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gteadsvxkv.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gtajmrusyh.html

Java: String.format("%03d", 7)
来源：http://dali.guannengcc.top/Article/details/gtuusxvspg.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtxlmqaidc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.meibo888.top/Article/details/gtqlvyfuat.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtomvegssr.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtshcsowpg.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtiuihfzlh.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gtllxldbho.html

JS:   [...s].reverse().join("")
来源：http://dali.sysykeji.top/Article/details/gtkbrpvyaw.html

TS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtizzqitqq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yanxiufei.cn/Article/details/gthlbkofbb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.kuanghao11.cn/Article/details/gtmtfnagjk.html

Ruby: s.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtarzkvlou.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinqigufen.top/Article/details/gtsuftwgkz.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtccnkdqbt.html

Py:   s.count("a")
来源：http://dali.aizwys.cn/Article/details/gtffsbgksg.html


<!-- 参考信息 -->