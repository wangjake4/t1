代发 wailian999

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2tdwuoltg.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2zwpehrdt.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2twimkbqv.html

TS:   arr.length
来源：http://dali.mhx1999.top/Article/details/gt2hzjkdsjt.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vwvbaqyv.html

Go:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2znuwfpnw.html

Ruby: arr.length; arr.size
来源：http://dali.gzhubu.top/Article/details/gt2oytnktsg.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gt2gwgqulgi.html

[D07] 切片 / 取子数组
来源：http://dali.hongshengwenyu.top/Article/details/gt2vjruusfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gt2lxqckzmv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2jkoynzps.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2sfmhqvtt.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2yjiycyko.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2erhukbcu.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gt2pxnndjvk.html

Ruby: arr[1, 3]
来源：http://dali.cucudq.cn/Article/details/gt2csrxrhrv.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gt2tvqynrtb.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gt2jwtsuxvv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gt2tjuhkdwh.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2nqqwkqnc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gt2nmyqvwhy.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gt2bargfdrq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zdqjudy.top/Article/details/gt2bltctsky.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gt2feaahvvw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqupgmvv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2xqfajphd.html

[D09] 排序（升序）
来源：http://dali.gotoacloud.top/Article/details/gt2rvfhpkwu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2qquualej.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2tvupcptn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gt2lqphfjuc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gaohongyu789.top/Article/details/gt2vpiylqpz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gt2uyonufjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gt2pmlojjde.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwkqdffu.html

C#:   list.Sort();
来源：http://dali.dianchejie.cn/Article/details/gt2fbfrbrig.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gt2syfaojnr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gt2dbcnqidm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gt2aspgcerf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gt2kkcgdama.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2ayrsfyay.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gt2fmfwzluo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gt2gbhkpoen.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnuioard.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftooeoci.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gt2brfremva.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gt2tjdzasad.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gt2olpzpxcw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gt2lxojicpr.html

TS:   [...arr].reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2livxztou.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ivsroozl.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2svrfwvoz.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqnyvilp.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2iilnvmxb.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gt2ybxaxeqg.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhuimpd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rzvvjfvm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruahldme.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2bepjabhu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2fdggtpgy.html

Go:   slices.Index(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2evcsbocx.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpcdtnil.html

C#:   list.IndexOf(x);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxqaayto.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daria6918.cn/Article/details/gt2mpflruvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2flkjbmyt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hysaishi.cn/Article/details/gt2mmjfaogh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2qjqxetxc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gt2dlcxwfmx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gt2tzkowgrj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.andypj.xyz/Article/details/gt2yectavlf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gt2setxeqqh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2mpalhaqi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2nfalnqyl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinqigufen.top/Article/details/gt2ekdhjjgf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2npecvnpc.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gt2yvnuzbln.html

TS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gt2rtuvwerf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.mhx1999.top/Article/details/gt2jvzqhcnv.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2ifsvwmre.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2wfqklnvo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2jyfiwdhh.html

[D15] 去重
来源：http://dali.yueranfly.top/Article/details/gt2fidzvtqv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2ujtkeybb.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2rhzqsztx.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2jbwyhijm.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2lcsfkqfi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2igoayhuy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wqmzjzaa.html

Ruby: arr.uniq
来源：http://dali.birdmap.top/Article/details/gt2ledjkjxy.html

C#:   list.Distinct().ToList()
来源：http://dali.jlsjyb.cn/Article/details/gt2yndruaef.html

[D16] 求和与平均值
来源：http://dali.xziqi.cn/Article/details/gt2omhojgzg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2xmfhydqf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mlutmtan.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gt2htpgxqgl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xylfe.cn/Article/details/gt2sjrsmldy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gt2qxxtyrmi.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gt2llyespcg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.bjfxy.top/Article/details/gt2rfdmvkct.html

C#:   list.Sum();  list.Average()
来源：http://dali.haohaochexian.top/Article/details/gt2ehlaqoqf.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2tvkwefls.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zksrkfke.html

PHP:  max($arr);  min($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2rpzorvzv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ivvv.top/Article/details/gt2wqrvmfzq.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2rfrqxpiz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenlongwang.top/Article/details/gt2faqwtngq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2sfppqhvq.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gt2pwzxepts.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgfzy.top/Article/details/gt2jlbuzuzi.html

[D18] 扁平化嵌套数组
来源：http://dali.vqdsnc.cn/Article/details/gt2rdhthsnr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj202588.top/Article/details/gt2hnlaygvn.html

PHP:  array_merge(...$nested);
来源：http://dali.cashguo.top/Article/details/gt2wdqcogwp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsqspyli.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gt2xgdrxwrs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqmzztyy.html

Go:   // 手写双层循环
来源：http://dali.yangfankeji.com/Article/details/gt2awbkjuim.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2kwyfhurv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gt2dhkicqcu.html

[D19] 按字段分组
来源：http://dali.yuxming.cn/Article/details/gt2obdnthpg.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ppjwa.cn/Article/details/gt2xgefsjcd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangdashe.top/Article/details/gt2zovbgjxu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gt2dbdqlgtu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.dashuyun.cn/Article/details/gt2atntklwq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jyoumei.cn/Article/details/gt2jdxzkkzm.html

Go:   // 手写 map[string][]T
来源：http://dali.tianlin.xyz/Article/details/gt2csymogmx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jiagoushi.top/Article/details/gt2foqhypfa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xuanzx.com/Article/details/gt2zjrbexrt.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gt2wxhtcsvo.html

Py:   Counter(arr)
来源：http://dali.guowangkeji.top/Article/details/gt2ucgupglr.html

PHP:  array_count_values($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2mndswrjp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gt2dhabmddn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2dxsqmrmq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2tlrmjyyp.html

Go:   // 手写 map[T]int
来源：http://dali.zdqjudy.top/Article/details/gt2mqkmcezt.html

Ruby: arr.tally
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ypxjxntr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cqqwz.cn/Article/details/gt2cvlahrpt.html

[D21] 判断是否包含某元素
来源：http://dali.jianghu66.top/Article/details/gt2drkzhoik.html

Py:   x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cptdtwrw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.bjfxy.top/Article/details/gt2phkqrztr.html

JS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2rjpuvkzm.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2rwoefxjg.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2ollefdiz.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2qlzwevyz.html

Ruby: arr.include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qybjreld.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2orubeowy.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2ffelxnwb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2kpputfgc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shuidangran.top/Article/details/gt2ojqnmcql.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xuanzx.com/Article/details/gt2iafffivr.html

TS:   [...arr];
来源：http://dali.zhongyouzk.top/Article/details/gt2gfngtwwi.html

Java: new ArrayList<>(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wmxevrkf.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2wyeyfwlm.html

Ruby: arr.dup;  arr.clone
来源：http://dali.hammf.cn/Article/details/gt2dswacogh.html

C#:   new List<int>(list);
来源：http://dali.jinqigufen.top/Article/details/gt2omyhfmwp.html

[D23] reduce 累积计算
来源：http://dali.chenlongwang.top/Article/details/gt2azsubkmm.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2oztjgqaj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2lschwsql.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.birdmap.top/Article/details/gt2grukqvlo.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yueranfly.top/Article/details/gt2qaxtfdxl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xylfe.cn/Article/details/gt2eostwmjw.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2ipwcshnd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2irtqduup.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rdjcohfk.html

[D24] 字典 / Map 基本操作
来源：http://dali.iojbl.cn/Article/details/gt2hxslvupm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.pycfn.com/Article/details/gt2ydjkmbph.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2xuybxpqo.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fxmsmacx.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gt2igpdcszp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gt2cwpmaxyl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.smart0.xyz/Article/details/gt2nrewhrxq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhoulong.xyz/Article/details/gt2umkziatm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.quarkkingdee.top/Article/details/gt2qailkpxm.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lswxkohf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tianlin.xyz/Article/details/gt2zodpyrdn.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2qjvyxrce.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2urxjwuwg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shzxlz.cn/Article/details/gt2vtolflsj.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfymmyzu.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yanxiufei.cn/Article/details/gt2ivhhhisc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2lojoxmvo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.svipenyu.cn/Article/details/gt2uvuvzecm.html

[D26] 数组转字符串
来源：http://dali.daria6918.cn/Article/details/gt2pftrdich.html

Py:   ", ".join(map(str, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2urbkqbjz.html

PHP:  implode(", ", $arr);
来源：http://dali.0kj1m.cn/Article/details/gt2qeumcyjh.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2kzkmjgnv.html

TS:   arr.join(", ")
来源：http://dali.daria6918.cn/Article/details/gt2iquemwmi.html

Java: String.join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zoviotko.html

Go:   strings.Join(strs, ", ")
来源：http://dali.smart0.xyz/Article/details/gt2ayglypei.html

Ruby: arr.join(", ")
来源：http://dali.dianchejie.cn/Article/details/gt2yuirkpxu.html

C#:   string.Join(", ", list)
来源：http://dali.ydzc1.top/Article/details/gt2kvtqqgqb.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2xnrmcrmi.html

E. 字符串处理
来源：http://dali.hammf.cn/Article/details/gt2pfagevtj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2dhfpmarn.html

[E01] 拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2qqsycibq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.wangshuangyany.cn/Article/details/gt2dtewfkmz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zdqjudy.top/Article/details/gt2dryztjqe.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gt2gcpehjdp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.vqdsnc.cn/Article/details/gt2ciyzsbqi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gt2toztupmp.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.smart0.xyz/Article/details/gt2uxenxzzm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yuxming.cn/Article/details/gt2ybrfueni.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2zcqqvazl.html

[E02] 重复字符串
来源：http://dali.yueranfly.top/Article/details/gt2tlmrptss.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gt2zdhezgul.html

PHP:  str_repeat("ab", 3);
来源：http://dali.tianlin.xyz/Article/details/gt2habznvtc.html

JS:   "ab".repeat(3)
来源：http://dali.cqqwz.cn/Article/details/gt2uekipnko.html

TS:   "ab".repeat(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swayqdyq.html

Java: "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gt2nrdpqnrc.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.redwolf501.top/Article/details/gt2wqjettiu.html

Ruby: "ab" * 3
来源：http://dali.yj202588.top/Article/details/gt2qnfcutdy.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gt2rwpaktib.html

[E03] 截取子串
来源：http://dali.xuanzx.com/Article/details/gt2bxsgbpap.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gt2okbyultt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gt2ystmogxz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.dianchejie.cn/Article/details/gt2vqncezow.html

TS:   s.slice(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2wptfpufj.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gt2oansczop.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gt2psqdlihb.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jqgfzy.top/Article/details/gt2rlrdgior.html

C#:   s.Substring(1, 3)
来源：http://dali.zhengqikj.top/Article/details/gt2amtonmps.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2tsnikknf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuetiantiany.cn/Article/details/gt2dchhdxua.html

PHP:  strpos($s, "x");
来源：http://dali.chenjidiqi.icu/Article/details/gt2ottwolwx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yonumen.top/Article/details/gt2vbcbbhdk.html

TS:   s.indexOf("x")
来源：http://dali.vqdsnc.cn/Article/details/gt2ljbfflkx.html

Java: s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gt2gnlqjoot.html

Go:   strings.Index(s, "x")
来源：http://dali.hnxiangtu.top/Article/details/gt2fifdvgyp.html

Ruby: s.index("x")
来源：http://dali.yonumen.top/Article/details/gt2cukebnem.html

C#:   s.IndexOf("x")
来源：http://dali.gaohongyu789.top/Article/details/gt2wokmxhku.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cobdgbbf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gt2jqezwlvq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gt2nwiwflnm.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ydzc1.top/Article/details/gt2xukctxza.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gogol.net.cn/Article/details/gt2fftyffkr.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.fzhhl.top/Article/details/gt2qpqajxhc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zzahgdpb.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2onewmcqq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egtqeewd.html

[E06] 替换子串
来源：http://dali.jyoumei.cn/Article/details/gt2pxyczmor.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shzxlz.cn/Article/details/gt2wticawic.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yongpay.top/Article/details/gt2rovszoju.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gt2bfnoxkwl.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2ztmvhiat.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2pagdqgsz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gt2jayotpbh.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2csnxvcws.html

C#:   s.Replace("a", "b")
来源：http://dali.shuidangran.top/Article/details/gt2ybofrotq.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gt2vfafndxz.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangshuangyany.cn/Article/details/gt2aijcoqtc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2fkgxaqfa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.fzhhl.top/Article/details/gt2xvrqpsca.html

TS:   s.split(",")
来源：http://dali.chenzaomai.com/Article/details/gt2amogmehl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhengqikj.top/Article/details/gt2njjexopo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dianchejie.cn/Article/details/gt2nwdjqctl.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gt2ougauzgp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gt2hthaytdg.html

[E08] 数组按分隔符合并
来源：http://dali.pengpengdd.cyou/Article/details/gt2xhxcyftp.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dpwqmziv.html

PHP:  implode(",", $items);
来源：http://dali.zhixingplan.top/Article/details/gt2qmdfxprq.html

JS:   items.join(",")
来源：http://dali.316326.xyz/Article/details/gt2unhujyyo.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2fhsrzwhi.html

Java: String.join(",", items)
来源：http://dali.chenlongwang.top/Article/details/gt2xauskydo.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gt2zjfljiro.html

Ruby: items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvmmqyhz.html

C#:   string.Join(",", items)
来源：http://dali.jianghu66.top/Article/details/gt2wclacyju.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2eyvfhntn.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gotoacloud.top/Article/details/gt2yazwjjyq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2ttpzirgo.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zdqjudy.top/Article/details/gt2uwfhklrn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gt2texvyysu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yuxming.cn/Article/details/gt2icsgjlrd.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhengqikj.top/Article/details/gt2hdffhfpu.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onroeogg.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.316326.xyz/Article/details/gt2wwhxnmqo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2xjoacjat.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.vqdsnc.cn/Article/details/gt2dfsafbxv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ydzc1.top/Article/details/gt2cyvqqmkd.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gt2simuycdx.html

TS:   "7".padStart(3, "0")
来源：http://dali.snrcjt.cn/Article/details/gt2mznntzni.html

Java: String.format("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tjgiqzrp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2tzeeebpl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zusksfvk.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gt2bwirprla.html

[E11] 反转字符串
来源：http://dali.hfpthk.cn/Article/details/gt2bmzgyaju.html

Py:   s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2vfkjdsvd.html

PHP:  strrev($s);
来源：http://dali.daxiang520.top/Article/details/gt2nkrhdoag.html

JS:   [...s].reverse().join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2imhazdva.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2plyjwncd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sysykeji.top/Article/details/gt2etsuegkq.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.jiagoushi.top/Article/details/gt2ejosrduf.html

Ruby: s.reverse
来源：http://dali.hysaishi.cn/Article/details/gt2lnecmkpy.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qvbjvoye.html

[E12] 统计某字符出现次数
来源：http://dali.hysaishi.cn/Article/details/gt2ncqdbxuc.html

Py:   s.count("a")
来源：http://dali.andypj.xyz/Article/details/gt2ukpzrvdz.html

PHP:  substr_count($s, "a");
来源：http://dali.jiagoushi.top/Article/details/gt2uwahodcx.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gt2qcgwppfd.html

TS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2mtwqflrr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.daxiang520.top/Article/details/gt2fjoebyxj.html

Go:   strings.Count(s, "a")
来源：http://dali.shuidangran.top/Article/details/gt2yshqpttk.html

Ruby: s.count("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaablhmm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.wangdashe.top/Article/details/gt2mmomjmoa.html

[E13] 逐字符遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqvhroiy.html


<!-- 参考信息 -->